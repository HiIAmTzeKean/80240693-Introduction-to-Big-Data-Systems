---
tags:
  - 🌱
  - ComputerScience
date: 15--Oct--2023
---
# Distributed file storage
Duplicating chucks of files in multiple machine nodes which is similar to [[RAID 1]]. The question raised would be how to distribute the data among the nodes.
## Google file system solution
One solution would be to have 3 replicas
1. Locally
2. Remote rack
3. Another replica on the same remote rack
There would be a google file  [[Master server]]  that indicates where the file chunks, this data is known as [[Meta data]]. The [[Chunk server]] will store the data and serve data to clients.

- [[Client distributed read]]
- [[Client distributed write]]

---
Links:
