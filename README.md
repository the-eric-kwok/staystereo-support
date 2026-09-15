# StayStereo 支持 / Support

StayStereo 是一款 macOS 菜单栏应用，用于阻止系统默认输入被切换到 AirPods 或其他蓝牙耳机麦克风，从而避免蓝牙输出降入低音质的 HFP/HSP 通话模式。它始终保留你选择的系统默认输出。

## 系统要求

- macOS 13 或更高版本

## 常见问题

### 它会不会改变我的输出设备？

不会。StayStereo 只修正系统默认输入，从不修改系统默认输出。

### 它录音吗？

不录音。应用不保存、不处理、不传输任何音频内容。欢迎演示仅在你授权后短暂打开输入约 100 毫秒，用于促使耳机进入通话模式，采集到的缓冲会立即丢弃。

### 为什么装了它，某个会议软件里声音还是变差了？

部分会议软件使用自己的麦克风设置，不会跟随系统默认输入。如果该软件内部被显式设为 AirPods 麦克风，请在软件设置中改成内建或外接麦克风。

### 试用和购买是怎么回事？

应用免费下载，首次运行即开始连续 168 小时的完整功能试用。试用到期后，自动保护与普通手动修正会停止，但设备状态、事件日志、设置浏览、欢迎演示和购买入口仍然可用。一次买断即可永久解锁全部保护功能，不含订阅。

### 换新 Mac 后如何恢复购买？

在新设备上打开应用，点击「恢复购买」，使用同一个 Apple ID 即可。

### 登录时启动不生效？

请确认应用从「应用程序」文件夹运行，并且已在菜单栏中打开「登录时启动」。如果仍然无效，请在「系统设置 → 通用 → 登录项」中检查是否被系统禁用。

## 已知限制

- 不保证所有蓝牙耳机都一定发生 HFP/HSP 降档，应用也不直接控制蓝牙 profile。
- 不管理其他应用内部单独选择的麦克风。
- 不创建虚拟音频设备。
- 演示之外，应用不使用麦克风权限，也不进行任何音频采集。

## 联系与反馈

遇到问题或有建议，请提交 [Issue](https://github.com/the-eric-kwok/staystereo-support/issues)。

## 隐私

见 [隐私政策](PRIVACY.md)。

---

# StayStereo Support

StayStereo is a macOS menu bar app that keeps the system default input away from AirPods or Bluetooth headset microphones, so Bluetooth playback does not fall into the low-quality HFP/HSP call profile. Your chosen system default output is never changed.

## Requirements

- macOS 13 or later

## FAQ

### Does it change my output device?

No. StayStereo only corrects the system default input and never modifies the system default output.

### Does it record audio?

No. The app never stores, processes, or transmits audio. The welcome demo only opens input briefly (about 100 ms) after you grant permission, to trigger headset call mode; captured buffers are discarded immediately.

### Why does audio still degrade in a conferencing app?

Some conferencing apps use their own microphone setting instead of the system default input. If such an app is explicitly set to the AirPods microphone, change that app's input setting to the built-in or an external microphone.

### How do the trial and purchase work?

The app is free to download and starts a continuous 168-hour full-featured trial on first run. After the trial ends, automatic protection and standard manual fixes stop, while device status, event logs, settings, the welcome demo, and the purchase entry remain available. A single one-time purchase unlocks all protection features permanently — no subscription.

### How do I restore my purchase on a new Mac?

Open the app on the new Mac, click "Restore Purchase", and use the same Apple ID.

### Launch at login does not work

Make sure the app runs from the Applications folder and that "Launch at Login" is enabled in the menu bar. If it still fails, check System Settings → General → Login Items for a system-level block.

## Known limitations

- Not every Bluetooth headset will necessarily drop to HFP/HSP; the app does not control Bluetooth profiles directly.
- The app does not manage microphones chosen inside other apps.
- The app does not create a virtual audio device.
- Outside the demo, the app does not use microphone permission and performs no audio capture.

## Contact

Report issues or suggestions via [Issues](https://github.com/the-eric-kwok/staystereo-support/issues).

## Privacy

See the [Privacy Policy](PRIVACY.md).
