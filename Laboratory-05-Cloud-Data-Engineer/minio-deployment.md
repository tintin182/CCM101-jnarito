# ☁️ MinIO Server Deployment

## 🐳 1. Docker Command

The following command was used to run the MinIO server in Docker.

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
  -e "MINIO_ROOT_USER=cloudadmin" \
  -e "MINIO_ROOT_PASSWORD=<YOUR_ROOT_PASSWORD>" \
  ghcr.io/imagegenius/minio:latest
```

## 🌐 2. Web Console Port

* **Port 9001:** Used to open the MinIO Web Console.
* **Port 9000:** Used for the MinIO API.

## 🪣 3. Bucket Name

* **Bucket Name:** `client-photos`

## ⚙️ 4. Environment Variables

The `-e` flags set the login details for the MinIO server.

* `MINIO_ROOT_USER=cloudadmin` sets the username.
* `MINIO_ROOT_PASSWORD` sets the password.
