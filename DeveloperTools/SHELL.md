#  OS Terminal, Console, Shell, and Kernel
- the terminal, console, shell and kernel all relate to how we interact with and understand computers, each serves a unique purpose
- the user interacts with the Terminal or Console, which hosts the Shell, and the Shell then communicates with the Kernel to execute commands and manage the system
- The Kernel is the foundation, managing the system's core operations and hardware.
- The Shell is the user-facing interface that allows users to send commands to the kernel.
- The Terminal (or a terminal emulator) provides the environment where the user types commands and sees the output, effectively running the shell.
- The Console represents a direct and often privileged access point to the system, often used for administrative tasks or troubleshooting, and it also runs a shell.

### Console
- a physical or virtual interface 
- provides a way to interact with the system
- the underlying hardware or software that provides a interface 
- can be a physical device, such as a keyboard and monitor
- can perform tasks such as booting the system

### Terminal/Command Line Interface
- a program that provides a text-based user-interface where you can communicate directly with the operating system
- terminal is a type of console, but not all consoles are terminals
- runs on top of the console
- you type commands, and the terminal processes those commands and displays output
- can execute commands, run programs, and display output
- Terminal(MAC), Command Prompt(Windows)

### Shell
- program that acts as an interpreter between the user and the kernel
- provides an interface (either command-line or graphical) for users to interact with the operating system
- when a user types a command, the shell interprets it and translates it into instructions that the kernel can understand and execute
- common examples include Bash in Linux and PowerShell in Windows
- There is 2 variants to the shell:
    - ***GUI shells:*** example is `File Explorer` that you use to interact with your files
    - **Commandline Interface:** a lot of the things that you do with the command line can be done using the GUI
        - the command line gives you greater control and it is easier and faster to do a lot of really common things

### Kernel
- core component of an operating system
- manages the system's hardware resources, including the CPU, memory, and input/output devices
- acts as a bridge between applications and the hardware, handling low-level tasks and providing essential services to other programs, including the shell
- a computer program that forms the innermost component of an OS after the Shell
- responsible for executing the commands with the help of othe components OS libraries and Device Drivers interacting with Application software and device hardware respectively




