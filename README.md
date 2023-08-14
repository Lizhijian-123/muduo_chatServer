# muduo_chatServer
基于muduo网络库 nginx负载均衡 redis话题发布和订阅   包含客户端和服务端 的 集群聊天源码
# 编译运行
```
git clone https://github.com/Lizhijian-123/mymuduo_chatServer.git
./autobuild.sh
cd bin
#运行服务端 带上要监听的ip和端口号
./ChatClient 127.0.0.1 6000
#运行客户端 带上要连接的ip和端口号
./ChatClient 127.0.0.1 6000
```
# nginx配置
自行下载编译nginx
修改conf目录下的nginx.conf(最好备份)
![image](https://github.com/Lizhijian-123/mymuduo_chatServer/assets/85280708/739ed59b-4720-42ca-bfa0-20ebdd12b9d4)






