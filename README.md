# OpenVPN-Linux-Build

***Building latest OpenVPN v2.6.10 on Linux***
```
apt update
apt upgrade
apt install build-essential libssl-dev liblzo2-dev libpam0g-dev zlib1g zlib1g-dev
wget https://swupdate.openvpn.org/community/releases/openvpn-2.6.12.tar.gz
tar -xvf openvpn-2.6.12.tar.gz
cd openvpn-2.6.12
./configure
make
make install
```
