# Android Engineering Foundations

Practice the data structures and reasoning that appear in everyday Android work. Start with the small exercises below, then use the [historical topic catalog](docs/topic-catalog.md) as a reference rather than a required checklist.

## Learning order

| Step | Learn | Show that you understand |
| --- | --- | --- |
| 1 | Lists, sets, maps, and equality | Deduplicate identifiers while preserving order. |
| 2 | Time and space complexity | Explain why a set avoids repeated list scans. |
| 3 | Stacks and queues | Model a navigation history or pending-work queue. |
| 4 | Sorting and binary search | Explain the sorted-input requirement and boundary cases. |
| 5 | State and separation of concerns | Keep data transformations independent of UI code. |

## Worked example: merge identifiers from two pages

A paginated feed returns `[3, 1, 3]`, then `[1, 2]`. We want `[3, 1, 2]`: the first occurrence wins, and display order remains stable.

```kotlin
fun mergeIds(existing: List<Int>, incoming: List<Int>): List<Int> {
    val seen = mutableSetOf<Int>()
    val result = mutableListOf<Int>()
    for (id in existing + incoming) {
        if (seen.add(id)) result.add(id)
    }
    return result
}

fun main() {
    check(mergeIds(listOf(3, 1, 3), listOf(1, 2)) == listOf(3, 1, 2))
    check(mergeIds(emptyList(), emptyList()).isEmpty())
    check(mergeIds(listOf(7), listOf(7, 7)) == listOf(7))
}
```

Trace the calls to `seen.add`: 3 succeeds, 1 succeeds, the second 3 fails, the next 1 fails, and 2 succeeds. With expected constant-time hash-set operations, this takes expected O(n + m) time and O(n + m) additional space, including the concatenated list. Scanning the growing output list for every identifier would instead have quadratic worst-case time.

**Try it:** remove the concatenated intermediate list while preserving the result. Then decide how the rule changes if a later page contains a newer version of the same item. Explain whether the first or latest item should win before changing your implementation.

## Worked example: find a value in sorted identifiers

For `[2, 5, 8, 12, 19]`, search for 12. The middle value is 8, so discard it and everything left of it. Search indices 3 through 4; index 3 contains 12. If the target is 7, the narrowed interval eventually becomes empty and the result is absent.

**Try it:** implement an iterative binary search that returns an index or -1. Check an empty list, one element, first/last elements, a missing value, and duplicates. State whether your implementation returns any occurrence or the first occurrence. Expected search complexity is O(log n) time and O(1) extra space; sorting unsorted input is separate work.

## Continue learning

[Android Engineers Academy](https://www.androidengineers.in/roadmap?utm_source=github&utm_medium=repository&utm_campaign=must-know) provides the broader learning paths. Apply a foundation in the [Compose masterclass](https://github.com/AndroidEngineers/jetpack-compose-masterclass), then explain the choice in your project README.

## Contribute

Add one focused explanation or worked exercise with inputs, expected outputs, edge cases, and a complexity or engineering tradeoff. Prefer a reproducible example over extending the topic catalog. Include the checks you ran.
