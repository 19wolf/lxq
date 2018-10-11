# LXD

## One Liner:

curl -sSL https://raw.githubusercontent.com/aaronstuder/lxd/master/menu.sh | bash

| Container | IP Address | Forwarded |
| ------------- | ------------- | |
| Host | 10.0.0.1 ||
| Nginx | 10.0.0.2 | 80/443 |
| OpenVPN |10.0.0.3 ||


| Container | IP Address | Ports Forwarded to Container |
| ------------- | ------------- | ----- |
| Host  | 10.0.0.1 | N/A |
| NGINX  | 10.0.0.2 | 80/TCP 443/TCP |
| Open VPN | 10.0.0.3 | 1194/UDP |
#To Do
- Make wget only download one file
- Enable firewall working
- Setup Logging
- make scripts only run once
- 
