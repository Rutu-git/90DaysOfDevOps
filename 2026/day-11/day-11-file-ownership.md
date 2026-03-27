# Day 11 – File Ownership Challenge (chown & chgrp)

## Task 1: Understand Ownership

<img width="899" height="254" alt="image" src="https://github.com/user-attachments/assets/4331192b-5bcb-45ee-9f4c-cc112952cd19" />

### Difference
- Owner = user who controls the file
- Group = users in that group share access based on permissions

## Task 2: chown (Change Owner)

<img width="731" height="177" alt="image" src="https://github.com/user-attachments/assets/7b9f9dcc-2b63-4cae-96f4-5f583de2e5a5" />

## Task 3: chgrp (Change Group)

<img width="805" height="261" alt="image" src="https://github.com/user-attachments/assets/8ba6a3b2-5ac5-45a1-b77e-668fe55c0fe0" />

## Task 4: Change Owner + Group Together

<img width="909" height="145" alt="image" src="https://github.com/user-attachments/assets/896656a2-5be0-4f01-b460-0bab01fa737b" />

## Commands Used
- ls -l
- touch filename
- mkdir directory
- sudo useradd username
- sudo groupadd groupname
- sudo chown owner filename
- sudo chgrp group filename
- sudo chown owner filename
- sudo chown -R owner directory

## What I Learned
- Every file has an owner and a group that control access.
- chown can change both owner and group, while chgrp changes only group.
- Recursive ownership (-R) is useful for managing entire project directories.
