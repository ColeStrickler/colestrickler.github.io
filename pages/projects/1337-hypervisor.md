---
layout: post
---

See full project and source code here: [1337Visor Source](https://github.com/ColeStrickler/1337Visor).


This project is a Type-2 Hypervisor for Windows utilizing AMD-V hardware assisted virtualization. This project is just a skeleton of a base hypervisor and I have created a few private forks that I have geared toward cheats for specific games or for reversing specific malware variants. I have not released these versions as the code is messy, as they are either for very specific malware variants, or due to the ethical and legal concerns regarding online game cheating.


This project entailed the following:
*   Parsing through the nitty-gritty of the x86-64 AMD manuals
*   Emulating page tables
*   Utiling AMD SVM architectural features
*   Setting up the virtual machine control block(VMCB) structure and making use of its features
*   Utilizing Windows Kernel API functions to initialize and manage hypervisor resources
*   Writing exit handler routines to intercept and virtualize certain architectural and OS events into the hypervisor
*   Learning WinDBG on a very deep level

![1337visor-windbg](/assets/img/1337visor.jpg)