<a id="top"></a>

<p align="center">
  <a href="#zh-cn"><strong>简体中文</strong></a> ·
  <a href="#en"><strong>English</strong></a>
</p>

---

<a id="zh-cn"></a>

# 参与 AhaKey 共创

感谢你参与 AhaKey 社区。

这份文档只说明：**如何提交贡献、如何协作、贡献如何被认可、GitHub 权限如何处理**。

如果你还不确定应该去哪个仓库、应该看 `desktop`、`protocol` 还是 `awesome-ahakey`，请先从组织首页开始：

👉 [`AhaKey Community`](https://github.com/AhakeyAI)

---

## 1. 当前维护分工

AhaKey 目前由一个小型维护团队维护。不同类型的贡献会由不同成员参与处理。

| 成员 | 主要角色 | 负责内容 |
|---|---|---|
| Ann | Official Product Software Lead | 负责官方产品软件的持续迭代。涉及最终进入官方 `desktop` 版本的功能，需要由 Ann 进行产品与软件方向把关。 |
| ZephyrKeXiner | Code Review & Merge Maintainer | 负责合并上来的代码审查、PR Review、合并判断和仓库代码质量把关。 |
| Vivian | Community Operations Maintainer | 负责社区维护、用户引导、Discussion / Issue 运营、`awesome-ahakey` 项目收录和社区协作统筹。 |

说明：

- 一般问题和想法可以先进入 Issue 或 Discussion。
- 代码和文档 PR 会由维护者 Review。
- 社区项目优先进入 `awesome-ahakey`。
- 涉及官方产品方向、默认体验或最终并入 `desktop` 的功能，会由官方产品软件负责人进一步确认。

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
```

示例：

```text
feat/macos-status-widget
fix/windows-ble-reconnect
docs/install-guide-update
chore/release-note-cleanup
```

---

## 5. Pull Request 规则

### 一个 PR 只解决一个问题

请尽量保持 PR 聚焦，不要把互不相关的改动混在一起。

好的 PR 示例：

- 改进一篇安装说明
- 补清楚一段协议文档
- 修复一个可复现 bug
- 增加一个社区项目条目
- 增加一个最小示例

### PR 标题建议

```text
docs: improve Windows install guide
fix: clarify BLE reconnect behavior
feat: add macOS build notes
chore: update release documentation
```

### 提交 PR 前请确认

- [ ] PR 目的清楚
- [ ] 修改范围聚焦
- [ ] 已经本地测试，或说明为什么无法测试
- [ ] 涉及 UI、连接、设备行为时提供截图或日志
- [ ] 涉及文档时保证链接有效
- [ ] 不提交 API Key、Token、私钥或个人配置
- [ ] 不提交无关二进制文件、安装包或编译产物
- [ ] 大功能、协议变更、默认行为变化已经先开 Issue 或 Discussion

---

## 6. 什么时候应该先讨论？

如果你不确定改动是否应该进入官方仓库，请先开 Issue 或 Discussion。

尤其是这些情况：

- 新功能方向不确定
- 改动影响默认体验
- 改动涉及 BLE 协议行为
- 改动涉及 release 或仓库结构
- 改动比较大，Review 成本较高
- 个人 workflow 或第三方工具，不确定是否应该合进官方

简单理解：

```text
不确定 → 先 Discussion
明确问题 → 提 Issue
已经改好 → 提 Pull Request
独立作品 → 提到 awesome-ahakey
```

---

## 7. 社区作品

如果你做的是独立客户端、工具、脚本、教程、workflow 或桌面 setup，通常不需要直接合进官方 `desktop`。

请优先提交到：

👉 [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

社区项目可以独立存在。优秀项目后续可以再讨论是否进入官方版本。

---

## 8. 贡献者认可

AhaKey 对贡献的回报，是让作品被看见、让贡献被记录、让长期贡献者参与产品方向，**不是自动发放仓库权限**。

| 身份 | 如何达到 | 你会获得什么 |
|---|---|---|
| Community Member | 使用 AhaKey，参与 Issue / Discussion | 参与社区、提问、反馈和讨论 |
| Maker | 作品、教程或 workflow 被 `awesome-ahakey` 收录 | 作者署名、项目展示、被更多用户看到 |
| Contributor | PR 被合并，或高质量反馈推动项目改进 | Release notes 鸣谢、贡献记录、优先被维护者关注 |
| Core Contributor / Maintainer | 长期稳定贡献，并被维护者邀请 | 参与路线图、Review、维护某个方向 |

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

---

## 10. Review 预期

AhaKey 目前由小团队维护，我们会尽量定期查看 Issue、Discussion 和 PR。

请理解：

- PR 不一定会立即 Review；
- 大功能可能需要先讨论方向；
- 不适合官方版本的功能，可能会被建议放到 `awesome-ahakey`；
- 维护者可能会要求补充测试、截图、日志或文档。

我们鼓励小而清晰的贡献，这类贡献通常更容易被 Review 和合并。

---

## 11. 合并边界

官方仓库优先接受稳定、通用、可维护的改动。

个人强定制 workflow、实验性工具、第三方集成和二创项目，不一定适合合进官方版本，但非常适合进入 `awesome-ahakey`。

我们的目标不是把所有东西都合并进官方，而是让高质量的 AhaKey 玩法都能被发现、复用和继续改造。

---

## 12. 开源协议

AhaKey 的不同仓库和资料采用不同开放策略。

| 内容 | 开放方式 |
|---|---|
| 官方桌面客户端代码 | 以对应仓库 `LICENSE` 文件为准，当前建议使用 MIT License |
| BLE 协议文档、README、教程类内容 | 以对应仓库声明为准，建议使用 CC BY 4.0 或随仓库 LICENSE |
| 社区项目、第三方工具、workflow | 由项目作者自行选择许可证，`awesome-ahakey` 仅做收录展示 |
| 固件源码、硬件设计文件、生产资料 | 不默认公开，采用申请制或受控开放 |
| 第三方依赖 | 遵守其原始许可证和版权声明 |

请注意：

- 开源仓库的具体授权以该仓库根目录中的 `LICENSE` 文件为准。
- 如果某个仓库没有明确 LICENSE，请不要默认认为它可以被自由复制、商用或再分发。
- 固件源码、硬件设计文件和生产资料即使向特定开发者开放，也不等于允许公开传播、网络分发、仿制、打板、量产或销售。
- 商业硬件合作、OEM、ODM、批量生产、对外销售等情况，需要单独取得书面授权。

---

## 13. 原创性与第三方代码

AhaKey 官方仓库中的核心代码和产品设计由 AhaKey 团队自主设计和开发，并非基于某个现有项目 fork、改名或二次包装而来。

我们重视开源许可证和原创性。如果仓库中使用第三方依赖、系统 SDK、开源库、示例代码或外部资源，应遵守其原始许可证，并在相关文件中保留必要的版权和许可证声明。

贡献者提交 PR 时，请确保：

- 你有权提交相关代码、文档或资源；
- 不要直接复制不兼容许可证的第三方代码；
- 不要移除第三方版权声明或许可证信息；
- 如果引用外部资料，请在 PR 中说明来源；
- 不要提交公司内部代码、客户代码、受限资料或未经授权的硬件 / 固件资料。

---

## 14. 固件源码与硬件资料

AhaKey 鼓励用户参与开源共创。

默认开放内容请以组织首页和各仓库 README 为准。

以下资料不默认公开：

- 固件源码
- 硬件原理图、PCB、生产资料
- 官方设备内部实现细节
- 可用于仿制、打板、量产、销售的硬件资料

如果你确实需要访问硬件嵌入式源码或固件资料，请提交 Source Access Request。

未经授权，不得将受控资料公开上传、网络分发、转发、出售、共享，不得用于自行打板、仿制、量产、销售或开发竞争性硬件产品。

---

## 15. 相关文档

- [`SUPPORT.md`](https://github.com/AhakeyAI/.github/blob/main/SUPPORT.md)：使用、安装、构建、协议问题支持入口
- [`SECURITY.md`](https://github.com/AhakeyAI/.github/blob/main/SECURITY.md)：安全问题、密钥泄露、隐私风险入口
- [`CODE_OF_CONDUCT.md`](https://github.com/AhakeyAI/.github/blob/main/CODE_OF_CONDUCT.md)：社区行为规范
- [`PULL_REQUEST_TEMPLATE.md`](https://github.com/AhakeyAI/.github/blob/main/.github/PULL_REQUEST_TEMPLATE.md)：PR 提交模板

---

## 16. 一句话原则

官方版本追求稳定，社区版本鼓励探索。

不是所有 DIY 都必须合进官方，但所有高质量的 AhaKey 工具、教程和 workflow 都值得被看见。

<p align="right"><a href="#top">↑ Back to top</a></p>

---

<a id="en"></a>

# Contributing to AhaKey

Thank you for contributing to AhaKey.

This document explains **how to contribute, how collaboration works, how contributions are recognized, and how GitHub permissions are handled**.

If you are not sure which repository to visit first, please start from the organization homepage:

👉 [`AhaKey Community`](https://github.com/AhakeyAI)

---

## 1. Current maintainers

AhaKey is currently maintained by a small team. Different types of contributions may be reviewed by different maintainers.

| Member | Main role | Responsibility |
|---|---|---|
| Ann | Official Product Software Lead | Leads ongoing official product software iteration. Features that may eventually become part of the official `desktop` version need final product and software direction review from Ann. |
| ZephyrKeXiner | Code Review & Merge Maintainer | Reviews incoming code, evaluates PR quality, and helps decide whether changes should be merged. |
| Vivian | Community Operations Maintainer | Maintains community operations, guides users, coordinates Discussions / Issues, curates `awesome-ahakey`, and supports community collaboration. |

Notes:

- General questions and ideas should start from Issues or Discussions.
- Code and documentation PRs will be reviewed by maintainers.
- Community projects should usually go to `awesome-ahakey` first.
- Features that affect official product direction, default experience, or the official `desktop` version may require final review from the official product software lead.

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
```

Examples:

```text
feat/macos-status-widget
fix/windows-ble-reconnect
docs/install-guide-update
chore/release-note-cleanup
```

---

## 5. Pull Request rules

### One PR, one purpose

Please keep each PR focused. Avoid mixing unrelated changes in the same PR.

Good PR examples:

- improve one installation guide
- clarify one protocol section
- fix one reproducible bug
- add one community project entry
- add one minimal example

### PR title examples

```text
docs: improve Windows install guide
fix: clarify BLE reconnect behavior
feat: add macOS build notes
chore: update release documentation
```

### Before opening a PR

Please check:

- [ ] The purpose is clear
- [ ] The scope is focused
- [ ] Tested locally, or explained why not
- [ ] Screenshots or logs are provided when UI, connection, or device behavior is involved
- [ ] Links are valid for documentation changes
- [ ] No API keys, tokens, private keys, or personal config
- [ ] No unrelated binaries, installers, or build artifacts
- [ ] Large features, protocol changes, or default behavior changes are discussed first

---

## 6. When to discuss first

If you are not sure whether a change belongs in the official repositories, please open an Issue or Discussion first.

Especially for:

- uncertain feature direction
- changes to default user experience
- BLE protocol behavior changes
- release or repository structure changes
- large changes with high review cost
- personal workflows or third-party tools that may not belong in official repos

Simple rule:

```text
Not sure → Discussion
Clear problem → Issue
Already changed something → Pull Request
Independent project → awesome-ahakey
```

---

## 7. Community projects

If you built an independent client, tool, script, tutorial, workflow, or desktop setup, it usually does not need to be merged into the official `desktop` repo.

Please submit it to:

👉 [`awesome-ahakey`](https://github.com/AhakeyAI/awesome-ahakey)

Community projects can exist independently. High-value projects may later be discussed as official features.

---

## 8. Contributor recognition

AhaKey rewards contribution with visibility, trust, and influence — **not automatic repository permissions**.

| Role | How it happens | What it means |
|---|---|---|
| Community Member | Use AhaKey, join Issues or Discussions | Join the community, ask questions, and share feedback |
| Maker | Your project, tutorial, or workflow is listed in `awesome-ahakey` | Author credit and project visibility |
| Contributor | Your PR is merged, or your feedback improves the project | Release notes recognition, contribution record, maintainer attention |
| Core Contributor / Maintainer | Long-term trusted contribution and maintainer invitation | Help shape roadmap, review, and maintain an area |

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

---

## 10. Review expectations

AhaKey is currently maintained by a small team. We try to review Issues, Discussions, and PRs regularly.

Please understand that:

- PRs may not be reviewed immediately;
- large features may need design discussion first;
- features that do not fit the official version may be redirected to `awesome-ahakey`;
- maintainers may ask for tests, screenshots, logs, or documentation.

Small and focused contributions are usually easier to review and merge.

---

## 11. Merge scope

Official repositories prioritize stable, general, and maintainable changes.

Highly personal workflows, experimental tools, third-party integrations, and remixes may not belong in the official version, but they are very welcome in `awesome-ahakey`.

Our goal is not to merge everything into the official product, but to make high-quality AhaKey ideas discoverable, reusable, and extensible.

---

## 12. Licensing

Different AhaKey repositories and materials may use different openness models.

| Content | Openness model |
|---|---|
| Official desktop client code | Subject to the `LICENSE` file in the repository; MIT License is recommended for open software repositories |
| BLE protocol docs, README files, tutorials | Subject to the repository notice; CC BY 4.0 or the repository LICENSE is recommended for documentation |
| Community projects, third-party tools, workflows | Licensed by their own authors; `awesome-ahakey` only lists and showcases them |
| Firmware source, hardware design files, production materials | Not public by default; controlled access or request-based access |
| Third-party dependencies | Subject to their original licenses and copyright notices |

Notes:

- The license of each open repository is defined by its own `LICENSE` file.
- If a repository has no clear LICENSE, do not assume it can be freely copied, used commercially, or redistributed.
- Firmware source, hardware design files, and production materials are not automatically open source even if they are shared with selected developers.
- Commercial hardware cooperation, OEM, ODM, mass production, resale, or customer delivery requires separate written authorization.

---

## 13. Originality and third-party code

The core code and product design in official AhaKey repositories are designed and developed by the AhaKey team. They are not a renamed fork or repackaging of another existing project.

We respect open-source licenses and original authorship. If a repository uses third-party dependencies, system SDKs, open-source libraries, sample code, or external assets, their original licenses and copyright notices should be respected and preserved.

When submitting a PR, please make sure that:

- you have the right to submit the code, documentation, or assets;
- you do not copy third-party code with incompatible licenses;
- you do not remove copyright or license notices;
- you mention the source if external material is referenced;
- you do not submit company-internal code, customer code, restricted materials, or unauthorized hardware / firmware materials.

---

## 14. Firmware source and hardware materials

AhaKey encourages open collaboration and community-driven development.

Please refer to the organization homepage and repository README files for what is open by default.

The following materials are not public by default:

- firmware source code
- schematics, PCB files, production materials
- internal implementation details
- materials that can be used for cloning, manufacturing, or resale

If you really need firmware or embedded source access, please submit a Source Access Request.

Without authorization, controlled materials may not be publicly uploaded, redistributed, shared, sold, used for board reproduction, cloning, manufacturing, resale, or competing hardware development.

---

## 15. Related files

- [`SUPPORT.md`](https://github.com/AhakeyAI/.github/blob/main/SUPPORT.md): support entry for usage, installation, build, and protocol questions
- [`SECURITY.md`](https://github.com/AhakeyAI/.github/blob/main/SECURITY.md): security issues, leaked secrets, and privacy risks
- [`CODE_OF_CONDUCT.md`](https://github.com/AhakeyAI/.github/blob/main/CODE_OF_CONDUCT.md): community behavior expectations
- [`PULL_REQUEST_TEMPLATE.md`](https://github.com/AhakeyAI/.github/blob/main/.github/PULL_REQUEST_TEMPLATE.md): PR template

---

## 16. One-line principle

Official versions prioritize stability. Community projects encourage exploration.

Not every DIY project needs to merge into the official product, but high-quality AhaKey tools, tutorials, and workflows deserve to be seen.

<p align="right"><a href="#top">↑ Back to top</a></p>
