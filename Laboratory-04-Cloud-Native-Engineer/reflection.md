# 💭 Mission Reflection

After working with Docker, I noticed that starting a container is much faster compared to setting up a Virtual Machine. With a Virtual Machine, I would need to install an entire operating system, configure it, and wait for it to boot. With Docker, the container can start in just a few seconds because it does not need a complete operating system. This makes Docker much easier and faster to use when running applications.

The port mapping `-p 8080:80` is needed because the web server inside the container is using port 80, while I want to access it from my computer using port 8080. The first number, `8080`, is the port on my computer, while `80` is the port inside the container. Because of this mapping, I can open `localhost:8080` in my browser and access the web server running inside the container.

When I use the `docker rm` command, the container is deleted. Any data that was stored only inside that container is also removed. This made me realize that containers are not meant to be used as permanent storage. If I need to keep important data even after removing a container, I would need to use something like a Docker volume.

I also think containerization makes it easier for developers and IT operations teams to work together. Developers can put the application and its needed files or dependencies inside a container, and the operations team can run that same container without having to set everything up again. This can make deployment easier and reduce problems caused by differences between environments.

My GitHub portfolio is slowly becoming a record of the things I have actually practiced. Instead of just having finished activities, I am adding my commands, files, configurations, and reflections. As I continue with the laboratory activities, I can see my repository becoming more organized and showing my progress.
