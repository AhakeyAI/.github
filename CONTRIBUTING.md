<a id="top"></a>

<p align="center">
  <a href="#zh-cn"><strong>简体中文</strong></a> ·
  <a href="#en"><strong>English</strong></a>
</p>

---

<a id="zh-cn"></a>

# 参与 AhaKey 共创

感谢你参与 AhaKey 社区。

这份文档说明：**如何提交贡献、如何协作、贡献如何被认可、GitHub 权限如何处理，以及不同类型贡献应该进入哪个仓库**。

如果你还不确定应该去哪个仓库、应该看 `desktop`、`protocol`、`awesome-ahakey` 还是 `firmware`，请先从组织首页开始：

👉 [`AhaKey Community`](https://github.com/AhakeyAI)

---

## 1. 当前维护分工

AhaKey 目前由一个小型维护团队维护。不同类型的贡献会由不同成员参与处理。

| 成员            | 主要角色                            | 负责内容                                                            |
| ------------- | ------------------------------- | --------------------------------------------------------------- |
| Ann           | Official Product Software Lead  | 负责官方产品软件的持续迭代。涉及最终进入官方 `desktop` 版本的功能，需要由 Ann 进行产品与软件方向把关。     |
| ZephyrKeXiner | Code Review & Merge Maintainer  | 负责合并上来的代码审查、PR Review、合并判断和仓库代码质量把关。                            |
| Vivian        | Community Operations Maintainer | 负责社区维护、用户引导、Discussion / Issue 运营、`awesome-ahakey` 项目收录和社区协作统筹。 |

说明：

* 一般问题和想法可以先进入 Issue 或 Discussion。
* 代码和文档 PR 会由维护者 Review。
* 官方桌面客户端相关贡献优先进入 `desktop`。
* BLE 协议、SDK、examples、自定义 HEX 构建说明相关贡献优先进入 `protocol`。
* 社区独立项目、教程、workflow、SDK demo 和自定义 HEX 玩法展示优先进入 `awesome-ahakey`。
* 官方固件发布说明、升级说明、兼容性说明进入 `firmware`。
* 涉及官方产品方向、默认体验或最终并入官方版本的功能，会由官方产品软件负责人进一步确认。

---

## 2. 新贡献者默认流程

大多数新贡献者没有 AhaKey 官方仓库的写权限。

默认流程是：

```text
Fork 官方仓库
→ 在自己的 Fork 里创建分支
→ 修改代码或文档
→ Push 到自己的 Fork
→ 向 AhaKey 官方仓库提交 Pull Request
→ 等待维护者 Review
→ 通过后由维护者合并
```

也就是说，新贡献者通常是在自己的 Fork 里创建分支，**不是在 AhaKey 官方仓库里创建分支**。

如果你只是做了一个独立项目、教程、workflow、SDK demo 或自定义 HEX 玩法展示，不一定需要把代码合进官方仓库。你可以优先提交到：

👉 [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

---

## 3. 核心规则

**不要直接 push 到 `main`。**

所有改动建议经过：

```text
Branch
→ Pull Request
→ Review
→ Merge
```

即使是长期贡献者，也应该通过 PR 协作。

请不要把下面这些内容直接提交到公开仓库：

* API Key、Token、私钥、个人配置文件
* 无关二进制文件、安装包或编译产物
* 未说明来源的第三方代码或资源
* 官方完整固件源码
* PCB、Gerber、BOM、生产测试资料、供应链资料
* 可用于仿制、打板、量产或开发竞争性硬件的生产级资料

---

## 4. 分支命名建议

请保持分支名称简单、清晰、可读。

推荐前缀：

```text
feat/...
fix/...
docs/...
chore/...
refactor/...
sdk/...
example/...
```

示例：

```text
feat/macos-status-widget
fix/windows-ble-reconnect
docs/install-guide-update
sdk/button-api-cleanup
example/light-status-demo
chore/release-note-cleanup
```

---

## 5. Pull Request 规则

### 一个 PR 只解决一个问题

请尽量保持 PR 聚焦，不要把互不相关的改动混在一起。

好的 PR 示例：

* 改进一篇安装说明
* 补清楚一段协议文档
* 修复一个可复现 bug
* 增加一个社区项目条目
* 增加一个最小 example
* 改进 SDK README
* 修正自定义 HEX 构建说明
* 增加一个按键 / 拨杆 / 灯光 / OLED demo

### PR 标题建议

```text
docs: improve Windows install guide
fix: clarify BLE reconnect behavior
feat: add macOS build notes
sdk: clarify button callback API
example: add OLED status demo
chore: update release documentation
```

### 提交 PR 前请确认

* [ ] PR 目的清楚
* [ ] 修改范围聚焦
* [ ] 已经本地测试，或说明为什么无法测试
* [ ] 涉及 UI、连接、设备行为时提供截图或日志
* [ ] 涉及 SDK、examples、自定义 HEX 构建时说明测试环境和构建结果
* [ ] 涉及文档时保证链接有效
* [ ] 不提交 API Key、Token、私钥或个人配置
* [ ] 不提交无关二进制文件、安装包或编译产物
* [ ] 不提交官方完整固件源码、PCB、Gerber、BOM、生产测试资料或供应链资料
* [ ] 大功能、协议变更、SDK API 变化、默认行为变化已经先开 Issue 或 Discussion

---

## 6. 什么时候应该先讨论？

如果你不确定改动是否应该进入官方仓库，请先开 Issue 或 Discussion。

尤其是这些情况：

* 新功能方向不确定
* 改动影响默认体验
* 改动涉及 BLE 协议行为
* 改动涉及 SDK API 或 examples 结构
* 改动涉及自定义 HEX 构建流程
* 改动涉及桌面端兼容性
* 改动涉及 release 或仓库结构
* 改动比较大，Review 成本较高
* 个人 workflow、第三方工具或自定义固件玩法，不确定是否应该合进官方
* 涉及固件 / 硬件深度共创、底层调试或生产级资料评估

简单理解：

```text
不确定 → 先 Discussion
明确问题 → 提 Issue
已经改好 → 提 Pull Request
独立作品 / SDK demo / 自定义 HEX 玩法 → 提到 awesome-ahakey
固件 / 硬件深度共创 → 提交 Hardware Source Access Program
```

---

## 7. 社区作品

如果你做的是独立客户端、工具、脚本、教程、workflow、SDK demo、自定义 HEX 玩法、按键 / 拨杆 / 灯光 / OLED 二创，通常不需要直接合进官方 `desktop`。

请优先提交到：

👉 [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

社区项目可以独立存在。优秀项目后续可以再讨论是否进入官方版本、官方 examples、官方文档或产品路线图。

适合提交到 `awesome-ahakey` 的内容包括：

* 第三方客户端
* 工具脚本
* 使用教程
* workflow preset
* SDK demo
* 自定义 HEX 玩法展示
* 按键、拨杆、灯光、OLED 二创
* 桌面 setup 展示
* 视频 / 图文教程
* 非敏感硬件二创，例如外壳、键帽、支架、桌面 setup

如果你改的是 `protocol` 仓库里的 SDK、协议文档、examples 或构建脚本，则可以向 `protocol` 提交 Pull Request。

---

## 8. 贡献者认可

AhaKey 对贡献的回报，不只是“感谢”和“署名”。

我们希望让真正参与共创的人获得：**被看见、被记录、被邀请体验新产品、参与路线图、影响官方产品方向**的机会。

这些权益不是自动兑换，也不是固定承诺，而是 AhaKey 对长期、高质量贡献者的优先支持和认可。

| 身份                            | 如何达到                                                     | 你会获得什么                                                                                                                    |
| ----------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Community Member              | 使用 AhaKey，参与 Issue / Discussion                          | 参与社区讨论；获得基础答疑；有机会参与公开测试和用户反馈收集。                                                                                           |
| Maker                         | 作品、教程、workflow、SDK demo 或自定义 HEX 玩法被 `awesome-ahakey` 收录 | 作者署名；项目展示；社区周报 / 官网 / 社群推荐机会；可使用 **AhaKey Maker** 头衔；优先参与软件和 SDK 新功能体验。                                                   |
| Contributor                   | PR 被合并，或高质量反馈推动项目改进                                      | Release notes 鸣谢；Contributor Wall 展示机会；PR 优先 Review；优先参与官方客户端、协议能力、SDK、examples、新 workflow 的内测；视贡献情况获得 AhaKey 周边、配件或设备优惠。 |
| Core Contributor / Maintainer | 长期稳定贡献，并被维护者邀请                                           | 参与路线图讨论；参与新硬件 / 新软件方向的早期评审；可成为某个方向的 owner / maintainer；视情况获得原型机、测试机、免费内测设备或联合共创署名机会。                                      |

我们也可能为特别优秀的社区成员设置更具荣誉感的社区称号，例如：

* **AhaKey Maker**
* **AhaKey SDK Pioneer**
* **AhaKey Workflow Pioneer**
* **AhaKey Core Contributor**
* **AhaKey Community Maintainer**
* **AhaKey Chief Workflow Officer**，用于特别活跃、长期推动某类工作流生态的共创者

GitHub 仓库权限不会自动授予。权限只会在有明确维护需要、长期信任和双方意愿时，由维护者邀请并按最小权限授予。

---

## 9. GitHub 权限说明

新贡献者默认使用：

```text
Fork → Branch in your fork → Pull Request
```

被邀请的 Core Contributor 可能会获得指定仓库的 `Write` 权限。

Maintainer 可能会获得指定仓库或方向的 `Maintain` 权限。

无论是否拥有写权限，都不应直接 push 到 `main`。

如果你只想提交独立项目、教程、workflow、SDK demo 或自定义 HEX 玩法，通常不需要官方仓库写权限，提交到 `awesome-ahakey` 即可。

---

## 10. Review 预期

AhaKey 目前由小团队维护，我们会尽量定期查看 Issue、Discussion 和 PR。

请理解：

* PR 不一定会立即 Review；
* 大功能可能需要先讨论方向；
* 不适合官方版本的功能，可能会被建议放到 `awesome-ahakey`；
* SDK API、BLE 协议、examples 或自定义 HEX 构建相关改动，可能需要更多测试或兼容性确认；
* 维护者可能会要求补充测试、截图、日志、构建结果或文档。

我们鼓励小而清晰的贡献，这类贡献通常更容易被 Review 和合并。

---

## 11. 开源协议

AhaKey 的不同仓库和资料采用不同开放策略。

| 内容                                        | 开放方式                                                    |
| ----------------------------------------- | ------------------------------------------------------- |
| 官方桌面客户端代码                                 | 以 `desktop` 仓库的 `LICENSE` 文件为准                          |
| AhaKey Developer Kit 中的公开文档、头文件、示例代码、构建脚本 | 以 `protocol` 仓库的 `LICENSE` 文件为准，当前采用 Apache License 2.0 |
| `protocol` 中的二进制核心运行库                     | 以 `sdk/core/BINARY_LICENSE.md` 为准                       |
| README、教程类内容                              | 以对应仓库声明为准；如果没有额外说明，优先遵循该仓库的 `LICENSE`                   |
| 社区项目、第三方工具、workflow、SDK demo              | 由项目作者自行选择许可证，`awesome-ahakey` 仅做收录展示                    |
| 官方固件 release notes、升级说明、兼容性说明             | 以 `firmware` 仓库声明为准                                     |
| 官方完整固件源码、硬件设计文件、生产资料                      | 不默认公开，采用表单评估、受控开放或单独书面授权                                |
| 第三方依赖、芯片厂商 SDK、工具链、供应商库                   | 遵守其原始许可证和版权声明                                           |

请注意：

* 开源仓库的具体授权以该仓库根目录中的 `LICENSE` 文件为准。
* 如果某个仓库没有明确 LICENSE，请不要默认认为它可以被自由复制、商用或再分发。
* 用户自己构建的 HEX 是自定义开发者固件，不等同于 AhaKey 官方固件。
* 固件源码、硬件设计文件和生产资料即使向特定开发者开放，也不等于允许公开传播、网络分发、仿制、打板、量产或销售。
* 商业硬件合作、OEM、ODM、批量生产、对外销售等情况，需要单独取得书面授权。

---

## 12. 原创性与第三方代码

AhaKey 官方仓库中的核心代码和产品设计由 AhaKey 团队自主设计和开发，并非基于某个现有项目 fork、改名或二次包装而来。

我们重视开源许可证和原创性。如果仓库中使用第三方依赖、系统 SDK、开源库、示例代码、芯片厂商 SDK、工具链或外部资源，应遵守其原始许可证，并在相关文件中保留必要的版权和许可证声明。

贡献者提交 PR 时，请确保：

* 你有权提交相关代码、文档或资源；
* 不要直接复制不兼容许可证的第三方代码；
* 不要移除第三方版权声明或许可证信息；
* 如果引用外部资料，请在 PR 中说明来源；
* 不要提交公司内部代码、客户代码、受限资料或未经授权的硬件 / 固件资料；
* 不要把第三方芯片 SDK、工具链或供应商库错误声明为 AhaKey 自有开源代码。

---

## 13. 固件 / 硬件深度共创与生产级资料

AhaKey 鼓励用户基于公开的 AhaKey Developer Kit 参与开发和二创。

普通开发者如果想做以下事情，应优先使用公开 `protocol` 仓库：

* 阅读 BLE 协议
* 开发第三方客户端
* 使用 SDK 改四个按键、拨杆、灯光、OLED
* 构建自己的自定义 HEX
* 参考 examples 做自己的玩法
* 将项目提交到 `awesome-ahakey` 展示

以下资料不默认通过公开仓库提供：

* 官方完整固件源码
* 硬件原理图、PCB、Gerber、BOM
* 生产测试资料
* 供应链资料
* 官方设备内部实现细节
* 可用于仿制、打板、量产、销售的生产级硬件资料

如果你希望进一步参与：

* 一起完善固件代码
* 补足硬件产品技术开发不足的地方
* 参与底层问题排查
* 参与硬件 / 固件技术共创
* 参与新硬件 / 新软件方向的技术讨论
* 申请更深度资料或生产级调试合作

请先提交：

👉 [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source)

AhaKey 团队会根据用途、风险、贡献方向和合作匹配度进行评估。如果适合，我们会进一步联系你。

未经授权，不得将受控资料公开上传、网络分发、转发、出售、共享，不得用于自行打板、仿制、量产、销售或开发竞争性硬件产品。

<p align="right"><a href="#top">↑ Back to top</a></p>

---

<a id="en"></a>

# Contributing to AhaKey

Thank you for contributing to AhaKey.

This document explains **how to contribute, how collaboration works, how contributions are recognized, how GitHub permissions are handled, and where different types of contributions should go**.

If you are not sure which repository to visit first, please start from the organization homepage:

👉 [`AhaKey Community`](https://github.com/AhakeyAI)

---

## 1. Current maintainers

AhaKey is currently maintained by a small team. Different types of contributions may be reviewed by different maintainers.

| Member        | Main role                       | Responsibility                                                                                                                                                                           |
| ------------- | ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Ann           | Official Product Software Lead  | Leads ongoing official product software iteration. Features that may eventually become part of the official `desktop` version need final product and software direction review from Ann. |
| ZephyrKeXiner | Code Review & Merge Maintainer  | Reviews incoming code, evaluates PR quality, and helps decide whether changes should be merged.                                                                                          |
| Vivian        | Community Operations Maintainer | Maintains community operations, guides users, coordinates Discussions / Issues, curates `awesome-ahakey`, and supports community collaboration.                                          |

Notes:

* General questions and ideas should start from Issues or Discussions.
* Code and documentation PRs will be reviewed by maintainers.
* Official desktop client contributions should go to `desktop`.
* BLE protocol, SDK, examples, and custom HEX build documentation should go to `protocol`.
* Community projects, tutorials, workflows, SDK demos, and custom HEX showcases should go to `awesome-ahakey`.
* Official firmware release notes, update instructions, and compatibility notes should go to `firmware`.
* Features that affect official product direction, default experience, or the official version may require final review from the official product software lead.

---

## 2. Default workflow for new contributors

Most new contributors do not have write access to official AhaKey repositories.

The default workflow is:

```text
Fork the official repository
→ Create a branch in your fork
→ Make code or documentation changes
→ Push to your fork
→ Open a Pull Request to the official AhaKey repository
→ Wait for maintainer review
→ Maintainers merge after approval
```

In other words, new contributors usually create branches in their own forks, **not in the official AhaKey repositories**.

If you built an independent project, tutorial, workflow, SDK demo, or custom HEX showcase, it may not need to be merged into an official repository. You can submit it to:

👉 [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

---

## 3. Core rule

**Do not push directly to `main`.**

All changes should go through:

```text
Branch
→ Pull Request
→ Review
→ Merge
```

Even long-term contributors should collaborate through Pull Requests.

Please do not submit the following to public repositories:

* API keys, tokens, private keys, or personal configuration
* unrelated binaries, installers, or build artifacts
* third-party code or assets without clear source information
* full official firmware source
* PCB, Gerber, BOM, production test materials, or supply-chain materials
* production-grade materials that can be used for cloning, manufacturing, mass production, or competing hardware development

---

## 4. Branch naming

Please keep branch names simple and descriptive.

Recommended prefixes:

```text
feat/...
fix/...
docs/...
chore/...
refactor/...
sdk/...
example/...
```

Examples:

```text
feat/macos-status-widget
fix/windows-ble-reconnect
docs/install-guide-update
sdk/button-api-cleanup
example/light-status-demo
chore/release-note-cleanup
```

---

## 5. Pull Request rules

### One PR, one purpose

Please keep each PR focused. Avoid mixing unrelated changes in the same PR.

Good PR examples:

* improve one installation guide
* clarify one protocol section
* fix one reproducible bug
* add one community project entry
* add one minimal example
* improve SDK README
* clarify custom HEX build instructions
* add one button / toggle / light / OLED demo

### PR title examples

```text
docs: improve Windows install guide
fix: clarify BLE reconnect behavior
feat: add macOS build notes
sdk: clarify button callback API
example: add OLED status demo
chore: update release documentation
```

### Before opening a PR

Please check:

* [ ] The purpose is clear
* [ ] The scope is focused
* [ ] Tested locally, or explained why not
* [ ] Screenshots or logs are provided when UI, connection, or device behavior is involved
* [ ] SDK, examples, or custom HEX build changes include test environment and build result notes
* [ ] Links are valid for documentation changes
* [ ] No API keys, tokens, private keys, or personal config
* [ ] No unrelated binaries, installers, or build artifacts
* [ ] No full official firmware source, PCB, Gerber, BOM, production test materials, or supply-chain materials
* [ ] Large features, protocol changes, SDK API changes, or default behavior changes are discussed first

---

## 6. When to discuss first

If you are not sure whether a change belongs in the official repositories, please open an Issue or Discussion first.

Especially for:

* uncertain feature direction
* changes to default user experience
* BLE protocol behavior changes
* SDK API or examples structure changes
* custom HEX build flow changes
* desktop compatibility changes
* release or repository structure changes
* large changes with high review cost
* personal workflows, third-party tools, or custom firmware experiences that may not belong in official repos
* firmware / hardware deep collaboration, low-level debugging, or production-grade material evaluation

Simple rule:

```text
Not sure → Discussion
Clear problem → Issue
Already changed something → Pull Request
Independent project / SDK demo / custom HEX showcase → awesome-ahakey
Deeper firmware / hardware collaboration → Hardware Source Access Program
```

---

## 7. Community projects

If you built an independent client, tool, script, tutorial, workflow, SDK demo, custom HEX experience, or button / toggle / light / OLED remix, it usually does not need to be merged into the official `desktop` repo.

Please submit it to:

👉 [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

Community projects can exist independently. High-value projects may later be discussed as official features, official examples, official documentation, or product roadmap input.

Good fits for `awesome-ahakey` include:

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

If you are improving SDK, protocol docs, examples, or build scripts inside the `protocol` repository, submit a Pull Request to `protocol`.

---

## 8. Contributor recognition

AhaKey rewards contribution with visibility, trust, early product access, and influence — **not automatic repository permissions**.

We want real contributors to have opportunities to be seen, recorded, invited to try new products, join roadmap discussions, and influence product direction.

These benefits are not automatic guarantees. They are ways for AhaKey to support long-term, high-quality contributors.

| Role                          | How it happens                                                                                   | What it means                                                                                                                                                                                                                         |
| ----------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Community Member              | Use AhaKey, join Issues or Discussions                                                           | Join the community, ask questions, share feedback, and join public feedback activities.                                                                                                                                               |
| Maker                         | Your project, tutorial, workflow, SDK demo, or custom HEX showcase is listed in `awesome-ahakey` | Author credit, project visibility, community / website showcase opportunities, **AhaKey Maker** title, and early access to software and SDK features.                                                                                 |
| Contributor                   | Your PR is merged, or your feedback improves the project                                         | Release notes recognition, Contributor Wall opportunity, priority review, beta access to official client / protocol / SDK / workflow features, and possible AhaKey accessories, perks, or device discounts depending on contribution. |
| Core Contributor / Maintainer | Long-term trusted contribution and maintainer invitation                                         | Roadmap discussion, early review of new hardware / software directions, ownership of a specific area, and possible prototype, test device, free beta hardware, or co-creation credit depending on contribution and availability.      |

Special community titles may also be used for outstanding contributors, such as:

* **AhaKey Maker**
* **AhaKey SDK Pioneer**
* **AhaKey Workflow Pioneer**
* **AhaKey Core Contributor**
* **AhaKey Community Maintainer**
* **AhaKey Chief Workflow Officer** for contributors who continuously push forward a specific workflow ecosystem

GitHub repository permissions are not granted automatically. They may be granted only when there is a clear maintenance need, long-term trust, and mutual agreement.

---

## 9. GitHub access

New contributors use:

```text
Fork → Branch in your fork → Pull Request
```

Invited Core Contributors may receive `Write` access to specific repositories.

Maintainers may receive `Maintain` access for specific repositories or areas.

No one should push directly to `main`, with or without write access.

If you only want to submit an independent project, tutorial, workflow, SDK demo, or custom HEX showcase, official repository write access is usually not needed. Submit it to `awesome-ahakey` instead.

---

## 10. Review expectations

AhaKey is currently maintained by a small team. We try to review Issues, Discussions, and PRs regularly.

Please understand that:

* PRs may not be reviewed immediately;
* large features may need design discussion first;
* features that do not fit the official version may be redirected to `awesome-ahakey`;
* SDK API, BLE protocol, examples, or custom HEX build changes may require more testing or compatibility checks;
* maintainers may ask for tests, screenshots, logs, build results, or documentation.

Small and focused contributions are usually easier to review and merge.

---

## 11. Licensing

Different AhaKey repositories and materials may use different openness models.

| Content                                                                            | Openness model                                                                                 |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| Official desktop client code                                                       | Subject to the `LICENSE` file in the `desktop` repository                                      |
| Public documentation, headers, examples, and build scripts in AhaKey Developer Kit | Subject to the `LICENSE` file in the `protocol` repository; currently Apache License 2.0       |
| Binary core runtime inside `protocol`                                              | Subject to `sdk/core/BINARY_LICENSE.md`                                                        |
| README files and tutorials                                                         | Subject to the repository notice; if not otherwise stated, follow the repository `LICENSE`     |
| Community projects, third-party tools, workflows, SDK demos                        | Licensed by their own authors; `awesome-ahakey` only lists and showcases them                  |
| Official firmware release notes, update docs, compatibility notes                  | Subject to the `firmware` repository notice                                                    |
| Full official firmware source, hardware design files, production materials         | Not public by default; controlled access, form-based review, or separate written authorization |
| Third-party dependencies, chip vendor SDKs, toolchains, vendor libraries           | Subject to their original licenses and copyright notices                                       |

Notes:

* The license of each open repository is defined by its own `LICENSE` file.
* If a repository has no clear LICENSE, do not assume it can be freely copied, used commercially, or redistributed.
* User-built HEX files are custom developer firmware and are not official AhaKey firmware.
* Firmware source, hardware design files, and production materials are not automatically open source even if they are shared with selected developers.
* Commercial hardware cooperation, OEM, ODM, mass production, resale, or customer delivery requires separate written authorization.

---

## 12. Originality and third-party code

The core code and product design in official AhaKey repositories are designed and developed by the AhaKey team. They are not a renamed fork or repackaging of another existing project.

We respect open-source licenses and original authorship. If a repository uses third-party dependencies, system SDKs, open-source libraries, sample code, chip vendor SDKs, toolchains, or external assets, their original licenses and copyright notices should be respected and preserved.

When submitting a PR, please make sure that:

* you have the right to submit the code, documentation, or assets;
* you do not copy third-party code with incompatible licenses;
* you do not remove copyright or license notices;
* you mention the source if external material is referenced;
* you do not submit company-internal code, customer code, restricted materials, or unauthorized hardware / firmware materials;
* you do not incorrectly label third-party chip SDKs, toolchains, or vendor libraries as AhaKey-owned open-source code.

---

## 13. Firmware / hardware deep collaboration and production-grade materials

AhaKey encourages developers to use the public AhaKey Developer Kit for open development and remixing.

If you want to do the following, please start with the public `protocol` repository:

* read the BLE protocol
* build a third-party client
* use the SDK to customize four keys, toggle, lights, or OLED
* build your own custom HEX
* learn from examples
* submit your project to `awesome-ahakey`

The following materials are not provided through public repositories by default:

* full official firmware source
* schematics, PCB, Gerber, BOM
* production test materials
* supply-chain materials
* internal implementation details
* production-grade hardware materials that can be used for cloning, manufacturing, or resale

If you want to:

* help improve firmware code
* fill technical gaps in hardware product development
* join low-level issue debugging
* join firmware / hardware technical collaboration
* join early technical discussions for new hardware or software directions
* request deeper materials or production-level debugging collaboration

please submit:

👉 [`Hardware Source Access Program`](https://ahakey.com/cn/hardware-source)

The AhaKey team will review the purpose, risk, contribution direction, and collaboration fit. If it fits, we will contact you for the next step.

Without authorization, controlled materials may not be publicly uploaded, redistributed, shared, sold, used for board reproduction, cloning, manufacturing, resale, or competing hardware development.

<p align="right"><a href="#top">↑ Back to top</a></p>
