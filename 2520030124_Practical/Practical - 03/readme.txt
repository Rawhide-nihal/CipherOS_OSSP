PRACTICAL-3
2520030124
M Nihal
S-7

Experiment: Process State Transitions in Linux
Aim:
To observe the different process states such as Ready, Running, Waiting, and Terminated using Linux monitoring tools like ps, top, and /proc.

Procedure:

1. Create a process using the following command:
   sleep 30 &

2. Find the process ID using:
   ps

   or:
   ps -ef | grep sleep

3. Check the process state using:
   ps -o pid,ppid,stat,cmd -p PID

   Replace PID with the process ID.

4. Check the process information using /proc:
   cat /proc/PID/status

5. Run the top command:
   top

   Observe the process and its CPU usage.

6. Press q to exit top.

Observations:

1. Ready:
   The process is ready to execute but is waiting for CPU time.

2. Running:
   The process is currently being executed by the CPU.

3. Waiting:
   The process is waiting for an event or resource. For example, the sleep command remains in a sleeping state until its timer expires.

4. Terminated:
   After the process finishes execution, it enters the terminated state and is removed from the active process list.

Example Output:

PID   PPID   STAT   CMD
2450  2300   S      sleep 30

In /proc/PID/status:

State:  S (sleeping)

Conclusion:

In this experiment, I observed process states using ps, top, and /proc. I understood that a process can move between different states depending on CPU availability, resource requirements, and execution. These Linux tools helped me understand how the operating system manages a process from execution to termination.
