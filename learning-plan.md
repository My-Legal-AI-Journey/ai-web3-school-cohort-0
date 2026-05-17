# 个人学习计划 — Week 1

> 画像：**AI 实操型（vibe coding）+ Web3 新手 + 法律方向 + 每晚 2h**  
> Handbook：https://aiweb3.school/zh/handbook/

## 你的学习原则（Agent 会按这个拆任务）

- **每天只追求「最小路径」完成**；推荐路径有余力再做。
- **不写复杂代码**：让 Claude Code 生成；你只改文字、点按钮、抄链接。
- **法律视角**：关注留痕、人工确认、可验证记录 — 与 Week 1「AI 输出 → 人审 → 链上验证」同构。

## Week 1 目标（2 小时/晚可完成版）

| 目标 | 做法 |
|------|------|
| 懂基础概念 | 每天 15–20 分钟 Handbook + Agent 用中文解释 |
| AI 工具实践 | Claude Code 整理笔记 / 生成 quiz 或流程图 |
| 测试网 | MetaMask + Sepolia，按 checklist 一步一步 |
| 最小合约 | **Remix 点选部署**（不强制 Hardhat） |
| 交叉实验 | AI 写步骤 → 你复核 → 钱包确认 → 浏览器截图 |
| PoW | `daily/` + 链接进 repo，能打卡即可 |

## 阅读路径（法律学员精简版）

### 每晚 15 分钟阅读（按顺序）

1. Handbook 首页 — 四层地图（已读可跳过）
2. Web3 基础 — 账户、钱包、签名、交易（侧边栏）
3. [Agent Workflow](https://aiweb3.school/zh/handbook/bridge/agent-workflow/) — **重点**：哪些必须人工
4. [Agent Wallet](https://aiweb3.school/zh/handbook/bridge/agent-wallet/) — Agent 不能拿私钥
5. [Verifiable AI](https://aiweb3.school/zh/handbook/bridge/verifiable-ai/) — 与法律「可验证材料」对照（可选）

### 可暂缓（Week 1 不强制）

- Hardhat / Foundry 工程化
- 模型微调、LoRA
- 进阶账户抽象实操

## 7 天节奏（每天 19:00–21:00）

| 天 | 19:00–19:40 | 19:40–20:40 | 20:40–21:00 |
|----|-------------|-------------|-------------|
| **D1 一** | 读 `profile.md`；`gh` 已登录则 **创建远程 repo 并 push** | Claude Code：根据本文件生成 **概念卡片**（LLM/agent/钱包） | 写 `daily/`，提交打卡草稿 |
| **D2 二** | Handbook：账户与钱包（20 分钟） | 安装 MetaMask + 新建**共学营钱包** | 笔记 `tasks/web3-wallet-lab.md`（不写私钥） |
| **D3 三** | 切换 Sepolia + 领测试币 | 发 1 笔小额转账 | Etherscan 抄 tx hash 进笔记 |
| **D4 四** | 看 Remix 入门视频/文档（15 分钟） | Remix 部署 Storage，**只点界面** | 记录合约地址 + 浏览器链接 |
| **D5 五** | Claude Code：写「交叉实验步骤」 | 你按步骤复核 + 钱包确认 1 次写入 | `experiments/cross-01.md` |
| **D6 六** | Agent 生成 **流程图**（AI→人审→链上） | 放入 `experiments/`，README 写分工 | 补 Week1 checklist |
| **D7 日** | 整理 `submissions/week1-pow.md` | 3 条行业观察（法律×AI×链） | 打卡 + 休息 |

## 给 Claude Code 的固定口令（可复制）

```text
我是法律背景学员，不会独立写代码。请用中文、分步骤、不要跳步：
1）今天要完成：[粘贴 learning-plan 当天任务]
2）输出：勾选清单 + 我需要点哪里 + 常见问题
3）不要让我一次性做超过 30 分钟的事
```

## Week 1 交付清单

| 交付物 | 位置 |
|--------|------|
| 学习计划 / 画像 | 本文件、`profile.md` |
| 每日打卡 | `daily/` |
| Web3 笔记 | `tasks/web3-wallet-lab.md` |
| 交叉实验 | `experiments/cross-01.md` |
| 汇总提交 | `submissions/week1-pow.md` |

## 不懂问题清单

1. 法律场景里，链上「可验证」和诉讼证据标准差在哪里？
2. vibe coding 完成的 demo 算不算合格 PoW？
3. Week 2 支付/身份是否和法律文书送达有类比？

---

*Agent 每晚可根据 `daily/` 把「明天最小路径」缩成 3 条以内。*
