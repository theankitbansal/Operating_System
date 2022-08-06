# Operating_System
Operating System Interview Questions


1. Why is the operating system important?

OS is the most essential and vital part of a computer without which it is considered useless. It enables an interface or acts like a link for interaction between computer software that is installed on OS and users. It also helps to communicate with hardware and also maintains balance among hardware and CPU. It also provides services to users and a platform for programs to run on. It performs all common tasks applications require. 

2. What's the main purpose of an OS? What are the different types of OS?

The main purpose of an OS is to execute user programs and make it easier for users to understand and interact with computers as well as run applications. It is specially designed to ensure that the computer system performs better by managing all computational activities. It also manages computer memory, processes, and operation of all hardware and software.

Types of OS:

Batched OS (Example: Payroll System, Transactions Process, etc.)
Multi-Programmed OS (Example: Windows O/S, UNIX O/S, etc.)
Timesharing OS (Example: Multics, etc.)
Distributed OS (LOCUS, etc.)
Real-Time OS (PSOS, VRTX, etc.)

3. What are the benefits of a multiprocessor system?

A Multiprocessor system is a type of system that includes two or more CPUs. It involves the processing of different computer programs at the same time mostly by a computer system with two or more CPUs that are sharing single memory. 

Benefits:

Such systems are used widely nowadays to improve performance in systems that are running multiple programs concurrently. 
By increasing the number of processors, a greater number of tasks can be completed in unit time. 
One also gets a considerable increase in throughput and is cost-effective also as all processors share the same resources.
It simply improves the reliability of the computer system.

4. What is RAID structure in OS? What are the different levels of RAID configuration?

RAID (Redundant Arrays of Independent Disks) is a method used to store data on Multiple hard disks therefore it is considered as data storage virtualization technology that combines multiple hard disks. It simply balances data protection, system performance, storage space, etc. It is used to improve the overall performance and reliability of data storage. It also increases the storage capacity of the system and its main purpose is to achieve data redundancy to reduce data loss. 

Different levels of RAID

Nowadays, RAID is available in various schemes or RAID level as given below:

