# Agent Skills Index

**Language:** English | [中文](./README.zh-CN.md)

**Author contact:** `vx:190569625`

`agent-skills` is the main index for reusable agent skills maintained by `onlyloveher`.

Each skill lives in its own standalone GitHub repository. This repository is only an index: it helps people and agents discover skills, understand their real use cases, and find the right repository quickly.

## Available Skills

| Skill | Repository | Runtimes | What it helps you do |
| --- | --- | --- | --- |
| [wechat-local-reader](https://github.com/onlyloveher/wechat-local-reader-skill) | [onlyloveher/wechat-local-reader-skill](https://github.com/onlyloveher/wechat-local-reader-skill) | Codex, OpenClaw, Hermes | Drop a WeChat Official Account article link into an agent, let the agent read it locally, extract the content, and generate a Markdown document for summary, analysis, notes, or downstream tasks. |
| [formal-chinese-docx-proposal-qa](https://github.com/onlyloveher/formal-chinese-docx-proposal-qa) | [onlyloveher/formal-chinese-docx-proposal-qa](https://github.com/onlyloveher/formal-chinese-docx-proposal-qa) | Codex, OpenClaw, Hermes | Draft, revise, and QA formal Chinese DOCX proposal documents, including evidence boundaries, structure, clickable TOC behavior, captions, formatting, diagram readability, and delivery checks. |
| [flowchart-delivery-qa](https://github.com/onlyloveher/flowchart-delivery-qa) | [onlyloveher/flowchart-delivery-qa](https://github.com/onlyloveher/flowchart-delivery-qa) | Codex, OpenClaw, Hermes | Create or review flowcharts, swimlane diagrams, architecture diagrams, SVG previews, and PDF deliverables with checks for logic, lanes, arrow routing, wording cleanup, and format fidelity. |

## Repository Rules

- `agent-skills` is the main index repository.
- Every skill must live in a separate standalone repository.
- Every skill repository must provide separate English and Chinese README files, linked at the top of each file.
- Every skill README should explain both the human value and the machine-readable integration details.
- Every skill README must include author contact: `vx:190569625`.

## Machine-Readable Index

Agents and tools can read [`skills.json`](./skills.json) to discover available skills, supported runtimes, keywords, and integration metadata.
