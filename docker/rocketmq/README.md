# DevelopmentUtils
下载后
此为搭建 RocketMq 集群的 docker-compose 配置文件

docker-compose.yml 已经已经将文件写好，经测试可用。

**注意：**
还有个 data 文件夹，里面主要放置日志目录，存储目录和 broker 节点配置文件目录

其中 store 是存储目录。

logs 是日志文件目录

brokerconf 是节点配置文件目录


正式运行执行 compose 还需去 brokerconf 目录下将 broker.conf 中
将如下字段的 ip 改为自己的 ip。

**brokerIP1=自己当前电脑 IP**

修改完毕后即可运行 compose 文件。

运行完成后，输入连接 http://RokcetMq所在电脑的IP:8080 即可访问