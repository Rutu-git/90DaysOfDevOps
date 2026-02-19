# Task 4 - Linux Practice: Processes and Services

# Process Checks

1. Check all running processes -

-> ps aux -
## Process Output

![ps command output](screenshots/ps-output.png)

2. Check interactive processes using top -

-> top
## Process Output

![top command output](screenshots/top-output.png)

3. Find process ID of ssh service -

-> pgrep ssh -
## Process Output

![pgrep ssh command output](screenshots/pgrep_ssh-output.png)

# Service Checks

1. Check service status -

->systemctl status nginx
# Service Output

![systemctl status nginx command output](screenshots/systemctl-status-nginx-output.png)

# Log Checks
1. Check logs of ssh service -
-> journalctl -u ssh --since "1 hour ago"

# log Output

![journalctl command output](screenshots/journalctl-output.png)

# Mini Troubleshooting Flow -

senario - nginx service is not running

1. check status -
     -> systemctl status nginx
2. Start the service -
     -> systemctl start nginx


