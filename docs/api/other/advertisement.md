#### 广告

广告API

广告能力在不同小程序端实现不同，使用时需注意用[条件编译](https://uniapp.dcloud.io/platform)调用不同平台的代码。

- App平台：无需编码，在打包App时可直接勾选广告位，[详见](https://dcloud.io/dad.html)
- 微信小程序：[规范文档](https://developers.weixin.qq.com/miniprogram/dev/api/wx.createRewardedVideoAd.html)
- 百度小程序：有组件但无API
- 支付宝小程序：不支持此能力
- 字节跳动小程序：基础库 1.19.0 开始支持本组件。但是目前只有今日头条app支持，抖音和今日头条极速版不支持，[规范文档](https://developer.toutiao.com/dev/cn/mini-app/develop/multi-server-support/restrictions-for-apps)
- QQ小程序：[规范文档](https://q.qq.com/wiki/develop/miniprogram/API/ad/qq.createRewardedVideoAd.html)
