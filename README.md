# 🖥️ Operating Systems – Implementation Oriented Projects

## 📌 Overview
This repository focuses on **implementation-based Operating System concepts**, emphasizing **how OS components work internally** rather than only theory.

It contains **code, simulations, and mini-projects** that demonstrate:
- Kernel-level behavior
- Core OS data structures
- Internal working of OS components

The repository is **progressively developed** as new concepts are implemented.

------

## 🎯 Objectives
- Strengthen **OS fundamentals** (GATE & university exams)
- Gain **interview-level understanding** of OS internals
- Build a **practical OS implementation portfolio**

------

## 🧠 Learning Approach
Focus is on:
- How OS concepts are **implemented**
- Data structures used by the OS
- Internal **kernel-level behavior**

------

## 📂 Repository Structure (Planned & Ongoing)
Operating-Systems/
│
├── Process_Management/
├── CPU_Scheduling/        (FCFS ✅,SJF ✅, others in progress)
├── Synchronization/
├── Deadlocks/
├── Memory_Management/
├── File_System/
├── IO_and_Disk/
├── System_Calls_and_Kernel/
├── Booting_and_Startup/
│
└── README.md

------

## ✅ Completed
- **CPU Scheduling**
  - FCFS,SJF scheduling
  - Ready queue simulation
  - Waiting & turnaround time calculation

---

## 🚧 Work in Progress

### 🔹 Process Management
- PCB & process states
- `fork`, `exec`, `wait`, `exit`
- Context switching
- Threads & TCB  
🎯 *Interview focus:* What happens internally during `fork()`?

### 🔹 CPU Scheduling (Advanced)
- SJF / SRTF
- Priority & Round Robin
- Timer interrupts & dispatcher  
🎯 *Common:* How Round Robin enforces time quantum

### 🔹 Synchronization
- Critical sections
- Test-and-Set, CAS
- Semaphores, mutexes, monitors  
🎯 *Key:* Kernel-level semaphore implementation

### 🔹 Deadlocks
- RAG, detection
- Banker’s algorithm
- Recovery techniques

### 🔹 Memory Management
- Paging & segmentation
- Virtual memory & TLB
- Page replacement algorithms  
🎯 *Must know:* Logical → Physical translation

### 🔹 File System
- File allocation methods
- Inodes & directories
- File operations

### 🔹 I/O & Disk
- Disk scheduling
- Interrupts & DMA
- Buffering & caching

### 🔹 System Calls & Kernel
- Syscall mechanism
- User vs kernel mode
- Kernel architectures

### 🔹 Booting
- Bootloader
- Kernel loading
- Init/systemd

---

## 🛠️ Tech Stack
- **Language:** C++
- **Domain:** Operating Systems (Low-level)
- **Platform:** Windows (WSL)

---

## 📈 Progress
- [x] FCFS,SJF Scheduling
- [ ] Process Management
- [ ] Round Robin
- [ ] Semaphores
- [ ] Banker’s Algorithm
- [ ] Memory Management
- [ ] File System

---

## 👨‍💻 Author
**Nikhil** — B.Tech CSE (Central University Of Jammu) 
Focus: OS, DSA, OOP ,DBMS


