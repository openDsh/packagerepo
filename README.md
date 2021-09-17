# Overview

Package Repo for OpenDsh

## Debian

### Buster

```bash
wget -qO - https://opendsh.github.io/packagerepo/PUBLIC.KEY | sudo apt-key add -
echo "deb [ arch=armhf ] https://opendsh.github.io/packagerepo/apt/debian buster main" > /etc/apt/sources.list.d/opendsh.list
```