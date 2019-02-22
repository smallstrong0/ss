### Shadowsocks 全端翻墙 

> 授人以渔

[搬瓦工VPS自建VPN 走你](http://www.smallstrong.site/2016/10/11/%E4%BA%94%E5%88%86%E9%92%9F%E6%95%99%E4%BD%A0%E5%9C%A8VPS%E4%B8%8A%E6%90%AD%E5%BB%BAVPN/)

#### 搬瓦工vps如果被封IP损失比较大，推荐 https://www.vultr.com/ 充值类型的按使用日期付费，IP被限制之后可以重新选择主机进行部署.

```
wget --no-check-certificate -O shadowsocks.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh
chmod +x shadowsocks.sh
./shadowsocks.sh 2>&1 | tee shadowsocks.log
```

启动：/etc/init.d/shadowsocks start
停止：/etc/init.d/shadowsocks stop
重启：/etc/init.d/shadowsocks restart
状态：/etc/init.d/shadowsocks status




