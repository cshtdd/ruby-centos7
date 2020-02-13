# ruby-docker-images
Docker images for Ruby development on different OS

# Centos 6  

## Building the image  

```bash
docker build --no-cache -t camilin87/ruby-centos:6 -f Dockerfile-centos6 .
docker push camilin87/ruby-centos:6
```

# Centos 7  

## Building the image  

```bash
docker build --no-cache -t camilin87/ruby-centos:7 -f Dockerfile-centos7 .
docker push camilin87/ruby-centos:7
```

# Ubuntu 18.04  

## Building the image  

```bash
docker build --no-cache -t camilin87/ruby-ubuntu:18.04 -f Dockerfile-ubuntu18 .
docker push camilin87/ruby-ubuntu:18.04
```
