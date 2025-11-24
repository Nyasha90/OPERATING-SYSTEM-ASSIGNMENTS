# OPERATING-SYSTEM-ASSIGNMENTS

📚 Operating System Lab Assignments Summary
The provided documents detail four distinct Lab Assignments for the ENCS351 Operating System Lab course, designed for B.Tech CSE, AI ML, Data Science, Cyber, FSD, and UX/UI programs. Each assignment focuses on core OS concepts using Python 3.x on a Linux OS environment.


Lab 1 

Process Creation and Management Using Python OS Module	
Process creation (fork, exec), child-parent relationship, Zombie and Orphan processes, inspecting process info from /proc, process prioritization using nice() values.
os, subprocess modules.


Lab 2 

System Startup, Process Creation, and Termination Simulation in Python	
System booting, concurrent process creation (multiprocessing), process lifecycle logging.
multiprocessing, logging, time modules.


Lab 3 

Simulation of File Allocation, Memory Management, and Scheduling in Python	
CPU Scheduling (Priority, Round Robin), File Allocation (Sequential, Indexed), Memory Allocation (Worst-fit, Best-fit, First-fit), Memory Management (MFT, MVT).
Python 3.x.


Lab 4 

System Calls, VM Detection, and File System Operations using Python	
Batch Processing simulation, System Startup and Logging (similar to Lab 2), System Calls/IPC (fork, exec, wait, pipe), VM Detection, CPU Scheduling (FCFS, SJF, Round Robin, Priority).
Python 3.x, Linux OS, os, platform, subprocess modules, Bash shell, C programming.


Detailed Task Overviews
Lab Assignment 1: Process Creation and Management
Task 1: Create N child processes using os.fork(). Parent must os.wait() for children.


Task 2: Child processes execute a Linux command (e.g., ls, date) using os.execvp() or subprocess.run().


Task 3: Simulate Zombie (parent skips wait()) and Orphan (parent exits first) processes and verify using ps -el | grep defunct. * Task 4: Read and print process info (name, state, memory) from /proc/[pid]/status, executable path from /proc/[pid]/exe, and file descriptors from /proc/[pid]/fd.


Task 5: Create CPU-intensive child processes and assign different nice() values to demonstrate scheduler impact on priority.

Lab Assignment 2: System Startup, Process Creation, and Termination Simulation

Objective: Simulate system startup and process lifecycle logging.

Sub-Tasks:

Initialize logging configuration to capture timestamped messages to process_log.txt.

Define a function to simulate a process task (e.g., time.sleep(2)).

Create and concurrently start at least two child processes using multiprocessing.

Use .join() to ensure proper termination and verify the log file output.

Lab Assignment 3: File Allocation, Memory Management, and Scheduling

Task 1: CPU Scheduling: Implement Priority and Round Robin algorithms and compute average Waiting Time (WT) and Turnaround Time (TAT).


Task 2 & 3: File Allocation: Simulate Sequential and Indexed file allocation strategies in Python. * Task 4: Contiguous Memory Allocation: Implement Worst-fit, Best-fit, and First-fit strategies for allocating processes to memory partitions.


Task 5: MFT & MVT Memory Management: Implement MFT (Fixed Partitions) and MVT (Variable Partitions) strategies.

Lab Assignment 4: System Calls, VM Detection, and File System Operations

Task 1: Batch Processing: Write a Python script using subprocess.call() to execute multiple .py files sequentially.


Task 2: System Startup and Logging: Simulate system startup using multiprocessing and logging (similar to Lab 2).


Task 3: System Calls and IPC: Use os.fork(), os.exec(), os.wait(), and implement Inter-Process Communication (IPC) using pipes in C or Python. * Task 4: VM Detection: Create a shell script to print system details and a Python script to programmatically detect if the system is running inside a Virtual Machine (VM).


Task 5: CPU Scheduling Algorithms: Implement FCFS, SJF, Round Robin, and Priority Scheduling algorithms to calculate WT and TAT (referencing existing code from Lab 3).
