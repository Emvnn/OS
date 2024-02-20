# Chapter One -- Introduction -- Lecture Notes

**An operating system acts as an intermediary between the user of a computer and the computer hardware.**

**The purpose of an operating system is to provide an environment in which a user can execute programs in a convenient and efficient manner.**

**A computer system can be divided roughly into four components: the hardware (computing resources), the operating system, the application programs, and a user.**

# 1.1 What Operating Systems Do

**Roughly speaking, a computing system consists of hardware, operating system, application programs, and a user.**


![text](https://www.cs.csustan.edu/~john/Classes/CS3750/Notes/Chap01/1_01cmpnts.jpg)


- **1.1.1 User View -** For many personal devices, the main goal of the OS is to make the computer easy to use.
- **1.1.2 System View -** the computer relies on the OS to allocate, manage, and control the resources, such as CPU time, forms of memory, and I/O devices.
- **1.1.3 Defining Operating Systems**
  - Operating systems first emerged as a form of automation, taking over tasks that had previously been performed by the user, the operator, of the computer.
  - We may think of an OS as a collection of automatic functions that make using the hardware easier, safer, and more efficient.
  - Usually when computer science professionals refer to the operating system, they mean something called the kernel.
  - The study of operating systems is mostly about the study of kernels.
    
In summary, the operating system includes the alwaysrunning kernel, middleware frameworks that ease application development and provide features, and system programs that aid in managing the system while it is running. 

# 1.2 Computer-System Organization

![text](https://www.cs.csustan.edu/~john/Classes/CS3750/Notes/Chap01/1_02typclPC.jpg)


the typical components of a personal computer: a bus, CPUs, primary memory, device controllers, and peripherals. An operating system is responsible for operating the peripherals by sending instructions to device controllers. Different device controllers have to be operated with their own special commands, so usually an OS has a separate section of code called a device driver, for interacting with each different kind of device controller.

- **1.2.1 Interrupts**

