# 智能体技能索引

**语言：** [English](./README.md) | 中文

**作者联系方式：** `vx:190569625`

`agent-skills` 是 `onlyloveher` 维护的智能体技能主索引仓库。

每个技能都放在独立的 GitHub 仓库中。本仓库只作为索引使用：帮助人和智能体发现技能、理解真实使用场景，并快速进入对应技能仓库。

## 可用技能

| 技能 | 仓库 | 运行环境 | 它能帮你做什么 |
| --- | --- | --- | --- |
| [wechat-local-reader](https://github.com/onlyloveher/wechat-local-reader-skill) | [onlyloveher/wechat-local-reader-skill](https://github.com/onlyloveher/wechat-local-reader-skill) | Codex, OpenClaw, Hermes | 把微信公众号文章链接丢给智能体，让智能体在本机读取文章、提取内容并生成 Markdown 文档，后续可以继续摘要、分析、做笔记或拆解任务。 |

## 仓库规则

- `agent-skills` 是主索引仓库。
- 每个技能必须放在一个独立仓库中。
- 每个技能仓库必须分别提供英文和中文 README，并在文件顶部互相链接。
- 每个技能 README 应同时说明“对人的使用价值”和“对智能体/工具的接入方式”。
- 每个技能 README 必须包含作者联系方式：`vx:190569625`。

## 机器可读索引

智能体和工具可以读取 [`skills.json`](./skills.json) 来发现可用技能、支持的运行环境、关键词和集成元数据。
