# 🏗️ Multi-Tier Architecture

## 📖 What Is a Two-Tier Architecture?

A two-tier architecture is a system divided into two parts: the application tier and the database tier. Each tier has its own responsibility, and they communicate with each other to make the application work. In this activity, **Nextcloud** is the application, while **MariaDB** is the database.

## 🌐 The Web/Application Tier

The web/application tier handles the part of the system that users interact with. It displays the web interface, receives HTTP requests from the browser, and processes user actions. In our deployment, **Nextcloud** serves as the web application that allows users to access and manage their files.

## 🗄️ The Database Tier

The database tier stores and manages the application's persistent data, such as user accounts and file-related information. It allows the application to save and retrieve information when needed. In our deployment, **MariaDB** acts as the database for Nextcloud.

## 🔗 Why Separate Them?

Separating the web application and database into two containers makes the system easier to manage and maintain. Each container has a specific responsibility, so we can update or troubleshoot one without rebuilding the entire system. It also makes it easier to scale the application and database independently when the system needs more resources.

## 🧩 Architecture Overview

* 🌐 **Nextcloud:** Handles the web interface and user requests.
* 🗄️ **MariaDB:** Stores and manages persistent application data.
* 🔗 **Communication:** Nextcloud connects to MariaDB to retrieve and save data.

**Architecture flow:**

`👤 User → 🌐 Nextcloud → 🗄️ MariaDB`
