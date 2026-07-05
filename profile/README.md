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
  官方硬件 · 桌面客户端 · Developer Kit · Awesome AhaKey · 社区共创
</p>

<p align="center">
  <a href="https://github.com/AhakeyAI/desktop/releases"><img alt="release" src="https://img.shields.io/badge/Download-Releases-blue"></a>
  <a href="https://github.com/AhakeyAI/desktop"><img alt="desktop" src="https://img.shields.io/badge/Desktop-Official-5C6BC0"></a>
  <a href="https://github.com/AhakeyAI/protocol"><img alt="developer-kit" src="https://img.shields.io/badge/Developer%20Kit-BLE%20%2B%20SDK-26A69A"></a>
  <a href="https://github.com/AhakeyAI/awesome-ahakey"><img alt="awesome-ahakey" src="https://img.shields.io/badge/Awesome-AhaKey-43A047"></a>
  <a href="https://github.com/orgs/AhakeyAI/discussions"><img alt="discussion" src="https://img.shields.io/badge/Discuss-GitHub%20Discussions-orange"></a>
</p>

---

## AhaKey 是什么？

AhaKey 是一个面向 AI 编程与桌面工作流的开放硬件项目。

我们希望把键盘、语音输入、AI coding agent、桌面状态反馈和社区 workflow 连接起来，让开发者可以更自然地控制 Claude、Cursor、Codex 等 AI 编程工具。

AhaKey 不是只卖一个键盘，而是希望长期建设：

```text
硬件入口
→ 官方桌面客户端
→ AhaKey Developer Kit
→ 第三方客户端 / SDK 二创 / 自定义 HEX
→ Awesome AhaKey 社区项目
→ 更深度的产品共创与路线图反馈
```

---

## AhaKey 的开放共创机制

AhaKey 采用 **“开源客户端 + AhaKey Developer Kit + Awesome AhaKey 社区共创 + 受控生产级资料”** 的分层开放机制。

我们默认开放：

* 官方桌面客户端源码
* BLE 协议文档
* AhaKey X1 硬件 SDK
* 按键、拨杆、灯光、OLED 等开发接口
* examples 示例项目
* 自定义 HEX 构建和烧录参考
* Awesome AhaKey / 社区项目展示入口
* 第三方客户端、脚本、workflow、教程和 SDK demo 共创入口

普通开发者需要开发客户端、workflow、按键玩法、拨杆逻辑、灯效、OLED 显示或自定义 HEX 时，应优先查看 **AhaKey Developer Kit**：

