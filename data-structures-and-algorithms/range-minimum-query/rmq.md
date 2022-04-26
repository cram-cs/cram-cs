# Range Minimum Query (RMQ)

_Pre-reqs: [todo](#)_

## Problem Statement

- Preprocess an array of numbers.
- Support queries on range `[i, j]` that returns the _index_ of minimum value in the range.

*Example*

| index |  0 |  1 |  2 |  3 |  4 |  5 |  6 |  7 | 8  |  9 | 10 |
| ----- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| value |  3 |  7 |  9 | 22 |  8 |  6 |  2 | 17 | 10 |  1 |  5 |

- `RMQ(2, 8) = 6`
  - The value at `array[6] = 2`, which is the smallest between indices 2 to 8
