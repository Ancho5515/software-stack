# Software Stack · 个人软件栈

记录个人日常工作、开发与生活中使用的软件，以及为完善现有工作流而自行开发的辅助工具。

以轻量、高效、稳定、易维护为选择原则，优先考虑开源软件，并根据实际使用需求持续调整。

## 开发与命令行

| 软件 | 简介 | 使用备注 |
| --- | --- | --- |
| [Git](https://git-scm.com/) | 分布式版本控制工具，用于管理代码、文档及项目变更历史。 | 日常项目版本管理，与 GitHub 配合使用。 |
| [PowerShell](https://github.com/PowerShell/PowerShell) + [Oh My Posh](https://ohmyposh.dev/) | 命令行与脚本自动化环境，搭配可定制的终端提示符。 | PowerShell 负责命令执行和自动化，Oh My Posh 用于展示 Git 状态、路径等上下文信息。 |
| [WinMerge](https://winmerge.org/) | 开源文件与目录比较、差异分析及合并工具。 | 用于代码、配置文件和目录差异检查，可作为 Beyond Compare 的替代方案。 |

### Oh My Posh 与 PowerShell 模块

- 本机安装的 Oh My Posh `24.8.0` 使用 `onehalf.minimal.omp.json` 主题。主题通过 `session`、`path`、`git` 和 `status` 内置段显示用户与主机名、当前路径、Git 分支与工作区状态，以及上一条命令的退出状态。
- PowerShell 启动时加载 `posh-vcpkg` `0.0.2`，为 `vcpkg` 提供命令补全。`PSReadLine` `2.4.5` 配置了历史命令预测及补全、撤销和历史搜索快捷键。
- 用户模块目录另装有 `posh-git` `1.1.0`，可按需导入。

## 文本编辑与文档

| 软件 | 简介 | 使用备注 |
| --- | --- | --- |
| [Notepad4](https://github.com/zufuliu/notepad4) | 轻量级 Windows 文本及代码编辑器，支持语法高亮、编码转换和文本搜索。 | 侧重启动速度、资源占用及大文件编辑；搭配自研 Notepad4 Sidebar，扩展垂直标签与 Markdown 预览功能。 |
| [Notepad4 Sidebar](https://github.com/Ancho5515/notepad4-sidebar) | 自研 Notepad4 外部侧边栏辅助工具。 | 通过独立窗口和垂直标签列表管理多个 Notepad4 窗口，并集成 Markdown 渲染与预览功能。 |

## 网络与下载

| 软件 | 简介 | 使用备注 |
| --- | --- | --- |
| [FluxDown](https://github.com/zerx-lab/FluxDown) | 基于 Rust 的多协议下载管理器，支持并行下载、断点续传及浏览器扩展集成。 | 作为 IDM 的替代选择，重点关注浏览器下载接管与网页媒体嗅探能力。 |
| [Clash Verge](https://github.com/zzzgydi/clash-verge) | 开源图形化网络代理客户端，支持规则分流与代理配置管理。 | 用于日常网络代理及规则管理。 |
| [Wireshark](https://www.wireshark.org/) | 开源网络协议分析工具，支持数据包捕获、协议解析与过滤。 | 用于网络通信调试、协议分析及故障排查。 |

## AI 与语言辅助

| 软件 | 简介 | 使用备注 |
| --- | --- | --- |
| [ChatGPT](https://chatgpt.com/) | AI 助手，支持自然语言问答、代码辅助、资料分析和文档处理。 | 用于技术研究、编程、信息整理及日常知识查询。 |
| [pinyin-gloss](https://github.com/Ancho5515/pinyin-gloss)（自研） | 输入法外挂翻译工具，在中文输入过程中提供英文释义辅助。 | 设计上与微软拼音配合，保留原有输入习惯，并通过额外的翻译能力减少应用之间的切换。 |

## 安全与桌面效率

| 软件 | 简介 | 使用备注 |
| --- | --- | --- |
| [Bitwarden](https://bitwarden.com/) | 开源密码管理器，支持加密保管、密码生成、自动填充及跨设备同步。 | 集中管理账户凭据，使用独立强主密码及多因素认证是建议的安全实践。 |
| [Snipaste](https://www.snipaste.com/) | 截图、标注和屏幕贴图工具。 | 用于快速截图、信息标记及将参考内容固定在桌面。 |
| [Ditto](https://ditto-cp.sourceforge.io/) | Windows 剪贴板历史管理工具，支持历史记录搜索和重复粘贴。 | 用于提高文本复制、资料整理和重复输入的效率。 |
| [7-Zip](https://www.7-zip.org/) | 开源文件压缩与解压工具，支持 7z、ZIP 等格式。 | 用于日常文件打包、压缩与解压。 |

## 图像浏览与分析

| 软件 | 简介 | 使用备注 |
| --- | --- | --- |
| [QuickView](https://github.com/justnullname/QuickView) | 基于 Direct2D 和 C++ 的轻量级开源 Windows 图像浏览工具，支持 GPU 加速。 | 日常普通图片浏览。 |
| [ImageJ](https://imagej.net/ij/) | 科学图像处理工具，支持 16 位灰度图像、像素值查看及基础测量。 | 部署于现场电脑，主要用于查看相机采集的 16 位图像及快速检查像素数据。 |
| [Fiji](https://fiji.sc/) | 基于 ImageJ 的科学图像处理发行版，集成丰富的分析插件。 | 部署于研发电脑，用于相机 16 位图像的深入分析、区域统计、图像处理及算法验证。 |

## 音视频播放

| 软件 | 简介 | 使用备注 |
| --- | --- | --- |
| [mpv.net](https://github.com/mpvnet-player/mpv.net) | 基于 mpv 的开源 Windows 视频播放器，提供图形界面与丰富的播放配置。 | 用于日常本地音视频播放，作为 PotPlayer 的轻量化开源替代方案。 |

## 维护说明

- 本仓库仅记录实际使用的软件及配套工具，不以收录数量为目标。
- 软件更换、停用或新增时，通过 Git 提交保留变更历史。
- 本机安装包、便携发布包和配套依赖存放在 `installers/`，包文件及依赖由 Git 忽略；[清单](installers/清单.md) 和 [SHA-256 校验文档](installers/SHA256SUMS.txt) 纳入版本管理。
- 自研工具单独标识；尚未明确的项目地址、版本和实现状态不作推断。
- 不在仓库中存放密码、访问令牌、代理订阅地址等敏感配置。
