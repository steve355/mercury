# Mercury

一个基于Trojan的Docker封装，包含服务器端与客户端，助你翻越防火墙。

使用方法：

1. 根据https://docs.docker.com/engine/install/，在系统内安装docker
1. 根据https://docs.docker.com/compose/install/，安装docker-compose
1. 执行`git clone https://github.com/steve355/camouflage.git`
1. 执行`git clone https://github.com/steve355/mercury.git`
1. 用HTTrack或其他工具下载一个网站，作为伪装网站，放在./camouflage/public中
1. 执行./camouflage/build.sh，会生成一个名叫camouflage的docker image
1. 安装certbot，并获取一个SSL证书
1. 调整./mercury/config/config.json
1. 执行 `docker-compose up -d`
