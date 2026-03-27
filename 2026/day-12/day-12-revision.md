# Day 12 – Breather & Revision (Days 01–11)

## Commands used

<img width="1517" height="343" alt="image" src="https://github.com/user-attachments/assets/ee06d7a0-3812-4cb8-9509-288d8e239a3d" />

<img width="729" height="109" alt="image" src="https://github.com/user-attachments/assets/d7b5b3fa-5fd4-467c-a9bf-025f7bd7baf3" />

## Cheat Sheet 
- ls -l → check permissions & ownership
- cd → navigate directories
- chmod → change permissions
- chown → change ownership
- ps aux → check running processes

1. Which 3 commands save you the most time and why?
- ls -l → quickly shows permissions and ownership
- ps aux → helps identify running processes
- chmod → allows quick permission changes

2. How do you check if a service is healthy?
- systemctl status ssh
- ps aux | grep ssh
- journalctl -u ssh

3. How do you safely change ownership and permissions?
- sudo chown user:group file.txt
- chmod 640 file.txt

4. What will you focus on improving in the next 3 days?
- Better understanding of permissions (numeric values)
- More practice with real scenarios
- Speed in using Linux commands
