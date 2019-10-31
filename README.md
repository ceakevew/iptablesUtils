## 上游项目地址
https://github.com/arloor/iptablesUtils

## 修改内容
1、通过 ip.sb 获取公网IPV4地址，方便NAT GCE AWS 阿里云等内网ip机型获取公网IP
2、修改 dnat.sh 下载逻辑，变更dnat.sh的下载地址，避免github raw dns污染导致异常
## 用法

```shell
wget -qO natcfg.sh https://raw.githubusercontent.com/wulabing/iptablesUtils/master/natcfg.sh && bash natcfg.sh
```

其他内容请参考上游项目
