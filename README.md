# 猛号网 · 穿云引线 App

穿云引线（NetLoan）双端 Android 应用发布仓库：**Client（我是出口）** 与 **Host（我要出口）**，提供 APK 下载与使用说明。

官网：<https://mhw.pub>

## 下载

当前版本：**v0.2.10-phase1**（2026-10-11） · 发行版：[GitHub](https://github.com/leporiinflabless-maker/netloan-release/releases) / [Gitee](https://gitee.com/mhwpub/netloan/releases)

| 应用 | 包名 | 用途 | 下载（GitHub / Gitee） |
|------|------|------|------|
| **Client · 我是出口** | `com.netloan.client` | 用本机 SIM 卡提供网络出口 | [GitHub](https://github.com/leporiinflabless-maker/netloan-release/releases/download/v0.2.10-phase1/netloan-client.apk) · [Gitee](https://gitee.com/mhwpub/netloan/releases/download/v0.2.10-phase1/netloan-client.apk) |
| **Host · 我要出口** | `com.netloan.host` | 让本机 / 热点走远端 IP | [GitHub](https://github.com/leporiinflabless-maker/netloan-release/releases/download/v0.2.10-phase1/netloan-host.apk) · [Gitee](https://gitee.com/mhwpub/netloan/releases/download/v0.2.10-phase1/netloan-host.apk) |

> 双端安装包同时收录于仓库 `apk/` 目录；Gitee 对超过 10MB 的文件要求登录后下载，推荐使用上方发行版直链。

- 安装：在系统设置中允许"安装未知应用"后直接安装。
- Client 无需 Root；Host 的「VPN 自用」模式无需 Root，「热点共享」模式需 Root。
- 两端均建议按使用说明开启保活设置，保证长时间在线。

### 文件校验（SHA-256）

| 文件 | SHA-256 |
|------|---------|
| netloan-client.apk | `b6f9ef79795b6d6008346f74f732547a2958a0df77aff840624ba5be9c5d4ecd` |
| netloan-host.apk | `8fea9b775a06b4ca2db66ff6468da9df43dd059234947a9cae642f9a38f72631` |

## 使用说明

- [Client · 我是出口 使用说明](docs/CLIENT_APP_USER_GUIDE.md)
- [Host · 我要出口 使用说明](docs/HOST_APP_USER_GUIDE.md)

## 更新日志

- **v0.2.10**（2026-10-11）：修复 0.2.9 加固版 Host 端打开「控制台」崩溃的问题；其余无变化。
- **v0.2.9**（2026-10-11）：安全加固（R8 代码混淆 / 反调试反注入 / 安装包签名校验），无界面变化。
- **v0.2.8**（2026-10-10）：Client 移除「发布我的 IP 出售」功能（IP 集市）。
- **v0.2.7**（2026-10-10）：房间被服务端删除时，双端自动退出到无房间状态（不再重拨/重试）。
- **v0.2.6**（2026-10-09）：品牌更新为「猛号网」，首页新增品牌广告词。
- **v0.2.5**（2026-10-09）：移除应用内卡密兑换功能。
