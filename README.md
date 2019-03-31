# docker-dotnet
Shrinking docker image size by choosing the correct runtime image

Build the docker image with different docker files 

```
docker build -f Dockerfile-0 . -t img0 
# 1.58 GB

docker build -f Dockerfile-1 . -t img1
# 273 MB

docker build -f Dockerfile-2 . -t img2
# 119 MB

docker build -f Dockerfile-3 . -t img3
# 63 MB
```
