<a id="top"></a>

<p align="center">
  <a href="#zh-cn"><strong>简体中文</strong></a> ·
  <a href="#en"><strong>English</strong></a>
</p>

---

<a id="zh-cn"></a>

# AhaKey Security Policy / 安全政策

感谢你帮助 AhaKey 保持安全。

如果你发现安全问题，请不要公开创建 Issue。  
请优先通过私密方式联系 AhaKey 团队。

---

## 1. 什么属于安全问题？

包括但不限于：

- API Key、Token、私钥、凭证泄露
- 用户隐私数据泄露
- 私有仓库、受控源码或硬件资料被未经授权访问
- 固件源码、硬件设计文件、生产资料被未经授权公开传播
- 可导致设备被异常控制的 BLE / 协议问题
- 可导致客户端执行非预期操作的问题
- 可绕过权限、授权或安全限制的问题
- release、安装包、更新包被篡改的风险
- 构建脚本、依赖、供应链相关风险
- 其他可能影响用户、设备、仓库或社区安全的问题

---

## 2. 什么不属于安全问题？

以下通常不属于安全问题，请优先走 `SUPPORT.md` 或对应仓库 Issue：

- 普通安装失败
- 客户端无法启动
- 蓝牙连接不稳定
- 设备无法识别
- 文档错误
- 功能建议
- 普通兼容性问题
- 不涉及敏感信息或安全绕过的 bug

普通支持入口：

👉 [`SUPPORT.md`](https://github.com/AhakeyAI/.github/blob/main/SUPPORT.md)

---

## 3. 如何报告安全问题？

请不要公开发 Issue。

你可以通过以下方式私密报告：

```text
Email: security@ahakey.com
Subject: [AhaKey Security] 问题简述
```

如果对应仓库已经开启 GitHub Private Vulnerability Reporting，也可以通过仓库 Security 页面提交私密漏洞报告。

---

## 4. 报告时请提供什么？

请尽量提供：

- 问题描述
- 影响范围
- 受影响仓库、版本、设备或平台
- 复现步骤
- 截图、日志或 PoC，如果有
- 你认为的风险等级
- 你的联系方式
- 是否已经公开传播或仅你本人知晓

信息越完整，我们越容易确认和修复问题。

---

## 5. 请不要这样做

在问题确认和修复前，请不要：

- 公开发布漏洞细节
- 在公开 Issue 中贴出密钥、Token、私钥、漏洞细节或利用方法
- 利用问题访问、修改、控制他人设备或数据
- 扩大测试范围到无关用户、设备或服务
- 将漏洞用于攻击、勒索、恶意传播或商业威胁
- 公开传播受控源码、固件资料、硬件设计文件或生产资料

---

## 6. 我们会如何处理？

收到报告后，我们会尽量：

1. 确认收到报告；
2. 初步判断问题是否属于安全问题；
3. 评估影响范围和严重程度；
4. 制定修复、缓解或公开说明方案；
5. 必要时发布修复版本、更新文档或撤回敏感内容；
6. 在合适情况下感谢报告者。

AhaKey 目前由小团队维护，我们会尽量及时处理安全问题，但具体响应时间可能取决于问题复杂度和影响范围。

---

## 7. 关于受控源码 / 硬件资料

AhaKey 的固件源码、硬件设计文件和生产资料不默认公开。

如果你发现以下情况，请按照本安全流程报告：

- 受控固件源码被公开上传到 GitHub / Gitee / GitLab
- 硬件原理图、PCB、生产资料被未经授权公开传播
- 私有仓库访问权限异常
- 有人售卖、转发或共享受控资料
- 有人使用受控资料进行仿制、打板、量产或竞争性硬件开发

未经授权，不得将受控资料公开上传、网络分发、转发、出售、共享，不得用于自行打板、仿制、量产、销售或开发竞争性硬件产品。

---

## 8. 安全报告者认可

如果你以负责任的方式报告有效安全问题，AhaKey 可能会在合适情况下给予感谢或鸣谢。

是否公开鸣谢会尊重报告者意愿和安全修复节奏。

<p align="right"><a href="#top">↑ Back to top</a></p>

---

<a id="en"></a>

# AhaKey Security Policy

Thank you for helping keep AhaKey safe.

If you discover a security issue, please do not open a public Issue.  
Please report it privately to the AhaKey team.

---

## 1. What counts as a security issue?

Security issues include, but are not limited to:

- API key, token, private key, or credential leaks
- user privacy risks
- unauthorized access to private repositories, controlled source, or hardware materials
- unauthorized public distribution of firmware source, hardware design files, or production materials
- BLE / protocol issues that may allow abnormal device control
- issues that may cause the client to perform unintended actions
- permission, authorization, or security bypasses
- tampering risks in releases, installers, or update packages
- build scripts, dependencies, or supply-chain risks
- other issues that may affect user, device, repository, or community security

---

## 2. What is usually not a security issue?

The following are usually not security issues. Please use `SUPPORT.md` or the related repository Issue instead:

- normal installation failures
- client startup failures
- unstable Bluetooth connection
- device detection problems
- documentation errors
- feature requests
- general compatibility issues
- bugs that do not involve sensitive information or security bypasses

General support entry:

👉 [`SUPPORT.md`](https://github.com/AhakeyAI/.github/blob/main/SUPPORT.md)

---

## 3. How to report a security issue

Please do not open a public Issue.

You can report security issues privately via:

```text
Email: security@ahakey.com
Subject: [AhaKey Security] Short issue summary
```

If the repository has GitHub Private Vulnerability Reporting enabled, you may also submit a private vulnerability report from the repository Security page.

---

## 4. What to include in your report

Please include as much of the following as possible:

- issue description
- affected scope
- affected repository, version, device, or platform
- steps to reproduce
- screenshots, logs, or PoC if available
- your estimated severity
- your contact information
- whether the issue is already public or only known to you

The more complete the report is, the easier it is for us to confirm and fix the issue.

---

## 5. What not to do

Before the issue is confirmed and fixed, please do not:

- publicly disclose vulnerability details
- post secrets, tokens, private keys, vulnerability details, or exploit methods in public Issues
- use the issue to access, modify, or control other users' devices or data
- expand testing to unrelated users, devices, or services
- use the vulnerability for attacks, extortion, malicious distribution, or commercial threats
- publicly distribute controlled source, firmware materials, hardware design files, or production materials

---

## 6. How we handle reports

After receiving a report, we will try to:

1. acknowledge the report;
2. decide whether it is a security issue;
3. assess impact and severity;
4. plan a fix, mitigation, or public note;
5. publish a fix, update documentation, or remove sensitive content if needed;
6. thank the reporter when appropriate.

AhaKey is currently maintained by a small team. We try to handle security issues promptly, but response time may depend on complexity and impact.

---

## 7. Controlled source and hardware materials

AhaKey firmware source, hardware design files, and production materials are not public by default.

Please report through this security process if you find:

- controlled firmware source publicly uploaded to GitHub / Gitee / GitLab
- schematics, PCB files, or production materials publicly redistributed without authorization
- abnormal access to private repositories
- someone selling, forwarding, or sharing controlled materials
- controlled materials being used for cloning, board reproduction, manufacturing, resale, or competing hardware development

Without authorization, controlled materials may not be publicly uploaded, redistributed, shared, sold, used for board reproduction, cloning, manufacturing, resale, or competing hardware development.

---

## 8. Recognition for security reports

If you responsibly report a valid security issue, AhaKey may thank or credit you when appropriate.

Public recognition will respect the reporter's preference and the security fix timeline.

<p align="right"><a href="#top">↑ Back to top</a></p>
