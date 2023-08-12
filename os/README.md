# Table of Content
## 1. [Introduction to Operating System](Readme.md#1.%20Introduction%20to%20Operating%20System)
*teaching hours: 2 hrs*
  
`1.1.`History
`1.2.` Introduction and Generation of Operating System
`1.3.` Objectives(Resource Manager and Extended Machine)
`1.4.` Types of Operating system
`1.5.` Function of Operating system.


## 2. [Operating System Structure](Readme.md#2.%20Operating%20System%20Structure)
*teaching hours: 2 hrs*
  
`2.1.` Introduction
`2.2.` Layered System
`2.3.` Kernel
`2.4.` Types of Kernel (Monolithic/Macro Kernel and Micro / Exo-Kernel)
`2.5.` Client-Server Model
`2.6.` Virtual Machines
`2.7.` Shell


## 3. [Process Management](Readme.md#3.%20Process%20Management)
*teaching hours: 15 hrs*
  
#### 3.1. Process Concepts:
`3.1.1.` Definitions of Process
`3.1.2.` The Process Model
`3.1.3.` Process States
`3.1.4.` Process State Transition
`3.1.5.` The Process Control Block
`3.1.6.` Operations on Processes (Creation, Termination, Hierarchies, Implementation)
`3.1.7.` Cooperating Processes
`3.1.8.` System Calls (Process Management, File Management, Directory Management)
  
#### 3.2. Threads:** 
`3.2.1.` Definitions of Threads
`3.2.2.` Types Of Thread Process(Single and Multi-threaded Process)
`3.2.3.` Benefits of Multi-thread
`3.2.4.` Multi-threading Models (Many-to-One-Model, One-to-One Model, Many-to-Many Model)
  
