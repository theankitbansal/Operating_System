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


