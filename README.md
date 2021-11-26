#  Wordpress webiste using Docker containers

Its just a documentation to create wordpress website using docker containers. Here, I'm provisioning to containers. One for databae and one for website files.
### Prerequisites

Install docker service on the server. 

```
#sudo apt get update
#sudo apt install docker.io
#service docker restart
#docker --version
```

Created a custom bridge to establish connection between two containers. [Bridge](https://docs.docker.com/network/bridge/). 

```
#docker network create wdnetwork
```

