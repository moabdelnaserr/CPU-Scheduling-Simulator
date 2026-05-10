# CPU Scheduling Simulator

A modern web-based simulator for comparing two preemptive CPU scheduling algorithms:

- Shortest Job First (SJF)
- Priority Scheduling

The project visualizes process execution using animated Gantt Charts and calculates important CPU scheduling metrics.

---

# Features

- Dynamic process input
- Input validation
- Preemptive SJF Scheduling
- Preemptive Priority Scheduling
- Animated Gantt Charts
- Waiting Time (WT) calculation
- Turnaround Time (TAT) calculation
- Response Time (RT) calculation
- Average metrics comparison
- Interactive and modern UI

---

# Technologies Used

- HTML
- CSS
- JavaScript
- GitHub Pages

---

# Algorithms Implemented

## 1. Shortest Job First (SJF)

The simulator uses Preemptive SJF (Shortest Remaining Time First).

The CPU always selects the process with the shortest remaining burst time.

### Advantages
- Reduces average waiting time
- Efficient for short processes

### Disadvantages
- Long processes may suffer starvation

---

## 2. Priority Scheduling

The simulator uses Preemptive Priority Scheduling.

The CPU selects the process with the highest priority  
(smaller priority number = higher priority).

### Advantages
- Important processes execute first
- Useful in real-time systems

### Disadvantages
- Low-priority processes may suffer starvation

---

# Performance Metrics

The simulator calculates:

## Waiting Time (WT)

WT = Turnaround Time - Burst Time

## Turnaround Time (TAT)

TAT = Completion Time - Arrival Time

## Response Time (RT)

RT = First Start Time - Arrival Time

---

# Input Validation

The system validates:

- Empty fields
- Duplicate process IDs
- Negative values
- Non-numeric input
- Zero or invalid burst time

---

# Example Test Case

| Process | Arrival Time | Burst Time | Priority |
|----------|--------------|-------------|-----------|
| P1 | 0 | 5 | 2 |
| P2 | 1 | 3 | 1 |
| P3 | 2 | 8 | 4 |

---

# Project Objectives

- Understand CPU Scheduling Algorithms
- Compare scheduling performance
- Analyze efficiency vs urgency
- Visualize CPU execution
- Study scheduling trade-offs

---

# Challenges Faced

- Implementing preemptive scheduling
- Synchronizing Gantt chart animations
- Calculating metrics correctly
- Handling invalid input cases

---

# Conclusion

This project demonstrates the behavior and comparison of two important CPU scheduling algorithms.

- SJF improves efficiency and minimizes waiting time.
- Priority Scheduling focuses on urgent processes.

The project highlights the trade-off between:
- Efficiency
- Fairness
- Urgency

---

# Team Members

| Name | ID |
| Mostafa Ahmed Gad | 20240954 |

| Omar Hoassam Mohammed | 20240627 |

| Marwan Awad Abd Al-Galil | 20240921 |
| Adham Ibrahim Saied | 20240103 |
| Mohammed AbdulNasser Ali Atta | 20240850 |
| Omar Wael Mohammed | 20230381 |