![image](https://user-images.githubusercontent.com/81725794/183254380-a290d1f2-240e-4f45-82f0-cadfaa1d1c44.png)

RAID 0 - Non-redundant striping: This level is used to increase the performance of the server.
RAID 1 - Mirroring and duplexing: This level is also known as disk mirroring and is considered the simplest way to implement fault tolerance.
RAID 2 - Memory-style error-correcting codes: This level generally uses dedicated hamming code parity I.e., a liner form of error correction code.
RAID 3 - Bit-interleaved Parity: This level requires a dedicated parity drive to store parity information.
RAID 4 - Block-interleaved Parity: This level is similar to RAID 5 but the only difference is that this level confines all parity data to a single drive.
RAID 5 - Block-interleaved distributed Parity: This level provides far better performance than disk mirroring and fault tolerance.
RAID 6 - P+Q Redundancy: This level generally provides fault tolerance for two drive failures.

5. What is GUI?

GUI (Graphical User Interface) is basically a type of user interface that allows users to use graphics to interact with OS. GUI is created because it is more user-friendly, less complex, and easier to understand rather than a command-line interface. Its main goal is to increase efficiency and ease of use. Instead of having to memorize commands, users can just click on a button to simply execute the procedure. Examples of GUI include Microsoft Windows, macOS, Apple’s iOS, etc.

6. What is a Pipe and when it is used?

The pipe is generally a connection among two or more processes that are interrelated to each other. It is a mechanism that is used for inter-process communication using message passing.  One can easily send information such as the output of one program process to another program process using a pipe. It can be used when two processes want to communicate one-way i.e., inter-process communication (IPC).

7. What are the different kinds of operations that are possible on semaphore?

There are basically two atomic operations that are possible:

Wait()
Signal()
8. What is a bootstrap program in OS?

It is generally a program that initializes OS during startup i.e., first code that is executed whenever computer system startups. OS is loaded through a bootstrapping process or program commonly known as booting. Overall OS only depends on the bootstrap program to perform and work correctly. It is fully stored in boot blocks at a fixed location on the disk. It also locates the kernel and loads it into the main memory after which the program starts its execution.

![image](https://user-images.githubusercontent.com/81725794/183254404-42248347-d82d-454b-b102-fefc855a9c6a.png)

9. Explain demand paging?

Demand paging is a method that loads pages into memory on demand. This method is mostly used in virtual memory. In this, a page is only brought into memory when a location on that particular page is referenced during execution. The following steps are generally followed:

Attempt to access the page.
If the page is valid (in memory) then continue processing instructions as normal.
If a page is invalid then a page-fault trap occurs.
Check if the memory reference is a valid reference to a location on secondary memory. If not, the process is terminated (illegal memory access). Otherwise, we have to page in the required page.
Schedule disk operation to read the desired page into main memory.
Restart the instruction that was interrupted by the operating system trap.

10. What do you mean by RTOS?

Real Time Operating System (RTOS) is an operating system that is used for real-time applications i.e., for those applications where data processing should be done in a fixed and small measure of time. It performs much better on tasks that are needed to be executed within a short time. It also takes care of execution, monitoring, and all-controlling processes. It also occupies less memory and consumes fewer resources. 

Types of RTOS:

Hard Real-Time
Firm Real-Time
Soft Real-Time

![image](https://user-images.githubusercontent.com/81725794/183254437-dae44043-dea6-4872-9055-7b541bc3c77b.png)

RTOS is used in Air traffic control systems, Anti-lock Brake Systems, and Heart pacemakers.

11. What do you mean by process synchronization?

Process synchronization is basically a way to coordinate processes that use shared resources or data. It is very much essential to ensure synchronized execution of cooperating processes so that will maintain data consistency. Its main purpose is to share resources without any interference using mutual exclusion. There are two types of process synchronization:

Independent Process
Cooperative Process

12. What is IPC? What are the different IPC mechanisms?

IPC (Interprocess Communication) is a mechanism that requires the use of resources like a memory that is shared between processes or threads. With IPC, OS allows different processes to communicate with each other. It is simply used for exchanging data between multiple threads in one or more programs or processes. In this mechanism, different processes can communicate with each other with the approval of the OS.

Different IPC Mechanisms:

Pipes
Message Queuing
Semaphores
Socket
Shared Memory
Signals

13. What is different between main memory and secondary memory.

Main memory: Main memory in a computer is RAM (Random Access Memory). It is also known as primary memory or read-write memory or internal memory. The programs and data that the CPU requires during the execution of a program are stored in this memory.
Secondary memory: Secondary memory in a computer are storage devices that can store data and programs. It is also known as external memory or additional memory or backup memory or auxiliary memory. Such storage devices are capable of storing high-volume data. Storage devices can be hard drives, USB flash drives, CDs, etc. 

![Screenshot (982)](https://user-images.githubusercontent.com/81725794/183254515-98838e55-6d8f-4a50-a406-4936220376d2.png)

14. What do you mean by overlays in OS?

Overlays is basically a programming method that divides processes into pieces so that instructions that are important and need can be saved in memory. It does not need any type of support from the OS. It can run programs that are bigger in size than physical memory by only keeping only important data and instructions that can be needed at any given time. 

15. Write top 10 examples of OS?

Some of the top OS’s that are used mostly are given below:

MS-Windows
Ubuntu
Mac OS
Fedora
Solaris
Free BSD
Chrome OS
CentOS
Debian
Android

Intermediate OS Interview Questions

16. What is virtual memory?

It is a memory management technique feature of OS that creates the illusion to users of a very large (main) memory. It is simply space where a greater number of programs can be stored by themselves in the form of pages. It enables us to increase the use of physical memory by using a disk and also allows us to have memory protection. It can be managed in two common ways by OS i.e., paging and segmentation. It acts as temporary storage that can be used along with RAM for computer processes. 

![image](https://user-images.githubusercontent.com/81725794/183254565-575660a8-cca4-4eaf-b532-91f2c4896b90.png)

17. What is thread in OS?

Thread is a path of execution that is composed of a program counter, thread id, stack, and set of registers within the process. It is a basic unit of CPU utilization that makes communication more effective and efficient, enables utilization of multiprocessor architectures to a greater scale and greater efficiency, and reduces the time required in context switching. It simply provides a way to improve and increase the performance of applications through parallelism. Threads are sometimes called lightweight processes because they have their own stack but can access shared data. 

Multiple threads running in a process share: Address space, Heap, Static data, Code segments, File descriptors, Global variables, Child processes, Pending alarms, Signals, and signal handlers. 

Each thread has its own: Program counter, Registers, Stack, and State.

![image](https://user-images.githubusercontent.com/81725794/183254583-e155df2f-595c-4db7-9c3d-0789b73d7118.png)

18. What is a process? What are the different states of a process?

The process is basically a program that is currently under execution. The main function of an OS is to manage and handle all of these processes. When a program is loaded into the memory and it becomes a process, it can be divided into four sections ─ stack, heap, text, and data. There are two types of processes:

1. Operating System Processes
2. User Processes

![image](https://user-images.githubusercontent.com/81725794/183254606-e523b891-e8e3-4e22-87c0-3f0a7ed3a566.png)

States of Process:

Different states of the process through which process goes are given below:

New State: In this state, a process is just created.
Running: In this state, the CPU starts working on the process’s instructions.
Waiting: In this state, the process cannot run because it just waits for some event to occur
Ready: In this state, the process has all resources available that are required to run but it waits to get assigned to a processor because CPUs are not working currently on instructions passed by the process.
Terminate: In this state, the process is completed I.e., the process has finished execution.

19. What do you mean by FCFS?

FCFS (First Come First Serve) is a type of OS scheduling algorithm that executes processes in the same order in which processes arrive. In simple words, the process that arrives first will be executed first. It is non-preemptive in nature. FCFS scheduling may cause the problem of starvation if the burst time of the first process is the longest among all the jobs. Burst time here means the time that is required in milliseconds by the process for its execution. It is also considered the easiest and simplest OS scheduling algorithm as compared to others. Implementation of FCFS is generally managed with help of the FIFO (First In First Out) queue. 

20. What is Reentrancy?

Reentrant is simply a function in which various clients can use and shares a single copy of a program during a similar period. This concept is generally associated with OS code and does not deal with concurrency. It has two major functions:

Program code cannot change or modify itself.
Local data for every client process needs to be stored in different disks.

21. What is a Scheduling Algorithm? Name different types of scheduling algorithms.

A scheduling algorithm is a process that is used to improve efficiency by utilizing maximum CPU and providing minimum waiting time to tasks. It simply deals with the problem of deciding which of outstanding requests is to be allocated resources. Its main aim is to reduce resource starvation and to ensure fairness amongst parties that are utilizing the resources. In simple words, it is used to allocate resources among various competing tasks. 

Types of Scheduling Algorithm

There are different types of scheduling algorithms as given below:

![image](https://user-images.githubusercontent.com/81725794/183254628-58d7b292-6762-465e-b20b-bb8a1ac0583f.png)


