# Task 2 - Linux Architecture, Processes, and systemd


# Core component of linux -

1) Kernel - it is core of operating system.
            It directly interact with hardware(CPU,RAM,DISK)
            It manages process scheduling, memory management, file system

2) User Space - It is space where user applicatins run.
                Eg. shell, browser, services, editor

3) init/systemd - first process started by kernel.
                  responsible for starting and managing services.
   

# How processes are created and managed?

Process - process is running instance of program.
          Each process has: PID, Memory usage, state.
          

Process creation -

- A process uses fork() → creates child process

- Child uses exec() → loads new program

- Kernel schedules CPU time


Process States -
1. Running - currently executing
2. slepping - waiting for the event/input
3. stopped - paused manually
4. zombie - finished but not cleaned by parents
5. dead - completely terminated


# What systemd does and why it matters?

systemd - starts system during boot.
          manages background services.

why it matter? -> you manages services like nginx, docker,ssh . you troubleshoot failed services.
                  you checks logs and restart services.


# Daily Linux Commands -

1. ps aux - view running process
2. top - real-time process monitoring, display linux processes.
3. systemctl status <services> - check service status
4. kill <PID> - stops process
5. journalctl -xe - View system logs

