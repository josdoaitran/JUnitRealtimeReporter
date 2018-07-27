# JUnitRealtimeReporter
JUnitRealtimeReporter


Using: http://reportportal.io

## Install and setup realtime report

+ Install a docker to our desktop. (Windows, Ubuntu, Macosx)
* Alternate solution: we can create a Virtual machine - VM on VMWare or Oracle Virtual Box and install UBUNTU operation.

To assure that docker was installed on our server by using this command:

```
root@ubuntu:~# docker -v
Docker version 18.06.0-ce, build 0ffa825
```

+ Configure and deploy ReportPortal with Docker-Compose file
Download default Docker compose file for the latest version or configure your own file.
```
curl https://raw.githubusercontent.com/reportportal/reportportal/master/docker-compose.yml -o docker-compose.yml
```

+ Start ReportPortal using the following command and wait a bit
```
docker-compose -p reportportal up -d --force-recreate
```

+ Open ReportPortal in new browser tab and login
```
# For user access:
default/ 1q2w3e
# or admin access:
superadmin/erebu
```
+ Add more dependencies to pom file



## Reference:
http://reportportal.io/download
