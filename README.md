# mini-gpu-firmware

Firmware for mini-gpu. Runs on control processor, manages GPU hardware.

## Components

### Core
- [ ] **Command Parser** — Parse command buffers from host
- [ ] **Kernel Dispatcher** — Configure and launch kernels on SIMT cores
- [ ] **Thread Block Scheduler** — Assign thread blocks to compute units
- [ ] **Memory Manager** — Track GPU memory allocation state

### Hardware Interface
- [ ] **Register Interface** — Read/write GPU control registers (MMIO)
- [ ] **Interrupt Handler** — Handle GPU completion and error interrupts
- [ ] **DMA Controller** — Manage data transfers between host and GPU memory

### Synchronization
- [ ] **Barrier Handler** — Implement barrier synchronization
- [ ] **Fence Manager** — Track kernel completion for host synchronization
- [ ] **Event System** — Signal completion to host

### Debug & Monitoring
- [ ] **Error Handler** — Catch and report GPU errors
- [ ] **Performance Counters** — Track cycles, occupancy, memory bandwidth
- [ ] **Logging** — Debug output for development
