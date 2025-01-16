---
layout: post
---

See full project and source code here: [Cache Modifications](https://github.com/ColeStrickler/rocket-chip-inclusive-cache/tree/memguardworking) & [MemGuard Driver](https://github.com/ColeStrickler/memguard/tree/firesim)


This project was a port of the MemGuard driver to RISC-V and FireSim simulation environment. MemGuard utilizes hardware performance counters to measure cache or DRAM bandwidth and to throttle cores that exceed user allocated bandwidth. The RocketChip L2 cache does not currently include these performance counters and this project required adding them. Additionally, it was required to implement user control over bandwidth limitations and the ability to control interrupt routing that allows for throttling CPU cores. These features were implemented via MMIO registers. Finally, modifications to the MemGuard kernel driver were needed to orchestrate this new infrastructure, and to program the PLIC.


![voxelworld](/assets/img/firesim_memguard.drawio.png)