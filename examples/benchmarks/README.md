<!-- DAGENO_AGENT_NAV_START -->

**Dageno Agent Project Map / Dageno Agent 项目导航**

If this repo is useful, you may also want the adjacent Dageno Agent projects for GEO, SEO, AI visibility, and content operations.
如果这个仓库对你有帮助，也可以看看这些相邻的 Dageno Agent 项目，用于 GEO、SEO、AI 可见性和内容增长工作流。

| Stage / 阶段 | Project / 项目 | Use it for / 用途 |
| --- | --- | --- |
| Diagnose / 诊断 | [seo-geo-audit](https://github.com/dageno-agents/seo-geo-audit) | SEO + GEO audit workflows for brands and agencies / 面向品牌和服务商的 SEO + GEO 诊断工作流 |
| Plan prompts / 提示词规划 | [geo-prompt-architecture](https://github.com/dageno-agents/geo-prompt-architecture) | AI visibility monitoring prompt system / AI 可见性监控提示词体系 |
| Generate topics / 生成选题 | [dageno-online-topic-prompt-generator](https://github.com/dageno-agents/dageno-online-topic-prompt-generator) | Dageno-ready Topic + Prompt generation from a real domain / 基于真实网站生成可导入 Dageno 的 Topic + Prompt |
| Build content / 内容生产 | [seo-geo-content-engine](https://github.com/dageno-agents/seo-geo-content-engine) | Full SEO/GEO content workflows / 完整 SEO/GEO 内容工作流 |
| Write from fanout / Fanout 写作 | [geo-content-writer](https://github.com/dageno-agents/geo-content-writer) | You are here: turn Dageno fanout into briefs, drafts, and review contracts / 当前项目：把 Dageno fanout 变成 brief、draft 和 review contract |
| Analyze organic growth / 分析自然增长 | [organic-content-intelligence](https://github.com/dageno-agents/organic-content-intelligence) | Search demand, page funnels, intent coverage, and GEO visibility / 搜索需求、页面漏斗、意图覆盖和 GEO 可见性分析 |
| Automate / 自动化 | [n8n-nodes-dageno](https://github.com/dageno-agents/n8n-nodes-dageno) | Dageno API node for n8n automation / 用于 n8n 自动化的 Dageno API 节点 |
| Learn API + MCP / API 与 MCP | [dageno-mcp-growth-playbook](https://github.com/dageno-agents/dageno-mcp-growth-playbook) | GEO reporting, prompt gaps, citation intelligence, and growth execution / GEO 报告、Prompt Gap、引用分析和增长执行手册 |

More projects / 更多项目: [geo-site-architecture-audit](https://github.com/dageno-agents/geo-site-architecture-audit), [brand-ai-performance-check](https://github.com/dageno-agents/brand-ai-performance-check), [geo-visual-content-engine](https://github.com/dageno-agents/geo-visual-content-engine), [seo-outreach-skill](https://github.com/dageno-agents/seo-outreach-skill).

Explore all repos / 查看全部项目: [github.com/dageno-agents](https://github.com/dageno-agents) · Product / 产品: [Dageno](https://dageno.ai/?utm_source=github&utm_medium=social&utm_campaign=official)

<!-- DAGENO_AGENT_NAV_END -->

# Benchmark Suite

This folder defines a lightweight benchmark pack for validating the official production flow from:

- backlog row
- editorial brief
- draft sections
- section review
- assembly review
- final gate

## Goal

Validate four things against real project examples:

1. articles do not collapse into near-duplicates
2. drafts sound more like edited blog posts than generic generated templates
3. cluster roles stay differentiated
4. the final payload provides enough structure for an external agent to execute the workflow

## Cases

- travel shortlist
- travel comparison
- enterprise category
- enterprise evaluation

## Suggested scoring

- `distinctness`: 1-5
- `naturalness`: 1-5
- `decision_support`: 1-5
- `brand_fit`: 1-5
- `cluster_role_clarity`: 1-5

## Recommended usage

1. produce the payload from the official command path
2. draft sections from `draft_package.draft_sections`
3. run section reviews from `review_package.section_review_contract`
4. assemble and run the final gate
5. record scores in `benchmark_manifest.json`
