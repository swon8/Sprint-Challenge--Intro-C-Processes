**1. List all of the main states a process may be in at any point in time on a standard Unix system. Briefly explain what each of these states means.**

a) Created: Process is initialized but not ready to run
b) Ready: Process is waiting to be assigned to a processor by OS
c) Running: Is executing instructions
d) Waiting: Process waits for input to continue
e) Terminated: Process ends


**2. What is a zombie process?**
A process thats been terminated but still has an entry in the process table.


**3. How does a zombie process get created? How does one get destroyed?**
Its created when the parent process fails to call a wait command. It destroyed when its parent process calls wait and removes its entry from the process table.


**4. What are some of the benefits of working in a compiled language versus a non-compiled language? More specifically, what benefits are there to be had from taking the extra time to compile our code?**

Compiled languages need to only be translated into machine language one time - when it is compiled. This allows for more efficient code and better memory management.