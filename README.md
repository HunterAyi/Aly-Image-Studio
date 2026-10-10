# Aly Image Studio

免费使用的本地 AI 图片与对话创作软件。作者 **ayi** · [Aly 官方入口](https://www.aly18.com)。

**正式首发：v0.27.2 · Windows 10 22H2 / Windows 11 x64**

## 下载与安装

**[① 下载压缩包（推荐）](https://github.com/HunterAyi/Aly-Image-Studio/releases/download/v0.27.2/AlyImageStudio-0.27.2-Windows-x64.zip)** · **[② 直接下载安装程序](https://github.com/HunterAyi/Aly-Image-Studio/releases/download/v0.27.2/AlyImageStudio-0.27.2.1-stable-Setup.exe)**

ZIP 仅包含安装程序、使用说明.txt、隐私说明.txt。解压后双击安装程序，可选择合适的磁盘和文件夹。无需安装 Python、Office 或 FFmpeg，安装后通过已有的 Edge / Chrome 使用。

1. 阅读免费使用许可，完成安装。
2. 双击桌面“Aly Image Studio”，打开本机工作台。
3. 在 API 设置中添加服务商 KEY，拉取并选择模型；生图和聊天分别设置。

[正式版本页与文件校验](https://github.com/HunterAyi/Aly-Image-Studio/releases/latest) · [安装与使用说明](docs/安装与使用说明.md) · [隐私说明](docs/隐私说明.md)

## 主要功能

- **图片创作**：文生图、参考图编辑、每批 1–4 个独立任务；近期任务、历史/图库、原图查看、重命名和另存为。
- **AI 对话**：多轮聊天，适用模型的图片与文件输入、PDF 处理、视频抽帧，以及用户授权和限额内的创作助手。
- **独立配置**：生图与聊天的多个平台、KEY 和模型独立管理，内置 Aly 入口并支持其他平台。
- **外观设置**：默认主题、蓝色之约、月光小憩、云端伙伴；即时主题预览、独立页面标题、五种本地字体及字号设置。
- **资料管理**：近期记录隐藏与逐步撤回、参考关联去重和缺失提示、缓存清理；配置、聊天和作品保存在本机。
- **更新与卸载**：软件内检查新版、下载校验并确认安装；安装目录与开始菜单提供明确的“卸载”入口。

具体模型能力以服务商、协议和型号为准。普通视频抽帧不包含音频。

## 后续版本更新

有新版时顶部显示提示，也可在系统设置点击“检查更新”。下载并校验后确认安装，软件正常退出后，会在**原安装文件夹**更新完整程序和依赖并重新启动，**无需重新选择文件夹**。KEY、设置、历史、草稿和作品保留。

官方更新支持 Windows 已开启的手动系统代理，例如 FlClash 的“系统代理”。GitHub 在国内的连接情况取决于网络；网盘手动下载备用由作者另行公布，目前没有国内自动更新镜像。

## 费用、资料与许可

软件免费，无软件账号登录；在线模型服务可能收费，费用由用户与服务商确认。收费生成/聊天请求不自动重试，超时后请先核对任务与服务商记录。

资料默认位于 `%LOCALAPPDATA%\AlyImageStudio`。KEY 按当前 Windows 用户加密保存，换用户或电脑可能需要重新输入。更新和默认卸载保留个人资料及外部原图，请自行备份重要作品。

安装器没有 Windows 可信代码签名。浏览器或 Windows 可能出现下载信誉、未知发布者或 SmartScreen 提示，请核对官方来源及版本页 SHA256；此类提示不等同病毒检测结果。[验证范围](docs/版本与验证说明.md)中列明了已验证与未验证项目。

[免费使用许可](LICENSE)允许个人/商业场景免费使用和原包免费分享。第三方组件保留各自许可证与修改/替换权利：[第三方说明](THIRD_PARTY_NOTICES.md)。原始许可、FFmpeg/dav1d 精确源码与构建说明、四字体原文件和 OFL 随程序安装；其余[第三方对应源码](https://github.com/HunterAyi/Aly-Image-Studio/releases/download/v0.27.2/Third-Party-Sources.zip)供许可查阅与开发者使用，普通用户无需另行下载。

本仓库提供介绍、说明和官方安装包，应用自有源码不公开。Release 中的 update-stable.json 和 .sig 是客户端更新必需文件，普通用户只需选择上方 ZIP 或安装程序。

## 问题反馈

[Issues 问题反馈](https://github.com/HunterAyi/Aly-Image-Studio/issues)：请提供软件版本、Windows 版本、操作步骤和错误提示；不要提交 KEY、数据库、私人聊天或个人作品。
