#Bio
Hello , My Name Is Ashkan Ebrahimi.
This Config For MTPROTO Proxy For Telegram.

## How Install ON Server :

### Debian & Ubuntu
```
$> apt-get install nodejs npm git
$> npm install pm2 -g
```
### CentsOS & RHEL
```
$> yum install nodejs npm git
$> npm install pm2 -g
```
Check the version of NodeJS, it should be version 6 or higher:
```
$> nodejs -v
v6.14.2
```
If it is lower than 6, you need to upgrade your linux OS or install nodejs from its we$
https://nodejs.org/en/download/


## How Run Proxy :

Start the proxy server from "Command Prompt" by following command:
```
$>  pm2 start mtproxy.js -i max
```


Video Learning :

https://www.youtube.com/watch?v=vNAq_PkR0o8

