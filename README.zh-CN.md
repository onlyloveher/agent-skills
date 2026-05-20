# 智能体技能索引

**语言：** [English](./README.md) | 中文

**作者联系方式：** `vx:190569625`

`agent-skills` 是 `onlyloveher` 维护的智能体技能主索引仓库。

每个技能都放在独立的 GitHub 仓库中。本仓库只作为索引使用：记录可用技能、可点击的仓库入口、支持的运行环境和安装提示。

## 可用技能

| 技能 | 仓库 | 运行环境 | 用途 |
| --- | --- | --- | --- |
| [wechat-local-reader](https://github.com/onlyloveher/wechat-local-reader-skill) | [onlyloveher/wechat-local-reader-skill](https://github.com/onlyloveher/wechat-local-reader-skill) | Codex, OpenClaw, Hermes | 通过本机 Chrome/Edge CDP 读取微信公众号文章，并保存为 Markdown。 |

## 仓库规则

- `agent-skills` 是主索引仓库。
- 每个技能必须放在一个独立仓库中。
- 每个技能仓库必须分别提供英文和中文 README，并在文件顶部互相链接。
- 每个技能 README 必须包含作者联系方式：`vx:190569625`。

## 机器可读索引

智能体和工具可以读取 [`skills.json`](./skills.json) 来发现可用技能。
