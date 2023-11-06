# About

This repository is for first phase of the "Operating System" course project at Amirkabir University of Technology in Fall 2022

The project has 3 phases:

#####  _⤷  [_phase1](https://github.com/mahlashrifi/xv6_New_SystemCall/blob/master/README)

#####  _⤷  [_phase2](https://github.com/mahlashrifi/xv6_Thread_Implementation)

#####  _⤷  [_phase3](https://github.com/mahlashrifi/xv6_Cpu_Scheduling)



## Overview

XV6 is a simple Unix-like teaching operating system that serves as a reference to better understand the concepts of operating systems.

In this phase, we have extended the xv6 operating system by adding new system calls to enhance its functionality.



## Added System Calls

- `getTicks`: A system call that returns the number of timer ticks since the operating system started.
- `getProcInfo`: This system call provides the PID and creation time of all processes in the RUNNING state.

The functionality of these parts can be tested using `getTicksTest` and `getProcInfoTest` commands.



