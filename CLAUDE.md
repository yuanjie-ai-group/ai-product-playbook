# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

A Chinese-language knowledge base: "AI 产品全链路修炼手册" — documenting the growth path from engineer → product → operations → business → co-founder at an AI startup called 元境 (yuanjie). **This is a content-only repo with no code, no build system, no tests.**

## Directory Taxonomy

Nine numbered sections forming a deliberate learning progression:

| # | Directory | Focus |
|---|-----------|-------|
| 01 | 产品思维 | Product fundamentals: user research, requirements, design, competitive analysis |
| 02 | AI产品专项 | AI-specific design patterns (conversational, generative, assistant, agent, search-augmented) |
| 03 | 增长与运营 | Growth frameworks, content ops, community, acquisition channels |
| 04 | 数据驱动 | Metrics, A/B testing, user behavior analysis, analytics tools |
| 05 | 商业与战略 | Business models, pricing, market positioning, fundraising |
| 06 | 团队与领导力 | Team building, cross-department collaboration, OKR, co-founder skills |
| 07 | 案例研究 | Case studies: successes (ChatGPT, Cursor, etc.), failures, and 元境 internal retrospectives |
| 08 | 认知升级 | Mental models, communication, industry cognition |
| 09 | 工具箱 | Templates (PRD, competitive analysis, BP) and tool recommendations |

Each section has a `README.md` explaining its learning objectives and subdirectory contents.

## Content Conventions

- **File naming**: `YYYY-MM-DD-描述性名称.md`
- **Required sections in every article**: 背景 (background), 实践过程 (practice), 效果/数据 (results/data), 经验总结 (takeaways)
- **Tags**: Use `#产品` `#增长` `#运营` `#商业` `#领导力` `#AI` `#案例`
- **Language**: All content in Chinese
- **Principle**: 实战优先 — all content must connect to 元境's actual product, not pure theory

## Case Study Framework (07-案例研究)

Each case study should answer six questions:
1. 产品定位 — what problem, who is the user
2. 核心体验 — what is the Aha Moment
3. 增长策略 — where do users come from, why do they recommend
4. 商业模式 — how it makes money, unit economics
5. 技术壁垒 — unique technical advantages
6. 可借鉴点 — what 元境 can learn from it

## Claude Code Skills Integration

This repository is designed to be used with an extensive set of Claude Code skills (76+) and commands (16+). When working with the user, leverage these skills to accelerate content creation:

| Stage | Key Skills | Quick Commands |
|-------|-----------|----------------|
| 01-产品思维 | `discovery-process`, `jobs-to-be-done`, `user-story`, `prd-development` | `/write-prd`, `/discover` |
| 03-增长与运营 | `acquisition-channel-advisor`, `seo`, `seo-geo`, `seo-content` | `/keyword-research`, `/audit-page`, `/write-content` |
| 05-商业与战略 | `business-health-diagnostic`, `roadmap-planning`, `positioning-statement` | `/strategy`, `/plan-roadmap`, `/prioritize` |
| 06-团队与领导力 | `director-readiness-advisor`, `altitude-horizon-framework` | `/leadership-transition` |
| 07-案例研究 | `company-research`, `research`, `research-deep` | - |

**Reference**: See [SKILL_GUIDE.md](./SKILL_GUIDE.md) for complete documentation.

**Usage**: Trigger skills naturally (e.g., "用JTBD分析这个需求" or "/write-prd 智能客服功能").

## When Editing This Repo

- Respect the numbered directory structure; don't add new top-level directories without discussion
- New articles go into the appropriate subdirectory under the right numbered section
- Empty subdirectories use `.gitkeep` as placeholders — remove `.gitkeep` once real content exists
- The README.md in each section describes its scope; keep it updated when adding content
- When creating new content, suggest relevant skills to the user (e.g., "可以用 `/write-prd` 来编写这个产品需求")
