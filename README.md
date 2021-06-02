# AWX 

AWX provides a web-based user interface, REST API, and task engine built on top of Ansible.

## Installation

Make sure [docker-compose](https://docs.docker.com/compose/install/) is installed 

Check (if installed) with command:
```sh
docker-compose --version
```
After that clone project:
```sh
git clone https://github.com/Ortoscale/AWX_INSTALL.git
mv AWX_INSTALL awx
cd awx && docker-compose up
```
When will the logs appear - stop containers with "Ctrl+C" on keyboard and
execute command to give the folder rigts:
```sh
chmod +x 777 redis_socket
```
Run all services:
```sh
docker-compose up -d
```
Wait 5 minutes and follow the link ip:8081. 
The default access:
login - admin,
password - password

Change info [here](https://github.com/Ortoscale/AWX_INSTALL/blob/master/add_config/krb5.conf). Have to change "WEBSITE.COM" to domain name and main domain contriller to yours. Small letters should be small, large large.

**Congratulations, you have installed awx**
