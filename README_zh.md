<!--
Canonical source: README.md
Locale: zh-CN
Do not edit product facts independently from the English canonical README.
-->

<p align="center">
  <img src="assets/readme/vimo-rebinder-icon.png" width="96" height="96" alt="Vimo Rebinder icon">
</p>

<h1 align="center">Vimo Rebinder</h1>

<p align="center">
  <strong>让每个应用都顺着你的快捷键习惯来。</strong>
</p>

<p align="center">
  一款面向 Windows 和 macOS 的无代码、应用专属快捷键工作流管理器。
</p>

<p align="center">
  <a href="https://github.com/ChenghaoQ/Vimo-Rebinder/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/ChenghaoQ/Vimo-Rebinder?label=latest%20release"></a>
  <img alt="Windows 10 and 11" src="https://img.shields.io/badge/Windows-10%20%2F%2011-2563eb">
  <img alt="macOS App Store" src="https://img.shields.io/badge/macOS-App%20Store-111827">
</p>

<p align="center">
  <a href="https://github.com/ChenghaoQ/Vimo-Rebinder/releases/latest"><strong>下载 Windows 版</strong></a>
  ·
  <a href="https://apps.microsoft.com/store/detail/9NVCW6P19QL7">Microsoft Store</a>
  ·
  <a href="https://apps.apple.com/us/app/vimo-rebinder/id6472165219?mt=12">Mac App Store</a>
  ·
  <a href="https://app.vimorebinder.com">官方网站</a>
  ·
  <a href="https://github.com/ChenghaoQ/Vimo-Rebinder/releases">Releases</a>
</p>

<p align="center">
  <strong>简体中文</strong> ·
  <a href="README.md">English</a> ·
  <a href="README_ja.md">日本語</a> ·
  <a href="README_ko.md">한국어</a> ·
  <a href="README_de.md">Deutsch</a> ·
  <a href="README_fr.md">Français</a> ·
  <a href="README_es.md">Español</a> ·
  <a href="README_pt-BR.md">Português</a> ·
  <a href="README_ru.md">Русский</a>
</p>

<p align="center">
  <img src="assets/readme/vimo-rebinder-hero.png" alt="Vimo Rebinder 快捷键管理器，标题为 Every Shortcut at Your Fingertips">
  <br>
  <em>一套快捷键结构，会自动适配当前正在使用的应用。</em>
</p>

## 每个应用，都有自己的快捷键语言。

浏览器标签页、编辑器、办公套件、设计工具和系统操作，都有各自的快捷键规则。同一个意图，在不同应用里可能要换成完全不同的按键组合，于是记忆成本、手指移动成本和上下文切换成本一起上来。

Vimo Rebinder 把这些分散的快捷键整理成一套有结构的工作流。它不是让你再背一堆新的按键，而是让你保留统一的命令层，同时自动把快捷键发送给当前正在使用的应用。

Vimo 不是在增加快捷键，而是在降低使用快捷键的成本。

## 使用前 / 使用后

| 没有 Vimo | 使用 Vimo |
| --- | --- |
| 每个应用一套不同的快捷键 | 一套统一的个人工作流 |
| 复杂别扭的多键组合 | 更容易上手的结构化快捷键序列 |
| 记忆彼此孤立的按键组合 | 按功能分组、按空间组织的布局 |
| 写脚本、维护脚本 | 可视化、无代码配置 |
| 每次重建环境都要从头开始 | 预设和可复用的应用配置 |

## 不只是另一种按键映射器

传统按键映射器改变的是“哪个键输出什么按键”。自动化和脚本工具能扩展电脑能做什么，但通常也意味着更高的上手和维护成本。

Vimo 处在另一层：它降低的是使用快捷键时的记忆成本、移动成本、冲突成本和上下文切换成本。它在某些场景下会与 AutoHotkey、PowerToys、Karabiner-Elements 这类工具重叠，但设计目标是互补，而不是完整替代。

## 看看 Vimo 怎么工作

| 工作流 | 示例 |
| --- | --- |
| 浏览器和编辑器标签 | 把切换、关闭、重新打开和移动标签统一放进同一套熟悉结构里。 |
| 窗口与桌面控制 | 把窗口操作、桌面移动和重复动作放在手已经习惯的位置。 |
| 应用专属工作 | 每个应用都能有自己的快捷键，同时你继续使用同一套 Vimo 命令习惯。 |

## 核心系统

| 能力 | 实际含义 |
| --- | --- |
| 应用专属配置 | 在不同应用之间复用同一套个人工作流，Vimo 会为当前应用发送匹配的快捷键。 |
| Super Key | 按住或点按一个选定按键进入 Vimo 的命令层，松开后恢复正常输入。 |
| 功能分组 | 把窗口、标签、桌面、编辑或导航等相关动作放在一起。 |
| 空间按键区 | 让窗口操作围绕 W，桌面操作围绕 D，相关命令尽量靠近分组键。 |
| 可视化快捷键提示 | 不用把所有快捷键都记住，也能直接看到下一步可用的动作。 |
| 预设和洞察 | 从现成布局开始，再回顾一段时间内的快捷键使用情况。 |

