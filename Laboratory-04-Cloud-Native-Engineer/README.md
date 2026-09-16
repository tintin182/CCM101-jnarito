# ☁️ Mission 4: The Cloud-Native Engineer

## 📋 Mission Overview

Congratulations! After successfully guiding our clients through multi-cloud evaluations, you have been promoted to the Cloud-Native Engineering Team at CloudNova Technologies.

Modern cloud computing is no longer just about renting Virtual Machines (VMs) from AWS or Azure. Today's enterprise applications are built using lightweight, portable, and lightning-fast technologies called Containers.

Your new mission is to understand the shift from traditional virtualization to containerization.

Using the KillerCoda Playground, you will step into the shoes of a Cloud-Native Engineer. You will research the differences between VMs and containers, execute your very first Docker commands, and deploy a live, containerized web server in seconds.

Remember: A traditional system administrator manages servers, but a cloud-native engineer manages the services running on them.

## 🎯 Objectives

At the end of this laboratory activity, you should be able to:

* Differentiate between traditional Virtual Machines (VMs) and Containers.
* Access a Docker-enabled cloud environment using KillerCoda.
* Execute fundamental Docker CLI (Command Line Interface) commands.
* Pull, run, manage, and terminate a containerized application (Nginx).
* Create professional technical documentation of container operations using Markdown.
* Continue developing a well-organized GitHub Cloud Computing Portfolio.

## 🐳 Docker Commands Executed

The following table contains the Docker commands executed during Checkpoints 3, 4, and 5.

| Command                          | What does this command do?                                                                                             |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| `docker version`                 | Displays Docker version information.                                                                                   |
| `docker info`                    | Displays information about the Docker environment.                                                                     |
| `docker pull nginx`              | Downloads the official Nginx image from Docker Hub.                                                                    |
| `docker run -d -p 8080:80 nginx` | Creates and starts an Nginx container in detached mode and maps port 8080 on the host to port 80 inside the container. |
| `curl http://localhost:8080`     | Sends an HTTP request to the Nginx web server running through the mapped port.                                         |
| `docker ps`                      | Lists the running containers.                                                                                          |
| `docker stop sharp_cohen`        | Stops the running Nginx container named `sharp_cohen`.                                                                 |
| `docker ps -a`                   | Lists running and stopped containers to verify the container status.                                                   |
| `docker rm sharp_cohen`          | Removes the stopped Nginx container named `sharp_cohen`.                                                               |
| `docker ps -a`                   | Verifies that the removed container no longer appears in the list.                                                     |

## 🧠 Skills Learned

* Understanding the differences between Virtual Machines and Containers.
* Using the KillerCoda Playground as a Docker-enabled cloud environment.
* Executing fundamental Docker CLI commands.
* Pulling and running a containerized Nginx web server.
* Mapping a host port to a container port.
* Verifying a running web server using `curl`.
* Managing the lifecycle of a Docker container.
* Creating technical documentation using Markdown.
* Organizing and maintaining a GitHub Cloud Computing Portfolio.

## ⚠️ Challenges Encountered

One challenge encountered during the activity was becoming familiar with the Docker CLI commands and understanding how each command is used in the container lifecycle. Another challenge was identifying the correct container name when stopping and removing the Nginx container. The Nginx container used in this activity was named `sharp_cohen`. Following the commands step by step helped in understanding how Docker containers can be pulled, started, verified, stopped, and removed.
