# Aly Image Studio

免费使用的本地 AI 图片与对话创作软件。作者 **ayi** · [Aly 官方入口](https://www.aly18.com)。

Windows 安装后通过已有的 Edge / Chrome 使用，无需安装 Python、Office 或 FFmpeg。配置、聊天与作品保存在本机；使用在线模型需要自行配置服务商 KEY，模型服务可能收费。

## 下载和安装

**[① 下载压缩包（推荐）](https://github.com/HunterAyi/Aly-Image-Studio/releases/download/v0.27.1/AlyImageStudio-0.27.1-Windows-x64.zip)** · **[② 直接下载安装程序](https://github.com/HunterAyi/Aly-Image-Studio/releases/download/v0.27.1/AlyImageStudio-0.27.1.1-stable-Setup.exe)**

当前 **v0.27.1**，安装修订 **0.27.1.1**。ZIP 只有安装程序、使用说明.txt、隐私说明.txt，解压后双击安装程序。必要许可和依赖随程序安装，不需要额外下载。

1. 阅读免费使用许可并安装，可选择合适的磁盘和文件夹。
2. 双击桌面“Aly Image Studio”启动本机工作台。
3. 在 API 设置中添加服务商 KEY，拉取并选择模型；生图和聊天分别设置。

已有 v0.26.1 的用户可从软件的系统设置检查更新，下载校验后确认安装。程序在**原安装文件夹**更新完整软件和依赖，无需重新选择目录，KEY、设置、历史和作品保留。

目标系统：Windows 10 22H2 / Windows 11 x64。[最新版本页与 SHA256](https://github.com/HunterAyi/Aly-Image-Studio/releases/latest) · [安装与使用说明](docs/安装与使用说明.md) · [验证范围](docs/版本与验证说明.md)。GitHub 国内连接因网络而异；网盘手动备用由作者另行安排，目前没有国内自动镜像。

## 本轮变化

- 选择主题：默认主题色块和三套主题预览，点击即时预览，确定保存，取消还原。
- 每主题独立页面标题，含符号最多12字，五种本地字体、合理字号；标题留在顶栏。
- 图片预览名称回到顶部，底部缩略图及参数排列调整；减少控件闪烁竖条。
- 近期记录可隐藏及逐步撤回，参考图关联去重、缺失提示和缓存清理。
- 安装文件夹新增红色垃圾桶图标的“卸载”入口，开始菜单也可卸载；默认保留个人资料。

## 图片与对话

文生图、参考图编辑、每批1–4个任务；近期任务、历史/图库、查看、重命名和另存为。多轮对话与适用模型的图片/文件输入、PDF处理、视频抽帧，以及用户授权和限额内的 AI 创作助手。生图与聊天的多个平台、KEY、模型独立管理。能力以实际服务商、协议和型号为准，普通视频抽帧不包含音频。

## 费用、资料与许可

软件免费，模型服务费用由用户与服务商确认。收费生成/聊天 POST 不自动重试；网络超时后请先核对任务与渠道记录。

资料默认位于 %LOCALAPPDATA%\AlyImageStudio，KEY 按当前 Windows 用户加密，换用户/电脑可能需要重新输入。更新和默认卸载保留资料及外部原图，请自行备份重要作品。[隐私说明](docs/隐私说明.md)。

安装器没有 Windows 可信代码签名，系统可能显示未知发布者或 SmartScreen；请核对官方来源与版本页 SHA256 并保持防护开启。公网 SmartScreen 体验尚未验证。

[免费使用许可](LICENSE)允许个人/商业场景免费使用及原包免费分享。第三方组件保留各自许可证与修改/替换权利：[第三方说明](THIRD_PARTY_NOTICES.md)，安装目录 licenses 内有原始许可和部分对应源码；其余[第三方组件对应源码](https://github.com/HunterAyi/Aly-Image-Studio/releases/download/v0.26.1/Third-Party-Sources.zip)继续适用于未变更的依赖。新增四字体原文件和 OFL 同时随软件安装。

本仓库只发布介绍、说明和安装包，应用自有源码不公开。Release 的 update-stable.json 和签名是客户端更新必须文件，普通用户只下载 ZIP 或 Setup。

[Issues 问题反馈](https://github.com/HunterAyi/Aly-Image-Studio/issues)：提供软件/Windows版本、复现步骤和错误提示；不要提交 KEY、数据库、私人聊天或个人作品。
