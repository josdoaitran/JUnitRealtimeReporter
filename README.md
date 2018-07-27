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

+ Start ReportPortal using the following command and wait a bit
```
docker-compose -p reportportal up -d --force-recreate
```

+ Add more dependencies to pom file



## Reference:
http://reportportal.io/download
