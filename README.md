
# Hyperledger fabric 2.0

A brief description of what this project does and who it's for


## Tools

- OS linux/Kali

- curl tool 

- git
- Docker engine
- docker compose
- Go: language
- Node
- npm 
- python


## Installation
Note:This installation is only for linux operating system
Install curl and following software package

```bash
sudo apt-get install curl
sudo apt-get install golang
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
```

Install Node js,npm,python and following software package

```bash
sudo apt-get install nodejs
sudo apt-get install npm
sudo apt update
sudo apt-get install python3
```
## Docker and Docker Compose
```bash
sudo apt install -y docker.io
sudo systemctl enable docker --now
sudo usermod -aG docker $USER   

DOCKER_CONFIG=${DOCKER_CONFIG:-$HOME/.docker}
mkdir -p $DOCKER_CONFIG/cli-plugins
curl -SL https://github.com/docker/compose/releases/download/v2.11.2/docker-compose-linux-x86_64 -o $DOCKER_CONFIG/cli-plugins/docker-compose

chmod +x $DOCKER_CONFIG/cli-plugins/docker-compose
sudo apt-get install docker-compose

```
## Update nodejs and Golang
```bash
wget https://dl.google.com/go/go1.13.x.linux-amd64.tar.gz\
tar -xzvf go1.13.x.linux-amd64.tar.gzsuod mv go/ /usr/local
export GOPATH=/usr/local/go
export PATH=$PATH:$GOPATH/bin
curl -sL https://deb.nodesource.com/setup_8.x |sudo bash -
sudo apt-get install -y nodejs
```
## Verify Versions

```bash
curl -V
npm -V
docker version
docker-compose version
go version
python -V
node -v

```
