# OpenClaw 中文 Skills 起步仓库

这个目录是一个面向中文场景的 OpenClaw 技能起步集合，围绕一条最小闭环：

1. `research-digest-zh`
2. `idea-to-draft-zh`
3. `source-to-weekly-brief-zh`

设计目标是先做窄能力、快速形成可演示结果，再基于真实使用反馈迭代并发布到 ClawHub。

## 目录结构

- `research-digest-zh/`
- `idea-to-draft-zh/`
- `source-to-weekly-brief-zh/`

每个技能至少包含：

- `SKILL.md`
- `templates/`
- `references/examples.md`
- `assets/sample-output-*.md`

## 为什么是这三个

这三项能形成一条可复用链路：

- 资料整理 -> 结构收束 -> 周期输出

它们更容易验证质量，也更容易对外展示。

## 使用方式

OpenClaw 会从 `<workspace>/skills` 读取本地技能。本目录已符合该约定。

建议测试提示词：

- "使用 `research-digest-zh` 将这些链接整理成中文研究摘要。"
- "使用 `idea-to-draft-zh` 将这个主题整理成中文初稿。"
- "使用 `source-to-weekly-brief-zh` 汇总本周来源更新并生成中文简报。"

## 后续迭代顺序

1. 收紧触发条件和输出契约
2. 每个技能增加真实样例产物
3. 增加评测提示词与回归清单
4. 按优先级发布到 ClawHub
