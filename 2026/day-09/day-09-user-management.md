# Day 09 – Linux User & Group Management Challenge

## Users & Groups Created
- Users: tokyo, berlin, professor, nairobi

<img width="535" height="440" alt="image" src="https://github.com/user-attachments/assets/bf164373-09b0-453e-9809-0886cf2574b9" />

<img width="873" height="175" alt="image" src="https://github.com/user-attachments/assets/883ad899-aeb1-4570-afbd-ca21d7a3b755" />

- Groups: developers, admins, project-team

  <img width="790" height="205" alt="image" src="https://github.com/user-attachments/assets/9af17c36-d8e6-4945-833f-e109a33dc4a6" />

## Group Assignments
- tokyo → developers, project-team
- berlin → developers, admins
- professor → admins
- nairobi → project-team

  <img width="748" height="258" alt="image" src="https://github.com/user-attachments/assets/7545217d-376b-43c2-9f76-9e96d67cd336" />

## Shared Directory

<img width="853" height="352" alt="image" src="https://github.com/user-attachments/assets/05b70edf-d9a3-4353-94a5-0e623de74be5" />

## Team Workspace

<img width="926" height="371" alt="image" src="https://github.com/user-attachments/assets/015a35fc-6ec7-4c66-bc5e-38b9f012f9c4" />

## Commands Used
- useradd -m username
- passwd username
- groupadd groupname
- usermod -aG group username
- groups username
- mkdir -p directory
- chgrp group directory
- chmod 775 directory
- sudo -u username command
- ls -ld directory

## What I Learned
1. How to create and manage users and groups in Linux
2. How group permissions enable collaboration
3. How to test access using different users
