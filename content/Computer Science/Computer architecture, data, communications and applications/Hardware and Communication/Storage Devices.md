---
banner: "![[computerscience.jpg]]"
---
# Data Storage 

> [!Tip] Image 
> ![[A-level Mindmap - 06 Data Storage.jpg|1000]]

> [!Info] Memory 
> - Memory is the space where data and programs are stored. Data in memory is accessed through instructions from the CPU.
> - Memory in a computer system is classified into primary and secondary memory. 
> ---
> 
> ### Types of Memory
> ##### Primary memory 
> - Primary memory is a type of memory that is accessed directly by the CPU. 
> - For example: RAM, ROM and cache.
> ##### Secondary memory 
> - Secondary memory refers to external storage devices such as hard drives, CDs, flash drives, etc.
> ##### Latency 
> - Latency is the time taken by components to respond to a request. 
> - To avoid short delays between the CPU’s request for data and finding the data in the memory, some instructions and data are copied to the cache.
>   ---
> ### RAM 
> - RAM is a temporary memory which stores data, files and parts of the operating system that is currently in use. 
> - When a program is loaded from the hard drive, all its contents, such as its instructions and data, are loaded to the RAM and the CPU accesses this information. 
> - It is also called the main memory. 
> - RAM is used by the operating system, applications and any data that are currently used.
> - The access time for a CPU to access any data from the RAM is less when compared to accessing data from a hard drive.
> - The larger the size of RAM, the faster the computer operates.
> - Buffers also use RAM.
> - When the power is lost, the contents of RAM are lost.
> - The contents of RAM can be read from, written to, and changed.
> - Each memory location in RAM has a unique address. (0x00000)
> 
> #### DRAM and SRAM 
> ##### Dynamic RAM (DRAM)
> -  DRAM consists of transistors that act as switches and capacitors that hold binary data.
> - DRAM has to be constantly refreshed (every 15 microseconds) to maintain the charge in the capacitor.
> - DRAM is used for main RAM memory.
>   
>##### Static RAM (SRAM)
>- SRAM uses ‘flip-flops’ which hold each bit of memory. 
>- SRAM need not be refreshed constantly.
>- SRAM is faster than DRAM.
>- SRAM is used in cache.
>- SRAM is more complex to build than DRAM and is therefore more expensive.
>- Due to the complex design and more transistors and additional wiring required in SRAM, it offers smaller capacity compared to DRAM.
>  ---
>  ### ROM
>  - Read Only Memory (ROM) is a permanent memory that is used to store the instructions that are executed once the computer is switched ON. 
>  - This set of instructions is called a boot process. This is responsible for initialising the hardware and operating system soon after the power is switched ON. 
>  - The contents of ROM are not erased, even when the power is switched OFF. 
>  - The contents of ROM can only be read and cannot be changed. 
>  - ROM is made by interconnecting several transistors. 
>  - It is an example for non-volatile memory.
>
>#### Flash Memory 
>- Flash memory is a type of ROM. It is programmed by applying a slightly larger electric current that forces an electron through a barrier.
>- Once the electrons cross this barrier, they get stored in a layer. The electrons can then be detected without affecting its position.
>- As a flash of current is used to store data, it is called flash memory. 
>- Flash memory is also rewritable.

> [!Info] Storage (HDDs)
> - Users need storage devices to store media and other files that require large amounts of space. 
> - This problem is solved by storage devices that work based on magnetic, optical and solid-state principles.
> ### Hard disk drives (HDDs)
> - Hard disk drives, also called magnetic disk drives, are used in computers and laptops.
> - It provides high storage capacity and is cost-effective.
> - Large storage facilities also use this technology.
> - In a computer, it stores the operating system, installed programs and user’s data. 
> - External hard disks are available to store data that are not frequently used or to back-up important information.
> ##### Structure of an HDD 
> - The disk is made of a magnetic surface, which is known as a platter. 
> - Digital data is stored in these magnetic platters. 
> - This disk can spin at about 7000 revolutions a second. 
> - Data can be accessed by a number of read-write heads on the surface.
> - The read-write heads move from the centre of the disk to the edge of the disk (and back again) 50 times a second. 
> - The data is read/written using magnetic properties.
> - The disk is divided into various sectors and tracks. 
> - Each sector in a track can store a specific number of bytes.
> ##### Latency of an HDD 
> - The access time of a hard disk drive is high compared to RAM. 
> - This is due to a large number of head movements.
> - Latency is defined as the time taken for a specific block of data to rotate around to the read-write head. 
> - The effect of latency becomes significant when a user receives messages such as ‘not responding’ and ‘please wait’.

> [!Info] Storage (SSDs)
> ### Solid State Drives (SDDs) 
> - The latency is reduced in SSD compared to HDD as there is no read/write head that needs to be moved. 
> - Data is stored and retrieved using the electronic properties in NAND chips.
> - This type of memory is used in USB devices to transfer information from one device to another. 
> - This is a type of solid-state device. 
> - Solid-state drives are a larger version of flash memory.
> - Digital data is stored in millions of transistors within the chip.
> - An SSD is a non-volatile rewritable memory. 
> - These are used in portable devices such as tablets and mobile phones.
>  ![[Pasted image 20230919120934.png|700]]
>  #### HDD vs SSD 
>  - A computer system has various applications with different requirements. 
>  - Some applications need faster access time. 
>  - A SSD can improve the access time but it is expensive compared to HDD. 
>  - Therefore, a combination of both is provided in a system. 
>  - Applications that require high performance are loaded into an SSD and those that are not frequently used are stored in an HDD.

> [!Info] Storage (Optical) 
> #### Basics
> - CD, DVD and Blu-ray discs use optics to store data. The surface of CDs and DVDs are made of light-sensitive organic dyes or metal alloys.
> - Data is read and written using laser light.
> - DVDs (4.7GB) can store large amounts of data compared to CDs (800 MB)
> - Blu-ray discs use blue laser light and can hold up to 50 GB. These optical storage systems are used to store music, movies and games.
> #### How it works: 
> - The clear plastic layer on the surface allows the laser light to pass through it. 
> - The colour changes in the dye layer when light falls on it. 
> - This change in colour is reflected and is detected by the computer while the data is read.
> #### Types of Optical Device 
> ##### Read-only: 
> - The data can be written only once at the manufacturing stage.
> - For example: programs, movies, and song distributed by its producers.
> ##### Read/write:
> - Read/write optical devices are used as external storage devices to transfer data from one device to another.

