# Document Writing Skill / 文档创作 Skill

A Chinese-language Codex skill for drafting, revising, reviewing, and verifying documents and creative work. It organizes writing around the reader's purpose, the evidence or story that supports the content, and the final artifact the reader receives.

这是一个中文 Codex Skill，适用于报告、工作沟通、技术与学习材料、Agent 指令、故事及制作文档。它帮助 Agent 按读者目的组织内容，并在交付前检查事实、结构和实际产物。

## 安装

使用 [skills CLI](https://github.com/vercel-labs/skills) 安装到 Codex 的全局技能目录：

```bash
npx skills add goosmanlei/document-writing-skill --skill document-writing -g -a codex
```

想先查看仓库中可安装的技能，可运行 `npx skills add goosmanlei/document-writing-skill --list`。安装后可在任务中明确使用 `$document-writing`，也可直接提出文档创作或修订需求。

Skill 位于 [`skills/document-writing/`](skills/document-writing/SKILL.md)：`SKILL.md` 是入口，`references/` 是按任务读取的参考文件，`agents/openai.yaml` 提供 Codex 显示名称和隐式调用设置。

## 使用范围

- 创作、改写、修订和审阅本地或在线文档与作品。
- 按实际用途选择论证与说明、创作与叙事、Agent 文档、修订与交付参考。
- 配合对应格式或平台的技能完成写入、渲染及回读。

本仓库只包含 Skill 本身，不包含其研究记录、历史案例或评测数据。

## 许可

[MIT License](LICENSE)
