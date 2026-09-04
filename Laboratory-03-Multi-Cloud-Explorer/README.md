## 🎯 Task

Launch a **KillerCoda Playground**.

Using Linux commands, identify the following information about the Linux server:

- 🖥️ Operating System
- ⚙️ CPU Information
- 🧠 Memory
- 💾 Disk Space

After collecting the information, answer the following question:

> **If this Linux server were migrated to the cloud, which AWS, Azure, and GCP services could host it?**

---

# 🔎 Linux Server Investigation

## 🖥️ 1. Operating System

### Command Used

```bash
cat /etc/os-release
```

### What Does This Command Do?

The `cat /etc/os-release` command displays information about the Linux operating system, including the distribution name and version.

### 📸 Terminal Output

![Operating System Information](screenshots/KillerCoda-terminal-1.png)

---

## ⚙️ 2. CPU Information

### Command Used

```bash
lscpu | grep -E 'Model name|^CPU\(s\):'
```

### What Does This Command Do?

This command displays only the important CPU information from `lscpu`:

- **Model name** – Shows the CPU model.
- **CPU(s)** – Shows the total number of logical CPUs.

Using `grep` filters the output so that only the required CPU information is displayed.

### 📸 Terminal Output

![CPU Information](screenshots/cpu-information.png)

---

## 🧠 3. Memory

### Command Used

```bash
free -h
```

### What Does This Command Do?

The `free -h` command displays information about the system's memory usage, including total, used, free, and available memory.

The `-h` option displays the values in a human-readable format such as MB or GB.

### 📸 Terminal Output

![Memory Information](screenshots/memory-information.png)

---

## 💾 4. Disk Space

### Command Used

```bash
df -h
```

### What Does This Command Do?

The `df -h` command displays information about the disk space used and available on the server's file systems.

The `-h` option displays the storage values in a human-readable format.

### 📸 Terminal Output

![Disk Space Information](screenshots/disk-space-information.png)

---

# 🐧 Linux Commands Used

| Command | Purpose | What It Does |
|---|---|---|
| `cat /etc/os-release` | 🖥️ Operating System | Displays information about the Linux distribution and version. |
| `lscpu \| grep -E 'Model name\|^CPU\(s\):'` | ⚙️ CPU Information | Displays the CPU model and total number of logical CPUs. |
| `free -h` | 🧠 Memory | Displays memory usage in a human-readable format. |
| `df -h` | 💾 Disk Space | Displays used and available disk space in a human-readable format. |

---

# ☁️ Cloud Migration

## ❓ Question

> **If this Linux server were migrated to the cloud, which AWS, Azure, and GCP services could host it?**

---

## 🟠 AWS – Amazon EC2

**Amazon EC2 (Elastic Compute Cloud)** could host the Linux server as a virtual machine.

EC2 allows CPU, memory, storage, and networking resources to be configured based on the requirements of the Linux server.

### Supporting Services

| AWS Service | Purpose |
|---|---|
| **Amazon EC2** | 🖥️ Hosts the Linux server as a virtual machine. |
| **Amazon EBS** | 💾 Provides persistent storage for the EC2 instance. |
| **Amazon VPC** | 🌐 Provides networking for the EC2 instance. |

---

## 🔵 Azure – Azure Virtual Machines

**Azure Virtual Machines** could host the Linux server as a virtual machine.

Azure provides Linux-compatible virtual machines with different CPU, memory, storage, and networking configurations.

### Supporting Services

| Azure Service | Purpose |
|---|---|
| **Azure Virtual Machines** | 🖥️ Hosts the Linux server as a virtual machine. |
| **Azure Managed Disks** | 💾 Provides persistent storage for the virtual machine. |
| **Azure Virtual Network** | 🌐 Provides networking for the virtual machine. |

---

## 🟢 GCP – Compute Engine

**Google Compute Engine** could host the Linux server as a virtual machine.

Compute Engine supports Linux operating systems and allows CPU, memory, storage, and networking resources to be configured according to the server's requirements.

### Supporting Services

| GCP Service | Purpose |
|---|---|
| **Compute Engine** | 🖥️ Hosts the Linux server as a virtual machine. |
| **Persistent Disk** | 💾 Provides persistent storage for the virtual machine. |
| **Virtual Private Cloud (VPC)** | 🌐 Provides networking for the virtual machine. |

---

# 📊 Cloud Service Comparison

| Category | 🟠 AWS | 🔵 Azure | 🟢 GCP |
|---|---|---|---|
| 🖥️ **Compute** | Amazon EC2 | Azure Virtual Machines | Compute Engine |
| 💾 **Storage** | Amazon EBS | Azure Managed Disks | Persistent Disk |
| 🌐 **Networking** | Amazon VPC | Azure Virtual Network | VPC |
| 🐧 **Linux Support** | ✅ Yes | ✅ Yes | ✅ Yes |

---

# 📝 Final Answer

If this Linux server were migrated to the cloud, the following services could host it:

| Cloud Provider | Recommended Service |
|---|---|
| 🟠 **AWS** | **Amazon EC2** |
| 🔵 **Azure** | **Azure Virtual Machines** |
| 🟢 **GCP** | **Compute Engine** |

All three cloud providers provide virtual machine services capable of running Linux servers.

The appropriate virtual machine size and configuration should be selected based on the **CPU, memory, disk space, operating system, and workload requirements** identified during the Linux investigation.

### 💡 Conclusion

The Linux server can be hosted on **AWS, Azure, or GCP** using their respective virtual machine services:

- 🟠 **AWS → Amazon EC2**
- 🔵 **Azure → Azure Virtual Machines**
- 🟢 **GCP → Compute Engine**

These services provide the necessary computing environment to run a Linux server in the cloud.
