yum install -y wget && wget https://raw.githubusercontent.com/yobabyshark/wireguard/master/wireguard_install.sh && chmod +x wireguard_install.sh && ./wireguard_install.sh

一、进入/etc/wireguard/目录，然后将client.conf下载到本地电脑；
二、下载安装TunSafe，点击file，选择import file，选择第5步下载的client.conf文件，导入到软件中;
三、导入后会自动连接，连接成功后，所有流量都会被代理，也就是全局代理。
