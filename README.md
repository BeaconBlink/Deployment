# Deployment

### Clone
Clone using HTTPS:
```bash
git  clone  --recurse-submodules https://github.com/BeaconBlink/Deployment.git
```
or using SSH:
```bash
git  clone  --recurse-submodules git@github.com:BeaconBlink/Deployment.git
```

### Update
```bash
git pull --recurse-submodules
git submodule update --remote --recursive
docker-compose build
```
