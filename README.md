# simple-multiprogramming-batch-operating-system.

this project, required to program a simulation of a simple multiprogramming batch
operating system. The system hardware specifications assumed in the simulation are as follows: 

1. A single- core CPU.
2. A hard disk with 2 GB available for user programs.
3. A RAM with 192 MB available for user programs.
4. A single IO device.

The simulation covers two features of the operating system:
1. Job scheduling: The operating system maintains a single job queue. Job Scheduler follows the
Smallest Storage Requirement (SSR) policy.
2. Process scheduling. The operating system maintains a single ready queue and a single I/O
queue. CPU Scheduler follows the First-Come, First-Served (FCFS) scheduling algorithm policy.
