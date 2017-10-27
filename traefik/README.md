# arm64v8-traefik
dockerfile for traefik.io on arm64v8 and alpine

# build and push

(change fredix with your hub.docker.com account)

* docker build -f Dockerfile.arm64v8 -t fredix/arm64v8-traefik:1.4.0 .
* docker push fredix/arm64v8-traefik:1.4.0
* update image on your docker swarm : docker service update --image fredix/arm64v8-traefik:1.4.0 traefik
