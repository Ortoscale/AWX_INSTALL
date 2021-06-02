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

User Authentication with Kerberos [here] (https://docs.ansible.com/ansible-tower/3.1.6/html/administration/kerberos_auth.html)

**Congratulations, you have installed awx**
