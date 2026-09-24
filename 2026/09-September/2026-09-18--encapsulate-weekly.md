---
title: encapsulate · 0914–0918
date: 2026-09-18
type: weekly
---

这周是集中补课周——API 本质 / 二次封装 / leaky abstraction / FastAPI / MCP / CI/CD / 软件测试体系，同时推进庄臣单证通提示词调试，中石油车辆轨迹完成需求会议，周五阅读《On Working with Wizards》做工作总结。

## 🧩 主线

### 学习：API 与 Web 工程

- **周一**：API 本质学习，调用大藏经 API，让 GPT 拆解 harness 仓库。
- **周二**：Deerpark API 学习，梳理 leaky abstraction 概念，接触 FastAPI，体验 Playwright MCP，确定学习方向。
- **周三**：庄臣回单单证通提示词调试（text→table 格式问题修复 ✅）；学习 CI/CD。
- **周四**：参观小悠盘；中石油车辆轨迹 RPA 需求会议；绘制个人 IT 知识地图（已学/在学/待学）。
- **周五**：阅读《On Working with Wizards》；做月中工作总结。

## 🧠 学到 / 想明白的

- **leaky abstraction**：直接暴露 raw data 是泄露，调用后需要二次封装屏蔽细节——这是 API 设计的核心原则。
- **Node.js / TypeScript / Streamlit 关系**：JS 是语言，Node 是运行时，TS 是带类型的 JS，Streamlit 是 Python 快速出 UI 的框架——分清层次，不再混淆。
- **CI/CD 理解**：Continuous Integration = 每次 push 自动跑测试；Continuous Deployment = 测试过了自动部署——把手动发布变成流水线。
- **IT 知识地图价值**：可视化区分已学/在学/待学，避免焦虑，聚焦当下该学的。
- **中石油车辆轨迹 RPA 设计思路**：遍历车牌子文件夹 → 查表找网址账密 → 自动操作截图 → 保存至对应子文件夹。
