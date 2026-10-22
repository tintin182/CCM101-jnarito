# ☁️ Cloud Automation Engineer

## 🎯 Mission Overview

Congratulations! Your ability to secure cloud environments has proven you are ready for the highest level of operations. You have been promoted to the Cloud Automation and DevOps Team at CloudNova Technologies.

Up until now, you have been acting as a traditional systems administrator—typing commands manually one by one. In large enterprise environments scaling to thousands of servers, manual administration is too slow and highly prone to human error. To survive at scale, you must learn to automate.

Using the KillerCoda Playground, you will step into the role of a Cloud Automation Engineer. You will learn the basics of Bash shell scripting, create an automated backup routine, assign executable permissions, and configure the Linux Cron scheduler to run your code autonomously.

Remember: **If you have to do a task more than twice in the cloud, you should automate it.**

## 🎯 Objectives

At the end of this laboratory activity, you should be able to:

- Understand the fundamental syntax of a Bash shell script, including variables and basic commands.
- Use a command-line text editor (nano) to write and save executable scripts.
- Modify Linux file permissions using the `chmod` command.
- Understand task scheduling and the syntax of a Linux crontab.
- Document automation code and Cron job configurations using Markdown.
- Complete the final chapter of your GitHub Cloud Computing Portfolio.

## 🛠️ Commands Executed

| Command | Purpose |
|---|---|
| `mkdir app-data` | Creates the sample application data folder. |
| `echo "This is critical client data." > app-data/data.txt` | Creates a test file with sample data. |
| `nano backup.sh` | Opens Nano to create or edit the backup script. |
| `chmod +x backup.sh` | Gives the script permission to run. |
| `./backup.sh` | Runs the backup script. |
| `ls -l backups/` | Checks whether the compressed backup file was created. |
| `crontab -l` | Displays the current scheduled tasks. |
| `env EDITOR=nano crontab -e` | Opens the cron schedule for editing. |

## 💡 Skills Learned

- Writing a Bash script to automate a task.
- Using variables to store folder names and timestamps.
- Creating compressed backups of application data.
- Changing file permissions with `chmod`.
- Scheduling tasks with Linux cron.
- Verifying backup files and cron schedules.
- Documenting commands and scripts using Markdown.
- Organizing a GitHub Cloud Computing portfolio.
