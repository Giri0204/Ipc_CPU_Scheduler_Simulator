# Intelligent CPU Scheduler Simulator

A GUI-based CPU scheduling simulator built using Python and Tkinter. This educational tool helps visualize and analyze the working of different CPU scheduling algorithms such as FCFS, SJF, Preemptive SJF, Priority Scheduling, and Round Robin.

## 🔧 Features

- Supports 5 popular scheduling algorithms:
  - First-Come, First-Served (FCFS)
  - Shortest Job First (SJF)
  - Preemptive Shortest Job First (PSJF)
  - Priority Scheduling
  - Round Robin (RR)
- User-friendly interface to input:
  - Process ID
  - Arrival Time
  - Burst Time
  - Priority (if required)
  - Time Quantum (for Round Robin)
- Real-time **Gantt Chart** visualization
- Calculation of:
  - Average Waiting Time
  - Average Turnaround Time
  - CPU Utilization
- Intelligent comparison and recommendation of optimal algorithm based on input data

## 🛠️ Tech Stack

- **Language:** Python 3
- **GUI:** Tkinter
- **Visualization:** Matplotlib 

## 🚀 Getting Started

### Prerequisites

Ensure Python 3.x is installed. Required libraries:
```bash
pip install matplotlib
```
How to run:
python Ipc_CPU_Scheduler_Simulator.py
