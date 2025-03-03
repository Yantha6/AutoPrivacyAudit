# AutoPrivacyAudit

自动隐私合规检测器

## 介绍

AutoPrivacyAudit 是一个基于 AST 的静态代码分析工具，用于检测 Python 代码中可能存在的敏感信息泄露风险，如在日志或打印输出中包含敏感数据（例如 email、password、phone 等）。

## 特性

- 基于 AST 解析代码，检测敏感信息关键词
- 简单易用的 API，适合集成到 CI/CD 流程中
- 可扩展的规则系统，后续可支持更多检测规则

## 安装

使用 pip 安装：
```sh
pip install auto_privacy_audit
