# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 新增

- 注册子模块：`apps/qtcloud-security`、`packages/quanttide-security-toolkit`、`examples/default`
- 注册子模块：`data/context`、`data/journal`
- 实验室新增 PoC 规划：漏洞管理与安全审计（对象 qtcloud-secret，子模块 `examples/default`）

### 变更

- 领域中文名更名：网络安全 → 安全工程
- 领域定义完善：概述、领域边界（五个能力域）、与 secret/auth/devops 领域的分工
- 实验室仓库更名：`quanttide-laboratory-of-software-security` → `quanttide-laboratory-of-security-engineering`
- QtCloud 安全云 README 落地：产品能力、相邻云分工、仓库结构规划；对标 Wazuh，首发能力域为漏洞管理、安全审计（子模块 `apps/qtcloud-security`）

## [0.1.0] - 2026-08-16

### 新增

- 初始化网络安全领域仓库
