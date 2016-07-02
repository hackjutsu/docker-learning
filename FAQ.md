#FAQ

#### How to change docker daemon working directory?
On ubuntu 14.04:
 - Edit docker config file: `sudo vim /etc/default/docker`
 - Add Docker option: `DOCKER_OPTS="-g=/my-directory`
 - Restart docker daemon: `sudo restart docker`
