# amazonlinux-build-docker-node20
build image for aws

# docker

```
docker login
```


## amazonlinux-node 20
  AWS amzonelinux image node JS 20
  [syl20lego/amazonlinux-build-docker-node20:latest](https://hub.docker.com/repository/docker/syl20lego/amazonlinux-build-docker-node20/general)

  Build:

  ```
  docker build --rm --no-cache -t image-amazonlinux-build-docker-node20 .
  docker run  --name image-amazonlinux-build-docker-node20 -it image-amazonlinux-build-docker-node20 /bin/bash
  ```
  Publish:

  ```
  docker tag image-amazonlinux-build-docker-node20 syl20lego/amazonlinux-build-docker-node20:2
  docker push syl20lego/amazonlinux-build-docker-node20:2
  docker run --rm -it syl20lego/amazonlinux-build-docker-node20:2 bin/bash
  ```
