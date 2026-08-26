PRACTICAL 02

BANDARU THRINADH
2520030529



Lab Summary: File Management and System Call Tracing

In this lab, I learned how the Linux operating system manages files using system calls. I developed a C program using open(), read(), write(), and close() to copy the contents of one file into another file. I also used the strace command to observe the system calls generated when reading a file using the cat command.

Here is a breakdown of what I learned:

open(): This system call is used to open a file. It returns a file descriptor that is used to access the file.
read(): This system call reads data from the source file into a buffer.
write(): This system call writes the data from the buffer into the destination file.
close(): This system call closes the files after the copying operation is completed.
strace: This utility was used to trace the system calls made by the cat sample.txt command. It helped me observe calls such as openat(), read(), write(), and close().
User Space and Kernel Space: The C program runs in user space, and when it needs to access files, it requests services from the kernel through system calls. The kernel handles the actual file and storage operations.
Conclusion

Overall, this practical helped me understand how Linux manages files through system calls. I learned how data moves between user space and kernel space during file operations and how strace can be used to observe the system calls made by a program. This practical also helped me understand the role of the Linux kernel in providing file management services.