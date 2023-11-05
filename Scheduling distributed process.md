---
tags:
  - 🌱
  - ComputerScience
date: 21--Oct--2023
---
# Scheduling distributed process
MPI has issues with scheduling processes since failures are hard to detect and not [[Fault tolerant]]. This is one of the reasons why it is not chosen to do [[Distributed computing system]].

## Collective MPI
Through use of simplified MPI [[API]] there is no need to manage processes individually.

## OpenMP
Able to manage scheduling but it does not tackle fault tolerance, rather [[Load balancing]].

---
Links:
