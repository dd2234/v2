1.	连接服务器
（1）输入服务器信息
 
（2）accept
 


（3）选择控制台
 
（4）进入控制台
 





2.	1Win运行脚本

(1)wget -N https://gitlab.com/rwkgyg/x-ui-yg/raw/main/install.sh && bash install.sh

 

如果遇到报错
 
运行 yum install wget
 
(2)	看到如下页面
 

 

（3）登录ui页面
 

2.2增加节点
http://3.87.149.201:12345/

 
 
 
 
 

 
 
复制此节点
vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICIiLAogICJhZGQiOiAiMy44Ny4xNDkuMjAxIiwKICAicG9ydCI6IDQ4NTkxLAogICJpZCI6ICIzMjk5ZTlkNS1iNWIxLTQ0NTEtYTc4MC1hN2NkMzExYmY2MDciLAogICJuZXQiOiAidGNwIiwKICAidHlwZSI6ICJub25lIiwKICAiaG9zdCI6ICIiLAogICJwYXRoIjogIiIsCiAgImF1dGhvcml0eSI6ICIiLAogICJ0bHMiOiAibm9uZSIsCiAgInNuaSI6ICIiLAogICJmcCI6ICIiCn0=
3.1 mac操作系统
运行脚本：
bash <(curl -s -L https://git.io/v2ray.sh)

如果提示 curl: command not found ，那是因为你的 VPS 没装 Curl
ubuntu/debian 系统安装 Curl 方法: apt-get update -y && apt-get install curl -y
centos 系统安装 Curl 方法: yum update -y && yum install curl -y
安装好 curl 之后就能安装脚本了
 
4.使用
安装软件
windows客户端：https://github.com/2dust/v2rayN/releases
V2Ray安卓客户端：https://github.com/2dust/v2rayNG/releases
V2Ray mac客户端：https://github.com/Cenmrev/V2RayX/releases

打开软件:导入上述节点
 ，从粘贴板导入，导入之后，右键选择设为活动服务器
