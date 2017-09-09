# arm64v8-traefik
dockerfile for traefik.io on arm64v8 and alpine

# build and push

(change fredix with your hub.docker.com account)

* docker build -f Dockerfile.arm64v8 -t fredix/arm64v8-traefik:1.3.8 .
* docker push fredix/arm64v8-traefik:1.3.8
