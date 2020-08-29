# A Simple Lab for HAproxy
This is simple lab enviroment that can be used for practicing ansible with [this](https://github.com/amirhne/flask-haproxy-scenario-playbook). The docker-compose file will deploy three ubuntu container with sshd service running.

## How To Use It?
You Should have docker and docker-compose installed on your machine the use the following docker-compose command to run the lab:
```
docker-compose up -d
```
use the following command to stop the project:
```
docker-compose down --rmi local
```

## SSH Credentials and Configuration
HA_proxy_Loadbalancer : 127.0.0.1:22

flask_server_1: 127.0.0.1:23

flask_server_2: 127.0.0.1:24

Username and password for all machines:

user: ansible

pass: 1234567
