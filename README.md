## Install Shadowsocks-libev with v2ray-plugin
This shell help you install shadowsocks listening on port 443 with Let's Encrypt and v2ray-plugin.  
### Introduction
Install [shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) and [v2ray-plugin](https://github.com/shadowsocks/v2ray-plugin).  
Get a certificate from [Let’s Encrypt](https://letsencrypt.org) to enable shadowsocks over websocket (HTTPS).  
You must use shadowsocks via port 443 with v2ray-plugin and can even run your shadowsocks server behind the CDN like [Cloudflare](https://www.cloudflare.com/).  

### Requirement
VPS  
You can sign up through my referral link:  

Domain  
You can register one for free at [freenom](https://my.freenom.com/clientarea.php).  
Point your domain to the IP address with A record.  
### Usage
```bash
# Installation
## CentOS 7
wget -O centos7-ss-install.sh https://github.com/niiiixd/shadowsocks-with-v2ray/blob/main/centos7-ss-install.sh
chmod +x centos7-ss-install.sh
./centos7-ss-install.sh

## Ubuntu 18.04/16.04 or Debian 9
wget -O ubuntu-ss-install.sh https://github.com/niiiixd/shadowsocks-with-v2ray/blob/main/ubuntu-ss-install.sh
chmod +x ubuntu-ss-install.sh
./ubuntu-ss-install.sh

# Manage shadowsocks with systemctl
systemctl status shadowsocks
systemctl start shadowsocks
systemctl stop shadowsocks
```
### Notice
Tested on CentOS 7, Ubuntu 18.04/16.04 and Debian 9.  
***Full of bugs.***  
***Under construction.***
