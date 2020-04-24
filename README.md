zookeeper-3.4.13 源码解析

zookeeper-3.4.13 编译：
zookeeper目录下(build.xml所在目录)，执行ant eclipse

idea Import->Existing Projects into Workspace


Main Class
org.apache.zookeeper.server.ZooKeeperServerMain
vm options
-Dlog4j.configuration=file:E:/github/zookeeper/conf/log4j.properties
program arguments
E:/github/zookeeper/conf/zoo.cfg


Main Class
org.apache.zookeeper.ZooKeeperMain
vm options
-Dlog4j.configuration=file:E:/github/zookeeper/conf/log4j.properties
