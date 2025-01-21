---
layout: post
---

See full project, technical report, and source code here: [GhostRace PoC](https://github.com/ColeStrickler/EECS750-FinalProject) 



In this project we reimplemented the micro-architectural attack performed via speculative race conditions seen in the [GhostRace Paper](https://download.vusec.net/papers/ghostrace_sec24.pdf). We followed their methodology and confirmed their findings. The attack consisted of the following steps:

*   abuse of Kernel data structures and IPI to unbound an UAF exploitation window
*   location of SCUAF gadget in the Linux Kernel
*   Harness to leverage the attack and leak arbitrary kernel data


![ghostrace](/assets/img/ghostrace.png)