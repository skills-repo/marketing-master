---
name: marketing-master
description: >-
  AI Agent 营销大师技能库：覆盖 SEO 审计与内容营销、高转化文案撰写、内容策略规划、着陆页构建四大能力，让独立开发者与小团队也能专业地推向市场。触发词："SEO"、"关键词研究"、"技术
  SEO"、"文案"、"PAS"、"AIDA"、"StoryBrand"、"着陆页"、"转化率"、"内容策略"、"编辑日历"、"主题集群"、"内容衰减"。
agent_created: true
metadata:
  version: 1.0.0
  category: 营销
  difficulty: 进阶
  platform: skills-repo
  created: 2026-07-26
  updated: 2026-08-09
  architecture: superpower
tags:
  - marketing
  - seo
  - copywriting
  - content-strategy
  - landing-page
---

# Marketing Master 营销大师

> 把 AI 编程助手变成一名覆盖「SEO 审计 → 内容策略 → 文案撰写 → 着陆页构建」全链条的营销搭档。本技能采用 superpower 架构：`SKILL.md` 只做路由，深层方法论放在 `references/`，细粒度能力放在 `skills/` 子技能，按需加载、互不干扰。

## 何时使用

- 需要做 **SEO 审计**：关键词研究、技术 SEO 诊断、竞品与 SERP 分析
- 需要写**高转化文案**：着陆页、广告、邮件，用 PAS / AIDA / StoryBrand 框架
- 需要规划**内容策略**：主题集群、编辑日历、内容衰减检测
- 需要**构建着陆页**：高转化结构、视觉层次、响应式与 CTA 优化

## 能力索引（超级技能路由）

| 任务 | 调用 | 关键词（grep 线索） |
|------|------|---------------------|
| SEO 审计与内容营销 | `skills/seo-auditor/SKILL.md` | seo-auditor, 关键词, 技术SEO, 竞品分析, SERP |
| 高转化文案撰写 | `skills/copywriting-pro/SKILL.md` | copywriting-pro, PAS, AIDA, StoryBrand, 文案, CTA |
| 内容策略规划 | `skills/content-strategist/SKILL.md` | content-strategist, 编辑日历, 主题集群, 内容衰减 |
| 着陆页构建 | `skills/landing-page-builder/SKILL.md` | landing-page, 转化率, Hero, 视觉层次, 响应式 |

> 路由规则：先判断任务属于「获取流量 / 创作内容 / 转化承接」哪一类；纯技术 SEO 调 `seo-auditor`，写词调 `copywriting-pro`，排期调 `content-strategist`，落地页调 `landing-page-builder`；需要串联全流程时读 `references/` 中的 playbook。

## 细粒度子技能（可单独安装）

| 子技能 | 路径 | 适用 |
|--------|------|------|
| seo-auditor | `skills/seo-auditor` | 关键词聚类、技术 SEO、竞品分析、内容审计 |
| copywriting-pro | `skills/copywriting-pro` | PAS/AIDA/StoryBrand 框架的着陆页与广告文案 |
| content-strategist | `skills/content-strategist` | 主题集群、编辑日历、内容衰减检测 |
| landing-page-builder | `skills/landing-page-builder` | 高转化结构、视觉层次、响应式、CTA 优化 |

## 适用场景

- 网站 SEO 健康检查与搜索引擎排名优化
- 产品发布/活动推广的文案与着陆页
- 博客/官网的长期内容规划与更新
- 独立开发者以低成本做专业级营销

## 限制

- 不涉及付费搜索（SEM/PPC）与社交媒体投放
- 不涉及大规模邮件营销自动化与 B2B 企业级策略
- 文案与 SEO 效果依赖产品定位准确性，不替代专业投放决策
