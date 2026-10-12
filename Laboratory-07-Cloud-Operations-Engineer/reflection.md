# 🔎 Reflection

During this laboratory activity, I learned how to check server resources, run a website using Docker, generate website requests, and check application logs and container performance. These activities helped me understand why monitoring is important in managing a server.

First, checking the host server's resources is important even if the containers are running perfectly because the server still needs enough RAM, CPU power, and disk space to support them. If the server runs out of memory or storage, the applications may become slow or stop working. Using the `free -h`, `df -h /`, and `top` commands helped me check the server's memory, storage, and running processes.

Second, the `docker logs` command helps troubleshoot problems by showing what happened inside an application. For example, I used this command to check the logs of my Nginx container named `client-website`. I found three successful HTTP requests with status code 200 and requests that returned a 404 error because the requested page did not exist. These logs helped me understand which requests worked and which ones failed.

Third, logs and metrics provide different types of information. Logs show specific events and errors that happen in an application, while metrics show measurements such as CPU usage and memory consumption. In this activity, I used `docker logs client-website` to find the 404 error and `docker stats` to check the container's resource usage. My container used 2.73 MiB of memory and had a CPU usage of 0.00% when I checked it.

Fourth, large companies can monitor thousands of containers using monitoring tools such as Prometheus and Grafana. These tools can collect, organize, and display information about many servers and containers. This helps their technical teams notice unusual activity and identify problems more easily.

Finally, this activity improved my ability to troubleshoot Linux environments because I learned how to use commands to check resources, test a website, find errors, and monitor a running container. I also learned that screenshots and Markdown reports are useful for recording results and presenting evidence of my work. Overall, this activity helped me become more confident in using Linux and Docker to monitor and troubleshoot a web application.
