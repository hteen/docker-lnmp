## Docker部署PHP环境
* PHP
* MySQL
* Nginx
* Redis

## 启动
1. 安装docker
```linux
# curl -fsSL https://get.docker.com/ | sh
```
国内加速
```linux
# curl -sSL https://get.daocloud.io/docker | sh
```

2. gi clone
```linux
# git clone https://github.com/hteen/docker-lnmp.git
```

3. 启动
```linux
# cd docker-lnmp
# docker-compose up -d
```
> 一般安装docker的时候就会自动安装docker-compose,如果没有安装 `docker-compose` 请先[安装](https://github.com/docker/compose/releases/)
