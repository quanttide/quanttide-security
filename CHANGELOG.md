# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 新增

- 注册子模块：`apps/qtcloud-security`、`packages/quanttide-security-toolkit`、`examples/default`
- 注册子模块：`data/context`、`data/journal`
- 实验室 PoC-001 执行完成：漏洞管理与安全审计（对象 qtcloud-secret @ `cec7701`；产出漏洞台账 v1、审计报告 v1、复盘报告 v1 与 8 层扫描产物，子模块 `examples/default`）
- 实验室 PoC-002 执行完成：漏洞管理与安全审计（对象 qtcloud-auth @ `f017ffa`；产出 18 条发现与 6 层扫描产物，子模块 `examples/default`）
- 语境仓库新增工作流总结：`security-audit-poc-workflow.md`（子模块 `data/context`）
- QtCloud 安全云三端 MVP 落地（子模块 `apps/qtcloud-security`）：provider/studio/cli 并行开发并合并联调，端到端复现实验室审计流程（8 层扫描 → 归一化 → 台账 → 状态机 → 报告）

### 变更

- 领域中文名更名：网络安全 → 安全工程
- 领域定义完善：概述、领域边界（五个能力域）、与 secret/auth/devops 领域的分工
- 实验室仓库更名：`quanttide-laboratory-of-software-security` → `quanttide-laboratory-of-security-engineering`
- QtCloud 安全云 README 落地：产品能力、相邻云分工、仓库结构规划；对标 Wazuh，首发能力域为漏洞管理、安全审计（子模块 `apps/qtcloud-security`）

## [0.1.0] - 2026-08-16

### 新增

- 初始化网络安全领域仓库
