本文仅供学习参考,无任何盈利性质,不承担任何法律责任
本文仅供VPN技术的学习记录，请勿传播
如果有人看到本文章，请勿私自搭建进行违法犯罪行为
Windows 科学上网（Ubuntu系统）
代码命令：
wget -N https://gitlab.com/rwkgyg/x-ui-yg/raw/main/install.sh && bash install.sh
浏览器访问IP:端口号
<img width="424" alt="image" src="https://github.com/dd2234/v2/assets/145436082/77788c0f-a390-43e8-a1f8-942777e157a2">

<img width="388" alt="image" src="https://github.com/dd2234/v2/assets/145436082/20bd3d4e-f130-4111-acd4-5af4ca0dc67f">


把二维码复制发给客户即可。


MAC科学上网（Debian系统）
代码命令：
rm -rf /etc/localtime
ln -s /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
当出现bash <(curl -s -L https://git.io/v2ray.sh)
时，操作如下：
apt-get update -y && apt-get install curl -y
直接复制给的代码即可


浏览器访问IP:端口号
学习网址：https://github.com/pitech007/v2ray/wiki/V2Ray%E4%B8%80%E9%94%AE%E5%AE%89%E8%A3%85%E8%84%9A%E6%9C%AC
windows客户端：https://github.com/2dust/v2rayN/releases
V2Ray安卓客户端：https://github.com/2dust/v2rayNG/releases
V2Ray mac客户端：https://github.com/Cenmrev/V2RayX/releases




SCOK5搭建（需要centos2h2G及以上配置）
1：yum install -y wget
2：wget —no-check-certificate https://raw.github.com/Lozy/danted/master/install.sh -O install.sh
3：bash install.sh --port=1080 --user=8888 --passwd=8888
