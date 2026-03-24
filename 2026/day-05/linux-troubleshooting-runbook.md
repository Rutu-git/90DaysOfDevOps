# Day 05- Linux Troubleshooting Drill

## Step 1: Check if cron is running
- systemctl status cron -
  shows service is active or inactive, shows logs, displays PID

  <img width="1516" height="532" alt="image" src="https://github.com/user-attachments/assets/a3127fc8-b5b3-4ace-820f-1614833208c2" />

## Step 2: Environment Basics
- uname -a -
  shows kernel version and OS architecture
  <img width="1468" height="133" alt="image" src="https://github.com/user-attachments/assets/e799979a-ea39-4fc4-9bb6-7aff9b914190" />

- cat /etc/os-release -
  shows OS name and version
  <img width="1061" height="392" alt="image" src="https://github.com/user-attachments/assets/e0487ece-748f-48dd-a4da-0edacc8c9fd7" />

## Step 3: Filesystem Sanity Check
- mkdir /tmp/runbook-demo -
  creates temp directory

- cp /etc/hosts /tmp/runbook-demo/hosts-copy -
  copies file

- ls -l /tmp/runbook-demo -
  list file details
  <img width="835" height="115" alt="image" src="https://github.com/user-attachments/assets/dd492fae-b11e-45de-859f-157e7e243fd7" />

## Step 4: Get Process ID of cron
- ps aux | grep cron -
  finds cron process
  <img width="1112" height="106" alt="image" src="https://github.com/user-attachments/assets/06115008-1643-4817-84bb-032280d0aad2" />

## Step 5: CPU & Memory Analysis 
- top -
  shows CPU live usage , memory usage
  <img width="1078" height="639" alt="image" src="https://github.com/user-attachments/assets/0e7d9472-c468-4d62-88a2-1576e8e8924f" />

- ps -o pid,pcpu,pmem,comm -p 1023 -
- 
  
