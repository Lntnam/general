##### # Tell Ubuntu to use Local Time 
```
timedatectl set-local-rtc 1 --adjust-system-clock
```

##### # Force Git to always use SSH
```
git config --global url."git@github.com:".insteadOf "https://github.com/"
```

##### # For git to use CRLF from input
```
git config --global core.autocrlf input
```

##### # SSH permission
.ssh folder: 700
.pub: 644
private keys: 600

##### # Stop all docker containers
docker stop $(docker ps -a -q)
