# group-chat-server
基于muduo实现的，服务器间可以通过redis进行通信，可以工作在nginx tcp负载均衡环境中的集群聊天服务器和客户端源码


## 编译方式1：
* cd build
* rm -rf *
* cmake ..
* make

## 编译方式2：直接运行编译脚本autobuild..sh
* chmod +x autobuild.sh
* ./autobuild.sh
