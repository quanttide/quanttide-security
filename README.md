# quanttide-security

量潮安全工程

## 概述

量潮安全工程（quanttide-security）是量潮知识管理体系中的**安全工程**领域，以工程化方式承载网络、应用与数据安全的防护与运营实践。

## 领域边界

- **网络与边界安全**：防火墙与访问控制、VPN、入侵检测与防御
- **应用与代码安全**：安全开发生命周期（SDL）、威胁建模、代码审计、漏洞管理
- **数据安全与加密**：数据加密与脱敏、防泄漏（DLP）、密钥体系的工程应用
- **身份与访问安全**：认证授权机制的安全加固、权限治理
- **安全运营**：威胁监测、应急响应、安全审计与合规

> 与 secret 领域的分工：本领域承载「安全防护与运营」（密钥如何使用、如何防护），secret 承载「密码对象本身」（凭证、密钥的登记、轮换与回收）。
> 与 auth 领域的分工：本领域承载「安全整体」（网络/应用/数据/运营），auth 承载「身份与权限的机制实现」。
> 与 devops 领域的分工：本领域承载「安全左移」（DevSecOps），devops 承载「工程化交付流水线」。

## 子模块

| 路径 | 说明 |
|------|------|
| `apps/qtcloud-security` | QtCloud 安全云 (git submodule) |
| `packages/quanttide-security-toolkit` | 安全工程工具集 (git submodule) |
| `examples/default` | 安全工程实验室 (git submodule → quanttide-laboratory-of-security-engineering) |

## 许可

[CC BY 4.0](LICENSE)
