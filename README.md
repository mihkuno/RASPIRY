# RASPIRY
Fix raspberry pi ntp servers for synced date-time

```java
sudo nano /etc/systemd/timesyncd.conf

NTP=time.google.com 1.google.pool.ntp.org 2.google.pool.ntp.org 3.google.pool.ntp.org

sudo systemctl restart systemd-timesyncd

timedatectl status

timedatectl show-timesync --all
```
