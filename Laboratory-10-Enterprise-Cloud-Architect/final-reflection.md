# 🎓 Final Reflection 

## 📖 Introduction

Completing Missions 1 through 10 of CCM101 helped me understand cloud computing and how it is used in real-world systems. Throughout the activities, I learned about cloud services, computer resources, networking, Linux commands, security, and automation.

I realized that cloud computing is not only about storing files online or using websites. It also involves setting up servers, managing applications, protecting data, and making sure that systems continue to work properly.

## ☁️ Learning Experience from Missions 1–9

The first nine missions introduced different cloud computing concepts and practical activities.

I learned about cloud infrastructure and its main components, including computing resources, storage, and networking. I also became familiar with cloud service providers such as Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

The activities involving cloud infrastructure planning helped me understand why it is important to choose the right resources before setting up a system.

I also gained experience using Linux commands to check operating system information, CPU specifications, memory usage, and available disk space. These activities improved my ability to work with a Linux environment and understand how a server uses its resources.

Working with PowerShell also helped me understand how scripts can make repetitive tasks easier. Instead of checking everything manually, scripts can collect information and perform tasks automatically.

Another important lesson was the need to protect systems through proper access settings, firewall rules, and responsible management of resources.

## 🏗️ Experience in Mission 10 – Enterprise Cloud Architect

Mission 10 allowed me to apply many of the things I learned from the previous activities in one project.

For this mission, I developed **CloudNova**, a website infrastructure running on Ubuntu Server inside Oracle VirtualBox.

I configured the server's network connections so that my Windows laptop could access the Ubuntu Server and its WordPress website. I also installed Docker and Docker Compose to run WordPress and MariaDB as connected containers.

I learned how important Docker volumes are because they allow application and database files to remain available even when containers are restarted or recreated.

For security, I configured UFW, restricted SSH access, disabled password authentication, and used an SSH key to connect to the server. I also added Docker firewall rules to limit access to the WordPress website.

One of the most important parts of the project was creating an automatic database backup. I developed a Bash script that creates a database copy, compresses it, checks whether the file is valid, and removes old backups after seven days. I then used Cron to schedule the backup every day.

This mission helped me understand how different parts of a server work together to run and maintain an application.

## ⚠️ Challenges and Lessons Learned

During the project, I encountered several problems, especially when configuring the network, SSH access, and firewall rules.

Some settings affected how the Windows laptop connected to the Ubuntu Server and how Docker handled incoming connections. I had to check the configurations and test the connections to make sure everything worked correctly.

Creating the backup script was another learning experience. I needed to understand how to access the database, create backup files, compress them, and schedule the process using Cron.

These challenges taught me that setting up a system requires patience, proper testing, and attention to detail. I also learned that it is important to understand commands before executing them, especially when working with security settings and stored data.

## 🎯 Conclusion

Overall, CCM101 gave me a better understanding of cloud computing and the work involved in managing a server.

Through the ten missions, I gained practical experience with cloud services, Linux, PowerShell, virtualization, Docker, networking, security, and automation.

CloudNova represents the knowledge and skills I developed throughout the course. Although there are still many things I need to learn, this project gave me a foundation that I can use in future IT projects and in my journey toward becoming an IT professional.