#### 3.3. Inter-Process Communication and Synchronization:
`3.3.1.` Introduction
`3.3.2.` Race Condition
`3.3.3.` Critical Regions
`3.3.4.` Avoiding Critical Region: Mutual Exclusion And Serializability
`3.3.5.` Mutual Exclusion Conditions
`3.3.6.` Proposals for Achieving Mutual Exclusion
`3.3.7.` Disabling Interrupts
`3.3.8.` Lock Variable
`3.3.9.` The #TSL ==(Test and Set Lock)== Instruction 
`3.3.10.` Strict Alteration (Peterson's Solution)
`3.3.11.` Sleep and Wake-up
`3.3.12.` Types of Mutual Exclusion (Semaphore, Monitors, Mutexes, Message Passing, Bounded Buffer)
`3.3.13.` Serializability: Locking Protocols and Time Stamp Protocols
`3.3.14.` Classical #IPC ==Inter Process Communication== Problems (Dinning philosophers Problems, The Readers and Writers Problem, The Sleeping Barber's Problem)
  
#### 3.4. Process Scheduling:
`3.4.1.` Basic Concept
`3.4.2.` Type of Scheduling (Preemptive Scheduling, Non-preemptive Scheduling, Batch, Interactive, Real Time Scheduling)
`3.4.3.` Scheduling Criteria or Performance Analysis
`3.4.4.` Scheduling Algorithm( #RR Round-Robin, #FCFS First Come First Served, #SJF Shortest-Job- First, #SPN Shortest Process Next, #SRT Shortest Remaining Time Next, Real Time, Priority Fair Share, Guaranteed, Lottery Scheduling, HRN, Multiple Queue, Multilevel Feedback Queue)   #SJF = #SPN 
`3.4.5.` Some Numerical Examples on Scheduling.


## 4. [Deadlocks](Readme.md#4.%20Deadlocks)
*teaching hours: 4 hrs*
  
`4.1.` System Model
`4.2.` System Resources: Premptable and Non-Preemptable
`4.3.` Conditions for Resource Deadlocks
`4.4.` Deadlock Modeling
`4.5.` The OSTRICH Algorithm
`4.6.` Method of Handling Deadlocks
`4.7.` Deadlock Prevention
`4.8.` Deadlock Avoidance: Banker's Algorithm
`4.9.` Deadlock Detection: Resource Allocation Graph
`4.10.` Recovery from Deadlock.


## 5. [Memory Management](Readme.md#5.%20Memory%20Management)
*teaching hours: 7 hrs*
  
#### 5.1. Basic Memory Management:
`5.1.1.` Introduction
`5.1.2.` Memory Hierarchy
`5.1.3.` Logical Versus Physical Address Space
`5.1.4.` Memory Management with Swapping: Memory Management with Bitmaps and with Linked List
`5.1.5.` Memory Management without Swapping
`5.1.6.` Contiguous-Memory Allocation: Memory Protection
`5.1.7.` Contiguous-Memory Allocation: Memory Allocation
`5.1.8.` Contiguous-Memory Allocation: Fragmentation(Inter-Fragmentation and External Fragmentation)
`5.1.9.` Non-Contiguous Memory location
`5.1.10.` Fixed Partitioning Vs. Variable Partitioning
`5.1.11.` Reallocation and Protection
`5.1.12.` Coalescing and Compaction

 
#### Virtual Memory:
`5.2.1.` Background
`5.2.2.` Paging
`5.2.3.` Structure of Page Table
`5.2.4.` Hierarchical Page Table
`5.2.5.` Hashed Page Table
`5.2.6.` Inverted Page Table
`5.2.7.` Shared Page Table
`5.2.8.` Block Mapping Vs. Direct Mapping
`5.2.9.` Demand Paging
`5.2.10.` Page Replacement and Page Faults
`5.2.11.` Page Replacement Algorithms: #FIFO==First-In-First-Out==, #OPR==Optimal Page Request==, #LRU==Least Recently Used==, #SCP==Second Chance Page Request==
`5.2.12.` Some Numerical Examples on Page Replacement
`5.2.13.` Thrashing
`5.2.14.` Segmentation
`5.2.15. `Segmentation With Paging. 


## 6. [Input/Output Device Management](Readme.md#6.%20Input/Output%20Device%20Management)
*teaching hours: 4 hrs*
  
`6.1.` Principle of I/O Devices
`6.2.` I/O Devices
`6.3.` Device Controllers
`6.4.` Memory Mapped I/O
`6.5.` Direct Memory Access #DMA
`6.6.` Principle of I/O Software
`6.7.` Goals of I/O Software
`6.8.` Program I/O, Interrupt - Driven I/O, I/O Using DMA #DMA
`6.9.` I/O Software Layers
`6.10.` Interrupts Handler
`6.11.` Device Drivers
`6.12.` Device Independent I/O Software
`6.13.` User-Space I/O Software
`6.14.` Disk Hardware
`6.15.` Disk Scheduling: Seek Time, Rational Delay, Transfer Time
`6.16.` Disk Scheduling Algorithms
`6.17.` #FCFS ==First Come First Served== Scheduling
`6.18.` #SSTF ==Short Seek Time First== Scheduling
`6.19.` SCAN Scheduling ==(Elevator / LOOK)==
`6.20.` C-SCAN Scheduling ==(Circular / C-LOOK)==
`6.21.` Lock Scheduling

  
## 7. [File System Interface Management](Readme.md#7.%20File%20System%20Interface%20Management)
*teaching hours: 2 hrs*
  
`7.1.` File Concept
`7.2.`  File Naming
`7.3.`  File Structure
`7.4.` File Type
`7.5.` File Access
`7.6.` File Attributes
`7.7.` File Operation and File Descriptors
`7.8.` Directories
`7.9.` Single-Level Directory Systems
`7.10.` Hierarchical Directory Systems
`7.11.` Path Names
`7.12.` Directory Operation
`7.13.` Access Methods: Sequential, Direct
`7.14.` Protection
`7.15.` Types of Access
`7.16.` Access Control List
`7.17.` Access Control Matrix


## 8. [Security Management](Readme.md#8.%20Security%20Management)
*teaching hours: 3 hrs*
  
`8.1.` Introduction
`8.2.` Security Problems
`8.3.` User Authentication
`8.4.` Passwords
`8.5.` password Vulnerabilities
`8.6.` Encrypted password
`8.7.` One Time Password
`8.8.` Bio-metric password
`8.9.` User Authorization

#### Program Threats**
`8.10.` Trojan Horse
`8.11.` Trap Door
`8.12.` Stack and Buffer Overflow

#### System Threats**
`8.13.` Worms
`8.14.` Viruses
`8.15.` Denial of Services


## 9. [Distributed Operating System](Readme.md#9.%20Distributed%20Operating%20System)
*teaching hours: 4 hrs*
  
`8.1.` Introduction
`8.2.` Advantages of Distributed System over Centralized System
`8.3.` Advantages of Distributed System over Independent PCs
`8.4.` Disadvantages of Distributed System
`8.5.` Hardware and Software Concepts
`8.6.` Communication in Distributed Systems
`8.7.` Message Passing
`8.8.` Remote Procedure Call
`8.9.` Process in Distribution System
`8.10.` Clock Synchronization


# 1. Introduction to Operating System
  
`1.1.` History
- 1st Generation: User Driven
- 2nd Generation: Batch
- 3rd Generation: Multi-programming
- 4th Generation: Client Server/ Distributed

`1.2.` Introduction and Generation of Operating System

>An operating system (OS) is a collection of system programs that
together control the operation of a computer system.

`1.3.` Objectives(Resource Manager and Extended Machine)
- Execute user programs and make solving user problems easier.
- Make the computer system convenient to use.
- Use the computer hardware in an efficient manner.

> OS as an Extended Machine Because OS creates higher-level abstraction for programmer.
> OS as a Resource Manager because OS primary function is to manage all pieces of a complex system.

`1.4.` Types of Operating system

	Batch System
	Spooling (Simultaneous Peripheral Operation On Line)
	Multiprogramming
	Timesharing
	Personal Computer
	Real-Time Systems
	Handheld System
	Distributed System
	Network OS

`1.5.` Function of Operating system.

	- Security
	- Control over System Performance
	- Error Defecting Aids
	- Memory Management
	- Process Management
	- Device Management


# 2. Operating System Structure
*teaching hours: 2 hrs*
  
`2.1.` Introduction

> Operating system is a software that acts as an intermediary between the user and computer hardware. It is a program with the help of which we are able to run various applications.

`2.2.` Layered System

> Layered Structure is a type of system structure in which the different services of the operating system are split into various layers, where each layer has a specific well-defined task to perform.
![[layered_os.jpg]]

`2.3.` Kernel

> Kernel is central component of an operating system that manages operations of computer and hardware.
>	- To establish communication between user level application and hardware. 
>	- To decide state of incoming processes.  
>	- To control disk management.  
>	- To control memory management. 
>	- To control task management.



`2.4.` Types of Kernel (Monolithic/Macro Kernel and Micro / Exo-Kernel)


>`. Monolithic Kernel`
> It is one of types of kernel where all operating system services operate in kernel space.
> Ex: Unix, Linux, Open VMS, XTS-400 etc.
>
>`. Micro Kernel`
It is kernel types which has minimalist approach.
Ex: Mach, L4, AmigaOS, Minix, K42 etc.

![[kernel_types.jpg]]

>`. Hybrid Kernel`
>It is the combination of both monolithic kernel and microkernel. It has speed and design of monolithic kernel and modularity and stability of microkernel.
> Ex: Windows NT, Netware, BeOS etc.

**System Call**

>A system call is a programmatic way in which a computer program requests a service from the kernel of the operating system it is executed on.
![[system_call.jpg]]

**System Program**

>System Programming can be defined as the act of building Systems Software using System Programming Languages.
![[system_program.jpg]]

`2.5.` Client-Server Model

>The Client-server model is a distributed application structure that partitions task or workload between the providers of a resource or service, called servers, and service requesters called clients
![[client_server.jpg]]



`2.6.` Virtual Machines

>Virtual Machine abstracts the hardware of our personal computer such as CPU, disk drives, memory, NIC (Network Interface Card) etc, into many different execution environments as per our requirements, hence giving us a feel that each execution environment is a single computer.
![[virtual_machine.jpg]]

`2.7.` Shell

>A shell is a special user program that provides an interface for the user to use operating system services.
![[shell.jpg]]


# 3. Process Management 
  
#### 3.1. Process Concepts: 
`3.1.1.` Definitions of Process

	Cook: Cpu
	Cake: Program
	Ingredent: Input Data
	Activities: Process

`3.1.2.` The Process Model
![[process_model.jpg]]


`3.1.3.` Process States
`3.1.4.` Process State Transition

![[process_queue.png]]

`3.1.5.` The Process Control Block
![[process_control_block.png]]
![[context_switching.png]]

`3.1.6.` Operations on Processes (Creation, Termination, Hierarchies, Implementation)
`3.1.7.` Cooperating Processes
`3.1.8.` System Calls (Process Management, File Management, Directory Management)

> A system call is a programmatic way in which a computer program requests a service from the kernel of the operating system it is executed on.
![[system_call.jpg]]
  
#### 3.2. Threads: 
`3.2.1.` Definitions of Threads

>Thread is light weight process.
> Ex: Checking spelling typing in Word.
  ![[user_vs_kernel_thread.png]]
  
`3.2.2.` Types Of Thread Process(Single and Multi-threaded Process)
![[threading.png]]

`3.2.3.` Benefits of Multi-thread
`3.2.4.` Multi-threading Models (Many-to-One-Model, One-to-One Model, Many-to-Many Model)

#### 3.3. Inter-Process Communication and Synchronization: #IPC
`3.3.1.` Introduction

> Inter-process communication (IPC) is a mechanism that allows processes to communicate with each other and synchronize their actions.
Process created:
> - Executing program
> - Subprocess
> - Daemon Email, Printer
![[interprocess_communication.png]]

`3.3.2.` Race Condition

>Two or more action implement on same process is called Race Condition.
Ex: Writing two data in one file.

`3.3.3.` Critical Regions

> A part of program where shared resource is accessed is called Critical Section.
![[critical_section.png]]

`3.3.4.` Avoiding Critical Region: Mutual Exclusion And Serializability

| ==X==                | Solving                           |
| ---------------- | --------------------------------- |
| Mutual Exclusion | No two process run simultaneously |
| Bounded Waiting  | No process run forever            |
| Progress         | No process block from outside     |
| Arbitrary Speed  | No assumption of time required    |

`3.3.5.` Mutual Exclusion Conditions

> Way of making sure that if one process is using a shared variable or file; the other process will be excluded (stop) from doing the same thing.
![[mutual_exclusion.png]]
![[mutual_exclusion_algorithm.jpg]]

`3.3.6.` Proposals for Achieving Mutual Exclusion

	. At any time, only one process is allowed to enter its critical section.
	. The solution is implemented purely in software on a machine.
	. A process remains inside its critical section for a bounded time only.
	. No assumption can be made about the relative speeds of asynchronous concurrent processes.
	. A process cannot prevent any other process from entering into a critical section.
	. A process must not be indefinitely postponed from entering its critical section.

`3.3.7.` Disabling Interrupts
![[disable_lock.png]]

`3.3.8.` Lock Variable

> The variable that used as lock (flag) for the entering critical section is called lock variable.


`3.3.9.` The #TSL ==(Test and Set Lock)== Instruction 
![[test_and_set_lock.png]]

- [ ] Lock

| array | 0   | 1   | 2   | 3   | 4   | 5   |
| ----- | --- | --- | --- | --- | --- | --- |


`3.3.10.` Strict Alteration (Peterson's Solution)
![[strict_alteration.png]]
- [ ] Flag Turn: I
- [ ] Flag Turn: J

`3.3.11.` Sleep and Wake-up

	wait(S){
	while(S<=0);   // busy waiting
	S--;
	}
	
	signal(S){
	S++;
	}



| `producer ` | Buffer Address |
|:-----------:| -------------- |
|     *N*     | +              |
|     ...     | .              |
|    3000     | .              |
|    2000     | .              |
|    1000     | .              |
|    0000     | .              |
| `Consumer`  | -              |



`3.3.12.` Types of Mutual Exclusion (Semaphore, Monitors, #Mutex ==Mutual Exclusiion Object==, Message Passing, Bounded Buffer)

*Semaphore*

> Semaphore is a normal variable used to coordinate the activities of multiple process in computer.

	// wait 'p', signal 'v' 
	
	wait(semaphore S){
	while(S<=0);   // busy waiting
	S--;
	}
	
	signal(semaphore S){
	S++;
	}
![[semaphore.png]]

*Monitor*

> Monitor is higher level of abstraction that appropriates access to critical region for process syncronization

	 Producer: produce
	 Consumer: wait if counter == 0 & consume if counter > 0
 
![[monitor.png]]

`3.3.13.` Serializability: Locking Protocols and Time Stamp Protocols

> Serializability is a term that is property of a system that describes how different process operates the stored data

| T1      | T2       |
| ------- | -------- |
| read(B) |          |
|         | read(B)  |
|         | write(B) |
| read(A) |          |
|         | read(A)  |
|         | write(A) |

*Lock Protocol*

	. Shared lock
- [ ] Shared lock and unlock 

`. Exclusive lock`

| ==X==   | `A`   | `B`   |
| --- | --- | --- |
| `A`   | AA  | AB  |
| `B`   | BA  | BB    |

*Time Stamp Protocol*
> uses time protocol to read and write

`3.3.14.` Classical #IPC ==Inter Process Communication== Problems (Dinning philosophers Problems, The Readers and Writers Problem, The Sleeping Barber's Problem)

*Dining Philosopher Problem*
>The Dining Philosopher Problem states that K philosophers are seated around a circular table with one chopstick between each pair of philosophers. There is one chopstick between each philosopher. A philosopher may eat if he can pick up the two chopsticks adjacent to him. One chopstick may be picked up by any one of its adjacent followers but not both.
![[dining_pholosopher.png]]

	process P[i]
	while true do{
	    wait(CHOPSTICK[i], CHOPSTICK[i+1 mod 5]);
		THINK;
	    signal(CHOPSTICK[i], CHOPSTICK[i+1 mod 5]);
	    EAT;
	}

*Reader Writer Problem*

	// wait 'p', signal 'v' 
	
	// writing
	do{
		wait(write);  // busy waiting
		// write
		// leave CR/CS
		signal(write);
	}while(True);
	
	// Reading
	do{
		wait(mutux);
		read_count++
		if(read_count == 1){
			wait(read);
		}
		signal(mutux);
		wait(mutux);
		read_count--;
	
		if(read_count == 0){
			signal(write);
		}
		signal(mutux);
	}while(True);

*Sleeping Barber*
![[sleeping_barber.png]]

#### 3.4. Process Scheduling: 
`3.4.1.` Basic Concept
![[schedules.png]]

`3.4.2.` Type of Scheduling (Preemptive Scheduling, Non-preemptive Scheduling, Batch, Interactive, Real Time Scheduling)

| Long Term Scheduler                    | Short Term Scheduler             | Medium Term Scheduler            |
| -------------------------------------- | -------------------------------- | -------------------------------- |
| It is job scheduler                    | It is CPU scheduler              | It is process swapping scheduler |
| It is slow                             | It is fast                       | It is medium                     |
| It select from pool and load to memory | It select from memory to execute | It re-introduce into memory      | 


| Dispatcher                                                       | Scheduler                                                        |
| ---------------------------------------------------------------- | ---------------------------------------------------------------- |
| Module that control CPU to process select by short time schedule | It is activity which selects process among other various process |
| It is code segment                                               | 3 types: short, medium, long                                     |
| No algorithm                                                     | FCFS, SSF, RR                                                    | 


`3.4.3.` Scheduling Criteria or Performance Analysis

`3.4.4.` Scheduling Algorithm( #RR Round-Robin, #FCFS First Come First Served, #SJF Shortest-Job- First, #SPN Shortest Process Next, #SRT Shortest Remaining Time Next, Real Time, Priority Fair Share, Guaranteed, Lottery Scheduling, HRN, Multiple Queue, Multilevel Feedback Queue)   #SJF = #SPN 

*Round Robin*

| process | Arrival Time | Cpu Burst |
| ------- | ------------ | --------- |
| P0      | 0            | 10        |
| P1      | 1            | 6         |
| P2      | 3            | 2         |
| P3      | 5            | 4         |

![[round_robin.jpg]]

`3.4.5.` Some Numerical Examples on Scheduling.

*FCFS (First Come First Served)*
![[first_come_first_served.png]]

*SJF (Short Job First) / SPN (Short Process Next)*
![[short_job_first.png]]

*SRTN (Short Remaining Time Next) / SRTF (Short Remaining Time First)*
![[short_remaining_time_next.png]]

*HRN (Highest Response Next)*

	 (waiting time + burst time) / burst time > High




# 4. Deadlocks 
*teaching hours: 4 hrs*
  
`4.1.` System Model
![[deadlock.jpg]]
![[deadlock_request_allocate.jpg]]

`4.2.` System Resources: Premptable and Non-Preemptable

`4.3.` Conditions for Resource Deadlocks

	- Mutual Exclusion
	- Hold and Wait
	- No preemption
	- Circular Wait

`4.4.` Deadlock Modeling

`4.5.` The OSTRICH Algorithm

`4.6.` Method of Handling Deadlocks

| Deadlock         | Approach                     |
| ---------------- | ---------------------------- |
| Mutual Exclusion | Spool Everything             |
| Hold and Wait    | Request all resource initial |
| No preemption    | Take resource away           |
| Circular Wait    | Order Resource Numerically   | 

`4.7.` Deadlock Prevention

	- Elimination Mutual Exclusion
	- Resource Allocation Graph
	- Banker Algorithm

`4.8.` Deadlock Avoidance: Banker's Algorithm

	1) Let Work and Finish be vectors of length ‘m’ and ‘n’ respectively. 
	Initialize: Work = Available 
	Finish[i] = false; for i=1, 2, 3, 4….n
	2) Find an i such that both 
	a) Finish[i] = false 
	b) Needi <= Work 
	if no such i exists goto step (4)
	3) Work = Work + Allocation[i] 
	Finish[i] = true 
	goto step (2)
	4) if Finish [i] = true for all i 
	then the system is in a safe state 


