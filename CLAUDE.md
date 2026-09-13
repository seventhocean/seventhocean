# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

This is a **GitHub profile repository** — its only purpose is to host `README.md` as a custom profile page for the user **Winter** (seventhocean). There is no source code, no build system, no tests, and no dependencies.

## Making Changes

The only meaningful file is `README.md`. It uses embedded HTML, shields.io badges, animated SVGs, and GitHub stats cards (github-readme-stats, github-profile-trophy). When editing:

- Keep the existing HTML/Markdown hybrid style consistent.
- Badge image URLs follow the pattern: `https://img.shields.io/badge/<label>-<message>-<color>?style=flat-square&logo=<name>&logoColor=white`
- Project / stats / language cards are served by the third-party `github-readme-stats` **mirror** `github-readme-stats-one.vercel.app`. ⚠️ The official `github-readme-stats.vercel.app` deployment is frequently paused (HTTP 503 `DEPLOYMENT_PAUSED`); if the cards break, curl the URLs and switch to a working mirror or self-host.
- The contribution heatmap uses `ghchart.rshah.org` (not Vercel-dependent), the streak card uses `streak-stats.demolab.com`, and the animated typing banner uses `readme-typing-svg.demolab.com`.
- `github-profile-trophy.vercel.app` and `github-readme-activity-graph.vercel.app` currently return HTTP 402 (payment required) — do not use them.
- Always verify every `<img src>` in `README.md` returns HTTP 200 with an `image/*` content type before pushing, since these are all third-party services.

## User Context

- Name: Winter (冬天)
- Location: Guangzhou, China
- Positioning: AI 订阅服务与效率工具分享 · 自媒体创作者 · 记录 AI 实践、技术与生活
- Tagline: “一个喜欢把复杂的东西讲清楚的人。” / AI 订阅 · 工作流 · 实战教程
- Personal homepage: https://waitwinter.homes
- Blog: https://winterwait.com (API: https://api.winterwait.com/api/v1/articles)
- AI shop: https://winterai.cc
- Email: waitwinter0521@163.com
- Zhihu: https://www.zhihu.com/people/an-he-32-97
- Xiaohongshu: https://www.xiaohongshu.com/user/profile/630ca5050000000012003523
- Interests: AI 应用、提示词工程、AI 工作流、Linux、云计算
- Tech: Python, TypeScript, Go, JavaScript, Shell, Kotlin, Vue, Flask, Docker, Kubernetes, Nginx, Redis, MySQL

### Sites / Products

| Site | URL |
|------|-----|
| 冬天 AI 小店 | https://winterai.cc |
| 冬天 · Blog | https://winterwait.com |
| Winter · Mail | https://mail.wintermiss.com |
| Flower 生图模板 | https://waitsummer.online |
| Winter · VPS | https://winters.eu.cc |
| Winter · Api | https://waitsummer.eu.cc |

### Featured Projects

- `seventhocean/Keeper` — 类 Claude Code 的对话式运维 Agent (Python)
- `seventhocean/FriendPS_Tools` — Flower：模板仓库 + AI 生图平台 (TypeScript)
- `seventhocean/auto_packing` — DeepFlow 补丁包构建与分发工具 (Python)

### Theme

The profile uses a “冬日夜晚，走进那一盏温暖的窗” (winter-night, warm-window) visual concept as **visual guidance only** — do NOT write this phrase into the visible README text. Stat cards use the `tokyonight` theme, and the accent color is `#58A6FF`.
