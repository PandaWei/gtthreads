# gtthreads
Two thread libraries - One POSIX compliant, another a symmetric multiprocessor library

Following added-by <weijg.fnst@cn.fujitsu.com>
https://www.quora.com/How-does-the-timer-interrupt-invoke-the-process-scheduler

Vinay Bharadwaj said,

Since this question is already answered, I will try to provide some code reference which someone may find useful. 
My github profile (jedivind/gtthreads) has two thread library implementations with schedulers for anyone interested
in learning more about how to set up timers, handlers, contexts and how to switch contexts with a scheduler.

The first implementation is a POSIX compliant user threads library implementation, like pthreads, but simpler. 
It uses a round robin scheduler.

The second implementation is a library for Symmetric multiprocessors and implements the Completely Fair Scheduler(CFS scheduler)
from the Linux kernel.
