# Mercury

A docker based trojan service. Including server side and client side. It helps you to bypass the firewall and visit any website.

Usage：

1. Install docker in your system based on this instructions https://docs.docker.com/engine/install/
1. Install docker-compose in your system based on this instructions https://docs.docker.com/compose/install/
1. Execute `git clone https://github.com/steve355/camouflage.git`
1. Execute `git clone https://github.com/steve355/mercury.git`
1. Using HTTrack or other similar tool to download a static website as camouflage website. Put html files to ./camouflage/public
1. Execute `./camouflage/build.sh`, a camouflage website docker image will be generated
1. Install certbot and obtain a free SSL certificate
1. Change ./mercury/config/config.json
1. Execute `docker-compose up -d`
