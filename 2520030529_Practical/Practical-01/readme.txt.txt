PRACTICAL 01

BANDARU THRINADH
2520030529



Lab Summary: Linux Command Execution and Hardware Management

In this lab, I learned how the Linux operating system creates and manages processes and how it interacts with computer hardware. I used a C program with fork(), exec(), and wait() to understand how a command entered by the user is executed.

Here is a breakdown of what I learned:

fork(): This system call creates a new child process from the parent process. I learned how Linux uses processes to execute different tasks.
exec(): The execlp() system call was used to execute the Linux command entered by the user. It replaces the child process with the specified command.
wait(): The wait() system call allows the parent process to wait until the child process finishes execution.
getpid() and getppid(): These functions were used to display the process ID of the current process and its parent process.
uname -a: This command displayed information about the Linux kernel and system architecture.
lscpu: This showed information about the CPU, including the number of cores, threads, and processor details.
lsblk: This displayed the storage devices and partitions available in the system.
ps and top: The ps command displayed running processes, while top provided a real-time view of processes and their CPU and memory usage.
Conclusion

Overall, this practical helped me understand how Linux executes commands using processes and system calls. I also learned how Linux manages CPU, memory, storage, and running processes. The operating system acts as a bridge between software and hardware and provides services that allow applications to use hardware resources efficiently.