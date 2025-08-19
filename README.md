# Weenix Kernel — Demonstration

This repository showcases the results of my work on **Weenix**, a Unix-like toy kernel.  
The source code is not included (per course policy), but here you can find screenshots, recordings,  
and explanations of the kernel features we (Group of 2) implemented as part of the semested long Kernel project of the course CSCI402 at USC.

---

## Features Implemented

- **Processes & Threads**
    - Full process lifecycle
    - Thread scheduling, synchronization
    - Mutexes & wait queues

- **Virtual File System (VFS)**
    - System calls: `open`, `close`, `read`, `write`
    - File descriptor tables per process
    - Support for device files

- **Virtual Memory**
    - Page fault handler
    - `mmap()` and `brk()` implementations
    - Copy-on-write and full `fork()` pipeline

---

## Demo
#### User Shell
![User Shell](assets/user_shell.jpeg)

#### User Shell `help` command
![User Shell Help](assets/help.jpeg)

#### User Shell `cat` command
![User Shell cat](assets/cat.jpeg)

#### Kernel Shell `help` command
![K Shell kshell_help](assets/kshell_help.jpeg)

#### User Shell `ls` command
![User Shell ls](assets/ls.jpeg)

#### User Shell `stat` command
![User Shell stat](assets/stat.jpeg)

#### User Shell `faber thread tests`
![User Shell cat](assets/faber_thread_tests.gif)

#### User Shell `fork-and-wait`
![User Shell fork](assets/fork_and_wait.jpeg)

#### `forkbomb` test - Upto 250 child threads
![User Shell forkbomb250](assets/forkbomb250.gif)

#### `forkbomb` test - Upto 500 child threads
![User Shell forkbomb500](assets/forkbomb500.gif)

#### `memtest`
![User Shell memtest](assets/memtest.jpeg)

#### `stresstest`
![User Shell stress](assets/stress.gif)
