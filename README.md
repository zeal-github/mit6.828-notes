# mit6.828-notes
notes when learning mit6.828 course

## 环境搭建
1. 使用docker，base image：ubuntu:16.04
2. docker pull ubuntu:16.04
3. docker run -it --env="DISPLAY" --volume="/tmp/.X11-unix:/tmp/.X11-unix:rw" --name=ubuntu16 ubuntu:16.04
4. `The follow commond is inside container ubuntu16`
4. git clone git@github.com:zeal-github/mit6.828-notes.git
5. cd mit6.828-notes
6. chmod a+x setup.bash
7. ./setup.bash
8. mkdir mit6828 && cd mit6828
9. git clone git@github.com:geofft/qemu.git
10. git clone https://pdos.csail.mit.edu/6.828/2018/jos.git lab
11. cd qemu
12. ./configure --prefix=/usr/local --target-list="i386-softmmu x86_64-softmmu"
13. make && make install
14. cd ./lab
15. make
16. make qemu
