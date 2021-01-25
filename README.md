# ROS1 base development docker container
ROS1 Dockerfile and accompanying Makefile to develop in a container with display and gpu support

## Usage

```shell
make build # build container
make up # bring up container
make up-display # bring up container with display support and no gpu support
make up-display-gpu # bring up container with display and gpu support (requires nvidia drivers)
make help # help
```
