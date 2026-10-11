# 🐳 Docker Compose Guide

### 1. What does the services: block do?

**Answer:**

The `services:` block defines the containers needed to run an application. In our project, it contains two services: `app` and `database`. The `app` service runs Nextcloud, which provides the interface for managing files, while the `database` service runs MariaDB, which stores application data. Defining both services in one file makes them easier to configure and manage.

### 2. How did the Nextcloud app container know how to find the database container?

**Answer:**

Nextcloud finds the database through the `MYSQL_HOST=database` environment variable in the Compose file. The value `database` matches the name of the MariaDB service. Docker Compose allows services in the same project to communicate using their service names, so Nextcloud can connect to MariaDB without needing to enter the database container's IP address manually.

### 3. What is the difference between `docker run` (which you used in Mission 4) and `docker-compose up -d`?

**Answer:**

The `docker run` command is commonly used to start an individual container by providing its settings in the command. When an application needs several containers, each one may require a separate command. In comparison, `docker-compose up -d` reads the `docker-compose.yml` file and starts the services defined in it. This makes the deployment easier to repeat because the configuration is saved in one file.

## 📌 Summary

Docker Compose makes it easier to manage an application that uses multiple containers. By keeping the configuration in a single file, cloud engineers can review the settings, start the required services, and repeat the deployment more consistently.
