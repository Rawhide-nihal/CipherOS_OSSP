PRACTICAL-1
2520030124
M Nihal
S-7



In this practical, I studied how the Linux operating system interacts with the hardware resources of a computer and provides different services to applications. For this purpose, I used Linux terminal commands such as uname, lscpu, lsblk, ps, and top. These commands helped me observe the system information, CPU details, storage devices, running processes, and resource utilization. From this practical, I understood that the Linux kernel acts as an important layer between the hardware and the software running on the system.

The uname -a command was used to obtain information about the Linux system, including the kernel name, kernel version, and machine architecture. The lscpu command provided details about the processor, such as CPU architecture, number of CPUs, cores, and threads. This helped me understand how Linux manages the processor through CPU scheduling. Multiple applications can run at the same time because the operating system allocates CPU time among different processes instead of allowing applications to directly control the CPU.

The lsblk command was used to identify the storage devices and partitions connected to the system. I understood that Linux provides an abstraction over physical storage devices by using block devices and filesystems. Applications can access data using files and directories without needing to know the physical sectors or exact location where the data is stored. The operating system and device drivers perform the required operations with the actual storage hardware.

The ps command was used to display the processes currently running on the system. It helped me understand that when a program is executed, the operating system creates a process and assigns it resources such as CPU time and memory. The top command provided a real-time view of running processes along with their CPU and memory usage. This demonstrated how Linux continuously monitors and manages the available system resources.

From this practical, I understood that the operating system provides an abstraction layer between applications and physical hardware. CPU resources are managed through processes and scheduling, memory is handled through virtual memory and allocation, storage is provided through filesystems and device drivers, and I/O devices are accessed through operating system services and drivers. Thus, Linux hides the complexity of hardware from applications and provides a simple and standardized way to use computer resources while the kernel manages the actual hardware operations.
