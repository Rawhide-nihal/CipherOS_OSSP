PRACTICAL 03

BANDARU THRINADH
2520030529


Lab Summary: Process Creation and Process State Management

In this lab, I learned how the Linux operating system creates and manages processes using the fork() system call. I developed a C program to create a parent and child process and displayed their Process IDs (PID) and Parent Process IDs (PPID). I also observed different process states using Linux monitoring tools.

Here is a breakdown of what I learned:

fork(): This system call creates a new child process from the existing parent process. Both processes continue their execution after fork().
getpid(): This function displays the PID of the current process. It helped me identify the parent and child processes.
getppid(): This function displays the PPID of a process and shows the relationship between the child and its parent.
wait(): The parent process uses wait() to wait for the child process to complete its execution.
sleep(): The sleep() function was used to keep the child process active for some time so that its state could be observed using Linux monitoring tools.
ps: This command was used to view the PID, PPID, and current state of running processes.
top: This command provided a real-time view of running processes and their CPU and memory usage.
/proc: The /proc/PID/status file was used to check detailed information about a particular process, including its current state, PID, and PPID.
Conclusion

Overall, this practical helped me understand how Linux creates parent and child processes and manages their execution. I learned how to identify processes using PID and PPID and observe their states using ps, top, and /proc. This practical also helped me understand the process life cycle from creation and execution to waiting and termination.