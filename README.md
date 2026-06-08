# VideoTool 更新发布仓（Public）

本仓库**仅用于**发布安装包与 `update/version.json`，不含业务源码。

买家软件通过内嵌地址自动检查更新，无需配置 GitHub。

## 发版

1. 在开发机运行 `scripts\build_installer.bat` 生成 `VideoTool-Setup-x.y.z.exe`
2. 在本仓创建 GitHub Release，上传 Setup 安装包
3. 更新 `update/version.json` 中的 `version`、`download_url`、`sha256`

详见主开发仓 `docs/DISTRIBUTION.md`。
