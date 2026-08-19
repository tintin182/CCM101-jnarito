# Infrastructure Components Found in My Linux Environment

This document identifies the main infrastructure components found in my Linux environment and connects each one to the concepts discussed in Chapter 2.

---

## 🖥️ Compute Resources

```

**Intel Xeon E312xx (Sandy Bridge, IBRS update)**  
**CPU:** 1 core  
**Architecture:** x86_64
```


Compute resources provide the processing power needed to run commands, applications, and other workloads. In a cloud environment, this processing power can come from virtual machines, virtual CPUs, GPUs, and other computing resources.

### Why is it important in cloud computing?

Without compute resources, applications and services would have no processing power to run. Cloud computing allows computing resources to be provided through virtual environments, making it possible to run workloads without directly managing the physical hardware.

### Relation to the KillerCoda Linux Environment

In my KillerCoda environment, the system is using an **Intel Xeon E312xx processor with 1 CPU core**. This virtual computing resource is what allows the Ubuntu Linux environment to process commands and run the activities required in this laboratory.

---

## 💾 Storage Resources

```

**Primary Storage:** 19 GB  
**Main Device:** `/dev/vda1`  
**Filesystem:** `ext4`  
**Available:** 13 GB
```
### Purpose

Storage resources provide space for keeping the operating system, applications, files, and other data. They allow information to remain available even when it is not currently being processed.

### Why is it important in cloud computing?

Cloud systems need storage to keep the data and files used by applications and services. Having reliable storage also makes it possible to manage and access data as computing needs change.

### Relation to the KillerCoda Linux Environment

The KillerCoda environment uses **`/dev/vda1` as its main storage device**, with a total capacity of **19 GB**. The system also has separate partitions for `/boot` and `/boot/efi`, which are part of the Linux environment.

---

## 🌐 Networking Resources

```

**Hostname:** `ubuntu`  
**IP Address:** `172.30.1.2`  
**Additional IP:** `172.17.0.1`
```
### Purpose

Networking resources allow computers, services, and other systems to communicate with each other. They provide the connection needed to send and receive information.

### Why is it important in cloud computing?

Networking is important because cloud resources are not isolated. They need to communicate with users, applications, servers, and other services. A working network allows these resources to exchange information and remain accessible.

### Relation to the KillerCoda Linux Environment

The KillerCoda environment identifies itself with the hostname **`ubuntu`** and has the IP addresses **`172.30.1.2`** and **`172.17.0.1`**. These addresses show the network information assigned to the Linux environment.

---

## 🐧 Operating System

```

**Ubuntu 24.04.4 LTS (Noble Numbat)**  
**Kernel:** `6.8.0-136-generic`
```
### Purpose

The operating system manages the computer's resources and provides the environment where commands and applications can run. It gives the user a way to interact with the system and its resources.

### Why is it important in cloud computing?

The operating system is the working environment that allows users and applications to use the available computing resources. It helps manage the system and provides the tools needed to perform different tasks on a cloud server.

### Relation to the KillerCoda Linux Environment

The Linux environment provided by KillerCoda is running **Ubuntu 24.04.4 LTS** with the **6.8.0-136-generic kernel**. This is the operating system I used to access the cloud environment and complete the laboratory activities.

---

## 📋 Summary

| Infrastructure Component | Value |
|---|---|
| 🖥️ Compute | Intel Xeon E312xx, 1 CPU core |
| 💾 Storage | 19 GB `/dev/vda1`, ext4 |
| 🌐 Networking | `ubuntu`, 172.30.1.2, 172.17.0.1 |
| 🐧 Operating System | Ubuntu 24.04.4 LTS |
