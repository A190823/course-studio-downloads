# 课程资料工作台 2.0 · 联网预览版

**教师只需下载 [CourseStudio-Online.zip](https://github.com/A190823/course-studio-downloads/releases/download/v2.0.0-preview.20260908/CourseStudio-Online.zip)**，解压后双击「开始备课.exe」。首次点击会自动下载约 286 MB 运行组件，此后直接使用本机组件。

- 无需手动安装 Python、Node.js、LibreOffice，无需管理员权限或命令行。
- 支持续传、取消、SHA-256 完整性校验。失败不会清除原有课程。
- 支持 Windows 10/11 x64，需要 .NET Framework 4.8，预留 1.5 GB 空间。
- 初次使用仍需连接自己的 AI 服务；调用费由所选服务收取。准备过程不上传密钥或课程。
- `core-*`、`renderer-*` 是启动器自动下载的组件，教师不用自己处理。
- 本仓库仅分发启动器与运行组件，不发布课程数据、密钥或产品源码。

## 请注意

这是**未签名预览版**，可能出现 Windows 安全提示。请核对来源及 SHA256SUMS.txt，不要关闭安全防护。
首次下载需要能访问 GitHub；不能保证所有学校网络都能连通，连不上可使用完整离线包。
本版简化安装分发，不代表生成内容已经完成教师验收；教学质量、PowerPoint/WPS 兼容及干净 Windows 机器验收仍须完成。

第三方组件保留各自许可。核心包包含 THIRD-PARTY-NOTICES.txt；渲染包包含 LICENSE.html、license.txt、NOTICE。
LibreOffice 26.2.6.3 二进制未改动，仅裁剪非必要资源。[对应源码](https://downloadarchive.documentfoundation.org/libreoffice/old/26.2.6.3/src/) / [许可说明](https://www.libreoffice.org/licenses/)。
