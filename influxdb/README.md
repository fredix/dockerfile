# influxdb
dockerfile for ARM32V7 (raspberry pi 2) https://github.com/influxdata/influxdb

# build and push

(change fredix with your hub.docker.com account)

* docker build -f Dockerfile.arm32v7 -t fredix/arm32v7-influxd .
* docker push fredix/arm32v7-influxdb