`4.9.` Deadlock Detection: Resource Allocation Graph

	Let Work and Finish be vectors of length m and n respectively. Initialize Work= Available. For i=0, 1, …., n-1, if Requesti = 0, then Finish[i] = true; otherwise, Finish[i]= false.
	Find an index i such that both 
	a) Finish[i] == false 
	b) Requesti <= Work 
	If no such i exists go to step 4.
	Work= Work+ Allocationi 
	Finish[i]= true 
	Go to Step 2.
	If Finish[i]== false for some i, 0<=i<n, then the system is in a deadlocked state. Moreover, if Finish[i]==false the process Pi is deadlocked.

`4.10.` Recovery from Deadlock.

	- Process Termination
	- Resource Preemption
	- Resource Allocation Graph
	- Priority Inversion
	- RollBack

# 5. Memory Management #
*teaching hours: 7 hrs*
  
#### 5.1. Basic Memory Management: 
`5.1.1.` Introduction

`5.1.2.` Memory Hierarchy
![[memory_hierarchy.png]]

`5.1.3.` Logical Versus Physical Address Space
![[logical_vs_physical_address.webp]]
![[diff_logical_vs_physical_address.jpg]]

*Memory Abstraction*

>It is a abstraction layer between program execution and memory that provide view of memory.

