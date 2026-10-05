# Imomushi, the Caterpillar

Operating System based on [ophub](https://github.com/ophub/amlogic-s9xxx-armbian)

**NOTE :** Please do initial setup normally (root pw, user set, locales), after that you can ditch the monitor and keyboard and access it via network.

## Init

```
# change hostname
hostnamectl set-hostname imomushi

#also change 127.0.1.1 to imomushi
sudo vim /etc/hosts
```
