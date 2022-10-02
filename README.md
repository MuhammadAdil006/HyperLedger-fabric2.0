
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
sudo apt-get install python
```
## Docker and Docker Compose
```bash
 curl -fsSL https://download.docker.com/linux/ubuntu/gpg |sudo apt-key add -
 sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release-cs) stable"
 $ sudo apt-get update
 $ apt-cache policy docker-ce 
 sudo apt-get install -y docker-ce
 sudo apt-get install docker-Compose
 sudo apt-get upgrade

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