*No memory Abstraction*

>It is running program without requesting memory.
>Ex: A main program executing want to stop. It copies its current state out of main memory. If it want to executes, it retrieve value.



`5.1.4.` Memory Management with Swapping: Memory Management with Bitmaps and with Linked List
![[bit_map.png]]
![[linked_list.jpg]]

`5.1.5.` Memory Management without Swapping

`5.1.6.` Contiguous-Memory Allocation: Memory Protection

`5.1.7.` Contiguous-Memory Allocation: Memory Allocation

	- Best Fit
	- Next Fit
	- Worst Fit
	- First Fit

`5.1.8.` Contiguous-Memory Allocation: Fragmentation(Inter-Fragmentation and External Fragmentation)

>Fragmentation: As process loaded or removed from memory it is broken into little piece. 

`5.1.9.` Non-Contiguous Memory location

`5.1.10.` Fixed Partitioning Vs. Variable Partitioning

	Uni-programming: run program at time.
	Multi-programming fixed partition: Address already fixed
	Multi-programming variable partition: Dynamic Address

`5.1.11.` Reallocation and Protection
>Reallocation:
>It is a process of assigning load address for position dependent code and data of program and adjusting the code and data to reflect the assigned address.
>
>Protecting:
>It is way to control memory access right on computer.

