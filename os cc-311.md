### Operating Systems (CC-311) and Operating Systems Lab (CC-311L) Topics and Sub-Topics

#### 1. Operating System Basics
   - Operating systems fundamentals
   - System calls
   - Linux System Call Interface (CC-311L)

#### 2. Process Management
   - **Process Concept and Scheduling**
     - Process concept
     - Process scheduling algorithms
     - Multiple-processor scheduling
     - Process Creation and Termination (CC-311L)
       - getpid(), getppid(), fork(), exit(), wait(), execl() system calls
   - **Inter-Process Communication (IPC)**
     - Inter-process communication mechanisms
     - Linux IPC tools (CC-311L)
       - Pipes
       - FIFOs
       - Sockets
   - **Signals**
     - Signal delivery and execution of signal handlers (CC-311L)
     - Synchronous and asynchronous signals (CC-311L)
     - Standard and real-time signals (CC-311L)
     - Signal disposition (e.g., SIGHUP, SIGINT, SIGKILL, SIGPIPE, SIGALARM, SIGTERM, SIGQUIT, SIGILL, SIGFPE, SIGSEGV, SIGSTOP, SIGTSTP, SIGCHLD, SIGCONT) (CC-311L)
     - Sending signals using the kill command (CC-311L)

#### 3. Multithreading
   - **Multithreaded Programming**
     - Multithreading models
     - Threading issues
     - Thread scheduling
     - Writing multi-threaded C programs using POSIX pthread library (CC-311L)
       - pthread_create(), pthread_join(), pthread_exit()
   - **Thread Synchronization**
     - Synchronization problems
     - Critical section
     - Synchronization hardware
     - Thread synchronization using pthread_mutex_t, pthread_mutex_lock(), pthread_mutex_unlock() (CC-311L)
   - **Scheduling Parameters**
     - Use of Linux schedtool command (CC-311L)
       - Scheduling policy
       - Nice value
       - Static priority
       - CPU affinity

#### 4. Memory Management
   - Swapping
   - Contiguous memory allocation
   - Segmentation and paging
   - **Virtual Memory Management**
     - Demand paging
     - Thrashing
     - Memory-mapped files
   - Swap space management

#### 5. File Systems
   - **File System Concepts**
     - File concept
     - Directory and disk structure
     - Directory implementation
     - Free space management
     - Disk structure and scheduling
   - **Linux File System Architecture (CC-311L)**
     - Linux File Hierarchy Standard
     - Schematic view of a standard UNIX file system
       - Boot block
       - Superblock
       - Inode block
       - Data blocks
   - **File System Mounting (CC-311L)**
     - Concept of file system mounting
     - Linux configuration files related to file system mounting
     - Linux commands: mount, umount, lsblk, blkid
   - **Maintaining File System Integrity (CC-311L)**
     - Commands: fsck, e2fsck
   - **File System Creation (CC-311L)**
     - Tools: mkfs, mke2fs, mkntfs, mkfs.fat, mkfs.minix
   - **File Management in Linux (CC-311L)**
     - Concept of PPFD (Parent Process File Descriptor)
     - Input, output, and error redirection

#### 6. File Permissions
   - **Standard File Permissions (CC-311L)**
     - Use of chmod and chown commands
     - Setting default file permissions using umask
   - **Special File Permissions (CC-311L)**
     - Saved SUID bit on files
     - Saved SGID bit on files and directories
     - Sticky bit on files and directories

#### 7. Device Files and Terminal Attributes
   - **Device Files (CC-311L)**
     - Seven file types in Linux
     - Contents of /dev/ directory
   - **Terminal Attributes (CC-311L)**
     - Overview of terminal devices
     - Comparison between disk and terminal files
     - Examining and changing terminal attributes using the stty command

#### 8. Links in File Systems
   - **Hard and Soft Links (CC-311L)**
     - Differences between hard and soft links
     - Use of ln command to create hard and soft links

#### 9. Deadlocks
   - Deadlock detection
   - Deadlock recovery

#### 10. System Protection and Security
   - System protection mechanisms
   - Operating system security
   - Virtual machines

#### 11. Linux System Administration
   - **Interacting with Linux Operating System (CC-311L)**
     - Virtualization and hypervisors
     - Linux distributions
     - Installing Linux on Sun VirtualBox
   - **Managing Services Using systemd (CC-311L)**
     - Introduction to Linux system daemon
     - systemd unit files
       - Targets Unit Files
       - Service Unit Files
     - Shell commands using systemctl
     - Writing and running a basic service
   - **Booting Process of a Linux System (CC-311L)**
     - Five phases of Linux booting
       - BIOS/UEFI Initialization
       - Master Boot Record
       - Boot Loader
       - Kernel Initialization
       - init or systemd Process

#### 12. Linux System Programming
   - **Program File Analysis (CC-311L)**
     - Use of GNU gcc compiler on Linux terminal
     - Format of a program file on disk and its components
     - Viewing contents using objdump and readelf commands
