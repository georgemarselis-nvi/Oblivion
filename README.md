# Oblivion
Oblivion is a hardware-software HPC checkpointing appliance that captures and restores full process and memory state across clusters in seconds.

Built from EPYC + NVMe + InfiniBand + DPU nodes, it forms a distributed RDMA-tier "memory vault" where running applications can be suspended, stored, and resumed transparently.
It integrates CRIU-style process capture with erasure-coded NVMe striping to achieve sub-minute, crash-resilient checkpointing for any workload, no code changes required.

This will be perfect for bioinformatics application snapshots and models, cuz if the app/model crashes you can open the contents of the memory on disk and see what went wrong. 

# Take an arrow to the knee

Save the process to disk

# I used to be an adventurer like you 

Restore the process

