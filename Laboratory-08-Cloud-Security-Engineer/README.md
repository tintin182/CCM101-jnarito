# 🛡️ Laboratory 08 — Cloud Security Engineer

## 🎯 Mission Overview

Congratulations! Your proactive approach to system monitoring has earned you a spot on the elite  
**Cloud Security Team** at CloudNova Technologies.  
In the cloud, leaving a server unsecured for even a few minutes can lead to automated brute-force  
attacks and data breaches. Your mission today applies the security concepts you learned in Chapter 8. You will  
implement the principle of defense in depth by locking down a live server using a host-based firewall.  
Using the KillerCoda Playground, you will step into the role of a Cloud Security Engineer. You will  
deploy a web application, audit the server's open ports, and configure the Uncomplicated Firewall (UFW) to block  
malicious traffic while allowing legitimate users to access the application.  
Remember: **Security is not a product you buy; it is a continuous process you maintain.**

## 📌 Objectives

At the end of this laboratory activity, you should be able to:

- Understand the concept of the Attack Surface and the Principle of Least Privilege (PoLP).
- Perform a basic security audit of active network ports on a Linux server.
- Configure the Uncomplicated Firewall (UFW) with a Default Deny policy.
- Implement granular port management to selectively allow SSH and HTTP traffic.
- Document firewall rules and security best practices using Markdown.
- Continue expanding your professional GitHub Cloud Computing Portfolio.

## 💻 Commands Executed

| Command | What This Command Does |
|---|---|
| `docker run -d --name secure-web-app -p 8080:80 nginx` | Runs an Nginx container in the background, names it `secure-web-app`, and maps port 8080 to port 80. |
| `docker ps` | Shows the Docker containers that are currently running. |
| `curl http://localhost:8080` | Sends a request to the web application to check if Nginx responds. |
| `sudo ufw allow ssh` | Allows SSH connections so administrators can manage the server remotely. |
| `sudo ufw default deny incoming` | Blocks incoming connections by default unless a firewall rule allows them. |
| `sudo ufw default allow outgoing` | Allows outgoing connections from the server by default. |
| `sudo ufw enable` | Turns on the UFW firewall and applies its rules. |
| `sudo ufw allow 8080/tcp` | Allows incoming TCP connections through port 8080 for the Nginx web application. |
| `sudo ufw status verbose` | Displays the firewall status, default policies, and other firewall details. |
| `sudo ufw status numbered` | Displays the firewall rules with numbers so they are easier to identify and manage. |

## 🧠 Skills Learned

- Understanding the Principle of Least Privilege and attack surface.
- Deploying an Nginx web server using Docker.
- Testing a web application using `curl`.
- Configuring UFW on Ubuntu.
- Setting a default deny policy for incoming connections.
- Allowing specific network ports for required services.
- Checking firewall rules and server security settings.
- Documenting technical work using Markdown.
- Maintaining a GitHub Cloud Computing Portfolio.
