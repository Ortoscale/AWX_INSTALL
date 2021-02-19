Before start install docker-compose (under root)
1. $ sudo curl -L "https://github.com/docker/compose/releases/download/1.28.3/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
2. $ sudo chmod +x /usr/local/bin/docker-compose
3. sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
4. docker-compose --version


1. clone this repo
2. $ `cd AWX_INSTALL`
3. $ `docker-compose up -d`
4. $ `chmod 777 redis_socket`
6. $ `docker-compose logs -f --tail=1`
