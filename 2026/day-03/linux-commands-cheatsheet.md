# Task 3 - Linux Commands Practice

# Process Management

1. ps aux - list all running processes
2. ps -ef - detailed process list with parent PID
3. top - real time process monitoring
4. htop - interactive process viewer
5. kill <PID> - terminate process by PID
6. kill -9 <PID> - force kill process
7. pkill <name> - kill process by name
8. bg - resume process in background
9. fg - bring process to foreground
10. jobs - show background jobs


# File System Commands

1. ls -l - list files with details
2. ls -a - show hidden files
3. cd <dir. - change directory
4. pwd - show current directory
5. mkdir <name> - create directory
6. rm <file> - remove file
7. rm -r <dir> - remove directory recursively
8. cp <src> <dest> - copy files/directory
9. mv <src> <dest> - move or rename file
10. touch <file> - create empty file
11. cat <file> - display file content
12. less <file> - view large file page by page
13. head <file> - show first 10 lines
14. tail -f <file> - live log monitoring
15. chmod 755 <file> - change file permission
16. chown user:group <file> - change file owner


# Networking Troubleshooting
1. ping <host> - check connectivity to server
2. ip addr - show ip address info
3. ss -tuln - show listening ports
4. netstat -tuln -check open ports
5. curl <url> - test HTTP request
6. dig <domain> - DNS lookup
7. traceroute <host> - trace network path

# Disk & System Info (Useful in Troubleshooting)

1. df -h - check disk space usage
2. du -sh <dir> - check folder size
3. free -m - check memory usage
4. uptime - show system load and uptime
5. uname -a - show system info
6. whoami - show current user


# During real troubleshooting:

- First check system → uptime, free -m, df -h

- Then check process → ps, top

- Then check network → ping, curl, ss

- Then check logs → tail -f /var/log/syslog
