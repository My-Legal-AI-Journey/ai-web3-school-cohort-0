# Learning Agent 配置说明

> **勿在本文件写入 API Key、Token、助记词或私钥。**

## 主工具

- **Claude Code**（终端）
- 可选辅助：Cursor Agent（本对话）

## API 路由

| 项目 | 值 |
|------|-----|
| 路由方式 | cc switch |
| 当前 profile | _待填写，如 glm / zai / custom_ |
| 接口类型 | OpenAI / Anthropic **兼容 API** |
| Base URL | _待填写_ |
| 默认模型 ID | _待填写_ |

## 与官方路径的差异

- 未使用 Anthropic 官方订阅；通过兼容 API 调用。
- 工具调用、长上下文、部分模型特性可能与官方 Claude 有差异 — 关键链上参数与事实须人工核对。

## WCB Agent API（可选，后续启用）

- 文档：https://web3career.build/llms.txt
- Secret 环境变量名建议：`WCB_AGENT_SECRET_API_KEY`（仅本地 / secrets，不进 repo）
- 写入型操作（提交任务、证据）须先展示 payload，经本人确认后再调用。

## Agent 职责边界

| Agent 可做 | 必须人工 |
|------------|----------|
| 生成学习计划、笔记、打卡草稿 | 在 WCB / 打卡平台点击提交 |
| 生成合约脚本说明、Remix 步骤 | 钱包签名、授权、转账 |
| 整理 Handbook feedback 草稿 | 确认后 push 到 public repo |
| `git status` / 建议 commit message | `gh auth login`、创建远程 repo、最终 push |
