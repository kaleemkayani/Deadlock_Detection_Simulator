# 🔒DEADLOCK DETECTION SIMULATOR
 ## 1. Introduction
Deadlock is one of the most critical problems in operating systems. It occurs when a set of processes are each waiting for resources held by other processes in the set, creating a circular dependency from which no process can proceed.
This project presents a Deadlock Detection Simulator — a fully interactive, web-based application that allows students and system designers to configure multi-process, multi-resource environments and analyze them using three industry-standard detection algorithms with real-time visual output.
### 1.1 Problem Statement
In modern operating systems, multiple processes compete for limited shared resources such as memory, printers, and I/O devices. When resource allocation is not carefully managed, deadlock can occur — halting all affected processes indefinitely. The ability to detect and analyze deadlock conditions is essential for system reliability.
## 2. Four Necessary Conditions
### 1	Mutual Exclusion:
                       Resources cannot be shared; only one process at a time can use a resource
### 2	Hold and Wait:
                     A process holds at least one resource and is waiting to acquire additional ones
### 3	No Preemption:
                  Resources cannot be forcibly taken away from a process; must be released voluntarily
### 4	Circular Wait:
                 A closed chain of processes exists, where each process waits for a resource held by the next
## 3 What is Deadlock?
A deadlock is a situation in which two or more competing actions are each waiting for the other to finish, and thus neither ever does. In an operating system, deadlock occurs when processes form a circular chain of resource dependency.
Classic analogy: Person A holds a pen and needs paper. Person B holds paper and needs a pen. Neither can proceed — this is a deadlock.
## 3. Detection Algorithms
#### 1 Banker's Algorithm
#### 2 Resource Allocation Graph (RAG)
#### 3 Wait-For Graph (WFG)
## Command Prompt
![image alt](https://github.com/kaleemkayani/Deadlock_Detection_Simulator/blob/bac6641bc1b6cdf89bbe29fcf674794a3e046291/OutPut%20Result/commad.png)
# OUTPUT SIMULATOR
## InterFace
![image alt](https://github.com/kaleemkayani/Deadlock_Detection_Simulator/blob/b0dfed9b4db9eacb77c538b1dab2e83ee34261a2/OutPut%20Result/interface.png)
## Result
![image alt](https://github.com/kaleemkayani/Deadlock_Detection_Simulator/blob/bac6641bc1b6cdf89bbe29fcf674794a3e046291/OutPut%20Result/Results.png)
## Guide
![image alt](https://github.com/kaleemkayani/Deadlock_Detection_Simulator/blob/bac6641bc1b6cdf89bbe29fcf674794a3e046291/OutPut%20Result/Guide.png)
