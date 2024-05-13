# Filehost services

## Run project

```bash
# Clone repo with submodules
git clone --recurse-submodules git@github.com:webforeman/filehost.git
# Go to project and create environment variables
cd filehost
cp example.env .env

# Build and run containers
docker-compose build --no-cache
docker-compose up -d
```
