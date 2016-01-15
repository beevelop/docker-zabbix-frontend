[![Travis](https://img.shields.io/travis/beevelop/docker-zabbix-frontend.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-zabbix-frontend)
[![Docker Pulls](https://img.shields.io/docker/pulls/beevelop/zabbix-frontend.svg?style=flat-square)](https://links.beevelop.com/d-zabbix-frontend)
[![ImageLayer](https://badge.imagelayers.io/beevelop/zabbix-frontend:latest.svg)](https://imagelayers.io/?images=beevelop/zabbix-frontend:latest)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# Zabbix 3 (Gorgeous Frontend)

> Zabbix 3 is still in Alpha and should not be used in production. This Docker images is thought to give you a preview of the upcoming great release (IMHO) :cookie:


----
### Pull from Docker Hub
```
docker pull beevelop/zabbix-frontend:latest
```

### Build from GitHub
```
docker build -t beevelop/zabbix-frontend github.com/beevelop/docker-zabbix-frontend
```

### Run image
```
docker run -it beevelop/zabbix-frontend bash
```

### Use as base image
```Dockerfile
FROM beevelop/zabbix-frontend:latest
```