# ElderTV

给家里老人用的安卓电视影视播放器，只提供安装包。

- 打开就是“接着看”，按一下确定继续播放
- 找片、我的收藏两个大按钮；分类在找片页里
- 播放控制条只留 10 个常用按钮：暂停、上一集、下一集、片头、片尾、换源、选集、倍速、字幕、更多
- 换源弹出候选列表，最快的排第一，换源后接着原来的进度
- 设置分“常用”和“高级设置”两页，老人用常用，帮忙配置的家人用高级设置
- 可选聚合：在手机上扫码打开控制台，管理订阅

不内置任何订阅源，片源地址需要自己填写。

## 下载

到 [Releases](../../releases) 下载 `ElderTV-1.0.0-armeabi-v7a.apk`，用 U 盘或局域网传到电视上安装。

GitHub 打不开时，可以用中转地址（第三方服务，一条不行换另一条）：

- https://ghfast.top/https://github.com/riowang88/ElderTV/releases/download/v1.0.0/ElderTV-1.0.0-armeabi-v7a.apk
- https://gh-proxy.com/https://github.com/riowang88/ElderTV/releases/download/v1.0.0/ElderTV-1.0.0-armeabi-v7a.apk

- 最低支持：安卓 7.0（API 24）及以上，32 位 ARM（大多数电视和盒子）
- 测试设备：雷鸟电视（Android 11）

## 说明

基于 [FongMi/TV](https://github.com/FongMi/TV) 的分支 [motao123/webtv](https://github.com/motao123/webtv) 修改，界面和交互按老人使用习惯重做。

## 许可证与源码

ElderTV 按 GPL-3.0 发布。每个版本的对应源码以压缩包形式附在该版本的 Release 里（`ElderTV-<版本>-source.tar.gz`）。
