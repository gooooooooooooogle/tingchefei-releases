# tingchefei-releases

银川停车费 Android 安装包与更新清单。

- `TingCheFei.apk`：最新安装包
- `version.json`：版本号、APK 地址、SHA-256、更新说明

App 启动时读取 `version.json`，发现新版本后下载 APK、校验 SHA-256，再交给系统安装器。
