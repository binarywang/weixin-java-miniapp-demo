### 本项目为weixin-java-tools的Demo演示程序，基于Spring Boot构建，实现微信小程序后端开发功能，支持多个小程序。
更多信息请查阅：https://github.com/Wechat-Group/weixin-java-tools

[![Build Status](https://travis-ci.org/binarywang/weixin-java-miniapp-demo.svg?branch=master)](https://travis-ci.org/binarywang/weixin-java-miniapp-demo)
-----------------------

## 使用步骤：
1. 配置：复制 `/src/main/resources/application.yml.template` 或者修改其扩展名生成 `application.yml` 文件，根据自己需要填写相关配置（需要注意的是：yml文件内的属性冒号后面的文字之前需要加空格，可参考已有配置，否则属性会设置不成功）；	
1. 运行Java程序：`WxMaDemoApplication`；
1. 打开shell或cmd，进入ngrok目录，运行 `ngrok -config ngrok.cfg -subdomain my-domain 8080` 如果运行失败，请更换my-domain为其它字符串，直至连接成功；
1. 如果需要接入消息服务，请配置微信小程序中的消息服务器地址：http://my-domain.tunnel.qydev.com/wx/portal/{appid} （注意my-domain要跟上面的一致，需要符合微信官方的要求，{appid}要使用对应的小程序的appid进行替换）， 官方文档接入指引：https://mp.weixin.qq.com/debug/wxadoc/dev/api/custommsg/callback_help.html
	