👉 [`protocol`](https://github.com/AhakeyAI/protocol)

社区独立项目、教程、workflow、SDK demo、自定义 HEX 玩法展示，默认提交到 **Awesome AhaKey**：

👉 [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

如果你希望进一步参与固件代码完善、硬件产品技术开发、底层调试、生产级资料评估或更深度的产品共创，可以提交：

👉 [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source)

PCB layout、Gerber、BOM、生产测试资料、供应链资料、完整官方固件源码等生产级资料不默认通过公开仓库开放。确有深度合作、生产级调试或特殊研究需求时，请通过表单或官方联系方式进一步沟通。

> **AhaKey 尊重用户对自己设备的本地控制权。**
> 我们不会故意通过远程认证、云端锁定或固件更新，破坏已公开协议和 SDK 下的合理本地开发、第三方客户端使用和自定义玩法探索。

---

## 你来到这里，通常是想做这些事

### 入门版

| 你想做什么                              | 去哪里                                                                | 说明                                          |
| ---------------------------------- | ------------------------------------------------------------------ | ------------------------------------------- |
| 直接使用官方客户端                          | [`desktop/releases`](https://github.com/AhakeyAI/desktop/releases) | 下载官方桌面客户端安装包                                |
| 查看 / 修改官方桌面端源码                     | [`desktop`](https://github.com/AhakeyAI/desktop)                   | 官方桌面客户端源码，客户端贡献走这里                          |
| 自己做客户端 / 工具 / workflow             | [`protocol`](https://github.com/AhakeyAI/protocol)                 | 查看 BLE 协议、通信文档和 examples                    |
| 改按键、拨杆、灯光、OLED 或构建 HEX             | [`protocol`](https://github.com/AhakeyAI/protocol)                 | AhaKey Developer Kit，包含硬件 SDK 和自定义 HEX 构建说明 |
| 欣赏并 Fork 别人的二创                     | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)     | 查看社区项目、教程、workflow、SDK demo、桌面 setup        |
| 提交自己的项目 / 教程 / workflow / SDK demo | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)     | 独立项目和社区作品默认提交到这里                            |

### 进阶版

| 你想做什么                     | 去哪里                                                                                       | 说明                                                      |
| ------------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| 发现官方客户端 bug               | [`desktop/issues`](https://github.com/AhakeyAI/desktop/issues)                            | 提交明确问题、复现步骤、日志或截图                                       |
| 发现协议、SDK、examples 或构建文档问题 | [`protocol/issues`](https://github.com/AhakeyAI/protocol/issues)                          | 反馈 BLE 协议、SDK、构建脚本、自定义 HEX 相关问题                         |
| 有想法想先讨论                   | [`Discussions`](https://github.com/orgs/AhakeyAI/discussions)                             | 发起问题、想法、玩法、共创讨论                                         |
| 做了完整项目，想让更多人看到            | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)                            | 提交项目链接、截图、视频、使用说明和作者信息                                  |
| 查看官方固件版本和升级说明             | [`firmware`](https://github.com/AhakeyAI/firmware)                                        | 官方固件 release notes、升级说明和兼容性说明                           |
| 想参与固件 / 硬件深度共创            | [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source)                 | 如果你希望一起完善固件代码、补足硬件产品技术开发不足、参与更深度调试或共创，可以先提交表单，我们评估后再联系你 |
| 需要生产级硬件资料或特殊深度合作          | [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source) / 官方邮箱 / 企业微信客服 | PCB、BOM、Gerber、生产测试资料、供应链资料等不通过公开仓库默认提供，需要单独沟通评估        |

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
    <td>AhaKey Developer Kit：BLE 协议、硬件 SDK、examples、自定义 HEX 构建说明</td>
    <td>想做第三方客户端、workflow、SDK 二创或自定义 HEX 的开发者</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/awesome-ahakey"><strong>awesome-ahakey</strong></a></td>
    <td>社区项目、教程、workflow、SDK demo 展示</td>
    <td>想看二创、Fork 别人项目、提交自己作品的人</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/firmware"><strong>firmware</strong></a></td>
    <td>官方固件发布说明、升级说明和兼容性说明</td>
    <td>想查看官方固件版本、升级记录和设备兼容信息的人</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/.github"><strong>.github</strong></a></td>
    <td>组织级贡献规则、Issue / PR 模板、社区支持信息</td>
    <td>准备提交 Issue、PR 或参与社区协作的人</td>
  </tr>
</table>

</div>

---

## 社区贡献怎么分？

| 类型                                         | 默认去哪里                                                                     | 说明                        |
| ------------------------------------------ | ------------------------------------------------------------------------- | ------------------------- |
| 官方桌面客户端 bug / 功能改进                         | [`desktop`](https://github.com/AhakeyAI/desktop)                          | 官方客户端代码贡献走公开 PR           |
| BLE 协议文档 / SDK / examples / 构建脚本           | [`protocol`](https://github.com/AhakeyAI/protocol)                        | Developer Kit 相关内容走公开仓库   |
| 第三方客户端 / 脚本 / workflow / 教程                | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)            | 社区项目、教程和 workflow 默认提交到这里 |
| SDK demo / 自定义 HEX 玩法 / 按键、拨杆、灯光、OLED 二创展示 | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)            | 展示成果、教程和使用方式，不提交生产级硬件资料   |
| 官方固件发布说明、升级说明、兼容性文档                        | [`firmware`](https://github.com/AhakeyAI/firmware)                        | 仅用于官方固件版本和升级相关信息          |
| 固件代码完善、硬件技术共创、底层调试或深度合作                    | [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source) | 先提交表单，AhaKey 团队评估后再联系     |
| PCB layout / Gerber / BOM / 生产测试资料 / 供应链资料 | 官方邮箱 / 企业微信客服                                                             | 不默认通过公开仓库提供，需要单独沟通评估      |

---

## 推荐路径

### 1）我想直接使用官方客户端

```text
进入 desktop/releases
→ 下载最新版本
→ 安装桌面客户端
→ 连接 AhaKey
→ 开始使用
```

入口：[`desktop/releases`](https://github.com/AhakeyAI/desktop/releases)

---

### 2）我想自己做客户端 / 工具 / workflow

```text
进入 protocol
→ 阅读 BLE 协议和通信文档
→ 参考 examples
→ 创建自己的 repo
→ 做出 demo
→ 提交到 awesome-ahakey
```

适合：

* 自己写 macOS / Windows 客户端
* 做 Cursor / Claude / Codex 工作流工具
* 做快捷键脚本
* 做状态同步工具
* 做自动化集成

入口：[`protocol`](https://github.com/AhakeyAI/protocol)

---

### 3）我想改按键、拨杆、灯光、OLED 或构建自己的 HEX

```text
进入 protocol
→ 阅读 AhaKey Developer Kit README
→ 查看 sdk/README.md
→ 选择 buttons / toggle / lights / display 等模块
→ 参考 examples
→ 构建自己的 HEX
→ 本地烧录到正版 AhaKey X1 硬件
```

适合：

* 改四个按键行为
* 改拨杆逻辑
* 改灯光效果
* 改 OLED 显示
* 做自己的 AI 编程状态反馈
* 构建自定义开发者固件

入口：[`protocol`](https://github.com/AhakeyAI/protocol)

> 用户自己构建的 HEX 是自定义开发者固件，不等同于 AhaKey 官方固件。
> 请不要将自定义 HEX 描述为官方固件，也不要冒充官方发布版本。

---

### 4）我想修改官方桌面客户端

```text
进入 desktop
→ 阅读 README
→ Fork 仓库
→ 修改代码
→ 本地测试
→ 提交 Pull Request
```

适合：

* 修 bug
* 改 UI
* 优化安装体验
* 增加 macOS / Windows 适配
* 改进官方默认体验
* 改进桌面端与设备通信逻辑

入口：[`desktop`](https://github.com/AhakeyAI/desktop)

---

### 5）我做了一个独立版本，想分享给社区

```text
进入 awesome-ahakey
→ 按模板提交项目
→ 社区收录
→ 让更多用户看到、学习和 Fork
```

适合：

* 第三方客户端
* 工具脚本
* 使用教程
* 工作流 preset
* SDK demo
* 自定义 HEX 玩法展示
* 按键、拨杆、灯光、OLED 二创
* 桌面 setup 展示
* 视频 / 图文教程
* 非敏感硬件二创，例如外壳、键帽、支架、桌面 setup

入口：[`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

---

### 6）我想查看官方固件版本和升级说明

```text
进入 firmware
→ 查看 release notes
→ 阅读升级说明
→ 确认设备兼容性
→ 按官方说明升级
```

适合：

* 查看官方固件版本
* 查看升级说明
* 查看兼容性记录
* 查看官方确认过的固件说明

入口：[`firmware`](https://github.com/AhakeyAI/firmware)

---

### 7）我想参与固件 / 硬件深度共创

```text
进入 Hardware Source Access Program
→ 填写你的基本信息、GitHub 用户名和想参与的方向
→ 说明你希望完善的固件代码、硬件技术问题或共创内容
→ AhaKey 团队评估用途和匹配度
→ 如果适合，我们会进一步联系你
```

适合：

* 一起完善固件代码
* 补足硬件产品技术开发不足的地方
* 参与底层问题排查
* 参与硬件 / 固件技术共创
* 参与新硬件 / 新软件方向的技术讨论
* 需要更深度资料或生产级调试合作

入口：[`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source)

---

## Issue / Discussion / PR / awesome-ahakey 分别用来做什么？

| 类型                             | 用途                   | 适合什么时候用                                  |
| ------------------------------ | -------------------- | ---------------------------------------- |
| Issue                          | 明确问题或明确需求            | bug、文档错误、可复现问题、具体功能请求                    |
| Discussion                     | 开放讨论和想法孵化            | 玩法讨论、共创想法、不确定的问题、高关注度话题                  |
| Pull Request                   | 提交具体改动               | 代码修改、文档修改、bug fix、功能实现                   |
| protocol                       | Developer Kit 相关开发入口 | BLE 协议、SDK、examples、自定义 HEX 构建说明         |
| awesome-ahakey                 | 社区作品展示               | 独立项目、第三方客户端、脚本、教程、workflow、SDK demo、二创展示 |
| firmware                       | 官方固件说明               | 官方固件 release notes、升级说明、兼容性说明            |
| Hardware Source Access Program | 固件 / 硬件深度共创入口        | 固件代码完善、硬件技术共创、底层调试、生产级资料评估               |
| 官方邮箱 / 企业微信客服                  | 特殊问题或深度合作            | 商务合作、重要问题、受控资料泄露、售后支持                    |

简单理解：

```text
不确定 → 先 Discussion
明确问题 → 提 Issue
客户端 / 文档 / SDK 已改好 → 提 Pull Request
做了独立项目、workflow 或 SDK demo → 提到 awesome-ahakey
需要官方固件版本和升级说明 → 看 firmware
想参与固件 / 硬件深度共创 → 提交 Hardware Source Access Program
生产级资料或特殊合作 → 联系官方
```

---

## 社区维护入口

这些文件不是新的用户入口，而是 AhaKey 社区的基础维护规则。
普通用户不需要一开始全部阅读；当你准备提 Issue、PR、报告安全问题或参与社区协作时，再查看对应文档即可。

| 你想做什么                    | 看这里                                                                                      | 说明                         |
| ------------------------ | ---------------------------------------------------------------------------------------- | -------------------------- |
| 了解如何提交 Issue / PR / 社区项目 | [`CONTRIBUTING.md`](https://github.com/AhakeyAI/.github/blob/main/CONTRIBUTING.md)       | 贡献规则、PR 流程、哪些内容适合提交到官方或社区  |
| 遇到使用、构建、连接、协议、SDK 问题     | [`SUPPORT.md`](https://github.com/AhakeyAI/.github/blob/main/SUPPORT.md)                 | 遇到问题时该去哪个仓库、需要提供什么信息       |
| 报告安全问题、密钥泄露、隐私风险         | [`SECURITY.md`](https://github.com/AhakeyAI/.github/blob/main/SECURITY.md)               | 安全问题请不要公开发 Issue，按安全流程联系团队 |
| 了解社区基本行为规范               | [`CODE_OF_CONDUCT.md`](https://github.com/AhakeyAI/.github/blob/main/CODE_OF_CONDUCT.md) | 保持友好、尊重、建设性的社区协作氛围         |

---

## 贡献方式

你可以贡献：

* bug report
* 文档修正
* 安装教程
* macOS / Windows 客户端改进
* BLE 协议反馈
* SDK 使用反馈
* examples 改进
* 构建脚本改进
* 第三方客户端
* workflow / preset / 脚本
* SDK demo
* 自定义 HEX 玩法展示
* 按键、拨杆、灯光、OLED 二创
* 使用视频、截图、教程
* 非敏感硬件二创展示
* 固件 / 硬件技术共创建议

建议尽量保持：

* 小步提交
* 说明清楚
* 有截图 / 日志 / demo 更好
* 不提交密钥、token、私人文件
* 不提交无关二进制文件、安装包或编译产物
* 大功能先 Discussion，再 PR
* 不提交官方完整固件源码、PCB、Gerber、BOM、生产测试资料或供应链资料
* 涉及生产级资料、底层调试或特殊深度合作时，先提交 Hardware Source Access Program 表单

---

## 官方入口、问题反馈与社群

需要了解 AhaKey、下载软件、购买设备、加入讨论或联系官方，可以从下面这些入口开始。

| 入口                             | 链接                                                                                                         | 适合做什么                            |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------- | -------------------------------- |
| 官网                             | [ahakey.com](https://ahakey.com)                                                                           | 产品介绍、下载入口、社区说明                   |
| GitHub                         | [AhakeyAI](https://github.com/AhakeyAI)                                                                    | 开源代码、Developer Kit、Issue、PR、社区项目 |
| Discord                        | [AhaKey Discord](https://discord.gg/Nn48cJXa)                                                              | 海外用户交流、开发者讨论、快速反馈                |
| X / Twitter                    | [@AhaKeyAI](https://x.com/AhaKeyAI)                                                                        | 海外动态、产品更新、开发者内容                  |
| 哔哩哔哩                           | [AhaKey Bilibili](https://space.bilibili.com/2001376117?spm_id_from=333.1007.0.0)                          | 视频教程、产品演示、开发过程记录                 |
| 淘宝店                            | [AhaKey 淘宝店](https://shop277996828.taobao.com/?spm=pc_detail.30350276.shop_block.dshopinfo.5ad17dd6tWyean) | 购买设备、订单相关问题                      |
| Hardware Source Access Program | [ahakey.com/cn/hardware-source](https://ahakey.com/cn/hardware-source)                                     | 固件 / 硬件深度共创、技术开发合作、生产级资料评估       |
| 官方邮箱                           | [zhangxinyang@ahakey.cn](mailto:zhangxinyang@ahakey.cn)                                                    | 合作、反馈、社区问题、重要问题联系                |

### 问题该去哪里？

| 你遇到的问题                           | 推荐入口                                                                                    |
| -------------------------------- | --------------------------------------------------------------------------------------- |
| 官方客户端 bug、安装失败、连接异常              | `desktop` GitHub Issues                                                                 |
| BLE 协议、SDK、examples、自定义 HEX 构建问题 | `protocol` GitHub Issues / Discussions                                                  |
| 想讨论玩法、workflow、二创方向              | GitHub Discussions                                                                      |
| 想展示自己的二创项目、教程、脚本、SDK demo        | `awesome-ahakey`                                                                        |
| 查看官方固件版本、升级说明、兼容性说明              | `firmware`                                                                              |
| 购买、发货、售后、设备使用问题                  | 淘宝店 / 企业微信客服                                                                            |
| 中文用户日常交流                         | 微信群 / QQ 群 / 小红书群                                                                       |
| 海外用户交流                           | Discord / X                                                                             |
| 固件 / 硬件深度共创、技术开发合作、生产级资料评估       | [Hardware Source Access Program](https://ahakey.com/cn/hardware-source) / 官方邮箱 / 企业微信客服 |
| 安全问题、密钥泄露、受控资料泄露                 | 请勿公开发 Issue，联系官方邮箱                                                                      |

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
  Official Hardware · Desktop Client · Developer Kit · Awesome AhaKey · Community Collaboration
</p>

<p align="center">
  <a href="https://github.com/AhakeyAI/desktop/releases"><img alt="release" src="https://img.shields.io/badge/Download-Releases-blue"></a>
  <a href="https://github.com/AhakeyAI/desktop"><img alt="desktop" src="https://img.shields.io/badge/Desktop-Official-5C6BC0"></a>
  <a href="https://github.com/AhakeyAI/protocol"><img alt="developer-kit" src="https://img.shields.io/badge/Developer%20Kit-BLE%20%2B%20SDK-26A69A"></a>
  <a href="https://github.com/AhakeyAI/awesome-ahakey"><img alt="awesome-ahakey" src="https://img.shields.io/badge/Awesome-AhaKey-43A047"></a>
  <a href="https://github.com/orgs/AhakeyAI/discussions"><img alt="discussion" src="https://img.shields.io/badge/Discuss-GitHub%20Discussions-orange"></a>
</p>

---

## What is AhaKey?

AhaKey is an open hardware project for AI coding and desktop workflows.

We connect keyboards, voice input, AI coding agents, desktop status feedback, and community workflows, so developers can control Claude, Cursor, Codex, and similar tools more naturally.

AhaKey is not just a keyboard. We are building:

```text
Hardware entry point
→ Official desktop client
→ AhaKey Developer Kit
→ Third-party clients / SDK remixes / custom HEX
→ Awesome AhaKey community projects
→ Deeper product collaboration and roadmap feedback
```

---

## AhaKey open collaboration model

AhaKey follows a layered openness model: **open-source client + AhaKey Developer Kit + Awesome AhaKey community collaboration + controlled production-grade materials**.

We open the following by default:

* official desktop client source code
* BLE protocol documentation
* AhaKey X1 Hardware SDK
* button, toggle, light, and OLED development APIs
* example projects
* custom HEX build and flashing references
* Awesome AhaKey community showcase
* third-party client, script, workflow, tutorial, and SDK demo collaboration entry points

Developers building clients, workflows, button behavior, toggle logic, light effects, OLED display logic, or custom HEX files should start with **AhaKey Developer Kit**:

👉 [`protocol`](https://github.com/AhakeyAI/protocol)

Independent community projects, tutorials, workflows, SDK demos, and custom HEX showcases should be submitted to **Awesome AhaKey** by default:

👉 [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

If you want to help improve firmware code, fill technical gaps in hardware product development, join deeper debugging, or explore deeper product collaboration, you can submit:

👉 [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source)

PCB layout, Gerber, BOM, production test materials, supply-chain materials, and the full official firmware source are not provided through public repositories by default. For deep collaboration, production-level debugging, or special research needs, please contact AhaKey directly.

> **AhaKey respects users' local control over their own devices.**
> We will not intentionally use remote authentication, cloud lock-in, or firmware updates to break reasonable local development, third-party clients, or custom experiments built on published protocols and SDKs.

---

## Start here

### Beginner

| What do you want to do?                                  | Where to go                                                        | Notes                                                                  |
| -------------------------------------------------------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------- |
| Use the official desktop client                          | [`desktop/releases`](https://github.com/AhakeyAI/desktop/releases) | Download the official desktop client                                   |
| View / modify the official desktop source code           | [`desktop`](https://github.com/AhakeyAI/desktop)                   | Official desktop client source; client contributions go here           |
| Build your own client / tool / workflow                  | [`protocol`](https://github.com/AhakeyAI/protocol)                 | Read BLE protocol, communication docs, and examples                    |
| Customize buttons, toggle, lights, OLED, or build HEX    | [`protocol`](https://github.com/AhakeyAI/protocol)                 | AhaKey Developer Kit, including Hardware SDK and custom HEX build docs |
| Explore and fork community projects                      | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)     | Browse community projects, tutorials, workflows, SDK demos, and setups |
| Submit your own project / tutorial / workflow / SDK demo | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)     | Independent community work goes here by default                        |

### Advanced

| What do you want to do?                                           | Where to go                                                                                                | Notes                                                                                                                                                                                              |
| ----------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Report a desktop client bug                                       | [`desktop/issues`](https://github.com/AhakeyAI/desktop/issues)                                             | Submit clear reproduction steps, logs, or screenshots                                                                                                                                              |
| Report protocol, SDK, example, or build documentation issues      | [`protocol/issues`](https://github.com/AhakeyAI/protocol/issues)                                           | BLE protocol, SDK, build scripts, and custom HEX issues                                                                                                                                            |
| Start a discussion                                                | [`Discussions`](https://github.com/orgs/AhakeyAI/discussions)                                              | Share ideas, questions, use cases, or collaboration topics                                                                                                                                         |
| Share a complete community project                                | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)                                             | Submit links, screenshots, videos, usage notes, and author information                                                                                                                             |
| Read official firmware release and update notes                   | [`firmware`](https://github.com/AhakeyAI/firmware)                                                         | Official firmware release notes, update instructions, and compatibility notes                                                                                                                      |
| Join deeper firmware / hardware collaboration                     | [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source)                                  | If you want to help improve firmware code, fill technical gaps in hardware product development, or join deeper debugging and collaboration, submit the form first and we will follow up if it fits |
| Need production-grade hardware materials or special collaboration | [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source) / official email / WeCom support | PCB, BOM, Gerber, production test materials, and supply-chain materials are not provided through public repositories by default                                                                    |

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
    <td>AhaKey Developer Kit: BLE protocol, Hardware SDK, examples, and custom HEX build docs</td>
    <td>Developers building third-party clients, workflows, SDK remixes, or custom HEX files</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/awesome-ahakey"><strong>awesome-ahakey</strong></a></td>
    <td>Community projects, tutorials, workflows, and SDK demo showcase</td>
    <td>People browsing community projects or submitting their own work</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/firmware"><strong>firmware</strong></a></td>
    <td>Official firmware release notes, update instructions, and compatibility notes</td>
    <td>Users who want to check official firmware versions and update information</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AhakeyAI/.github"><strong>.github</strong></a></td>
    <td>Shared contribution rules, Issue / PR templates, and support information</td>
    <td>Contributors preparing to submit Issues, PRs, or community contributions</td>
  </tr>
</table>

</div>

---

## Community contributions

| Type                                                                                                   | Default place                                                             | Notes                                                                     |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Official desktop client bugs / improvements                                                            | [`desktop`](https://github.com/AhakeyAI/desktop)                          | Client code contributions go through public PRs                           |
| BLE protocol docs / SDK / examples / build scripts                                                     | [`protocol`](https://github.com/AhakeyAI/protocol)                        | Developer Kit changes go to the public repo                               |
| Third-party clients / scripts / workflows / tutorials                                                  | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)            | Community projects, tutorials, and workflows go here by default           |
| SDK demos / custom HEX projects / button, toggle, light, OLED remixes                                  | [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)            | Showcase results and usage notes, not production-grade hardware materials |
| Official firmware release notes, update docs, compatibility docs                                       | [`firmware`](https://github.com/AhakeyAI/firmware)                        | Official firmware version and update information only                     |
| Firmware code improvement, hardware technical collaboration, deeper debugging or special collaboration | [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source) | Submit the form first; the AhaKey team will follow up if it fits          |
| PCB layout / Gerber / BOM / production test materials / supply-chain materials                         | Official email / WeCom support                                            | Not provided through public repositories by default                       |

---

## Recommended paths

### 1) I want to use the official desktop client

```text
Go to desktop/releases
→ Download the latest version
→ Install the desktop client
→ Connect AhaKey
→ Start using it
```

Entry: [`desktop/releases`](https://github.com/AhakeyAI/desktop/releases)

---

### 2) I want to build my own client / tool / workflow

```text
Go to protocol
→ Read BLE protocol and communication docs
→ Check examples
→ Create your own repo
→ Build a demo
→ Submit it to awesome-ahakey
```

Best for:

* macOS / Windows third-party clients
* Cursor / Claude / Codex workflow tools
* shortcut scripts
* status sync tools
* automation integrations

Entry: [`protocol`](https://github.com/AhakeyAI/protocol)

---

### 3) I want to customize buttons, toggle, lights, OLED, or build my own HEX

```text
Go to protocol
→ Read the AhaKey Developer Kit README
→ Check sdk/README.md
→ Choose buttons / toggle / lights / display modules
→ Check examples
→ Build your own HEX
→ Flash it locally to genuine AhaKey X1 hardware
```

Best for:

* changing four-button behavior
* changing toggle logic
* changing light effects
* changing OLED display
* building your own AI coding status feedback
* building custom developer firmware

Entry: [`protocol`](https://github.com/AhakeyAI/protocol)

> User-built HEX files are custom developer firmware and are not official AhaKey firmware.
> Please do not describe custom HEX files as official firmware or use them to impersonate official releases.

---

### 4) I want to modify the official desktop client

```text
Go to desktop
→ Read the README
→ Fork the repository
→ Modify the code
→ Test locally
→ Submit a Pull Request
```

Best for:

* bug fixes
* UI improvements
* installation improvements
* macOS / Windows support
* official default experience improvements
* desktop-to-device communication improvements

Entry: [`desktop`](https://github.com/AhakeyAI/desktop)

---

### 5) I built an independent project and want to share it

```text
Go to awesome-ahakey
→ Submit your project with the template
→ Get listed by the community
→ Help more users discover, learn from, and fork it
```

Best for:

* third-party clients
* utility scripts
* tutorials
* workflow presets
* SDK demos
* custom HEX showcases
* button, toggle, light, and OLED remixes
* desk setup showcases
* video / written guides
* non-sensitive hardware remixes such as cases, keycaps, stands, and desk setups

Entry: [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

---

### 6) I want to read official firmware versions and update notes

```text
Go to firmware
→ Read release notes
→ Check update instructions
→ Confirm device compatibility
→ Update according to official docs
```

Best for:

* checking official firmware versions
* reading update instructions
* checking compatibility notes
* reading official firmware documentation

Entry: [`firmware`](https://github.com/AhakeyAI/firmware)

---

### 7) I want to join deeper firmware / hardware collaboration

```text
Go to Hardware Source Access Program
→ Fill in your basic information, GitHub username, and collaboration direction
→ Explain the firmware code, hardware technical gap, or product development issue you want to help with
→ AhaKey team reviews the purpose and fit
→ If it fits, we will contact you for the next step
```

Best for:

* helping improve firmware code
* filling technical gaps in hardware product development
* joining low-level issue debugging
* joining firmware / hardware technical collaboration
* joining early technical discussions for new hardware or software directions
* deeper materials or production-level debugging collaboration

Entry: [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source)

---

## What are Issue / Discussion / PR / awesome-ahakey for?

| Type                           | Purpose                                        | Best used for                                                                                                          |
| ------------------------------ | ---------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Issue                          | Clear problems or concrete requests            | bugs, documentation errors, reproducible problems, specific feature requests                                           |
| Discussion                     | Open-ended discussion and idea incubation      | workflows, ideas, uncertain questions, collaboration topics                                                            |
| Pull Request                   | Concrete changes                               | code changes, documentation changes, bug fixes, implemented features                                                   |
| protocol                       | Developer Kit development entry                | BLE protocol, SDK, examples, and custom HEX build docs                                                                 |
| awesome-ahakey                 | Community showcase                             | independent projects, third-party clients, scripts, tutorials, workflows, SDK demos, remixes                           |
| firmware                       | Official firmware docs                         | official firmware release notes, update instructions, and compatibility notes                                          |
| Hardware Source Access Program | Deeper firmware / hardware collaboration entry | firmware code improvement, hardware technical collaboration, low-level debugging, production-grade material evaluation |
| Official email / WeCom support | Special issues or deeper collaboration         | business collaboration, important issues, controlled material leaks, after-sales support                               |

Simple rule:

```text
Not sure → Discussion
Clear problem → Issue
Client / docs / SDK already changed → Pull Request
Built an independent project, workflow, or SDK demo → awesome-ahakey
Need official firmware versions or update notes → firmware
Want deeper firmware / hardware collaboration → submit Hardware Source Access Program
Production-grade materials or special collaboration → contact AhaKey
```

---

## Community maintenance files

These files are not extra entry points for new users.
They are the basic rules and support files that help keep the AhaKey community maintainable.

| What do you want to do?                                             | Read this                                                                                | Notes                                                                                 |
| ------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| Learn how to submit Issues, PRs, or community projects              | [`CONTRIBUTING.md`](https://github.com/AhakeyAI/.github/blob/main/CONTRIBUTING.md)       | Contribution rules, PR flow, and what belongs in official repos or community projects |
| Get help with usage, builds, connection, protocol, or SDK questions | [`SUPPORT.md`](https://github.com/AhakeyAI/.github/blob/main/SUPPORT.md)                 | Where to ask questions and what information to provide                                |
| Report security issues, leaked secrets, or privacy risks            | [`SECURITY.md`](https://github.com/AhakeyAI/.github/blob/main/SECURITY.md)               | Please do not open public Issues for security problems                                |
| Understand community behavior expectations                          | [`CODE_OF_CONDUCT.md`](https://github.com/AhakeyAI/.github/blob/main/CODE_OF_CONDUCT.md) | Keep the community friendly, respectful, and constructive                             |

---

## Ways to contribute

You can contribute:

* bug reports
* documentation improvements
* installation guides
* macOS / Windows client improvements
* BLE protocol feedback
* SDK usage feedback
* example improvements
* build script improvements
* third-party clients
* workflows / presets / scripts
* SDK demos
* custom HEX showcases
* button, toggle, light, and OLED remixes
* videos, screenshots, and tutorials
* non-sensitive hardware remix showcases
* firmware / hardware technical collaboration suggestions

Please try to keep contributions:

* small and reviewable
* clearly explained
* accompanied by screenshots / logs / demos when helpful
* free of secrets, tokens, or personal files
* free of unrelated binaries, installers, or build artifacts
* discussed first if the feature is large
* free of the full official firmware source, PCB, Gerber, BOM, production test materials, or supply-chain materials
* submitted through Hardware Source Access Program first when production-grade materials, low-level debugging, or special collaboration is involved

---

## Official links, feedback, and support

To learn about AhaKey, download software, buy the device, join discussions, or contact the team, start here.

| Entry                          | Link                                                                                                                | Best for                                                                                                          |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| Website                        | [ahakey.com](https://ahakey.com)                                                                                    | Product information, downloads, and community information                                                         |
| GitHub                         | [AhakeyAI](https://github.com/AhakeyAI)                                                                             | Source code, Developer Kit, Issues, PRs, community projects                                                       |
| Discord                        | [AhaKey Discord](https://discord.gg/Nn48cJXa)                                                                       | International community, developer discussions, quick feedback                                                    |
| X / Twitter                    | [@AhaKeyAI](https://x.com/AhaKeyAI)                                                                                 | Product updates, development notes, international posts                                                           |
| Bilibili                       | [AhaKey Bilibili](https://space.bilibili.com/2001376117?spm_id_from=333.1007.0.0)                                   | Videos, tutorials, product demos, development logs                                                                |
| Taobao Store                   | [AhaKey Taobao Store](https://shop277996828.taobao.com/?spm=pc_detail.30350276.shop_block.dshopinfo.5ad17dd6tWyean) | Purchase, orders, device-related questions                                                                        |
| Hardware Source Access Program | [ahakey.com/cn/hardware-source](https://ahakey.com/cn/hardware-source)                                              | Deeper firmware / hardware collaboration, technical development partnership, production-grade material evaluation |
| Email                          | [zhangxinyang@ahakey.cn](mailto:zhangxinyang@ahakey.cn)                                                             | Collaboration, feedback, community issues, important contact                                                      |

### Where should I ask?

| What you need                                                                                                     | Recommended place                                                                                        |
| ----------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Official client bugs, installation failures, connection issues                                                    | `desktop` GitHub Issues                                                                                  |
| BLE protocol, SDK, examples, custom HEX build issues                                                              | `protocol` GitHub Issues / Discussions                                                                   |
| Workflow, remix, or project ideas                                                                                 | GitHub Discussions                                                                                       |
| Sharing your own project, tutorial, script, or SDK demo                                                           | `awesome-ahakey`                                                                                         |
| Official firmware versions, update notes, compatibility docs                                                      | `firmware`                                                                                               |
| Purchase, shipping, after-sales, device usage                                                                     | Taobao / WeCom support                                                                                   |
| Chinese community discussion                                                                                      | WeChat / QQ / Xiaohongshu groups                                                                         |
| International community discussion                                                                                | Discord / X                                                                                              |
| Deeper firmware / hardware collaboration, technical development partnership, production-grade material evaluation | [Hardware Source Access Program](https://ahakey.com/cn/hardware-source) / official email / WeCom support |
| Security issues, leaked secrets, controlled material leaks                                                        | Do not open a public Issue; contact the official email                                                   |

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
