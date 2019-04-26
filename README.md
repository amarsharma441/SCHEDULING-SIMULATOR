# SCHEDULING-SIMULATOR
Problem Statement : Create a simulator for scheduling a given set of processes in user space only. The simulator should read from a configuration file a set of parameters for each process: Length of time for which process will execute, priority of the process and the preferred scheduling policy - FIFO or Round Robin, the time at which the process executes and if it is a CPU intensive process _or an I/O intensive process. Apart from this read the quantum of time given to each process. Now simulate a scheduling algorithm which uses FIFO/Round Robin with priority based scheduling.
At the end of the run print the following quantities for each process: 
a. Number of times the process was scheduled. 
b. A timeline for the process containing the state transitions - Ready, waiting 
c. Running and Terminated and the timestamp for each transition. 
d. Time taken to complete the process. 
e. Number of times the process waited for I/O. 
f. The priority of the process and preferred scheduling algorithm.
After printing the above values print the average time of completion for processes.

![](Input1.png)
