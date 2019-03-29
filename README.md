[![码云Gitee](https://gitee.com/binary/weixin-java-miniapp-demo/badge/star.svg?theme=blue)](https://gitee.com/binary/weixin-java-miniapp-demo)
[![Github](http://github-svg-buttons.herokuapp.com/star.svg?user=binarywang&repo=weixin-java-miniapp-demo&style=flat&background=1081C1)](https://github.com/binarywang/weixin-java-miniapp-demo)
[![Build Status](https://travis-ci.org/binarywang/weixin-java-miniapp-demo.svg?branch=master)](https://travis-ci.org/binarywang/weixin-java-miniapp-demo)
-----------------------

### 本项目为WxJava的Demo演示程序，基于Spring Boot构建，实现微信小程序后端开发功能，支持多个小程序。
更多信息请查阅：https://github.com/Wechat-Group/WxJava

## 使用步骤：
1. **请注意，本demo为简化代码编译时加入了lombok支持，如果不了解lombok的话，请先学习下相关知识，比如可以阅读[此文章](https://mp.weixin.qq.com/s/cUc-bUcprycADfNepnSwZQ)**；
1. 另外，新手遇到问题，请务必先阅读[【开发文档首页】](https://github.com/Wechat-Group/WxJava/wiki)的常见问题部分，可以少走很多弯路，节省不少时间。
1. 配置：复制 `/src/main/resources/application.yml.template` 或者修改其扩展名生成 `application.yml` 文件，根据自己需要填写相关配置（需要注意的是：yml文件内的属性冒号后面的文字之前需要加空格，可参考已有配置，否则属性会设置不成功）；	
1. 运行Java程序：`WxMaDemoApplication`；
1. 如果需要接入消息服务，请配置微信小程序中的消息服务器地址：http://外网可访问的域名/wx/portal/{appid} （注意{appid}要使用对应的小程序的appid进行替换）， 官方文档接入指引：https://developers.weixin.qq.com/miniprogram/dev/framework/server-ability/message-push.html
	
