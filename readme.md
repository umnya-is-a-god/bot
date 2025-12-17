## Install:

```shell
wget -O- https://raw.githubusercontent.com/umnya-is-a-god/vpnbot/master/scripts/init.sh | sh -s YOUR_TELEGRAM_BOT_KEY master
```
#### Restart:
```shell
cd /vpnbot
make r
```
#### autoload:
```shell
crontab -e
```
add `@reboot cd /root/vpnbot && make r` and save
