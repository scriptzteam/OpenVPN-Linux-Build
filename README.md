# OpenVPN-Linux-Build

***Building latest OpenVPN v2.5.8 on Linux***
```
apt update
apt upgrade
apt install build-essential libssl-dev liblzo2-dev libpam0g-dev zlib1g zlib1g-dev
wget https://swupdate.openvpn.org/community/releases/openvpn-2.5.8.tar.gz
tar -xvf openvpn-2.5.8.tar.gz
cd openvpn-2.5.8
./configure
make
make install
```
