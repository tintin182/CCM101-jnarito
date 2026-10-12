
# ☁️ The Cloud Operations Engineer

## 🎯 Mission Overview

Congratulations! Your ability to deploy multi-tier architectures has proven your technical capabilities.  
You have now been promoted to the **Cloud Operations Team** (often referred to in the industry as Site Reliability  
Engineering, or SRE) at CloudNova Technologies.  
Deploying a cloud application is only the first step; keeping it running smoothly is the real challenge.  
When a server crashes or a web page takes ten seconds to load, you cannot simply guess what is wrong. You  
must rely on **Observability and Monitoring** to see inside your infrastructure.  
Using the KillerCoda Playground, you will step into the role of a Cloud Operations Engineer. You will  
establish a performance baseline for your Linux server, deploy a containerized application, generate artificial web  
traffic, and hunt down performance metrics and system logs to prove the application is healthy.  
Remember: **A developer hopes the application works; a Site Reliability Engineer uses metrics and logs to prove it.**

## 🎯 Mission Objectives

At the end of this laboratory activity, you should be able to:

- Utilize native Linux command-line tools to monitor host CPU, Memory, and Disk capacity.
- Deploy a web container and track its real-time performance using Docker metrics.
- Generate web traffic and extract application access logs for analysis.
- Translate raw performance data into a readable technical report using Markdown.
- Continue expanding a professional GitHub Cloud Computing Portfolio.

## 🛠️ Monitoring Commands Executed

| Command | Purpose |
|---|---|
| `free -h` | Check the server's RAM usage. |
| `df -h /` | Check the total and available storage of the root file system. |
| `top` | View running processes and CPU usage. |
| `docker run -d --name client-website -p 8080:80 nginx` | Run the Nginx website container in the background. |
| `curl http://localhost:8080` | Visit the website using three HTTP requests. |
| `curl http://localhost:8080/hidden-admin-page` | Request a page that does not exist and generate a 404 error. |
| `docker ps` | Check whether the Nginx container is running. |
| `docker logs client-website` | View the website's logs and find the 404 error. |
| `docker stats` | Check the container's live CPU and memory usage. |

## 💡 Skills Learned

- Checking RAM and disk storage using Linux commands.
- Running an Nginx website using Docker.
- Sending website requests using `curl`.
- Finding a 404 error in the website logs.
- Checking the container's CPU and memory usage.
- Writing reports and organizing screenshots using Markdown and GitHub.
