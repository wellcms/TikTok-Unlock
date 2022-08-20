# TikTok

#### 前言介绍
通过配置下面文中的规则配置,实现免拔卡,TikTok,转载本文请标明出处,谢谢合作

### 使用方法

1.  点击配置文件--点击Raw--跳转后拷贝浏览器输入框的链接
2.  打开Shadowrocket--点击配置--添加配置
3.  粘贴链接-点击下载--下载后点击使用配置
4.  安装证书信任证书

[Rule]
DOMAIN,p16-tiktokcdn-com.akamaized.net,PROXY
DOMAIN-SUFFIX,amemv.com,PROXY
DOMAIN-SUFFIX,byteoversea.com,PROXY
DOMAIN-SUFFIX,ibytedtos.com,PROXY
DOMAIN-SUFFIX,ibyteimg.com,PROXY
DOMAIN-SUFFIX,ipstatp.com,PROXY
DOMAIN-SUFFIX,muscdn.com,PROXY
DOMAIN-SUFFIX,musical.ly,PROXY
DOMAIN-SUFFIX,sgpstatp.com,PROXY
DOMAIN-SUFFIX,snssdk.com,PROXY
DOMAIN-SUFFIX,tik-tokapi.com,PROXY
DOMAIN-SUFFIX,tiktok.com,PROXY
DOMAIN-SUFFIX,tiktokcdn.com,PROXY
DOMAIN-SUFFIX,tiktokv.com,PROXY
DOMAIN-KEYWORD,-tiktokcdn-com,PROXY
USER-AGENT,TikTok*,PROXY
FINAL,DIRECT
