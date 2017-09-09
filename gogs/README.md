# arm64v8-gogs
dockerfile for gogs.io on arm64v8 and alpine

# build and push

* git clone https://github.com/gogits/gogs
* cp Dockerfile.arm64v8 gogs
* cd gogs
* git checkout tags/v0.11.29


(change fredix with your hub.docker.com account)

* docker build -f Dockerfile.arm64v8 -t fredix/arm64v8-gogs:v0.11.29 .
* docker push fredix/arm64v8-gogs:v0.11.29
