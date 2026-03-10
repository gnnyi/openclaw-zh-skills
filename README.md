# OpenClaw Chinese Skill Starter Kit

An opinionated starter kit for building Chinese-first OpenClaw skills around a
simple chain:

- research digest
- idea to draft
- weekly brief

This repository is designed to serve two jobs:

1. the source repo for the skills themselves
2. a GitHub Pages project page under `docs/`

## Included skills

- `research-digest-zh`
- `idea-to-draft-zh`
- `source-to-weekly-brief-zh`

Each skill includes:

- `SKILL.md`
- `agents/openai.yaml`
- `references/examples.md`
- `templates/`
- `assets/sample-output-*.md`

## Repository layout

```text
skills/
  research-digest-zh/
  idea-to-draft-zh/
  source-to-weekly-brief-zh/
docs/
  index.html
  styles.css
```

## Publish to GitHub

1. Create a new GitHub repository.
2. Add the remote:

```bash
git remote add origin <your-github-repo-url>
```

3. Commit and push:

```bash
git add .
git commit -m "Initial OpenClaw starter kit"
git branch -M main
git push -u origin main
```

## Enable GitHub Pages

In the GitHub repository settings:

1. Open `Settings -> Pages`
2. Set `Source` to `Deploy from a branch`
3. Choose branch `main`
4. Choose folder `/docs`

GitHub Pages will then publish the project page from `docs/`.

## Current status

The repo is ready for:

- GitHub versioning
- GitHub Pages project showcase
- later publishing of selected skills to ClawHub

