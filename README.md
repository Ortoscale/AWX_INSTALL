Before start install docker-compose (under root)
1. $ `sudo curl -L "https://github.com/docker/compose/releases/download/1.28.3/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose`
2. $ `sudo chmod +x /usr/local/bin/docker-compose`
3. `sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose`
4. `docker-compose --version`

Clone this repo
1. $ `cd AWX_INSTALL`
2. $ `docker-compose up -d`
3. $ `chmod 777 redis_socket`
4. $ `docker-compose logs -f --tail=1`
