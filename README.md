# Servers deployment

Deployment scripts for the server-side of the BeaconBlink project.

## Components:
- ### [**Main server and web application**](https://github.com/BeaconBlink/Server)
- ### [**"Mapping" server running alongside a machine learning module**](https://github.com/BeaconBlink/Room_mapping)
- ### **MongoDB database**
- ### **MongoExpress WebUI**

## Deployment
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
