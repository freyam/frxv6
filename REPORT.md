# Report

This is the fourth assignment for the course **Operating Systems and Networks**.

Xv6 is a simplified operating system developed at MIT. Its main purpose is to explain the main concepts of the operating system by studying an example Kernel. xv6 is a re-implementation of Dennis Ritchie's and Ken Thompson's Unix Version 6 (v6). xv6 loosely follows the structure and style of v6, but is implemented for a modern RISC-V multiprocessor using ANSI C.

As part of the assignment, I have fulfilled the following specifications:

# Specification 1 (System Call Tracing)

To add a new system call `trace` which is called using the user program `strace`.

SYNTAX: `strace mask command [args]`

# Specification 2 (Scheduling Mechanisms)

## First Come First Serve (FCFS)

First Come First Serve (FCFS) is a scheduling algorithm that is used to assign a process to a CPU. The process that is assigned to the CPU is the one that arrives first.

## Priority Based Scheduling (PBS)

Priority Based Scheduling (PBS) is a scheduling algorithm that is used to assign a process to a CPU. The process that is assigned to the CPU is the one with the highest priority.

## Multilevel Feedback Queue (MLFQ)

Multilevel Feedback Queue (MLFQ) is a scheduling algorithm that is used to assign a process to a CPU. The process that is assigned to the CPU is the one with the highest priority. The priority of the process is determined by the number of times it has been assigned to the CPU. The priority of the process is increased by one when it is assigned to the CPU (CPU Bursts). The priority of the process is decreased by one when it is finished executing (IO Bursts).

# Specification 3 (Procdump)

Procdump is a utility that is used to generate a report of the processes that are running on a system.
