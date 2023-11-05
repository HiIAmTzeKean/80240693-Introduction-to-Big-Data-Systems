---
tags:
  - 🌱
  - ComputerScience
date: 22--Oct--2023
modified: 29--Oct--2023
---
# MapReduce
A [[Functional programming]] idea to implement parallel processing.

Allows the [[Parallelism]] to occur without the programmer from specifying the details.

## Implementation
[[Reduce function]]
[[Map function]]

Once the [[Map function]] is done, the results will be passed to a barrier and [[Shuffling function]] is done before it is passed to the [[Reduce function]].

## Challenges
It is an iterative algorithm and thus can only solve problems sequentially.

---
Links: [[deanMapReduceSimplifiedData2008]]
