# 🖥️ Operating System — Essential Interview Notes  

A clean and simple set of important OS concepts explained in an interview-friendly manner.  
Perfect for quick revision and strengthening understanding of core OS fundamentals.

---

## 1️⃣ What is an Operating System?  
Software that manages hardware resources and provides an interface for users and applications.  
Examples: Windows, Linux, macOS.

---

## 2️⃣ Process vs Thread  

| Feature | Process | Thread |
|--------|---------|--------|
| Definition | Program in execution | Lightweight subprocess |
| Memory | Has its own memory | Shares memory with process |
| Switching | Slow | Fast |
| Use | Browsers, Games | Tasks inside same app |

---

## 3️⃣ Process States  
- New  
- Ready  
- Running  
- Blocked  
- Terminated  

---

## 4️⃣ Process Control Block (PCB)  
Data structure storing process information:  
- Process ID  
- Registers  
- Program counter  
- Scheduling info  
- Memory info  

---

## 5️⃣ CPU Scheduling Algorithms  
- **FCFS** – First Come First Serve  
- **SJF** – Shortest Job First  
- **Round Robin** – Time-based  
- **Priority Scheduling**  
- **Multilevel Queue**

---

## 6️⃣ Context Switching  
Process of saving the current process state and loading the next one.  
Enables multitasking.

---

## 7️⃣ Deadlock  
A situation where processes wait forever for resources.

**Conditions (Coffman Conditions):**  
1. Mutual Exclusion  
2. Hold and Wait  
3. No Preemption  
4. Circular Wait  

---

## 8️⃣ Deadlock Handling  
- **Prevention** – Break one of the 4 conditions  
- **Avoidance** – Banker's Algorithm  
- **Detection & Recovery** – Identify & restart  

---

## 9️⃣ Multithreading  
Multiple threads running inside a process for faster performance.  
Used in browsers, game engines, servers.

---

## 🔟 Memory Management  
Techniques for handling memory efficiently.

- **Contiguous Allocation**  
- **Paging**  
- **Segmentation**  
- **Virtual Memory**

---

## 1️⃣1️⃣ Paging  
Divides memory into fixed-size blocks called pages (logical) and frames (physical).  
Solves external fragmentation.

---

## 1️⃣2️⃣ Segmentation  
Divides memory into variable-sized segments (code, data, stack).  
Solves logical grouping.

---

## 1️⃣3️⃣ Virtual Memory  
Allows execution of programs larger than physical memory by using disk space (swap area).  
Implemented using paging.

---

## 1️⃣4️⃣ Thrashing  
Occurs when system spends more time swapping pages than executing instructions.

---

## 1️⃣5️⃣ Page Replacement Algorithms  
- **FIFO**  
- **LRU** (Least Recently Used)  
- **Optimal**  
Used when a page fault occurs.

---

## 1️⃣6️⃣ Page Fault  
Occurs when required page is not found in main memory.  
OS loads it from disk.

---

## 1️⃣7️⃣ File System  
Manages file storage, directories, access permissions.  
Examples: FAT32, NTFS, ext4.

---

## 1️⃣8️⃣ System Calls  
Interface between user programs and OS.

Types:  
- Process control  
- File management  
- Device management  
- Communication  

Example: `fork()`, `exec()`, `open()`, `close()`

---

## 1️⃣9️⃣ Kernel  
Core of the OS. Manages memory, processes, devices.  

**Types:**  
- Monolithic Kernel  
- Microkernel  
- Hybrid Kernel  

---

## 2️⃣0️⃣ Monolithic vs Microkernel  

| Feature | Monolithic | Microkernel |
|--------|------------|-------------|
| Speed | Fast | Slower |
| Size | Large | Small |
| Reliability | Less | More |
| Example | Linux | Minix |

---

## 2️⃣1️⃣ Buffering & Caching  
- **Buffering:** Temporary storage during data transfer  
- **Caching:** Storing frequently accessed data for faster access  

---

## 2️⃣2️⃣ Semaphore  
A synchronization mechanism to avoid race conditions.  
Types:  
- Binary Semaphore  
- Counting Semaphore  

---

## 2️⃣3️⃣ Race Condition  
Occurs when multiple processes modify shared data simultaneously.

---

## 2️⃣4️⃣ Critical Section  
Part of code where shared resources are accessed.  
Solved using locks, semaphores, mutexes.

---

## 2️⃣5️⃣ IPC (Inter-Process Communication)  
Methods used by processes to communicate.

Techniques:  
- Pipes  
- Shared Memory  
- Message Queues  
- Sockets  

---

## 🎥 Recommended YouTube Playlists  
- **Gate Smashers – OS Playlist**  
  https://youtube.com/playlist?list=PLn32mJ8RhQWiIgEoD2U3gHoHC3ApDOHas

- **Vivek Gupta – OS Revision**  
  https://youtu.be/2LOpVPMiGUw

---
