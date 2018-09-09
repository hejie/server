
##### 进入docker 容器操作
##### 进入 Docker 容器操作。登录到部署了 Docker 应用的服务器上，执行 docker ps，可以查看到当前已经启用的容器再执行 docker exec -ti $container_id bash 可以进入到 Docker 容器中

##### 查看日志 ,docker inspect —format {{.LogPath}} $container_id 定位到对应容器中应用的日志路径

##### sudo systemctl daemon-reload
##### sudo systemctl restart docker


##### systemctl start docker     #运行Docker守护进程
##### systemctl stop docker      #停止Docker守护进程
##### systemctl restart docker   #重启Docker守护进程

##### sudo service docker restart #重启Docker守护进程

##### sudo systemctl restart docker.service #重启docker

##### 查看已有镜像 docker images 

##### 强制删除镜像。

##### docker  rmi  –f  registry.cn-hangzhou.aliyuncs.com/lxepoo/apache-php5


##### du -hs 查看当前目录占用容量大小

##### docker system df -v 查看容器、镜像、卷的详细占用大小