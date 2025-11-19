# Basic forks and C Style Development

Basic forks and C Style Development is my second assignment for the Operating Systems Course.

## Overview

This Project Demonstrates the fork() call, Starting and Stopping processes and Linker and Loader.

## Project Contents

This Project contains:  


Source Code:  
fork(): Lab5Ex1.c  
Linker: file1BeforeMod.c , file1AfterMod.c , file2.c
Loader: Lab5_6.c


Test Screenshots for each:  
fork(): Lab5Ex1_CompliedSC.png  
Process creation in background: Lab5Ex2_CompliedSC.png  
Stopping Processes: Lab5Ex3_CompliedSC.png  
Pausing and Continuing a process: Lab5Ex4_CompliedSC.png  
Linker: Lab5Ex5_BeforeModifying_CompliedSC.png, Lab5Ex5_AfterModifying_CompliedSC.png  
Loader: Lab5Ex6_CompliedSC.png  
Makefile : Makefile_Testing.png

Makefile:  
Makefile.txt

## How to Compile
All programs can be compiled using the included Makefile:

```bash
make          # Build all programs
make fork     # Build only fork.c
make fileprog # Build file1.c + file2.c program
make simple   # Build simple.c program
```
## License

[MIT](https://choosealicense.com/licenses/mit/)
