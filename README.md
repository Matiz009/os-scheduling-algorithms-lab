# OS Scheduling Algorithms Lab

C and C++ programs from my Operating Systems lab: CPU scheduling, memory allocation, paging and deadlock avoidance.

## Features

- CPU scheduling: FCFS (`fcfs.c`), Round Robin (`rr.c`, `rr2.c`, `rr3.c`, `rr.cpp`), non-preemptive priority (`priority-np.c`, with arrival time in the `.cpp` version), Shortest Job First (`shortest-j-f.c`) and SRTF (`srtf.c`)
- Memory allocation: first fit (`first fit.c`) and worst fit (`worst fit.c`)
- Paging (`paging.c`, `Pagging (OS).c`)
- Banker's algorithm (`bankers.c`, `Banker's algorithm.cpp`)
- Lab exam practice questions

## Tech stack

C, C++ (GCC)

## Getting started

```bash
git clone https://github.com/Matiz009/os-scheduling-algorithms-lab.git
cd os-scheduling-algorithms-lab
gcc fcfs.c -o fcfs && ./fcfs
```

Each program is standalone and reads its input from the console.

## Project structure

One source file per algorithm, in the repo root. The `.exe` and `.o` files are old Windows build outputs.

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
