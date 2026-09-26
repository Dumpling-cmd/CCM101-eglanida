# MinIO Deployment

**Name:** Edmund Glanida

**Course and Section:** BSIT 4-L

## Docker Deployment

I used KillerCoda Ubuntu Playground to deploy an S3-compatible object storage server using Docker.

The original Docker command provided in the laboratory activity used `minio/minio`. However, the image was no longer accessible in the environment, so I used a working MinIO image from GitHub Container Registry.

### Docker Command Used

```bash
docker run -d -p 9000:9000 -p 9001:9001 -e "MINIO_ROOT_USER=cloudadmin" -e "MINIO_ROOT_PASSWORD=CloudNova2026!" --name minio-server ghcr.io/golithus/minio:latest server /data --console-address ":9001"