# StayStereo 隐私政策 / Privacy Policy

最后更新：2026 年 9 月 15 日

Last updated: Sep. 15, 2026

## 简体中文

StayStereo 是一款运行在 macOS 上的菜单栏应用，用于阻止系统默认输入被切换到蓝牙耳机麦克风。本政策说明该应用如何处理你的数据。

### 我们不收集任何数据

StayStereo 不收集、不上传、不共享任何个人信息。具体而言：

- 不收集设备标识符、设备名称或使用统计；
- 不使用任何分析、广告或追踪 SDK；
- 不要求注册账户，也不提供账户体系；
- 不上传设置、事件日志、试用记录或购买记录。

### 你的数据留在本机

应用在本机保存以下内容，均不会离开你的 Mac：

- 保护开关、首选备用输入设备 UID、保护关键词、暂停到期时间（存于 `UserDefaults`）；
- 首次运行时间与试用状态记录（存于系统钥匙串 Keychain）。

这两类数据仅用于恢复应用设置和计算试用期。卸载应用后，这些数据会随应用容器一并移除；钥匙串中的记录可在「钥匙串访问」中手动删除。

### 麦克风

欢迎演示为了复现蓝牙耳机的通话音质，会在你授权后短暂打开音频输入，约 100 毫秒后立即停止，采集到的缓冲会被直接丢弃。

- 应用不录音、不保存、不处理、不传输任何音频内容；
- 拒绝麦克风权限不会影响常规的保护功能，只会让演示无法稳定复现通话音质。

### 网络访问

除 StoreKit 完成商品加载、购买、恢复购买和交易更新所需的 Apple 通信外，应用不会发起其他网络请求。

### 购买

应用内购买由 Apple 的 StoreKit 处理。我们不会接触你的支付信息，也无法将你的 Apple ID 与任何使用数据关联。

### 儿童

应用不面向儿童，也不会有意收集儿童的任何信息。

### 变更

本政策如有更新，会随应用版本一同发布，并更新本文档顶部的日期。

### 联系方式

如有疑问，请通过 [Issues](https://github.com/the-eric-kwok/staystereo-support/issues) 联系我们。

## English

StayStereo is a macOS menu bar app that keeps the system default input away from Bluetooth headset microphones. This policy explains how the app handles your data.

### We collect nothing

StayStereo does not collect, upload, or share any personal information. Specifically:

- No device identifiers, device names, or usage analytics are collected.
- No analytics, advertising, or tracking SDKs are used.
- No account is required, and none exists.
- Settings, event logs, trial records, and purchase records are never uploaded.

### Your data stays on your Mac

The app stores the following locally, and none of it leaves your Mac:

- Protection toggle, preferred fallback device UID, protection keywords, and pause expiry (`UserDefaults`).
- First-run timestamp and trial state (system Keychain).

This data is used only to restore your settings and compute the trial period. Uninstalling the app removes the app container; the Keychain entry can be removed manually in Keychain Access.

### Microphone

To reproduce Bluetooth call-mode audio quality, the welcome demo briefly opens audio input after you grant permission, then stops about 100 milliseconds later. Captured buffers are discarded immediately.

- The app never records, stores, processes, or transmits audio.
- Denying microphone access does not affect normal protection; it only prevents the demo from reliably reproducing call-mode audio.

### Network access

Apart from the Apple communication StoreKit needs for product loading, purchases, restores, and transaction updates, the app makes no network requests.

### Purchases

In-app purchases are handled by Apple's StoreKit. We never see your payment information and cannot link your Apple ID to any usage data.

### Children

The app is not directed at children and does not knowingly collect any information from them.

### Changes

Any update to this policy ships with an app version and updates the date at the top of this document.

### Contact

For questions, please reach out via [Issues](https://github.com/the-eric-kwok/staystereo-support/issues).
