# Overview

Package Repo for OpenDsh

## Debian

### Buster

```bash
wget -v -O PUBLIC.KEY https://opendsh.github.io/packagerepo/PUBLIC.KEY 
apt-key add PUBLIC.KEY
rm PUBLIC.KEY 
bash -c "echo 'deb [ arch=armhf ] https://opendsh.github.io/packagerepo/apt/debian buster main' > /etc/apt/sources.list.d/opendsh.list"

```