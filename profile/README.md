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
  <a href="https://github.com/AhakeyAI/desktop/releases"><img alt="release" src="https://img.shields.io/badge/Download-Releases-blue"></a>
  <a href="https://github.com/AhakeyAI/desktop"><img alt="desktop" src="https://img.shields.io/badge/Desktop-Official-5C6BC0"></a>
  <a href="https://github.com/AhakeyAI/protocol"><img alt="protocol" src="https://img.shields.io/badge/Protocol-BLE-26A69A"></a>
  <a href="https://github.com/AhakeyAI/awesome-ahakey"><img alt="awesome" src="https://img.shields.io/badge/Community-Projects-43A047"></a>
  <a href="https://github.com/orgs/AhakeyAI/discussions"><img alt="discussion" src="https://img.shields.io/badge/Discuss-GitHub%20Discussions-orange"></a>
</p>

---

## 你来到这里，通常是想做这几件事

| 你想做什么 | 去哪里 | 说明 |
|---|---|---|
| 我想直接使用官方客户端 | [`Releases`](https://github.com/AhakeyAI/desktop/releases) | 下载官方桌面客户端安装包 |
| 我想查看 / 修改官方桌面端源码 | [`desktop`](https://github.com/AhakeyAI/desktop) | Fork 后改代码，再提交 PR |
| 我想自己做客户端 / 工具 | [`protocol`](https://github.com/AhakeyAI/protocol) | 阅读 BLE 协议，做自己的客户端、脚本或 workflow |
| 我想欣赏并 Fork 别人的二创 | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey) | 查看社区项目、教程、工作流、桌面 setup |
| 我做了独立版本 / 教程 / workflow，想提交给社区 | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey) | 按模板提交你的项目，让更多人看到 |
| 我发现了 bug | [`Issues`](https://github.com/AhakeyAI/desktop/issues) | 提交明确问题、复现步骤、日志或截图 |
| 我有一个想法，想先讨论 | [`Discussions`](https://github.com/orgs/AhakeyAI/discussions) | 发起问题、想法、玩法、共创讨论 |
| 我想申请固件源码 / 硬件资料 | [`Discussions`](https://github.com/orgs/AhakeyAI/discussions) | 固件源码、硬件设计文件、生产资料不默认公开，需要单独申请 |

---

## 仓库说明

<div align="center">

<table>
  <tr>
    <th>仓库</th>
    <th>用途</th>
    <th>适合谁看</th>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/desktop"><strong>desktop</strong></a></td>
    <td>官方桌面客户端</td>
    <td>想使用、构建、修改官方客户端的人</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/protocol"><strong>protocol</strong></a></td>
    <td>AhaKey BLE 协议与客户端开发参考</td>
    <td>想自己做客户端、脚本、工具、workflow 的人</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/awesome-ahakey"><strong>awesome-ahakey</strong></a></td>
    <td>社区项目、教程、workflow 展示</td>
    <td>想看二创、Fork 别人项目、提交自己作品的人</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/firmware"><strong>firmware</strong></a></td>
    <td>固件版本说明、升级说明、兼容性说明</td>
    <td>想了解固件版本和升级信息的人</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/.github"><strong>.github</strong></a></td>
    <td>组织级贡献规则、Issue / PR 模板、社区支持信息</td>
    <td>准备提交 Issue、PR 或参与社区协作的人</td>
  </tr>
</table>

</div>

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

### 1）我想直接使用官方客户端

```text
进入 Releases
→ 下载最新版本
→ 安装桌面客户端
→ 连接 AhaKey
→ 开始使用
```

适合：

- 只想使用 AhaKey
- 不改代码
- 不做开发
- 需要下载安装包

入口：[`desktop/releases`](https://github.com/AhakeyAI/desktop/releases)

---

### 2）我想修改官方客户端

```text
进入 desktop
→ 阅读 README
→ Fork 仓库
→ 修改代码
→ 本地测试
→ 提交 Pull Request
```

适合：

- 修 bug
- 改 UI
- 优化安装体验
- 增加 macOS / Windows 适配
- 改进官方默认体验

入口：[`desktop`](https://github.com/AhakeyAI/desktop)

---

### 3）我想自己做客户端 / 工具

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

入口：[`protocol`](https://github.com/AhakeyAI/protocol)

---

### 4）我想欣赏并 Fork 别人的二创

```text
进入 awesome-ahakey
→ 找到感兴趣的项目
→ 查看 README / Demo
→ Fork 或参考实现
→ 做自己的改造
```

适合：

- 看别人怎么玩 AhaKey
- 找现成工具和教程
- Fork 社区项目继续改
- 学习第三方客户端或 workflow 的实现方式

入口：[`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

---

### 5）我做了一个独立版本，想分享给社区

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

入口：[`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

---

### 6）我发现了 bug

```text
进入对应仓库的 Issues
→ 描述问题
→ 提供复现步骤
→ 补充系统环境、日志或截图
→ 等待维护者确认
```

适合用 Issue 的情况：

- 官方客户端无法启动
- BLE 连接异常
- 某个功能稳定复现错误
- 文档有明显错误
- 构建 / 安装流程失败
- 协议文档中某个字段不清楚

常用入口：

- 官方客户端问题：[`desktop/issues`](https://github.com/AhakeyAI/desktop/issues)
- 协议问题：[`protocol/issues`](https://github.com/AhakeyAI/protocol/issues)

---

### 7）我有一个想法，想先讨论

```text
进入 Discussions
→ 描述你的想法 / 玩法 / 场景
→ 和社区一起讨论
→ 成熟后再决定是否开 Issue 或 PR
```

适合用 Discussion 的情况：

- 你还不确定这是不是 bug
- 你有一个新功能想法
- 你想讨论某种 AhaKey 玩法
- 你想展示正在做的 DIY
- 你想发起一个高关注度的共创话题
- 你想问“这个功能该不该做、怎么做”

入口：[`GitHub Discussions`](https://github.com/orgs/AhakeyAI/discussions)

---

## Issue / Discussion / PR / awesome-ahakey 分别用来做什么？

| 类型 | 用途 | 适合什么时候用 |
|---|---|---|
| Issue | 明确问题或明确需求 | bug、文档错误、可复现问题、具体功能请求 |
| Discussion | 开放讨论和想法孵化 | 玩法讨论、共创想法、不确定的问题、高关注度话题 |
| Pull Request | 提交具体改动 | 代码修改、文档修改、bug fix、功能实现 |
| awesome-ahakey | 展示社区作品 | 独立项目、第三方客户端、脚本、教程、workflow、二创展示 |

简单理解：

```text
不确定 → 先 Discussion
明确问题 → 提 Issue
已经改好 → 提 Pull Request
做了独立作品 → 提到 awesome-ahakey
```

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
  <a href="https://github.com/AhakeyAI/desktop/releases"><img alt="release" src="https://img.shields.io/badge/Download-Releases-blue"></a>
  <a href="https://github.com/AhakeyAI/desktop"><img alt="desktop" src="https://img.shields.io/badge/Desktop-Official-5C6BC0"></a>
  <a href="https://github.com/AhakeyAI/protocol"><img alt="protocol" src="https://img.shields.io/badge/Protocol-BLE-26A69A"></a>
  <a href="https://github.com/AhakeyAI/awesome-ahakey"><img alt="awesome" src="https://img.shields.io/badge/Community-Projects-43A047"></a>
  <a href="https://github.com/orgs/AhakeyAI/discussions"><img alt="discussion" src="https://img.shields.io/badge/Discuss-GitHub%20Discussions-orange"></a>
</p>

---

## Start Here

| What do you want to do? | Where to go | Notes |
|---|---|---|
| Use the official desktop client | [`Releases`](https://github.com/AhakeyAI/desktop/releases) | Download the official desktop client |
| View / modify the official desktop source code | [`desktop`](https://github.com/AhakeyAI/desktop) | Fork the repo, make changes, and submit a PR |
| Build your own client / tool | [`protocol`](https://github.com/AhakeyAI/protocol) | Read the BLE protocol and build your own client, script, or workflow |
| Explore and fork community remixes | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey) | Browse community projects, tutorials, workflows, and setups |
| Submit your own project / tutorial / workflow | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey) | Submit your project and let more people see it |
| Report a bug | [`Issues`](https://github.com/AhakeyAI/desktop/issues) | Submit a clear issue with reproduction steps, logs, or screenshots |
| Start a discussion | [`Discussions`](https://github.com/orgs/AhakeyAI/discussions) | Share ideas, questions, use cases, or collaboration topics |
| Request firmware source / hardware materials | [`Discussions`](https://github.com/orgs/AhakeyAI/discussions) | Firmware source and hardware files are not public by default |

---

## Repositories

<div align="center">

<table>
  <tr>
    <th>Repository</th>
    <th>Purpose</th>
    <th>Who should read it</th>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/desktop"><strong>desktop</strong></a></td>
    <td>Official desktop client</td>
    <td>Users or developers who want to use, build, or modify the official client</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/protocol"><strong>protocol</strong></a></td>
    <td>AhaKey BLE protocol and client development reference</td>
    <td>Developers building their own clients, scripts, tools, or workflows</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/awesome-ahakey"><strong>awesome-ahakey</strong></a></td>
    <td>Community projects, tutorials, and workflow showcase</td>
    <td>People browsing remixes, forking projects, or submitting their own work</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/firmware"><strong>firmware</strong></a></td>
    <td>Firmware version notes, upgrade notes, and compatibility notes</td>
    <td>Users who want to understand firmware versions and upgrade information</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/.github"><strong>.github</strong></a></td>
    <td>Shared contribution rules, Issue / PR templates, and support information</td>
    <td>Contributors preparing to submit Issues, PRs, or community contributions</td>
  </tr>
</table>

</div>

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

### 1) I want to use the official desktop client

```text
Go to Releases
→ Download the latest version
→ Install the desktop client
→ Connect AhaKey
→ Start using it
```

Best for:

- users who only want to use AhaKey
- no code changes
- no development work
- downloading installers

Entry: [`desktop/releases`](https://github.com/AhakeyAI/desktop/releases)

---

### 2) I want to modify the official desktop client

```text
Go to desktop
→ Read the README
→ Fork the repository
→ Modify the code
→ Test locally
→ Submit a Pull Request
```

Best for:

- bug fixes
- UI improvements
- installation experience improvements
- macOS / Windows support improvements
- improvements to the official default experience

Entry: [`desktop`](https://github.com/AhakeyAI/desktop)

---

### 3) I want to build my own client / tool

```text
Go to protocol
→ Read the BLE protocol
→ Check examples
→ Create your own repo
→ Build a demo
→ Submit it to awesome-ahakey
```

Best for:

- your own macOS / Windows client
- Cursor / Claude / Codex workflow tools
- shortcut scripts
- OLED / RGB / config tools
- automation integrations

Entry: [`protocol`](https://github.com/AhakeyAI/protocol)

---

### 4) I want to explore and fork community remixes

```text
Go to awesome-ahakey
→ Find an interesting project
→ Read its README / Demo
→ Fork it or learn from it
→ Build your own remix
```

Best for:

- seeing how others use AhaKey
- finding existing tools and tutorials
- forking community projects
- learning from third-party clients or workflow implementations

Entry: [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

---

### 5) I built an independent project and want to share it

```text
Go to awesome-ahakey
→ Submit your project with the template
→ Get listed by the community
→ High-value features may later be evaluated for the official desktop
```

Best for:

- third-party clients
- utility scripts
- tutorials
- workflow presets
- desktop setup showcases
- video / article tutorials

Entry: [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

---

### 6) I found a bug

```text
Go to Issues
→ Describe the problem
→ Provide reproduction steps
→ Add environment info, logs, or screenshots
→ Wait for maintainer confirmation
```

Use Issues for:

- official client startup failures
- BLE connection problems
- reproducible feature bugs
- documentation errors
- build / installation failures
- unclear protocol fields

Common entries:

- Desktop issues: [`desktop/issues`](https://github.com/AhakeyAI/desktop/issues)
- Protocol issues: [`protocol/issues`](https://github.com/AhakeyAI/protocol/issues)

---

### 7) I have an idea and want to discuss it first

```text
Go to Discussions
→ Describe your idea / use case / workflow
→ Discuss with the community
→ Open an Issue or PR later if it becomes clear
```

Use Discussions for:

- uncertain questions
- new feature ideas
- AhaKey workflow discussions
- DIY build logs
- high-attention collaboration topics
- questions like “should this be built?” or “how should this be built?”

Entry: [`GitHub Discussions`](https://github.com/orgs/AhakeyAI/discussions)

---

## What are Issue / Discussion / PR / awesome-ahakey for?

| Type | Purpose | Best used for |
|---|---|---|
| Issue | Clear problems or concrete requests | bugs, documentation errors, reproducible problems, specific feature requests |
| Discussion | Open-ended discussion and idea incubation | workflows, ideas, uncertain questions, collaboration topics |
| Pull Request | Concrete changes | code changes, documentation changes, bug fixes, implemented features |
| awesome-ahakey | Community showcase | independent projects, third-party clients, scripts, tutorials, workflows, remixes |

Simple rule:

```text
Not sure → Discussion
Clear problem → Issue
Already changed something → Pull Request
Built an independent project → awesome-ahakey
```

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
