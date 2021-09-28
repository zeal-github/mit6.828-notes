# mit6.828-notes
notes when learning mit6.828 course

## 环境搭建
1. 使用docker，base image：ubuntu:16.04
2. docker pull ubuntu:16.04
3. docker run -it --env="DISPLAY" --volume="/tmp/.X11-unix:/tmp/.X11-unix:rw" --name=ubuntu16 ubuntu:16.04
4. 