`5.1.12.` Coalescing and Compaction
>Coalescing:
>It is a process of merging adjacent holes to form a single larger hole.
>
>Compaction:
>When swapping creates multiple hole in memory, it os possible to combine them all in one big hole by moving all the process downward as far as possible.
 
#### Virtual Memory: 
`5.2.1.` Background
>It is a storage allocation scheme in which secondary memory can be addressed as through it were part of the main memory.

`5.2.2.` Paging
>It is a storage mechanism used to retrieved process from the secondary storage to main memory in form of page.

>Working Set: The set of page that number of a process id.
>Page Fault: When particular page is not found in page table.
>Trashing: A program caused page fault every structure.
>
`5.2.3.` Structure of Page Table

`5.2.4.` Hierarchical Page Table

`5.2.5.` Hashed Page Table

`5.2.6.` Inverted Page Table

`5.2.7.` Shared Page Table

`5.2.8.` Block Mapping Vs. Direct Mapping

`5.2.9.` Demand Paging

`5.2.10.` Page Replacement and Page Faults

	- OPR
	- SCP
	- FIFO
	- LRU

`5.2.11.` Page Replacement Algorithms: #FIFO==First-In-First-Out==, #OPR==Optimal Page Request==, #LRU==Least Recently Used==, #SCP==Second Chance Page Request==

