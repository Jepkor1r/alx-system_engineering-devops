#Processes and signals
Processes can be created, managed, and terminated by the operating system
Examples of processes include web servers, database servers, and user applications
Signals in Linux
Signals are a way for the operating system to communicate with a running process
Signals are software interrupts that notify a process of an event or condition
Signals can be sent to a process for various reasons, such as:
Termination of the process
Attempt to access invalid memory
Receipt of input (e.g., Ctrl+C)
Expiration of a timer
Handling Signals
Processes can handle signals in different ways:
Default Action: The operating system has predefined actions for each signal, such as terminating the process or ignoring the signal.
Signal Handler: A process can define a custom signal handler function that is called when a specific signal is received. This allows the process to perform specific actions in response to the signal.
Signal Blocking: A process can choose to block certain signals, preventing them from being delivered and handled.
Signal Management Tools
kill command: Used to send signals to processes. Can specify the signal to be sent and the target process.
psig command: Displays information about the signals that are queued, pending, blocked, or ignored by a process.
signal system call: Allows a process to set a custom signal handler function for a specific signal.
