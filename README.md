# UpdateForPerish
走向灭亡de更新道路 ， 不管有没有 反正文档是给了，兼容你们来，处理看着办 每日一波秀操作🐒 ---来自于大厂的爱



[1. 微信小程序-小程序登录、用户信息相关接口调整更新说明](https://developers.weixin.qq.com/miniprogram/dev/api/open-api/user-info/wx.getUserProfile.html)


```
考虑到近期开发者对小程序登录、用户信息相关接口调整的相关反馈，为优化开发者调整接口的体验，《小程序登录、用户信息相关接口调整说明》公告中关于小程序回收 wx.getUserInfo 接口可获取用户授权的个人信息能力的截止时间调整至2021年4月28日24时。
在此期间，未调整的小程序可能会在微信开发者工具收到“平台 getUserInfo 接口能力调整，请尽快适配”提醒，建议开发者尽快适配 wx.getUserInfo 接口回收场景。
后续开发者可以使用 wx.getUserProfile 接口获取用户授权的个人信息。
```


[2. 更新 API 开放 wx.chooseContact](https://developers.weixin.qq.com/miniprogram/dev/api/device/contact/wx.chooseContact.html)


```
拉起手机通讯录，选择联系人。

v2.16.0 (2021-03-03) 更新的AIP版本

很兼容机型=>小米系列 😨

目前使用量比较小，待更新bug

```