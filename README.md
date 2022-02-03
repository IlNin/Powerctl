# Powerctl
Co-developed with advisor Romolo Marotta for the Master’s degree, Powerctl is a Linux kernel module that introduces a suite of system calls that allows userspace software to target new performance profiles by transitioning to specific CPU hardware states. By enabling these states during spinlockbased synchronization, specifically in those phases of the execution where threads waste clocks by continuously spinning on the locks, it is possible to improve the efficiency of the computation.

In this repository you can find my thesis and presentation, for the code you can go to https://github.com/HPDCS/powerctl/tree/draft
