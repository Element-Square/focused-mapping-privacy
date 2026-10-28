# 集火映射 隐私政策

**Focused mapping Privacy Policy**

生效日期 / Effective date：2026-10-28  
最后更新 / Last updated：2026-10-28

开发者 / Developer：集火映射（Focused mapping）  
联系邮箱 / Contact：请在此处填写你的支持邮箱（须与 Google Play 开发者邮箱一致）

---

## 中文

### 1. 我们是谁

「集火映射」（Google Play 显示名称：集火映射，软件包名称 `com.elsq.mapping`）是一款运行在 Android 设备上的物理键盘、鼠标与触控映射工具。本政策说明本应用如何处理信息。

### 2. 核心原则

本应用的映射计算、按键方案、绑定列表和灵敏度等配置，均保存在你的设备本地。本应用不会把键盘按键内容、鼠标轨迹、游戏账号或密码上传到开发者服务器。

### 3. 本应用处理的信息

| 信息 | 是否离开本机 | 用途 |
| --- | --- | --- |
| 按键映射方案、灵敏度、悬浮窗显示设置 | 否，仅本机 SharedPreferences / 本地文件 | 记住你的布局和偏好 |
| 已绑定应用的名称与包名 | 否，仅本机 | 「我的绑定」里识别目标应用，并在进入该应用时启用映射 |
| 已安装应用列表（仅用于选择绑定目标） | 否，仅在本机读取 | 添加绑定时展示可启动的应用 |
| 前台应用包名（设备本地检测） | 否 | 判断当前是否处于绑定应用，以便显示或隐藏映射浮层 |
| 通知 | 否 | 显示服务运行状态、无线调试配对提示 |
| 本机网络（局域网 / Wi-Fi 组播） | 仅在本机局域网 | Android 11 及以上「无线调试」配对；不用于广告追踪 |
| 打开外部链接 | 仅在你主动点击时 | 例如打开 Shizuku 官方说明页 |

本应用当前未接入第三方广告 SDK、未接入 Firebase / Crashlytics 等云端分析，也未要求注册账号。

### 4. 权限说明

你只会在对应功能需要时被请求授权：

- **悬浮窗（SYSTEM_ALERT_WINDOW）**：在目标应用画面上方显示半透明键位指引、准星或程序光标。不会用于遮挡系统付款或登录界面来骗取信息。
- **通知（POST_NOTIFICATIONS）**：显示映射服务是否在运行，以及无线调试配对状态。
- **前台服务（CONNECTED_DEVICE）**：在连接键鼠或完成激活后保持映射服务可用。
- **忽略电池优化（可选）**：减少系统在后台杀掉映射服务。
- **网络与 Wi-Fi 状态**：无线调试配对、检测局域网连接。
- **Shizuku 授权（可选）**：仅在你主动选择「使用 Shizuku 激活」时，由你在 Shizuku 应用中确认。用于在本机完成映射激活。你也可以改用无线调试或电脑 ADB。

未授予某项权限时，对应功能不可用，其余功能仍可使用。

### 5. 激活方式

映射需要在本机获得输入能力。激活由你主动选择，可选：

1. 无线调试（Android 11 及以上，在本机完成配对）
2. Shizuku（需你另行安装并授权）
3. 电脑 USB / ADB
4. 已 Root 设备上的本机激活

激活过程中的配对码、调试连接只在你的设备或你连接到的电脑之间使用，开发者不会远程收取这些信息。

### 6. 我们不会做的事

- 不会上传你的按键记录、聊天内容、游戏账号或密码
- 不会出售个人数据
- 不会用悬浮窗伪装成其他应用的付款或登录窗口
- 不会在未说明的情况下把数据发给广告网络

### 7. 数据保留与删除

配置保存在本机。卸载本应用，或在系统设置中清除本应用数据，即可删除这些本地信息。

如需协助确认删除方式，可发送邮件到上方联系邮箱。

### 8. 儿童

本应用面向能够理解键鼠映射的一般用户，不以 13 岁以下儿童为主要对象，也不会故意收集儿童的个人数据。

### 9. 政策更新

若处理方式发生实质变化，我们会更新本页日期，并在应用内或 Google Play 产品详情中提示。请以本页最新版本为准。

### 10. 联系我们

隐私相关请求请发送至本页顶部的联系邮箱，并注明「集火映射 隐私」。

---

## English

### 1. Who we are

Focused mapping (Play listing name: 集火映射) is an Android tool that maps a physical keyboard and mouse to on-screen touch. This policy describes how the app handles information.

### 2. Local-first

Key layouts, bindings, sensitivity, and overlay settings are stored on your device. Mapping runs on-device. The app does not upload keystrokes, mouse paths, game accounts, or passwords to a developer server.

### 3. Information the app uses

| Data | Leaves the device? | Purpose |
| --- | --- | --- |
| Mapping profiles and display settings | No | Remember your layout |
| Bound app names and package names | No | Enable mapping for apps you bind |
| Installed-app list (on device) | No | Let you pick an app to bind |
| Foreground app package (on device) | No | Show or hide the overlay for the bound app |
| Notifications | No | Service status and wireless-debugging pairing |
| Local network / Wi-Fi multicast | Local network only | Wireless debugging pairing on Android 11+ |
| External links | Only if you tap them | For example the Shizuku documentation site |

The current build does not include a third-party ads SDK, Firebase/Crashlytics, or an account system.

### 4. Permissions

- **Display over other apps**: show key guides, crosshair, or a program cursor above a bound app. It is not used to spoof payment or login screens.
- **Notifications**: service running state and pairing prompts.
- **Foreground service (connected device)**: keep mapping available while a keyboard/mouse session is active.
- **Ignore battery optimizations (optional)**: reduce the chance the system stops the service.
- **Internet / Wi-Fi state**: wireless debugging pairing.
- **Shizuku (optional)**: only after you choose Shizuku activation and confirm it in the Shizuku app.

### 5. Activation

You choose how to activate mapping on the device: wireless debugging, Shizuku, computer ADB, or root. Pairing codes stay between your phone and, if used, your computer.

### 6. What we do not do

We do not sell personal data, upload your key log, or use the overlay to impersonate another app’s checkout or login screen.

### 7. Retention and deletion

Uninstall the app or clear its data in Android settings to remove local configuration. Email the address at the top of this page if you need help.

### 8. Children

The app is not directed at children under 13, and we do not knowingly collect their personal data.

### 9. Changes

Material changes will be reflected by the date on this page.

### 10. Contact

Use the email at the top of this page, with the subject “Focused mapping privacy”.
