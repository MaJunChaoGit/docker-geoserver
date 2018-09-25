# docker-geoserver

基于docker镜像部署的[GeoServer](http://geoserver.org/) .



## 安装

通过使用以下命令拉取镜像

```shell
$ docker pull MaJunChaoGit/docker-geoserver
```

Alternatively you can build the image locally

```
$ git clone https://github.com/MaJunChaoGit/docker-geoserver.git
$ cd docker-geoserver
$ docker build -t "MaJunChaoGit/docker-geoserver" .
```

## 启动

使用以下命令进行启动

```
$ docker run --name "geoserver" -d -p 8080:8080 MaJunChaoGit/geoserver
```

通过浏览器输入`http://localhost:8080/geoserver` 并且输入以下账号密码进行登录

- 账号: admin
- 密码: geoserver