*First In First Out*
![[first_in_first_out.png]]

*Optimal Page Replacement*
![[optimal_page_replacement.png]]

*Least Recently Used*
`Hit: 12`
![[least_recently_used.png]]


*Second Chance Page Replacement*
![[second_chance_page_rep.png]]

`5.2.12.` Some Numerical Examples on Page Replacement

`5.2.13.` Thrashing
>Trashing: A program caused page fault every structure.

`5.2.14.` Segmentation
> It is a memory management technique in which the memory is divided into variable size partition.

`5.2.15. `Segmentation With Paging.
![[segmentation_paging.jpg]]



# 6. Input/Output Device Management #
*teaching hours: 4 hrs*
  
`6.1.` Principle of I/O Devices
`6.2.` I/O Devices
`6.3.` Device Controllers
> The collection of electronic operate a bus is called device controller.

`6.4.` Memory Mapped I/O
>The device control register are mapped in to memory space is called memory mapped I/O.

`6.5.` Direct Memory Access #DMA
>It is a method of transferring data from the computer RAM to another part of computer without processing using CPU.
![[Direct_memory_access.png]]

`6.6.` Principle of I/O Software

	- Device Independent
	- uniform Naming
	- Error Handling
	- Synchronous vs Asynchronous transfer
	- Buffering

