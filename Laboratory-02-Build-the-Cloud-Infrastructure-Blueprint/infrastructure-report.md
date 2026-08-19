# Infrastructure Report
---

## 🖥️ 1 — Operating System

The investigated cloud server is running **Ubuntu 24.04.4 LTS**, also known by its release name **Noble Numbat**.

Ubuntu LTS releases are designed to provide a stable and reliable environment for long-term use, making them well suited for server and cloud computing workloads.

**Operating System:** `Ubuntu 24.04.4 LTS`  
**Release Name:** `Noble Numbat`

---

## ⚙️ 2 — Kernel Version

The server is running the following Linux kernel:

**Kernel:** `6.8.0-136-generic`

The Linux kernel is responsible for managing core system operations, including hardware resources, processes, memory, and communication between the operating system and underlying infrastructure.

---

## 🧠 3 — CPU Model

The server is provisioned with an **Intel Xeon E312xx** processor identified with a **Sandy Bridge architecture** and IBRS security update.

**CPU Model:** `Intel Xeon E312xx`  
**Architecture:** `x86_64`  
**Architecture Generation:** `Sandy Bridge`

The `x86_64` architecture indicates that the server uses a 64-bit instruction set, which is standard for modern server and cloud computing environments.

---

## 🔢 4 — CPU Cores

The investigated environment provides **1 virtual CPU core**.

| CPU Configuration | Value |
|---|---:|
| **CPU(s)** | **1** |
| **Core(s) per Socket** | **1** |
| **Socket(s)** | **1** |

This represents a small-scale cloud computing environment suitable for basic server administration, command-line exercises, testing, and lightweight workloads.

---

## 💾 5 — Total RAM

The server has approximately **1.9 GiB of total RAM** available.

| Memory | Amount |
|---|---:|
| **Total** | **1.9 GiB** |
| Used | 411 MiB |
| Free | 870 MiB |
| Available | 1.5 GiB |
| Swap | 1.0 GiB |

The available memory indicates that the server still has sufficient resources for the lightweight tasks performed during this laboratory activity.

A **1.0 GiB swap space** is also configured, providing additional virtual memory that can be used when physical RAM becomes limited.

---

## 💿 6 — Disk Capacity

### Primary Storage

The server's primary storage provides approximately **19 GB** of disk capacity.

| Device | Size | Used | Available | Mount Point |
|---|---:|---:|---:|---|
| `/dev/vda1` | 19 GB | 5.4 GB | 13 GB | `/` |

The root partition `/` contains the primary operating system and other system files required for the server to operate.

### Additional Partitions

The system also contains dedicated boot-related partitions:

| Device | Size | Mount Point |
|---|---:|---|
| `/dev/vda16` | 881 MB | `/boot` |
| `/dev/vda15` | 105 MB | `/boot/efi` |

These partitions support the system's boot process and provide the necessary files for loading the operating system.

---

## 🗂️ 7 — Mounted File Systems

The server uses several file systems to organize system data and provide access to different parts of the operating environment.

### Main File Systems

| Mount Point | Source | File System |
|---|---|---|
| `/` | `/dev/vda1` | `ext4` |
| `/boot` | `/dev/vda16` | `ext4` |
| `/boot/efi` | `/dev/vda15` | `vfat` |

The primary root partition uses **ext4**, a widely used Linux file system designed for reliability and general-purpose storage.

### Virtual File Systems

The system also uses virtual file systems for managing hardware, processes, and kernel information.

| Mount Point | Source | File System |
|---|---|---|
| `/run` | `tmpfs` | `tmpfs` |
| `/dev` | `udev` | `devtmpfs` |
| `/proc` | `proc` | `proc` |
| `/sys` | `sysfs` | `sysfs` |

These virtual file systems do not function like traditional disk storage. Instead, they provide interfaces between the Linux kernel and system processes, devices, and runtime information.

---

## 🌐 8 — Hostname

The hostname assigned to the server is:

**Hostname:** `ubuntu`

The hostname provides an identifiable name for the system within its computing environment and is commonly used when managing multiple servers.

---

## 📡 9 — IP Address

The investigated server has the following network addresses:

**Primary IP:** `172.30.1.2`  
**Additional IP:** `172.17.0.1`

The primary address represents the server's main network interface within the laboratory environment, while the additional address is associated with another virtual or container-based network interface.

---

# 📊 Infrastructure Summarized version

The following table summarizes the key specifications identified during the cloud server investigation.

| Category | Result |
|---|---|
| **Operating System** | Ubuntu 24.04.4 LTS |
| **Kernel** | 6.8.0-136-generic |
| **CPU** | Intel Xeon E312xx |
| **CPU Architecture** | x86_64 |
| **CPU Cores** | 1 |
| **RAM** | 1.9 GiB |
| **Primary Disk** | 19 GB |
| **Root File System** | ext4 |
| **Hostname** | `ubuntu` |
| **Primary IP Address** | `172.30.1.2` |
| **Additional IP Address** | `172.17.0.1` |

---
