# OpenClaw 中文 Skills 仓库

这是一个持续更新的 OpenClaw 中文 Skills、模板与演示仓库。

当前先围绕一条最小闭环来构建：

- 研究资料整理
- 选题到初稿
- 信息到周报

这个仓库同时承担两件事：

1. 作为 skills 的源码仓库
2. 作为 GitHub Pages 项目展示页的内容来源

## 当前收录的 skills

- `research-digest-zh`
- `idea-to-draft-zh`
- `source-to-weekly-brief-zh`

每个 skill 当前都包含：

- `SKILL.md`
- `agents/openai.yaml`
- `references/examples.md`
- `templates/`
- `assets/sample-output-*.md`

## 仓库结构

```text
skills/
  research-digest-zh/
  idea-to-draft-zh/
  source-to-weekly-brief-zh/
docs/
  index.html
  styles.css
```

## 发布到 GitHub

1. 创建远端仓库
2. 添加 remote：

```bash
git remote add origin <你的 GitHub 仓库地址>
```

3. 提交并推送：

```bash
git add .
git commit -m "Initial OpenClaw zh skills starter kit"
git branch -M main
git push -u origin main
```

## 启用 GitHub Pages

在 GitHub 仓库设置中：

1. 打开 `Settings -> Pages`
2. Source 选择 `Deploy from a branch`
3. Branch 选择 `main`
4. Folder 选择 `/docs`

之后 GitHub Pages 会直接发布 `docs/` 里的项目展示页。

## 当前状态

这个仓库已经适合继续做三类事情：

- 持续沉淀 OpenClaw 中文 skills
- 通过 GitHub Pages 展示项目
- 后续选择部分 skill 发布到 ClawHub
