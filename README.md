# dev-test-tools

> 轻量、可复用的测试工具集：跨项目测试执行 / 覆盖率聚合 / 缺陷台账 / 测试报告生成

---

## 特性

- 跨项目测试执行（pytest 统一编排）
- 覆盖率聚合（多项目覆盖率汇总）
- 缺陷台账管理（缺陷登记/跟踪/关闭闭环）
- 测试报告生成（CSV/Markdown 模板化）
- 与调度器协同（夜间测试任务经 dev-task-scheduler 触发）

---

## 快速开始

```bash
# CLI 接口
dev-test-tools run / coverage / report / defect
```

## 技术栈

Python 3.10+ / pytest + coverage / CSV（UTF-8 BOM）

## 与技能库的关系

本项目承载**工具实现**，方法论/流程由对应技能库承载（单一信源互补）：
- .trae/skills/role-testing（方法论技能，单一信源互补）

跨项目调用遵循 `PROJECT_ROOT` 环境变量注入规范（对齐 `tool_calling_standard.md`）。

---

## 治理

- 遵循 DevProjectTeamSkill 全生命周期与铁律卡
- 授权依据：AUTH-024（`/Volumes/BR256G/DevProjectTeamSkill/台账/14_授权登记.csv`）
- 立项依据：INC-2026-09-01-003（评分 95/100）

---

*知识产权所有：段波（验证邮箱：duanbo.douglas@163.com）*
