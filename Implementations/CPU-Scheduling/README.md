# CPU Scheduling Algorithms (C++)

This directory contains implementations of **CPU scheduling algorithms**
written in **C++** as part of Operating Systems learning and practice.

🚧 **Status:** Work in Progress  
More scheduling algorithms will be added progressively.

---

## 📂 Folder Structure
cpu_scheduling/
├── FCFS.cpp
└── README.md



---

## ✅ Implemented Algorithms

### 1️⃣ First Come First Serve (FCFS)
**File:** `FCFS.cpp`

**Description:**
Implements the **First Come First Serve (FCFS)** CPU scheduling algorithm
based on arrival time.

**Features:**
- Sorts processes by arrival time
- Calculates:
  - Start Time (ST)
  - Completion Time (CT)
  - Turnaround Time (TAT)
  - Waiting Time (WT)
- Displays:
  - Scheduling table
  - Average WT and TAT
  - Gantt Chart representation
- Handles CPU idle time

**Concepts used:**
- Structures (`struct`)
- Sorting with custom comparator
- Dynamic memory allocation
- Scheduling metrics calculation

---

## 🔜 Planned Algorithms (To Be Added)

- Shortest Job First (SJF)
- Shortest Remaining Time First (SRTF)
- Priority Scheduling
- Round Robin (RR)
- Multilevel Queue Scheduling

---

## ▶️ How to Run

Compile and run any algorithm file individually.

Example (FCFS):
```bash
g++ FCFS.cpp -o fcfs
./fcfs

