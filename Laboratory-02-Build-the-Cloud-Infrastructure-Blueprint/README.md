# Laboratory 02 — Build the Cloud Infrastructure Blueprint
---

## 1. Mission Overview

Congratulations,

Your onboarding has been successfully completed, and your Cloud Computing Portfolio has been approved by

your supervisor.

CloudNova Technologies has now assigned you to your **first official project**.

Before deploying cloud services, every cloud engineer must understand the infrastructure that powers modern

cloud computing. Your mission is to investigate the components of cloud infrastructure, identify how compute,

storage, networking, and identity services work together, and document your findings as if you were preparing

technical documentation for a client.

Using the **KillerCoda Playground**, Linux tools, official cloud documentation, and your GitHub Cloud Computing

Portfolio, you will complete a series of engineering tasks that simulate the planning phase of a cloud deployment.

Remember: **Great cloud engineers build systems—but exceptional cloud engineers document and justify**

**every design decision.**

---

## 2. Objectives

At the end of this laboratory activity, you should be able to:

- Explain the major components of cloud infrastructure.
- Investigate the hardware and software resources available in a Linux environment.
- Differentiate compute, storage, networking, and identity resources.
- Interpret the relationship between cloud infrastructure components.
- Create professional technical documentation using Markdown.
- Continue building a structured GitHub Cloud Computing Portfolio.

---

## 3. Cloud Infrastructure Components

During this laboratory, I investigated four major infrastructure components available in the KillerCoda Linux environment.

| Component | Observed Information |
|---|---|
| **Compute** | Intel Xeon E312xx, 1 CPU core, x86_64 architecture |
| **Storage** | 19 GB primary storage on `/dev/vda1` |
| **Networking** | Hostname `ubuntu`, IP addresses `172.30.1.2` and `172.17.0.1` |
| **Operating System** | Ubuntu 24.04.4 LTS, Linux kernel `6.8.0-136-generic` |

### Compute

Compute resources provide the processing power needed to run applications, commands, and workloads. In the KillerCoda environment, the available processor allows the Linux system to execute the commands and tasks required throughout the laboratory.

### Storage

Storage provides space for the operating system, applications, and files. The KillerCoda environment uses `/dev/vda1` as its main filesystem with a total capacity of 19 GB.

### Networking

Networking allows systems and services to communicate with one another. The KillerCoda environment provides a hostname and IP addresses that identify its network configuration.

### Operating System

The operating system manages the available resources and provides the environment used to run commands and applications. The KillerCoda environment runs Ubuntu 24.04.4 LTS with the `6.8.0-136-generic` Linux kernel.

---

## 4. Tools Used

| Tool | Purpose |
|---|---|
| **KillerCoda Playground** | Provided the cloud-based Linux environment used for the laboratory |
| **Ubuntu Linux** | Operating system used to investigate and interact with the cloud environment |
| **Linux CLI** | Used to gather system, storage, and networking information |
| **Adobe XD** | Used to design the cloud infrastructure diagram |
| **Git** | Used for version control and tracking changes |
| **GitHub** | Used to store and maintain the Cloud Computing Portfolio |
| **Markdown** | Used to create and organize the technical documentation |
| **ChatGPT and Claude** | I used both of these AI to help correct grammar, improve the clarity of some sentences, and explain or clarify ideas that I encountered while working on the activity|

---

## 5. Linux Commands Executed

The following commands were used during the laboratory to navigate the Linux environment, manage files, investigate system resources, and update the GitHub repository.

### File and Directory Commands

| Command | What It Does |
|---|---|
| `cd <directory>` | Moves into a specified directory. |
| `mkdir <directory-name>` | Creates a new directory or folder. |
| `touch <filename>` | Creates a new empty file. |
| `nano <filename>` | Opens a file in the Nano text editor for creating or editing content. |
| `cat <filename>` | Displays the contents of a file in the terminal. |

### Linux System Information Commands

| Command | What It Does |
|---|---|
| `cat /etc/os-release` | Displays information about the Linux distribution and operating system version. |
| `uname -r` | Displays the current Linux kernel version. |
| `lscpu` | Displays detailed information about the CPU and processor architecture. |
| `nproc` | Shows the number of available processing units. |
| `free -h` | Displays system memory and swap usage in a human-readable format. |
| `df -h` | Displays available and used disk space for mounted filesystems. |
| `findmnt` | Displays mounted filesystems and their mount points. |
| `hostname` | Displays the hostname assigned to the Linux system. |
| `hostname -I` | Displays the IP addresses assigned to the Linux system. |
| `ip addr` | Displays the network interfaces, IP addresses, subnet information, and interface status. |
| `ip route` | Displays the server's routing table, including the default gateway used for network traffic. |

### Git Commands

| Command | What It Does |
|---|---|
| `git clone <repository-url>` | Copies an existing GitHub repository to the Linux environment. |
| `git status` | Shows the current state of the Git repository. |
| `git add .` | Stages all new and modified files for the next commit. |
| `git commit -m "message"` | Saves the staged changes as a commit with a descriptive message. |
| `git push` | Uploads committed changes from the local repository to GitHub. |

### Git Workflow Used

```bash
git clone <repository-url>
cd <repository-name>

mkdir <folder-name>
touch <filename>
nano <filename>

git status
git add .
git commit -m "Complete laboratory activity"
git push

```
## 6. Skills Learned

This laboratory helped me understand how the different parts of a cloud environment work together.

Through the activities, I learned and practiced:

- Identifying compute, storage, networking, and operating system resources.
- Using Linux commands to investigate a cloud-based environment.
- Reading and interpreting information returned by the Linux terminal.
- Understanding how different infrastructure resources relate to cloud computing.
- Comparing equivalent infrastructure services from AWS, Microsoft Azure, and Google Cloud.
- Creating a cloud infrastructure design using Adobe XD.
- Using Git to track and manage changes.
- Using GitHub to store and maintain my Cloud Computing Portfolio.
- Writing and organizing technical documentation using Markdown.

One of the most useful things I learned from this activity is that cloud infrastructure is not made up of separate components working alone. Compute, storage, networking, and the operating system work together to provide an environment where applications and services can run.

## 7. Challenges Encountered

One of the main challenges I encountered was understanding how the resources shown inside the KillerCoda Linux environment relate to the infrastructure concepts discussed in cloud computing.

Another challenge was interpreting the output of different Linux commands. Some commands displayed a large amount of information, so I had to identify which details were relevant to compute, storage, networking, and the operating system.

Creating the cloud infrastructure design was also challenging because I had to think about how the different components connect and work together rather than simply listing them. Using Adobe XD helped me organize these ideas into a visual representation.

I also had to be careful when working with Git and GitHub, especially when staging files, creating commits, and pushing changes to the repository. This helped me understand the basic workflow of maintaining a project using version control.

Overall, these challenges helped me become more comfortable with investigating a Linux environment, understanding cloud infrastructure, and documenting technical work clearly.
