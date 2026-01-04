<<<<<<< HEAD
# HoneyOS
=======
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

Clone el **repositorio** y continue con el proceso.

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

Para ejecutar el proyecto debe tomar en cuenta
que este proyecto es muy pesado y debera tener almenos 
15 Gb de espacio y 16 de RAM

```bash
docker compose up -d
```


## Documentation
>>>>>>> 61e42f0 (has config docker compose)
