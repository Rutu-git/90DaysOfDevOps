# Day 29 – Introduction to Docker

# Task 1:
## Docker -
Docker is a platform that allows you to build, package and run application inside container.
This ensures that application runs same everywhere.

## Container -
A container is lightweight, standalone package that includes application code, runtime, libraries and files.

## Container VS Virtual Machine -
-Container - share the host OS kernel and isolate application
-VM - runs full operating system on hypervisor

## Docker Architecture -
1. Docker client - command line tool
2. Docker Daemon - runs in background
3. Docker images - read-only template
4. Docker container - running instance of image
5. Docker registry - stores docker images

# Task 2: Install Docker
 1. Install Docker (Ubuntu) -
sudo apt update
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker

2. Verify Installation -
<img width="718" height="163" alt="image" src="https://github.com/user-attachments/assets/18b1f410-b8e2-45c8-a64f-69d24754ca2d" />

3. Run Hello World Container -
<img width="1025" height="594" alt="image" src="https://github.com/user-attachments/assets/cd4dd0ec-c497-4034-af55-5bea3453b40f" />

# Task 3:
## Running real containers -
<img width="812" height="110" alt="image" src="https://github.com/user-attachments/assets/980697b2-4638-4f16-bab2-beaeddefa2e0" />

<img width="1596" height="538" alt="image" src="https://github.com/user-attachments/assets/d46e3f99-66b1-4388-961a-1884326d4066" />

## Run Ubuntu Container -
<img width="1181" height="265" alt="Screenshot 2026-02-25 214249" src="https://github.com/user-attachments/assets/d1f26801-6084-4ecf-ae78-822d3687d148" />

## List Running Containers -
docker ps -
<img width="1461" height="468" alt="image" src="https://github.com/user-attachments/assets/138a54e7-d85e-428e-af10-07f6dff1ce81" />

## Stop and Remove Container -
<img width="543" height="135" alt="image" src="https://github.com/user-attachments/assets/cc640f34-a3fa-4534-9475-33d509cdd62d" />



