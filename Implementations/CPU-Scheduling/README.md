# CPU Scheduling Algorithms (C++)

This directory contains implementations of **CPU scheduling algorithms**
written in **C++** as part of Operating Systems learning and practice.

🚧 **Status:** Work in Progress  
More scheduling algorithms will be added progressively.

---

## 📂 Folder Structure
cpu_scheduling/
├── FCFS.cpp
├── SJF.cpp
└── README.md



---

## ✅ Implemented Algorithms
1️⃣ First Come First Serve (FCFS)

File: FCFS.cpp

Schedules processes based on arrival time

Calculates ST, CT, TAT, WT

Displays average WT & TAT

Generates Gantt Chart

Handles CPU idle time

2️⃣ Shortest Job First (SJF) – Non-Preemptive

File: SJF.cpp

Selects process with minimum burst time

Non-preemptive execution

Calculates ST, CT, TAT, WT

Displays average WT & TAT

Generates Gantt Chart

🔜 Planned Algorithms

Shortest Remaining Time First (SRTF)

Priority Scheduling

Round Robin (RR)

Multilevel Queue Scheduling

▶️ How to Run
g++ FCFS.cpp -o fcfs
./fcfs

g++ SJF.cpp -o sjf
./sjf
