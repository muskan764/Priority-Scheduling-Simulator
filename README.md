# 🖥️ Priority Scheduling Simulator

This project simulates **priority-based CPU scheduling**, a common concept in operating systems.  

It calculates the **waiting time** and **turnaround time** for each process based on their priorities and burst times, and displays the execution order and average times.

---------------------------------------------------------------------------------------------------------

## ⚙️ How It Works

1. Define a list of processes with their **process ID**, **burst time**, and **priority**.  
2. The program sorts processes based on priority (lower number = higher priority).  
3. Calculates:
   - **Waiting Time (WT)** for each process  
   - **Turnaround Time (TAT)** for each process  
4. Prints the process table and the **average waiting and turnaround times**.  

---------------------------------------------------------------------------------------------------------

## 🚀 Usage

1. Run the Python script:
```bash
python priority_scheduling.py
Example Input (in script):

process_ids = [0, 1, 2, 3]
burst_time = [10, 1, 2, 1]
priority = [3, 1, 4, 2]
Sample Output:
Process  Priority  Burst Time  Waiting Time  Turnaround Time
0        3         10          3             13
1        1         1           0             1
2        4         2           13            15
3        2         1           1             2
```

Average Waiting Time: 4.25

Average Turnaround Time: 7.75

---------------------------------------------------------------------------------------------------------
✨ Features

✅ Calculates waiting time and turnaround time for each process

✅ Handles multiple processes with different priorities

✅ Computes average waiting and turnaround times

✅ Demonstrates CPU scheduling behavior in operating systems
