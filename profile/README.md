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

## AhaKey 的开放共创机制

AhaKey 采用 **“开源软件 + 开放协议 + 社区共创 + 受控硬件资料”** 的分层开放机制。

我们默认开放官方桌面客户端源码、BLE 协议文档、客户端开发示例和社区项目展示入口，鼓励用户基于公开协议开发自己的客户端、脚本、工具和 AI workflow。

固件源码、硬件设计文件、PCB、BOM 和生产资料不默认公开。如确有学习、调试、研究或共创需要，可以通过官方申请入口提交申请。

> **AhaKey 尊重用户对自己设备的本地控制权。**  
> 我们不会故意通过远程认证、云端锁定或固件更新，破坏已公开协议下的合理本地开发和第三方客户端使用。

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
| 我想申请固件源码 / 硬件资料 | [`Permission`](https://ahakey.com/cn/hardware-source/apply) | 固件源码、硬件设计文件、生产资料不默认公开，需要单独申请 |

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

## 社区维护入口

这些文件不是新的用户入口，而是 AhaKey 社区的基础维护规则。  
普通用户不需要一开始全部阅读；当你准备提 Issue、PR、报告安全问题或参与社区协作时，再查看对应文档即可。

| 你想做什么 | 看这里 | 说明 |
|---|---|---|
| 了解如何提交 Issue / PR / 社区项目 | [`CONTRIBUTING.md`](https://github.com/AhakeyAI/.github/blob/main/CONTRIBUTING.md) | 贡献规则、PR 流程、哪些内容适合提交到官方或社区 |
| 遇到使用、构建、连接、协议问题 | [`SUPPORT.md`](https://github.com/AhakeyAI/.github/blob/main/SUPPORT.md) | 遇到问题时该去哪个仓库、需要提供什么信息 |
| 报告安全问题、密钥泄露、隐私风险 | [`SECURITY.md`](https://github.com/AhakeyAI/.github/blob/main/SECURITY.md) | 安全问题请不要公开发 Issue，按安全流程联系团队 |
| 了解社区基本行为规范 | [`CODE_OF_CONDUCT.md`](https://github.com/AhakeyAI/.github/blob/main/CODE_OF_CONDUCT.md) | 保持友好、尊重、建设性的社区协作氛围 |

简单理解：

```text
想贡献 → CONTRIBUTING
遇到问题 → SUPPORT
安全问题 → SECURITY
社区行为规范 → CODE_OF_CONDUCT
```

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

## 本地优先与第三方客户端

AhaKey 鼓励用户基于公开 BLE 协议开发自己的客户端、脚本、工具和 workflow。

我们会尽量保持公开协议的稳定性和可理解性，并通过文档、示例代码和社区项目帮助开发者进行二次开发。

> **我们不会故意通过远程认证、云端锁定或固件更新，破坏已公开协议下的合理本地开发和第三方客户端使用。**

如果协议未来需要调整，我们会尽量通过文档、版本说明和社区讨论提前说明变化。

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

如果你的项目确实需要访问这些资料，请先提交 [`Permission`](https://ahakey.com/cn/hardware-source/apply)。

未经授权，不得使用受控资料自行打板、仿制、量产、销售或开发竞争性硬件产品。

---

## 官方入口、问题反馈与社群

如果你想了解 AhaKey、下载软件、购买设备、加入讨论或联系官方，可以从下面这些入口开始。

| 入口 | 链接 | 适合做什么 |
|---|---|---|
| 官网 | [ahakey.com](https://ahakey.com) | 产品介绍、下载入口、社区说明、硬件源码申请 |
| GitHub | [AhakeyAI](https://github.com/AhakeyAI) | 开源代码、协议文档、Issue、PR、社区项目 |
| Discord | [AhaKey Discord](https://discord.gg/Nn48cJXa) | 海外用户交流、开发者讨论、快速反馈 |
| X / Twitter | [@zhngxnyng199073](https://x.com/zhngxnyng199073) | 海外动态、产品更新、开发者内容 |
| 哔哩哔哩 | [AhaKey Bilibili](https://space.bilibili.com/2001376117?spm_id_from=333.1007.0.0) | 视频教程、产品演示、开发过程记录 |
| 淘宝店 | [AhaKey 淘宝店](https://shop277996828.taobao.com/?spm=pc_detail.30350276.shop_block.dshopinfo.5ad17dd6tWyean) | 购买设备、订单相关问题 |
| 官方邮箱 | [zhangxinyang@ahakey.cn](mailto:zhangxinyang@ahakey.cn) | 合作、反馈、社区问题、重要问题联系 |

### 问题该去哪里？

| 你遇到的问题 | 推荐入口 |
|---|---|
| 官方客户端 bug、安装失败、连接异常 | GitHub Issues |
| 协议开发、第三方客户端、workflow 想法 | GitHub Discussions |
| 想展示自己的二创项目、教程、脚本 | awesome-ahakey |
| 购买、发货、售后、设备使用问题 | 淘宝店 / 企业微信客服 |
| 中文用户日常交流 | 微信群 / QQ 群 / 小红书群 |
| 海外用户交流 | Discord / X |
| 安全问题、密钥泄露、受控资料泄露 | 请勿公开发 Issue，联系官方邮箱 |

<details>
<summary><strong>扫码加入中文社群 / 联系客服</strong></summary>

<br>

<div align="center">

<table>
  <tr>
    <th>微信公众号</th>
    <th>微信讨论群</th>
    <th>QQ 讨论群</th>
  </tr>
  <tr>
    <td align="center"><img src="./assets/qr/wechat-official-account.png" width="150"><br>关注公众号</td>
    <td align="center"><img src="./assets/qr/wechat-group.png" width="150"><br>加入微信讨论群</td>
    <td align="center"><img src="./assets/qr/qq-group.png" width="150"><br>加入 QQ 讨论群</td>
  </tr>
  <tr>
    <th>小红书群</th>
    <th>企业微信客服</th>
    <th>更多入口</th>
  </tr>
  <tr>
    <td align="center"><img src="./assets/qr/xhs-group.png" width="150"><br>加入小红书群</td>
    <td align="center"><img src="./assets/qr/wecom-support.png" width="150"><br>联系专人客服</td>
    <td align="center"><a href="https://ahakey.com">ahakey.com</a><br>官网与下载入口</td>
  </tr>
</table>

</div>

</details>

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

## AhaKey open collaboration model

AhaKey follows a layered openness model: **open-source software + open protocol + community collaboration + controlled hardware materials**.

We open the official desktop client source code, BLE protocol documentation, client development examples, and community project showcase entry points by default. We encourage developers to build their own clients, scripts, tools, and AI workflows based on the public protocol.

Firmware source code, hardware design files, PCB files, BOM, and production materials are not public by default. If you need them for learning, debugging, research, or collaboration, you can submit a request through the official application page.

> **AhaKey respects users' local control over their own devices.**  
> We will not intentionally use remote authentication, cloud lock-in, or firmware updates to break reasonable local development or third-party clients built on published protocols.

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
| Request firmware source / hardware materials | [`Permission`](https://ahakey.com/cn/hardware-source/apply) | Firmware source and hardware files are not public by default |

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

## Community maintenance files

These files are not extra entry points for new users.  
They are the basic rules and support files that help keep the AhaKey community maintainable.

You do not need to read all of them at the beginning.  
Check the relevant file when you are ready to submit an Issue, open a Pull Request, report a security issue, or participate in community collaboration.

| What do you want to do? | Read this | Notes |
|---|---|---|
| Learn how to submit Issues, PRs, or community projects | [`CONTRIBUTING.md`](https://github.com/AhakeyAI/.github/blob/main/CONTRIBUTING.md) | Contribution rules, PR flow, and what belongs in official repos or community projects |
| Get help with usage, builds, connection, or protocol questions | [`SUPPORT.md`](https://github.com/AhakeyAI/.github/blob/main/SUPPORT.md) | Where to ask questions and what information to provide |
| Report security issues, leaked secrets, or privacy risks | [`SECURITY.md`](https://github.com/AhakeyAI/.github/blob/main/SECURITY.md) | Please do not open public Issues for security problems |
| Understand community behavior expectations | [`CODE_OF_CONDUCT.md`](https://github.com/AhakeyAI/.github/blob/main/CODE_OF_CONDUCT.md) | Keep the community friendly, respectful, and constructive |

Simple rule:

```text
Want to contribute → CONTRIBUTING
Need help → SUPPORT
Security issue → SECURITY
Community behavior → CODE_OF_CONDUCT
```

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

## Local-first and third-party clients

AhaKey encourages users to build their own clients, scripts, tools, and workflows based on the public BLE protocol.

We try to keep the public protocol stable and understandable, and we support secondary development through documentation, example code, and community projects.

> **We will not intentionally use remote authentication, cloud lock-in, or firmware updates to break reasonable local development or third-party clients built on published protocols.**

If the protocol needs to change in the future, we will try to communicate the changes through documentation, version notes, and community discussions.

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

If your project really requires access, please submit a [`Permission`](https://ahakey.com/cn/hardware-source/apply).

Without authorization, controlled materials may not be used for board reproduction, cloning, manufacturing, resale, or development of competing hardware products.

---

## Official links, feedback, and support

If you want to learn about AhaKey, download software, buy the device, join discussions, or contact the team, start here.

| Entry | Link | Best for |
|---|---|---|
| Website | [ahakey.com](https://ahakey.com) | Product information, downloads, community info, hardware source request |
| GitHub | [AhakeyAI](https://github.com/AhakeyAI) | Source code, protocol docs, Issues, PRs, community projects |
| Discord | [AhaKey Discord](https://discord.gg/Nn48cJXa) | International community, developer discussions, quick feedback |
| X / Twitter | [@zhngxnyng199073](https://x.com/zhngxnyng199073) | Product updates, development notes, international posts |
| Bilibili | [AhaKey Bilibili](https://space.bilibili.com/2001376117?spm_id_from=333.1007.0.0) | Videos, tutorials, product demos, development logs |
| Taobao Store | [AhaKey Taobao Store](https://shop277996828.taobao.com/?spm=pc_detail.30350276.shop_block.dshopinfo.5ad17dd6tWyean) | Purchase, orders, device-related questions |
| Email | [zhangxinyang@ahakey.cn](mailto:zhangxinyang@ahakey.cn) | Collaboration, feedback, community issues, important contact |

### Where should I ask?

| What you need | Recommended place |
|---|---|
| Official client bugs, installation failures, connection issues | GitHub Issues |
| Protocol development, third-party clients, workflow ideas | GitHub Discussions |
| Sharing your own remix, tutorial, script, or workflow | awesome-ahakey |
| Purchase, shipping, after-sales, device usage | Taobao / WeCom support |
| Chinese community discussion | WeChat / QQ / Xiaohongshu groups |
| International community discussion | Discord / X |
| Security issues, leaked secrets, controlled material leaks | Do not open a public Issue; contact the official email |

<details>
<summary><strong>Chinese community QR codes / support contact</strong></summary>

<br>

<div align="center">

<table>
  <tr>
    <th>WeChat Official Account</th>
    <th>WeChat Group</th>
    <th>QQ Group</th>
  </tr>
  <tr>
    <td align="center"><img src="./assets/qr/wechat-official-account.png" width="150"><br>Follow us</td>
    <td align="center"><img src="./assets/qr/wechat-group.png" width="150"><br>Join WeChat group</td>
    <td align="center"><img src="./assets/qr/qq-group.png" width="150"><br>Join QQ group</td>
  </tr>
  <tr>
    <th>Xiaohongshu Group</th>
    <th>WeCom Support</th>
    <th>More</th>
  </tr>
  <tr>
    <td align="center"><img src="./assets/qr/xhs-group.png" width="150"><br>Join Xiaohongshu group</td>
    <td align="center"><img src="./assets/qr/wecom-support.png" width="150"><br>Contact support</td>
    <td align="center"><a href="https://ahakey.com">ahakey.com</a><br>Website and downloads</td>
  </tr>
</table>

</div>

</details>

<p align="right"><a href="#top">↑ Back to top</a></p>