*Interrupt*
>Hardware mechanism to notify CPU

*Polling*
> Processing is interruped at brief interval to allow the CPU to check back to I/O to see if the I/O operation has completed.

`6.7.` Goals of I/O Software
`6.8.` Program I/O, Interrupt - Driven I/O, I/O Using DMA #DMA

*Programmed I/O*
![[programmed_IO.png]]

*Interruped I/O*
![[interruped_IO.png]]

*DMA*
![[DMA_IO.png]]

`6.9.` I/O Software Layers
![[IO_layer.png]]

`6.10.` Interrupts Handler
`6.11.` Device Drivers
`6.12.` Device Independent I/O Software

	- Buffering
	- Error Reporting
	- Uniform interface for device driver
	- provide a device independent block size

`6.13.` User-Space I/O Software
`6.14.` Disk Hardware
`6.15.` Disk Scheduling: Seek Time, Rational Delay, Transfer Time
>seek time: Arm position
>Rotational delay: surface/ disk rotate
>transfer time: data transfer time

`6.16.` Disk Scheduling Algorithms
`6.17.` #FCFS ==First Come First Served== Scheduling
`6.18.` #SSTF ==Short Seek Time First== Scheduling
`6.19.` SCAN Scheduling ==(Elevator / LOOK)==
`6.20.` C-SCAN Scheduling ==(Circular / C-LOOK)==
`6.21.` Lock Scheduling

