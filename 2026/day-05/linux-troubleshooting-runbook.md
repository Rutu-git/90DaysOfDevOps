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
  shows CPU % used by cron , memory %
  <img width="665" height="117" alt="image" src="https://github.com/user-attachments/assets/67b24845-a392-421e-8338-7569ca7ad0a3" />

- free -h -
  shows RAM usage
  <img width="1048" height="137" alt="image" src="https://github.com/user-attachments/assets/aaf69d5b-723b-44b7-995b-690beabed470" />

## Step 6: Disk & IO Check
- df -h -
  shows disk usage
  <img width="1049" height="458" alt="image" src="https://github.com/user-attachments/assets/6baeb4fd-7443-4ec2-aaa1-91aa11e011ef" />

- du -sh /var/log -
  shows log folder size

## Step 7: Network Check
- ss -tulpn -
  opens port
  <img width="1428" height="284" alt="image" src="https://github.com/user-attachments/assets/e762c5e9-afb4-4d99-9573-36cbe4a37da0" />

- curl -I http://localhost -
  test local response

## Step 8: Logs Analysis
- journal -u cron -n 50 -
  shows last 50 logs of cron

- tail -n 50 /var /log/syslog -
  shows system logs
  
