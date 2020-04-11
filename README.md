[![码云Gitee](https://gitee.com/binary/weixin-java-miniapp-demo/badge/star.svg?theme=blue)](https://gitee.com/binary/weixin-java-miniapp-demo)
[![Github](http://github-svg-buttons.herokuapp.com/star.svg?user=binarywang&repo=weixin-java-miniapp-demo&style=flat&background=1081C1)](https://github.com/binarywang/weixin-java-miniapp-demo)
[![Build Status](https://travis-ci.org/binarywang/weixin-java-miniapp-demo.svg?branch=master)](https://travis-ci.org/binarywang/weixin-java-miniapp-demo)
-----------------------

<table border="0">
	<tbody>
		<tr>
			<td align="left" valign="middle">
        <a href="http://mp.weixin.qq.com/mp/homepage?__biz=MzI3MzAwMzk4OA==&hid=1&sn=f31af3bf562b116b061c9ab4edf70b61&scene=18#wechat_redirect" target="_blank">
				  <img height="120" src="https://gitee.com/binary/weixin-java-tools/raw/master/images/qrcodes/mp.png">
        </a>
			</td>
			<td align="center" valign="middle">
				<a href="https://cloud.tencent.com/redirect.php?redirect=1014&cps_key=a4c06ffe004dbcda44036daa1bf8f876&from=console" target="_blank">
					<img height="120" src="https://gitee.com/binary/weixin-java-tools/raw/master/images/banners/tcloud.jpg">
				</a>
			</td>
			<td align="right" valign="middle">
				<a href="https://mp.weixin.qq.com/s/R30CNEpkELJg4SRkX0mTDA" target="_blank">
					<img height="120" src="https://gitee.com/binary/weixin-java-tools/raw/master/images/banners/planB.jpg">
				</a>
			</td>
			<td align="center" valign="middle">
				<a href="https://www.vultr.com/?ref=7888900-4F" target="_blank">
					<img height="120" src="https://gitee.com/binary/weixin-java-tools/raw/master/images/banners/vultr.jpg">
				</a>
			</td>
			<td align="center" valign="middle">
				<a href="https://promotion.aliyun.com/ntms/act/qwbk.html?userCode=7makzf5h" target="_blank">
					<img height="120" src="https://gitee.com/binary/weixin-java-tools/raw/master/images/banners/aliyun.jpg">
				</a>
			</td>
		</tr>
	</tbody>
</table>

### 本项目为WxJava的Demo演示程序，基于Spring Boot构建，实现微信小程序后端开发功能，支持多个小程序。
更多信息请查阅：https://github.com/Wechat-Group/WxJava

## 使用步骤：
1. **请注意，本demo为简化代码编译时加入了lombok支持，如果不了解lombok的话，请先学习下相关知识，比如可以阅读[此文章](https://mp.weixin.qq.com/s/cUc-bUcprycADfNepnSwZQ)**；
1. 另外，新手遇到问题，请务必先阅读[【开发文档首页】](https://github.com/Wechat-Group/WxJava/wiki)的常见问题部分，可以少走很多弯路，节省不少时间。
1. 配置：复制 `/src/main/resources/application.yml.template` 或者修改其扩展名生成 `application.yml` 文件，根据自己需要填写相关配置（需要注意的是：yml文件内的属性冒号后面的文字之前需要加空格，可参考已有配置，否则属性会设置不成功）；	
1. 运行Java程序：`WxMaDemoApplication`；
1. 如果需要接入消息服务，请配置微信小程序中的消息服务器地址：http://外网可访问的域名/wx/portal/{appid} （注意{appid}要使用对应的小程序的appid进行替换）， 官方文档接入指引：https://developers.weixin.qq.com/miniprogram/dev/framework/server-ability/message-push.html
	