*RAID*
>Redundant Array of independent Disk
>It is data storage virtualization technology that combines multiple physical disk drive component into single logical unit.

| RAID | data                                            |
| ---- | ----------------------------------------------- |
| 0    | create one larger virtual disk                  |
| 1    | store duplicate copy on each disk               |
| 2    | an error code used in disk                      |
| 3    | used storing parity                             |
| 4    | used large stripe, read record from single disk |
| 5    | based on block level striping with parity       |
| 6    | block level striping with two parity bit        | 
  
# 7. File System Interface Management #
*teaching hours: 2 hrs*
  
`7.1.` File Concept
`7.2.`  File Naming
`7.3.`  File Structure

	- unstructured
	- record structured
	- tree structured
	- file system layout

`7.4.` File Type

	- ascii
	- binary

`7.5.` File Access

	- direct
	- sequential

`7.6.` File Attributes

	- read, write, execute
	- password, hidden, size

`7.7.` File Operation and File Descriptors
`7.8.` Directories

	- single
	- two level
	- hirearchial

*Implementing Files*

	contgous Allocation

| file   | start block | length |
| ------ | ----------- | ------ |
| file A | 2           | 3      |
| file B | 19          | 5      |
| file C | 28          | 2      |

	linked list
![[linked_list_file.jpg]]

	Index Allocation

| file   | Index Block |
| ------ | ----------- |
| File A | 17          |
| File B | 23          | 

`7.9.` Single-Level Directory Systems

`7.10.` Hierarchical Directory Systems

`7.11.` Path Names

`7.12.` Directory Operation

`7.13.` Access Methods: Sequential, Direct

`7.14.` Protection

	owner group public

`7.15.` Types of Access

`7.16.` Access Control List

	chmod rwx-rwx-rwx filename.extention

`7.17.` Access Control Matrix

| operation | read  | write | execute |
| --------- | ----- | ----- | ------- |
| rwx       | 1     | 1     | 1       |
| .....     | ..... | ..... | .....   |
| 000       | 0     | 0     | 0        |


# 8. Security Management #
*teaching hours: 3 hrs*
  
`8.1.` Introduction

| Security Goal                 | Threat              |
| ----------------------------- | ------------------- |
| Confidentiality               | Exposure of data    |
| Integrity (accuracy / modify) | Tampering with data |
| Availablity                   | Denial of service   | 

`8.2.` Security Problems
`8.3.` User Authentication
`8.4.` Passwords
`8.5.` password Vulnerabilities
`8.6.` Encrypted password
`8.7.` One Time Password
`8.8.` Bio-metric password
`8.9.` User Authorization

#### Program Threats
`8.10.` Trojan Horse
`8.11.` Trap Door
`8.12.` Stack and Buffer Overflow

#### System Threats
`8.13.` Worms
`8.14.` Viruses
`8.15.` Denial of Services


# 9. Distributed Operating System #
*teaching hours: 4 hrs*
  
`8.1.` Introduction
![[distributed_os.jpg]]

`8.2.` Advantages of Distributed System over Centralized System
`8.3.` Advantages of Distributed System over Independent PCs
`8.4.` Disadvantages of Distributed System
`8.5.` Hardware and Software Concepts

	- Single instruction, single data
	- single instruction, multiple data
	- multiple instruction, single data
	- multiple instuction, multiple data

`8.6.` Communication in Distributed Systems

	- Shared memory
	- message passing
	- remote procedure call

`8.7.` Message Passing
`8.8.` Remote Procedure Call
`8.9.` Process in Distribution System
`8.10.` Clock Synchronization

	- internal and external clock synchronization
	- centralized and distributed clock distribution


























