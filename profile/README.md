<a id="top"></a>

<p align="center">
  <a href="#zh-cn"><strong>简体中文</strong></a> ·
  <a href="#en"><strong>English</strong></a>
</p>

---

<a id="zh-cn"></a>

<h1 align="center">⌨️ AhaKey Community</h1>

<p align="center">
  <strong>面向 AI 编程与桌面工作流的开放硬件入口</strong>
</p>

<p align="center">
  官方硬件 · 桌面客户端 · BLE 协议 · 社区扩展
</p>

<p align="center">
  <a href="https://github.com/AhakeyAI/desktop"><img alt="desktop" src="https://img.shields.io/badge/Desktop-Official-blue"></a>
  <a href="https://github.com/AhakeyAI/protocol"><img alt="protocol" src="https://img.shields.io/badge/Protocol-BLE-informational"></a>
  <a href="https://github.com/AhakeyAI/awesome-ahakey"><img alt="awesome" src="https://img.shields.io/badge/Community-Projects-success"></a>
  <a href="https://github.com/AhakeyAI/firmware"><img alt="firmware" src="https://img.shields.io/badge/Firmware-Notes-lightgrey"></a>
</p>

---

## 你来到这里，通常是想做这几件事

| 你想做什么 | 去哪里 | 说明 |
|---|---|---|
| 我想使用官方客户端 | [`desktop`]([https://github.com/AhakeyAI/desktop](https://github.com/AhakeyAI/desktop/releases)) | 下载、安装、构建官方桌面客户端 |
| 我想修改官方桌面端 | [`desktop`](https://github.com/AhakeyAI/desktop) | Fork 后改代码，再提交 PR |
| 我想自己做客户端 / 工具 | [`protocol`](https://github.com/AhakeyAI/protocol) | 阅读 BLE 协议，做自己的客户端、脚本或 workflow |
| 我做了独立版本 / 教程 / workflow | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey) | 提交社区项目、脚本、教程、工作流、桌面 setup |
| 我想申请固件源码 / 硬件资料 | Source Access Request | 固件源码、硬件设计文件、生产资料不默认公开，需要单独申请 |

---

## AhaKey 默认开放什么？

### 默认开放

- 官方桌面客户端源码
- AhaKey BLE 协议文档
- 客户端开发示例
- 社区工具、脚本、workflow、教程展示入口

### 不默认开放

- 固件源码
- 硬件原理图 / PCB / 生产资料
- 官方设备内部实现细节
- 可用于仿制、量产、商业销售的硬件资料

> 如果你只是想做自己的客户端、脚本或 workflow，通常**不需要固件源码**，请先阅读 [`protocol`](https://github.com/AhakeyAI/protocol)。

---

## 推荐路径

### 1）我想改官方客户端

```text
进入 desktop
→ 阅读 README
→ Fork 仓库
→ 修改代码
→ 提交 Pull Request
```

适合：

- 修 bug
- 改 UI
- 优化安装体验
- 增加 macOS / Windows 适配
- 改进官方默认体验

---

### 2）我想做自己的客户端 / 工具

```text
进入 protocol
→ 阅读 BLE 协议
→ 参考 examples
→ 创建自己的 repo
→ 做出 demo
→ 提交到 awesome-ahakey
```

适合：

- 自己写 macOS / Windows 客户端
- 做 Cursor / Claude / Codex 工作流工具
- 做快捷键脚本
- 做 OLED / RGB / 配置工具
- 做自动化集成

---

### 3）我做了一个独立版本，想分享给社区

```text
进入 awesome-ahakey
→ 按模板提交项目
→ 社区收录
→ 优秀功能可进一步评估是否进入官方 desktop
```

适合：

- 第三方客户端
- 工具脚本
- 使用教程
- 工作流 preset
- 桌面 setup 展示
- 视频 / 图文教程

---

## 仓库说明

| 仓库 | 用途 |
|---|---|
| [`desktop`](https://github.com/AhakeyAI/desktop) | 官方桌面客户端 |
| [`protocol`](https://github.com/AhakeyAI/protocol) | AhaKey BLE 协议与客户端开发参考 |
| [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey) | 社区项目、教程、workflow 展示 |
| [`firmware`](https://github.com/AhakeyAI/firmware) | 固件版本说明、升级说明、兼容性说明 |
| [`.github`](https://github.com/AhakeyAI/.github) | 组织级贡献规则、Issue / PR 模板、社区支持信息 |

---

## 贡献方式

你可以贡献：

- bug report
- 文档修正
- 安装教程
- macOS / Windows 客户端改进
- BLE 协议反馈
- 第三方客户端
- workflow / preset / 脚本
- 使用视频、截图、教程

建议尽量保持：

- 小步提交
- 说明清楚
- 有截图 / 日志 / demo 更好
- 不提交密钥、token、私人文件
- 大功能先 Discussion，再 PR

---

## 关于固件源码 / 硬件资料

固件源码、硬件设计文件和生产资料**不默认公开**。

如果你的项目确实需要访问这些资料，请先提交 **Source Access Request**，并说明：

- 你是谁
- 你购买 / 使用的 AhaKey 设备
- 你想做什么项目
- 为什么公开 BLE 协议不够用
- 是否涉及商业用途
- 是否会公开发布
- 是否需要修改固件或硬件

未经授权，不得使用受控资料自行打板、仿制、量产、销售或开发竞争性硬件产品。

---

## 一句话原则

> 官方版本追求稳定，社区版本鼓励探索。  
> 不是所有 DIY 都必须合进官方，但所有高质量的 AhaKey 玩法、工具和 workflow 都值得被看见。

<p align="right"><a href="#top">↑ Back to top</a></p>

---

<a id="en"></a>

<h1 align="center">⌨️ AhaKey Community</h1>

<p align="center">
  <strong>An open hardware entry point for AI coding and desktop workflows</strong>
</p>

<p align="center">
  Official Hardware · Desktop Client · BLE Protocol · Community Extensions
</p>

<p align="center">
  <a href="https://github.com/AhakeyAI/desktop"><img alt="desktop" src="https://img.shields.io/badge/Desktop-Official-blue"></a>
  <a href="https://github.com/AhakeyAI/protocol"><img alt="protocol" src="https://img.shields.io/badge/Protocol-BLE-informational"></a>
  <a href="https://github.com/AhakeyAI/awesome-ahakey"><img alt="awesome" src="https://img.shields.io/badge/Community-Projects-success"></a>
  <a href="https://github.com/AhakeyAI/firmware"><img alt="firmware" src="https://img.shields.io/badge/Firmware-Notes-lightgrey"></a>
</p>

---

## Start Here

| What do you want to do? | Where to go | Notes |
|---|---|---|
| Use the official desktop client | [`desktop`](https://github.com/AhakeyAI/desktop) | Download, install, or build the official desktop client |
| Modify the official desktop client | [`desktop`](https://github.com/AhakeyAI/desktop) | Fork the repo, make changes, and submit a PR |
| Build your own client / tool | [`protocol`](https://github.com/AhakeyAI/protocol) | Read the BLE protocol and build your own client, script, or workflow |
| Share your own project / tutorial / workflow | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey) | Submit community projects, scripts, tutorials, workflows, or setups |
| Request firmware source / hardware materials | Source Access Request | Firmware source, hardware design files, and production materials are not public by default |

---

## What is open by default?

### Open by default

- Official desktop client source code
- AhaKey BLE protocol documentation
- Client development examples
- Community tools, scripts, workflows, and tutorial showcase entry points

### Not open by default

- Firmware source code
- Hardware schematics / PCB / production materials
- Internal implementation details of official devices
- Hardware materials that can be used for cloning, manufacturing, or commercial resale

> If you only want to build your own client, script, or workflow, you usually **do not need firmware source code**. Please start with [`protocol`](https://github.com/AhakeyAI/protocol).

---

## Recommended paths

### 1) I want to modify the official desktop client

```text
Go to desktop
→ Read the README
→ Fork the repository
→ Modify the code
→ Submit a Pull Request
```

Suitable for:

- bug fixes
- UI improvements
- installation experience improvements
- macOS / Windows support improvements
- improvements to the official default experience

---

### 2) I want to build my own client / tool

```text
Go to protocol
→ Read the BLE protocol
→ Check examples
→ Create your own repo
→ Build a demo
→ Submit it to awesome-ahakey
```

Suitable for:

- your own macOS / Windows client
- Cursor / Claude / Codex workflow tools
- shortcut scripts
- OLED / RGB / config tools
- automation integrations

---

### 3) I built an independent project and want to share it

```text
Go to awesome-ahakey
→ Submit your project with the template
→ Get listed by the community
→ High-value features may later be evaluated for the official desktop
```

Suitable for:

- third-party clients
- utility scripts
- tutorials
- workflow presets
- desktop setup showcases
- video / article tutorials

---

## Repositories

| Repository | Purpose |
|---|---|
| [`desktop`](https://github.com/AhakeyAI/desktop) | Official desktop client |
| [`protocol`](https://github.com/AhakeyAI/protocol) | AhaKey BLE protocol and client development reference |
| [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey) | Community projects, tutorials, and workflows |
| [`firmware`](https://github.com/AhakeyAI/firmware) | Firmware version notes, upgrade notes, and compatibility notes |
| [`.github`](https://github.com/AhakeyAI/.github) | Shared contribution rules, Issue / PR templates, and support info |

---

## Ways to contribute

You can contribute:

- bug reports
- documentation improvements
- installation guides
- macOS / Windows client improvements
- BLE protocol feedback
- third-party clients
- workflows / presets / scripts
- videos, screenshots, and tutorials

Please try to keep contributions:

- small and reviewable
- clearly explained
- accompanied by screenshots / logs / demos when helpful
- free of secrets, tokens, or personal files
- discussed first if the feature is large

---

## About firmware source / hardware materials

Firmware source code, hardware design files, and production materials are **not publicly released by default**.

If your project really requires access, please submit a **Source Access Request** and explain:

- who you are
- which AhaKey device you own / use
- what project you want to build
- why the public BLE protocol is not enough
- whether commercial use is involved
- whether the result will be published
- whether firmware or hardware modification is required

Without authorization, controlled materials may not be used for board reproduction, cloning, manufacturing, resale, or development of competing hardware products.

---

## One-line principle

> Official versions prioritize stability.  
> Community versions encourage exploration.  
> Not every DIY idea needs to merge into the official product, but high-quality AhaKey tools, workflows, and ideas deserve to be seen.

<p align="right"><a href="#top">↑ Back to top</a></p>
