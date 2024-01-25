---
banner: "![[computerscience.jpg]]"
---
# Processor Architecture

> [!Info]- Hardware 
> **Hardware** refers to the **physical components of a computer system**. The core components of any computer system are:
> - Processor
> - Main memory
> - Input/output controllers 
>These three components are sometimes referred to as the **'three-box model'**. They are linked by the system bus, which is a high-speed communication channel.
>The three-box model describes a **von Neumann machine** (or **von Neumann architecture**). This is the model proposed by John von Neumann and his peers in 1945 for "an electronic digital computer", and remains the fundamental architecture used today for general purpose computers. An alternative architecture — **Harvard architecture** — with two banks of main memory, was proposed at the same time by researchers at Harvard.
Most computers have a wide range of additional hardware. These are called **peripheral devices** and are connected through the input/output controllers. They can be broadly categorised into three groups
> - Secondary storage devices, e.g. a hard disk
> - Input devices, e.g. a keyboard or sensor
> - Output devices, e.g. a speaker or actuator
> Some peripheral devices, such as a touchscreen display, provide both input and output functionality.
Peripheral devices can be internal or external. For example, a hard disk can be installed inside the system case, or it can be attached by connecting a cable from the device to a port (e.g. a USB port).
>Some hardware devices, such as keyboards, have a mechanical aspect and contain moving parts, which can be used to control them. Other hardware devices, such as [solid-state disks](https://isaaccomputerscience.org/concepts/sys_hard_secondary_storage#solid-state), are solely controlled by electrical signals.

> [!Info]- Von Neumann Architecture 
> In the 1940s, **John von Neumann** and his team developed the concept of the stored program computer. The Von Neumann architecture used the idea of **storing program instructions and data** in **main memory** and moving them between memory and the processor. **Von Neumann architecture** is used in many modern-day computer systems.
**The von Neumann architecture** consists of
> - a Processor
> - a Memory unit that can communicate directly with the processor
> - connections for input and output devices
> - Secondary storage for saving/backing up data
> ---
> ![[Von_Neumann_Architecture.png]] 
> ^^^^^^ MUST BE DRAWN IN THIS SPECIFIC WAY ^^^^^^^
> B - Arithmetic Logic Unit (ALU)  
A - Control Unit (CU)
![[Von Neumann Architecture.png|500]]
> ---
> The processor can access the instructions and data in the main memory as required to execute the program. It does this by using dedicated connections called **buses**:
> - an **address bus** is used to identify the addressed location
> - a **data bus** is used to transfer the contents to/from that location 
> - This means that **the same address and data buses** are used in the process of transferring **instructions and data** between main memory and the processor. A third bus, the **control bus**, is used to synchronise and control operations.

> [!Info]- Data Hierarchy 
> - L1 is the fastest cache and L4 is the slowest cache
> ![[hierarchy.png]]
> ![[cache_miss-memory-hierarcny.jpg]]

> [!Info]- Parallel Processing
> - Parallel processing came about by the physical limitation of how many transistors you can fit in a CPU.
> - To get around this, manufacturers put multiple CPUs together (calling them cores) to come together and make one larger processor.
> - This allows a single task to be split into multiple subtasks, each completed by a separate core. These subtasks are called threads.
> - This should, in theory, speed up the processing time.
> 
> Advantages: 
> 	- Faster execution as more instructions run in a shorter time span.
> 	- Each task is shared, so no one processing unit will be more loaded by the others.
> 
> Disadvantages:
> 	- More difficult to write programs that take advantage of a multiple core system.
> 	- Data must be up to date and processing units will need to change their calculations based on the actions of other programming units.
> 	- Cannot split sequential/serialised tasks.
> 	- Concurrency means more software bugs to deal with.

> [!Tip] Amdahl's Law 
> - Amdahl's Law tells you how much performance you can gain from parallelizing your code.
> - $p$ is the ratio of the parallelizable code over the total execution time.
> - $n$ is the number of processors or the part of the task that speeds up due to the improved system resources.
> - $$\text{speed up}=\frac{1}{(1-p)+\frac{p}{n}}$$

> [!Example]- Amdahl's Law example 
> - Imagine we have 4 cores and 10% of the code is parallelizable
> - $\frac{1}{(1-0.1)+\frac{0.1}{4}}=\frac{1}{0.9+0.025}$
> - $=1.081$
