# Docker for Spunky Bot

For Spunky Bot it is not necessary to build and maintain an own Docker image.

You can run an Alpine image from the folder where you installed Spunky Bot with the following command:

```shell
docker run -it --rm --name spunkybot -v "$PWD":/usr/src/spunkybot -w /usr/src/spunkybot python:2.7-alpine python spunky.py
```
