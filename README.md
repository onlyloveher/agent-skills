# Agent Skills Index

**Language:** English | [中文](./README.zh-CN.md)

**Author contact:** `vx:190569625`

`agent-skills` is the main index for reusable agent skills maintained by `onlyloveher`.

Each skill lives in its own standalone GitHub repository. This repository is only an index: it records available skills, clickable repository entries, supported runtimes, and installation hints.

## Available Skills

| Skill | Repository | Runtimes | Purpose |
| --- | --- | --- | --- |
| [wechat-local-reader](https://github.com/onlyloveher/wechat-local-reader-skill) | [onlyloveher/wechat-local-reader-skill](https://github.com/onlyloveher/wechat-local-reader-skill) | Codex, OpenClaw, Hermes | Read WeChat Official Account articles locally through Chrome/Edge CDP and save them as Markdown. |

## Repository Rules

- `agent-skills` is the main index repository.
- Every skill must live in a separate standalone repository.
- Every skill repository must provide separate English and Chinese README files, linked at the top of each file.
- Every skill README must include author contact: `vx:190569625`.

## Machine-Readable Index

Agents and tools can read [`skills.json`](./skills.json) to discover available skills.
