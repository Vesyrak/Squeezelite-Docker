# Squeezelite-Docker

This is a docker image for x86-supported devices wanting to run squeezelite in a docker image.
No configuration happens, as it is more often than not not necessary.

Execute using docker run --privileged vesyrak/squeezelite-docker

## Docker-Compose

```
version: "3"

services"
  squeezelite:
    image: vesyrak/squeezelite-docker
    container_name: squeezelite
    privileged: true
    restart: always
```

