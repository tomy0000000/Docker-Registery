# Ubuntu Xenial

The popular Linux distribution based on Debian, as a development runtime.

## Information

![ubuntu](https://github.com/tomy0000000/Docker-Registry/workflows/ubuntu/badge.svg)

| Configurations    |                         |
| ----------------- | ----------------------- |
| Base Image        | `ubuntu:xenial`         |
| Container Name    | `awesome-ubuntu`        |
| Volumes           | `.` → `/home/$(whoami)` |
| Network           |                         |
| Working Directory | `/`                     |
| Expose Port       |                         |

## Install

* Build the Dockerfile

```bash
docker build --tag tomy0000000/ubuntu:xenial .
```

* Start Container

```bash
docker run \
		-it --rm \
		--name="some-ubuntu" \
		--volume="$PWD:/home/$USER" \
		tomy0000000/ubuntu:xenial bash
```

## Usage




## Custom Setting

### Applied

* 

### Runtime

* Bind host's runtime directory to container's home directory

### Host Machine

* 

## References

* [Base Image Reference](https://hub.docker.com/_/ubuntu)
