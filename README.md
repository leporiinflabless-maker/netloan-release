# 猛号网 · 穿云引线 App

穿云引线（NetLoan）双端 Android 应用发布仓库：**Client（我是出口）** 与 **Host（我要出口）**，提供 APK 下载与使用说明。

官网：<https://mhw.pub>

## 下载

当前版本：**v0.2.6-phase1**（2026-10-09）

| 应用 | 包名 | 用途 | 下载 |
|------|------|------|------|
| **Client · 我是出口** | `com.netloan.client` | 用本机 SIM 卡提供网络出口 | [netloan-client.apk](apk/netloan-client.apk) |
| **Host · 我要出口** | `com.netloan.host` | 让本机 / 热点走远端 IP | [netloan-host.apk](apk/netloan-host.apk) |

- 安装：在系统设置中允许"安装未知应用"后直接安装。
- Client 无需 Root；Host 的「VPN 自用」模式无需 Root，「热点共享」模式需 Root。
- 两端均建议按使用说明开启保活设置，保证长时间在线。

### 文件校验（SHA-256）

| 文件 | SHA-256 |
|------|---------|
| netloan-client.apk | `e41cdaffe35dd3a3d718ff7b40b3ddb5e580e8ba87aa69813a9d250aab44a9ed` |
| netloan-host.apk | `9ab3d2bce8cd5731e8e95f865d9c1cd107ed9d70c21f575b9c8a41b09778f549` |

## 使用说明

- [Client · 我是出口 使用说明](docs/CLIENT_APP_USER_GUIDE.md)
- [Host · 我要出口 使用说明](docs/HOST_APP_USER_GUIDE.md)

## 更新日志

- **v0.2.6**（2026-10-09）：品牌更新为「猛号网」，首页新增品牌广告词。
- **v0.2.5**（2026-10-09）：移除应用内卡密兑换功能。
