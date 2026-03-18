## Day 30 – Docker Images & Container Lifecycle

## Task 1: Docker Images
- docker pull nginx
- docker pull ubuntu
- docker pull alpine
  
<img width="1077" height="427" alt="image" src="https://github.com/user-attachments/assets/fa549e33-8dc2-42e5-95f8-e67f9223ddad" />

<img width="1005" height="290" alt="image" src="https://github.com/user-attachments/assets/8efe8a13-2408-456d-97a4-1b8c0312c9a7" />

<img width="1031" height="226" alt="image" src="https://github.com/user-attachments/assets/b51d7c4d-50dc-4c5a-a631-d9d028d031dd" />

# List of images

<img width="1160" height="670" alt="image" src="https://github.com/user-attachments/assets/ab0e770d-ea13-4c8e-9835-0667394011fb" />

## Compare Ubuntu vs Alpine

ubuntu → Large (~78.1MB)

alpine → Very small (~8.44MB)

Why Alpine is smaller?

Minimal OS (only essential packages)

Uses musl libc instead of glibc

Designed for lightweight containers

## Inspect an Image

Shows detailed JSON info:
- Layers
- Environment variables
- Entry point
- Network config

<img width="1355" height="736" alt="image" src="https://github.com/user-attachments/assets/6a2963bb-69c1-490c-af19-0c98de583fa2" />

<img width="1461" height="682" alt="image" src="https://github.com/user-attachments/assets/3cd05697-c667-43ea-b433-a63a33dd9679" />

<img width="1456" height="696" alt="image" src="https://github.com/user-attachments/assets/9501bb77-3e88-45ad-907b-c90a4a16c5dc" />

# Remove an Image

<img width="1104" height="149" alt="image" src="https://github.com/user-attachments/assets/fdb135dd-b9c2-4036-a18d-896bbb5714d6" />

## Task 2: Image Layers
- Shows layers used to build the image
- Each command in Dockerfile = one layer

<img width="1361" height="570" alt="image" src="https://github.com/user-attachments/assets/52082a14-52f9-4cf3-a286-c175493a1725" />

## What are Layers?

Docker images are made of multiple layers

Each layer is:
- Read-only
- Cached
- Reusable

## Why Docker uses layers:
- Faster builds (caching)
- Efficient storage (shared layers)
- Easy version control

## Task 3: Container Lifecycle
Creates container but does not start it

<img width="819" height="136" alt="image" src="https://github.com/user-attachments/assets/96969918-14c6-447b-838c-a7b198b2c587" />

Start Container

<img width="504" height="82" alt="image" src="https://github.com/user-attachments/assets/153fc36f-c920-4fc5-a865-323d6d887554" />

Pause Container

<img width="498" height="81" alt="image" src="https://github.com/user-attachments/assets/69584ddc-5645-45ba-978f-993058074982" />

Unpause Container

<img width="537" height="93" alt="image" src="https://github.com/user-attachments/assets/ee0e67c5-434c-42e1-b0d9-fddac3227606" />

Restart Container

<img width="550" height="97" alt="image" src="https://github.com/user-attachments/assets/93e0612f-377b-4193-a42a-6fd6957ae45d" />

Kill Container

<img width="537" height="100" alt="image" src="https://github.com/user-attachments/assets/78443c37-1024-48d3-b099-b57c012cb990" />

Remove Container

<img width="535" height="88" alt="image" src="https://github.com/user-attachments/assets/cb974a16-8227-4546-b01b-701f789d7019" />

Check Status

<img width="1452" height="708" alt="image" src="https://github.com/user-attachments/assets/50e4a1a2-734d-4298-bb4d-be081663ed10" />

## Task 4: Working with Running Containers

- Run Nginx in Detached Mode

<img width="910" height="94" alt="image" src="https://github.com/user-attachments/assets/6eb8dac6-9186-4d11-9462-ac398c23d3cc" />

- View Logs

<img width="1240" height="632" alt="image" src="https://github.com/user-attachments/assets/5bd04649-105e-4c38-ad21-3d0431341629" />

- Exec into Container

<img width="1198" height="236" alt="image" src="https://github.com/user-attachments/assets/365f1a39-4a82-4b87-b2f7-3231786755b6" />

## Task 5: Cleanup
- Stop All Running Containers

<img width="600" height="108" alt="image" src="https://github.com/user-attachments/assets/02c534be-99c5-4206-b112-f888de293374" />

- Remove All Stopped Containers

<img width="525" height="442" alt="image" src="https://github.com/user-attachments/assets/6ff65f2c-878e-4261-a252-11f1f2532fed" />

- Check Disk Usage

<img width="821" height="183" alt="image" src="https://github.com/user-attachments/assets/14c12e4c-bacb-4fcd-bb13-4895a7203e55" />




