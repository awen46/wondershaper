# wondershaper
wondershaper是一款在Linux内核下基于TC工具的对整块网卡的限度工具，虽然有很久没有更新了，但是测试老版本在Centos6.3上依然可以使用。
# 首先下载wondershaper的rpm安装包
安装wondershaper：  [root@localhost ~]# rpm -ivh wondershaper-1.1a-7.noarch.rpm 
# 限速命令： 
第一个参数为网卡接口名，后面两个数字分别代表下行和上行的速度（单位Kb）  
[root@localhost ~]# wondershaper eth0 5000 500 
# 取消限速：  
[root@localhost ~]# wondershaper clear eth0
