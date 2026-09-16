## 🔄 Container Lifecycle Management

### 1. List Running Containers

```bash
docker ps
```

Lists the Docker containers that are currently running.

### 2. Stop the Nginx Container

```bash
docker stop <container-name-or-id>
```

Stops the currently running Nginx container using its container name or ID.

### 3. Verify the Container Status

```bash
docker ps -a
```

Lists running and stopped containers to verify that the Nginx container has been stopped.

### 4. Remove the Nginx Container

```bash
docker rm <container-name-or-id>
```

Removes the stopped Nginx container from the Docker environment.

### 5. Verify Container Removal

```bash
docker ps -a
```

Verifies that the removed Nginx container no longer appears in the list of containers.

### 📸 Evidence

The complete container lifecycle is documented in the following screenshot:

`![Container Lifecycle](screenshots/container-lifecycle.png)`
