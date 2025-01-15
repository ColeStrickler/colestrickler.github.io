---
layout: post
---

See full project and source code here: #### [SwagOS Source](https://github.com/ColeStrickler/swagOS/tree/main).


The goal of this project was to build a fully functional SMP operating for x86-64. This was a substantial undertaking that entailed the following tasks:
*   Writing a boot entry to set up initial page tables, privilege modes, and pass the multiboot header to the kernel
*   Reading and dealing with data structures passed from the firmware
*   Setting up interrupts in the IDT and programming the APIC chip
*   Creating and managing GDT entries
*   Creating a kernel and user mode memory allocator
*   Initializing SMP CPUs and structures
*   Writing a task scheduler
*   Managing multiple CPU synchronization throughout the Kernel
*   Managing fonts(harder than it sounds) and writing a text to framebuffer driver
*   Writing an Ext2 Filesystem driver
*   Implementing various synchronization primitives such as sleep locks and spin locks
*   Writing a PS2 Keyboard driver
*   Writing an IDE disk driver
*   Utilizing SMEP and SMAP for kernel protections
*   Utilizing the original UNIX buffered IO mechanism for efficent disk IO
*   Implementing a rich number of system calls for user mode use
*   Creating a user-mode shell 
*   Created a user-mode libc
*   Creating clones of basic UNIX programs such as cat, clear, ls, etc.
*   Learned how to effectively organize a complex build process

