# cordova-plugin-x5-tbs

把``Cordova``的``WebView``替换为腾讯的[X5](http://x5.tencent.com/)。使用腾讯TBS完整版SDK。

## 优劣比较

### 优势
- 安装包体积小：由于QQ、微信、QQ空间等在中国的巨大装机量，与``Crosswalk``比较，``X5``内核仅增加不到300KB左右的``apk``大小。
- 兼容性强：统一不同设备到同一内核，不需要担心国产ROM奇特“定制”及老版本``WebView``造成的兼容性问题。
- 视频播放能力强：自带多种解码器，也可支持直播。
- 新浏览器特性支持：如HTTP/2、Service Worker等。．

一．接入步骤：
1.向cordiva工程中添加x5 webview插件：
```
cordova plugin add https://github.com/442623641/cordova-plugin-x5-tbs.git

```

## 环境

### 当前版本,更新时间20180510

X5：tbs_sdk_thirdapp_v3.6.0.1234_43608_sharewithdownload_withoutGame_obfs_20180510_111111

Chromium: 57.0.2987.132

## 感谢

此项目继承自项目：https://github.com/runner525/x5webview-cordova-plugin


二．熟悉android开发的同学可以参考x5官网来灵活使用x5内核．常用链接如下：

官网(https://x5.tencent.com/tbs/)

常见问题(https://x5.tencent.com/tbs/faq.html)

论坛(http://bbs.mb.qq.com/forum-112-1.html)

内核加载问题检测工具(http://bbs.mb.qq.com/thread-1944983-1-1.html)