<p align="center">
  <img src="assets/readme/key-zones.png" alt="Vimo Rebinder 键盘布局，展示 Superkey、文本快捷键、方向键、重复动作和扩展区域">
</p>

<p align="center">
  <img src="assets/readme/grouping-shortcuts.png" alt="Vimo Rebinder 快捷键分组示例，把复杂快捷键简化为 Superkey 序列">
</p>

<p align="center">
  <img src="assets/readme/key-hints.png" alt="Vimo Rebinder 按下 Superkey 后显示可用命令提示">
</p>

## 三步开始

1. 安装 Vimo Rebinder。
2. 选择一个全局工作流，或者选定一个应用。
3. 把动作分配到一种符合你习惯的快捷键结构里。

跟着浮动提示熟悉布局即可。不需要脚本，每个快捷键都可以随时调整或移除。

## Free 和 Pro

| 能力 | Free | Pro |
| --- | --- | --- |
| 无限全局快捷键 | ✓ | ✓ |
| 标签箭头导航 | ✓ | ✓ |
| 系统快捷键预设 | ✓ | ✓ |
| 应用专属配置 | — | ✓ |
| 完整预设库 | — | ✓ |
| 在应用之间移动或复制快捷键 | — | ✓ |
| 最多在 3 台设备上使用 | — | ✓ |

查看当前方案和价格，请访问 [pricing page](https://app.vimorebinder.com/pricing/)。

## 下载

| 平台 | 入口 | 说明 |
| --- | --- | --- |
| Windows 10 / 11 | [Latest GitHub Release](https://github.com/ChenghaoQ/Vimo-Rebinder/releases/latest) | Windows 安装包通过 GitHub Releases 发布。 |
| Windows 10 / 11 | [Microsoft Store](https://apps.microsoft.com/store/detail/9NVCW6P19QL7) | 通过商店安装、更新和管理购买记录。 |
| macOS 13.0+ | [Mac App Store](https://apps.apple.com/us/app/vimo-rebinder/id6472165219?mt=12) | macOS 通过 App Store 分发，不通过 GitHub Release 资源。 |

## Windows 安装与隐私

直接下载的 Windows 安装包通过官方 [Vimo Rebinder GitHub Releases](https://github.com/ChenghaoQ/Vimo-Rebinder/releases/latest) 分发。

直接安装包使用 Vimo 的自签名发布证书。Windows 可能会在首次安装前要求导入该证书。Microsoft Store 版本不需要这一步。

快捷键配置保存在本地。只有在工作流功能启用时，Vimo 才会观察键盘快捷键和当前活动应用。

技术细节请参见 [隐私政策](https://app.vimorebinder.com/docs/privacy-policy/)、[Windows 安装指南](docs/windows-installation.md) 和 [隐私与数据说明](docs/privacy-and-data.md)。

## 平台与语言

- Windows 10 和 Windows 11
- Windows 安装包：x64
- macOS 13 或更高版本
- English、简体中文、日本語、한국어、Français、Deutsch、Español、Português、Русский

## FAQ

### Vimo Rebinder 是按键映射器吗？

它可以重绑定快捷键工作流，但它的主要目标更广：应用专属的快捷键结构、可视化提示、预设，以及一套统一的命令层。

### 它会取代 AutoHotkey、PowerToys、Karabiner-Elements 或脚本工具吗？

不会。这些工具在很多自动化和按键映射场景下都很优秀。Vimo 关注的是无代码的快捷键工作流管理，在职责不冲突时也可以和其他工具一起使用。

### GitHub 会提供 macOS 下载吗？

不会。GitHub Release 资源只发布 Windows 安装包。macOS 用户应使用 [Mac App Store](https://apps.apple.com/us/app/vimo-rebinder/id6472165219?mt=12)。

### 官方 Vimo 购买和 Microsoft Store 购买可以互通吗？

不可以。它们的产品功能是等价的，但购买记录和许可证恢复路径是分开管理的。

### 为什么 Vimo 需要键盘访问权限？

Super Key、应用专属工作流、浮动提示和重绑定后的快捷键执行都依赖键盘事件处理。如果你不想启用这些行为，可以关闭 Vimo。

## 支持

- [GitHub Issues](https://github.com/ChenghaoQ/Vimo-Rebinder/issues)：用于反馈 bug、安装问题和可复现的产品问题。
- [GitHub Releases](https://github.com/ChenghaoQ/Vimo-Rebinder/releases)：用于查看 Windows 发布资源和版本历史。
- [官方网站](https://app.vimorebinder.com)：用于产品页面、价格和政策链接。
- Email: [vimo_rebinder@outlook.com](mailto:vimo_rebinder@outlook.com)

## 专有软件

Vimo Rebinder 是专有软件。这个仓库是 Vimo Rebinder 的公开产品和发布入口，不是开源许可授权。
