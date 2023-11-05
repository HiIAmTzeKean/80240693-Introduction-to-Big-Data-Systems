---
tags:
  - 🌱
  - ComputerScience
date: 15--Oct--2023
---
# Client distributed write
Consistency challenges when there are [[Concurrency]] access or machine failures. [[Google file system]] makes a trade off of consistency with performance.

## Procedure

Client communicates with master
Client will first locate the secondary then the primary replica
- The rationale is because there may be concurrent writes

---
Links:
