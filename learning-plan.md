# 个人学习计划 — Week 1

> 基于 [Handbook](https://aiweb3.school/zh/handbook/) 与共学营 Week 1 大纲。  
> 画像：**AI 熟悉 + Web3 新手 + 能独立开发**。

## Week 1 目标（最小集）

- [ ] 理解 LLM / prompt / workflow / agent / tool use 边界
- [ ] 完成测试网：钱包 → 领币 → 转账 → 浏览器验证
- [ ] 部署最小合约并完成一次读 + 一次写
- [ ] 完成一次 **AI 生成 → 人工复核 → 钱包确认 → 链上验证** 交叉实验
- [ ] 本 repo 有可提交的 PoW（commit、daily、experiments）

## 阅读路径（按 Handbook 四层地图）

### 已具备基础 — 快速扫读

- AI 基础：重点看 [Agent Workflow](https://aiweb3.school/zh/handbook/bridge/agent-workflow/) 中与 human-in-the-loop 相关的边界
- 你已有 Skills 实践，可对照 Handbook 补术语即可

### 本周主攻 — 逐节阅读

| 优先级 | Handbook 章节 | 目的 |
|--------|-----------------|------|
| P0 | [Web3 基础](https://aiweb3.school/zh/handbook/) 侧边栏 — 账户/钱包/交易相关 | 测试网操作语言 |
| P0 | [Web3 Tool Use](https://aiweb3.school/zh/handbook/bridge/web3-tool-use/) | Agent 如何调用链上工具（理论） |
| P0 | [Agent Workflow](https://aiweb3.school/zh/handbook/bridge/agent-workflow/) | 交叉实验流程设计 |
| P1 | [Agent Wallet](https://aiweb3.school/zh/handbook/bridge/agent-wallet/) | 权限与「Agent 不碰私钥」 |
| P1 | [AI Security](https://aiweb3.school/zh/handbook/bridge/ai-security/) | 输出验证、越权防护 |
| P2 | [Chain-aware Context](https://aiweb3.school/zh/handbook/bridge/chain-aware-context/) | Week 2 预热 |

## 7 天执行节奏（可调整）

| 天 | 最小路径 | 推荐路径 | 挑战路径 |
|----|----------|----------|----------|
| D1 | 确认画像；`gh auth login`；完善 `profile.md` | 创建 GitHub 远程 repo 并 push | 配置 WCB Agent API（仅本地 secret） |
| D2 | 读 Handbook Web3 账户概念；安装 MetaMask | Sepolia 领测试币 | 对比 EOA vs 智能账户阅读笔记 |
| D3 | 发送 1 笔测试转账 + Etherscan 记录 | 写 `tasks/web3-wallet-lab.md` | 第二笔转账给不同地址 |
| D4 | Remix 部署 Storage 合约 | 一次 `set` + 一次 `get` + 浏览器链接 | Hardhat/Foundry 本地部署 |
| D5 | Claude Code 生成交叉实验步骤文档 | 执行交叉实验并写 `experiments/cross-01.md` | 画完整 workflow + 失败点 |
| D6 | 可交互 demo（quiz 或流程图）入 `experiments/` | README 写 agent vs 人工分工 | 两工具对比（Claude Code vs Cursor） |
| D7 | 整理 `submissions/week1-pow.md` | 行业观察 3 条笔记 | 进阶：ETH skill 或 OpenClaw 阅读笔记 |

## Week 1 交付清单

| 交付物 | 文件/位置 |
|--------|-----------|
| Learning Agent 配置 | `agent-config.md` |
| 学习日志 | `daily/` |
| Web3 实验记录 | `tasks/web3-*.md` |
| 交叉实验 | `experiments/cross-01.md` |
| Handbook 反馈 | `handbook-feedback/` |
| 打卡 / WCB 提交 | `daily/` 内链接 + `submissions/` |

## 不懂问题清单（持续更新）

1. Session Key / 账户抽象在 Week 1 需要实操到什么程度？
2. WCB 打卡与 repo commit 的对应关系是否有一对一 rubric？
3. 兼容 API 下 Claude Code 的 tool use 与官方差异如何记录为 PoW？

---

*下次更新：完成 Web3 第一天实验后，由 Agent 根据 `daily/` 进展修订本表。*
