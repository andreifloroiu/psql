# psql

PostgreSQL interactive terminal Docker image with ```psql```.

## Building

### Local

```bash
docker build . -t psql:latest
```

### Other architecture

```bash
docker buildx build --platform linux/amd64,linux/arm/v7,linux/arm64 --build-arg ALPINE_VERSION=latest . 
```
