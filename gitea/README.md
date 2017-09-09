# arm64v8-gitea
dockerfile for gitea.io on arm64v8 and alpine

# build and push

* git clone https://github.com/go-gitea/gitea
* cp Dockerfile.arm64v8 gitea
* cd gitea

(change fredix with your hub.docker.com account)

* docker build -f Dockerfile.arm64v8 -t fredix/arm64v8-gitea:v1.2 .
* docker push fredix/arm64v8-gitea:v1.2
