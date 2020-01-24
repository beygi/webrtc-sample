
Running this sample
---------------------
## Installation

### nodejs
```bash
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
```

### docker 
```bash
sudo apt install docker docker-compose
```

### bower and http server
```bash
sudo npm install -g bower
```
```bash
sudo npm install -g http-server
```


## Running

### install packages for server and client app
```
npm install
cd static
bower install --allow-root
```
### run kurento container
```bash
docker-compose up
```
### run server
```
npm start
```

Open https://localhost:8443/ with a WebRTC capable browser

You can access recorded file on host machine in this address :
```
/tmp/webrtc/
```