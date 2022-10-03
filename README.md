 
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
sudo apt-get install build-essential checkinstall libssl-de
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.32.1/install.sh | bash
curl -O https://dl.google.com/go/go1.17.1.linux-amd64.tar.gz

curl -O https://dl.google.com/go/go1.17.1.linux-amd64.tar.gz
tar -xvf go1.17.1.linux-amd64.tar.gz
sudo mv go /usr/loca
export GOROOT=/usr/local/go
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
## If you find docker error.[CLick here ](https://computingforgeeks.com/install-docker-and-docker-compose-on-kali-linux/)to resolve.


## Install Samples,Binary and Docker Images
make a folder and install testnet 


```bash
mkdir testfolder
cd testfolder
curl -sSL https://bit.ly/2ysbOFE | bash -s


```

## setting path of all bins in pathvariable
(assuming currently in fabric smaple folder)

```bash
cd bin
pwd


```
/home/adil/Desktop/BLockchain/fabric-samples/bin

there will be path given like that copy path

```bash
vim ~/.bashrc

```
file will be opened 
export PATH=$PATH:/home/adil/Desktop/BLockchain/fabric-samples/bin
PLACE this line and save it 
How to save:
after inserting press esc
then type :wq 
it will be saved and exit
