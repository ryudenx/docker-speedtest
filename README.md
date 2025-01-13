# docker-speedtest

## Run

### Ubuntu base

```bash
docker build -t ryudenx/speedtest-ubuntu:latest https://github.com/ryudenx/docker-speedtest.git -f Dockerfile_Ubuntu
docker run --rm -it --privileged ryudenx/speedtest-ubuntu:latest
```

### Rocky Linux base

```bash
docker build -t ryudenx/speedtest-rocky:latest https://github.com/ryudenx/docker-speedtest.git -f Dockerfile_Rocky
docker run --rm -it --privileged ryudenx/speedtest-rocky:latest
```