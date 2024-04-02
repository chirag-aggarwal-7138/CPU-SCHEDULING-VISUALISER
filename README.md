
# CPU SCHEDULING ALGORITHM VISUALISER

## Introduction <br>

The CPU Scheduling Algorithm Visualizer is a web-based tool that allows users to interactively visualize various CPU scheduling algorithms. This project aims to provide an educational resource for understanding how different scheduling algorithms work internally and their effects on the execution of processes in a CPU. <br>

## Features <br>
- Interactive visualization of CPU scheduling algorithms
- Real-time updates to process queues, timelines, and statistics
- User-friendly interface for adjusting algorithm parameters
- Clear visualization of process execution, arrival times, waiting times, and more
<br>

## Algorithms Implemented
- First Come First Serve (FCFS)
- Shortest Job First (SJF)
- Round Robin Scheduling (RRS)
- Longest Job First (LJF)
- Priority CPU Scheduling
- Longest Remaining Time First (LRTF)
- Shortest Remaining Time First (SRTF)

<br>

### Live: https://chirag-aggarwal-7138.github.io/CPU-SCHEDULING-VISUALISER/

## Tech Stack
- HTML
- CSS
- JavaScript
- BootStrap

## Implementation 👇


### FCFS (First Come First Serve):  <br>
FCFS Algorithm. is a non-preemptive algorithm and it execute processes according to its arrival time(process that comes first in the ready queue). FCFS also suffers from starvation which arise if the first process has larger burst time. <br>

### SJF (Shortest Job First):   <br>
SJF Algorithm. is a non-preemptive algorithm in which the process having shortest /smallest burst time is executed first. It significantly reduces the average waiting time for other processes awaiting execution. <br>


### RRS (Round Robin Algorithm):  <br>
Round robin is a pre-emptive algorithm. The process that is preempted is added to the end of the queue. This algorithm also offers starvation free execution of processes.  <br>


### LJF (Longest Job First):  <br> 
LFJ algorithm is a pre-emptive algorithm. The process having the largest burst time is chosen for the next execution. When a job comes in, it is inserted in the ready queue based on its burst time. <br>


### Priority CPU Scheduling:  <br>
It is a non-preemptive algorithm. In this algo if the new process arrived at the ready queue has a higher priority than the currently running process, the CPU is preempted, which means the processing of the current process is stoped and the incoming new process with higher priority gets the CPU for its execution.  <br>


### LRTF (Longest Remaining Time First):   <br>
LRTF is a pre-emptive algorithm. Here the job that has the highest burst time is allocated CPU first. The operating system to schedule the incoming processes so that they can be executed in a systematic way. In case of LRTF the average waiting time is high.  <br>



### SRTF (Shortest Remaining Time First):  <br>
SRTF is a pre-emptive algorithm. At the arrival of every process, the short term scheduler schedules the process with the least remaining burst time among the list of available processes and the running process. Processes which have long burst time will have to wait for long time for execution  <br>


## Installation

    Clone the repository: git clone https://agreeable-moss-01c72060f.5.azurestaticapps.net
    Navigate to the project directory: cd cpu-scheduling-visualizer
    Open index.html in your preferred web browser.

## Usage

    Open the visualizer in your web browser.
    Select an algorithm from the dropdown menu.
    Configure algorithm-specific parameters (if applicable).
    Add processes with their arrival times, burst times, and priorities.
    Click "Run" to visualize the algorithm's execution.
