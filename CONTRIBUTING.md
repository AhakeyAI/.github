[English](#english) | [简体中文](#简体中文)

---

# English

## AhaKey Collaboration Guide

This document describes how contributors can work with the AhaKey community repositories.

Our goal is simple:

- keep contribution paths open
- keep `main` stable
- make review and merging predictable
- make it easy for new contributors to participate

---

## Core Rule

**Do not push directly to `main`.**

All changes should go through:

1. a branch
2. a pull request
3. review
4. merge

---

## Contributor Types

### 1. Community contributors

This is the default path for new contributors.

Recommended workflow:

1. Fork the repository
2. Create a branch in your fork
3. Make focused changes
4. Open a pull request to the upstream repository

This path is suitable for:

- documentation updates
- small fixes
- setup notes
- integration experiments
- showcase and community resource updates

### 2. Core contributors

Core contributors are trusted contributors who collaborate more frequently.

Recommended workflow:

1. Create a branch in the official repository
2. Open a pull request to `main`
3. Wait for review
4. Merge after approval

Core contributors should still avoid pushing directly to `main`.

### 3. Maintainers

Maintainers are responsible for:

- reviewing pull requests
- merging approved changes
- managing labels, issues, and discussions
- preparing releases
- keeping repository boundaries clear

---

## Recommended Teams

When the community grows, we recommend keeping at least two teams:

### `maintainers`
Suggested permission:
- admin

Responsibilities:
- merge pull requests
- manage releases
- configure repository settings
- maintain branch protection rules

### `core-contributors`
Suggested permission:
- write

Responsibilities:
- create branches in official repositories
- submit pull requests
- participate in ongoing technical collaboration

For most new contributors, fork + pull request is preferred.

---

## Branch Naming

Please keep branch names simple and descriptive.

Recommended prefixes:

- `feat/...`
- `fix/...`
- `docs/...`
- `chore/...`

Examples:

- `feat/macos-status-widget`
- `fix/windows-bridge-readme`
- `docs/install-guide-update`
- `chore/release-note-cleanup`

---

## Pull Request Rules

### Keep pull requests focused

One pull request should solve one problem.

Avoid mixing unrelated changes in the same PR.

### Good pull request examples

- improve one installation guide
- clarify one protocol section
- fix one build instruction
- add one community resource entry

### PR title examples

- `docs: improve Windows install guide`
- `fix: clarify BLE bridge setup`
- `feat: add macOS build notes`

### Suggested PR template

```md
## What this PR does

-

## Why

-

## Scope

-

## Notes

-
```

---

## Review Rules

### Basic review rule

A pull request should be merged only after review.

Recommended minimum rule:

- at least 1 approval
- unresolved review comments should be addressed
- no direct push to `main`

### Fast-merge candidates

These can usually be reviewed and merged more quickly:

- documentation updates
- README improvements
- showcase entries
- small community resource updates

### Higher-scrutiny changes

These should be reviewed more carefully:

- protocol command behavior
- desktop platform source code
- release-related changes
- firmware-related documentation
- repository structure changes

---

## Recommended Branch Protection

For core repositories such as:

- `.github`
- `desktop`
- `protocol`
- `awesome-ahakey`
- `firmware`

we recommend protecting the `main` branch with rules such as:

- require a pull request before merging
- require at least 1 approval
- require conversation resolution before merging
- do not allow force pushes
- do not allow branch deletion

As the project grows, status checks and CI can be added later.

---

## Repository-Specific Contribution Suggestions

### `desktop`
Best for:
- platform docs
- build instructions
- bug fixes
- desktop client improvements
- platform-specific notes for Windows and macOS

### `protocol`
Best for:
- protocol docs
- minimal examples
- command clarification
- BLE service explanations

### `awesome-ahakey`
Best for:
- community tools
- showcases
- workflows
- tutorials
- integrations

### `firmware`
Best for:
- release notes
- update instructions
- compatibility notes
- official firmware documentation

---

## Communication Suggestions

Before making larger changes, contributors are encouraged to:

- open an issue
- start a discussion
- confirm scope with maintainers

This is especially recommended for:

- architectural changes
- repository restructuring
- protocol behavior changes
- release process changes

---

## AhaKey-Specific Notes

Before contributing, contributors are encouraged to first identify the most relevant repository:

- `desktop` — official desktop baseline
- `protocol` — BLE protocol documentation and examples
- `awesome-ahakey` — community projects, workflows, and showcases
- `firmware` — firmware-related release notes and documentation

For questions, ideas, and early discussion, please use AhaKey Discussions when appropriate.

For installation and user-facing setup guidance, please prefer the official website / documentation pages when available.

Please also read:

- `SUPPORT.md`
- `SECURITY.md`
- `CODE_OF_CONDUCT.md`

---

## Preferred Workflow Summary

### For new contributors
**Fork → Branch → PR**

### For core contributors
**Official repo branch → PR → Review → Merge**

### For maintainers
**Review → Approve → Merge → Release**

---

# 简体中文

## AhaKey 社区协作规则

这份文档用于说明，AhaKey 社区中的贡献者应该如何参与各个仓库的协作。

我们的目标很简单：

- 让贡献路径保持开放
- 让 `main` 分支保持稳定
- 让 review 和 merge 过程可预期
- 让新贡献者容易参与

---

## 核心规则

**不要直接 push 到 `main`。**

所有改动统一走：

1. 新建分支
2. 提交 PR
3. review
4. merge

---

## 贡献者类型

### 1）社区贡献者

这是默认的参与路径，适合刚进入社区的新贡献者。

推荐流程：

1. Fork 仓库
2. 在自己的 fork 中创建分支
3. 完成改动
4. 向上游仓库提交 PR

适合的贡献类型包括：

- 文档更新
- 小修复
- setup 说明
- integration 实验
- showcase / 社区资源补充

### 2）核心贡献者

核心贡献者适合已经持续参与并且协作比较稳定的人。

推荐流程：

1. 在官方仓库中创建分支
2. 向 `main` 提交 PR
3. 等待 review
4. 审核通过后再 merge

即使是核心贡献者，也不建议直接 push 到 `main`。

### 3）维护者

维护者主要负责：

- review PR
- merge 已通过的改动
- 管理 labels、issues、discussions
- 准备 release
- 保持仓库边界清晰

---

## 推荐的团队结构

当社区开始扩大后，建议至少保留两个 team：

### `maintainers`
建议权限：
- admin

主要职责：
- 合并 PR
- 管理 release
- 配置仓库设置
- 维护分支保护规则

### `core-contributors`
建议权限：
- write

主要职责：
- 在官方仓库中创建分支
- 提交 PR
- 参与持续性的技术协作

对于大多数新贡献者，仍然建议优先使用 fork + PR。

---

## 分支命名规范

请尽量保持分支名称简单、清晰、可读。

推荐前缀：

- `feat/...`
- `fix/...`
- `docs/...`
- `chore/...`

示例：

- `feat/macos-status-widget`
- `fix/windows-bridge-readme`
- `docs/install-guide-update`
- `chore/release-note-cleanup`

---

## Pull Request 规则

### 一个 PR 只解决一个问题

请尽量保持 PR 聚焦。

不要把互不相关的改动混在同一个 PR 里。

### 好的 PR 示例

- 改进一篇安装说明
- 补清楚一段协议文档
- 修复一条构建说明
- 增加一条社区资源收录

### PR 标题示例

- `docs: improve Windows install guide`
- `fix: clarify BLE bridge setup`
- `feat: add macOS build notes`

### 推荐 PR 模板

```md
## What this PR does

-

## Why

-

## Scope

-

## Notes

-
```

---

## Review 规则

### 基础 review 规则

一个 PR 应该在 review 之后再 merge。

推荐最小规则：

- 至少 1 个 approval
- review 评论未解决前不要 merge
- 不允许直接 push 到 `main`

### 可以相对快合的改动

以下类型通常可以更快 review 和 merge：

- 文档更新
- README 改进
- showcase 条目补充
- 社区资源链接更新

### 需要更谨慎 review 的改动

以下改动建议更认真地 review：

- 协议命令相关内容
- desktop 平台源码
- release 相关内容
- firmware 相关文档
- 仓库结构调整

---

## 推荐的 `main` 分支保护规则

对于以下核心仓库：

- `.github`
- `desktop`
- `protocol`
- `awesome-ahakey`
- `firmware`

建议为 `main` 打开保护规则，例如：

- merge 前必须走 pull request
- 至少需要 1 个 approval
- conversation 未解决前不能 merge
- 不允许 force push
- 不允许删除分支

后续随着项目成长，再逐步补 CI 和状态检查。

---

## 各仓库适合接收什么类型的贡献

### `desktop`
适合：
- 平台文档
- 构建说明
- bug 修复
- desktop client 改进
- Windows / macOS 平台相关说明

### `protocol`
适合：
- 协议文档
- 最小示例
- 命令说明补充
- BLE service 说明优化

### `awesome-ahakey`
适合：
- 社区工具
- showcase
- workflows
- tutorials
- integrations

### `firmware`
适合：
- 发布说明
- 升级说明
- 兼容性说明
- 官方固件相关文档

---

## 沟通建议

当改动比较大时，建议先：

- 开 issue
- 发 discussion
- 先和 maintainers 对齐范围

尤其是以下类型的改动，建议先沟通：

- 架构调整
- 仓库重组
- 协议行为变化
- release 流程变化

---

## AhaKey 补充说明

在开始贡献前，建议先判断你的改动最适合进入哪个仓库：

- `desktop` — 官方 desktop baseline
- `protocol` — BLE 协议文档与示例
- `awesome-ahakey` — 社区项目、workflow 和 showcase
- `firmware` — 固件相关发布说明与文档

如果是问题、想法或前期讨论，建议优先使用 AhaKey Discussions。

如果涉及安装、使用说明和面向普通用户的 setup 指引，优先以官网 / 独立站文档为准。

同时也请阅读：

- `SUPPORT.md`
- `SECURITY.md`
- `CODE_OF_CONDUCT.md`

---

## 推荐协作流程总结

### 对新贡献者
**Fork → Branch → PR**

### 对核心贡献者
**官方仓库建分支 → PR → Review → Merge**

### 对维护者
**Review → Approve → Merge → Release**
