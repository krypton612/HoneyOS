## Overview

This repository is a **fork and practical guide based on the T-Pot project**, intended for deployment and experimentation purposes.

---

## Prerequisites

Before starting, ensure the following tools are installed on your system:

- Docker
- Docker Compose

---

## Setup
### Step 1 — Clone this repository


Clone the **repository** and continue with the process.

```bash
git clone https://github.com/krypton612/HoneyOS
```

### Step 2 — Create the working directory

Create a directory owned by **UID 2000** and **GID 2000**.  
This directory will be used as a shared Docker volume.

```bash
cd HoneyOS
mkdir data
sudo chown 2000:2000 data
```
## Run

### Step 3 — Run this project


To run the project, please note that it is a very large project and will require at least 15 GB of disk space and 16 GB of RAM.

```bash
docker compose up -d
```


## Documentation
[HoneyOS - Documentation](https://krypton612.github.io/docs/)