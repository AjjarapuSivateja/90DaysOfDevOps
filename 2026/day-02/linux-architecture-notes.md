	Core components of linux:

Linux core components are - ASKH
•	Application(A)->Software and Graphical Interfaces that users interact with.
•	Shell(S)-> A command line interpreter to talk to kernel.
•	Kernel(K)-> Heart of linux, manages hardware,memory processes etc.
•	Hardware(H)-> Physical components like CPU, memory, disks etc.

	Process:
	Process is an instance of a computer program that is being executed.

Process states:

	Running or Runnable(R): when a process takes the cpu core to execute its logic,it is called running state. When a running process is to give up its cpu for other process,it goes into runnable state. 

	Sleeping state:
•	UnInterruptible sleep(D): waits for the resources to be available before it moves into a runnable state and doesn’t react to any signals.
•	Interruptible sleep(S):is  will react to signals and the availability of resources.

	Stopped State(T):From a running or runnable state, we could put a process into the stopped state(T)

	Zombie State(Z): When a process has completed its execution or is terminated, it’ll send the SIGCHLD signal to the parent process and go into the zombie state. The zombie process, also known as a defunct process, will remain in this state until the parent process clears it off from the process table.

	Systemd:
•	Systemd is both an init system and  a service manager for linux.
•	An init system (short for initialization) is the first program that runs when you turn on your computer. It has the special process ID of 1 and is responsible for starting everything else on your computer. 
•	A service manager, on the other hand, handles starting, stopping, and monitoring the programs (called services) that run in the background on your system.


