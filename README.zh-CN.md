<!-- DAGENO_AGENT_NAV_START -->

**Dageno Agent Project Map / Dageno Agent 项目导航**

Docs / 文档: [README](https://github.com/dageno-agents/geo-content-writer) · [简体中文](https://github.com/dageno-agents/geo-content-writer/blob/main/README.zh-CN.md)

If this repo is useful, you may also want the adjacent Dageno Agent projects for GEO, SEO, AI visibility, and content operations.
如果这个仓库对你有帮助，也可以看看这些相邻的 Dageno Agent 项目，用于 GEO、SEO、AI 可见性和内容增长工作流。

| If you want to... / 如果你想... | Project / 项目 | Plain-language difference / 白话区别 |
| --- | --- | --- |
| First diagnose a site / 先给网站做体检 | [seo-geo-audit](https://github.com/dageno-agents/seo-geo-audit) | Like an SEO + GEO medical report: technical issues, content gaps, trust signals, off-site mentions, and AI visibility in one audit / 像一份 SEO + GEO 体检报告，把技术问题、内容缺口、信任信号、站外提及和 AI 可见性放到一起看 |
| Turn a real website into Dageno topics and prompts / 把真实网站变成 Dageno 监控题库 | [dageno-online-topic-prompt-generator](https://github.com/dageno-agents/dageno-online-topic-prompt-generator) | Crawls the site and studies the business first, then generates Topic clusters and high-intent Prompts. Not an industry-template prompt dump / 先看网站和业务，再生成 Topic 集群和高意图 Prompt，不是套行业模板 |
| Produce SEO/GEO articles from keywords or briefs / 从关键词或 brief 批量生产内容 | [seo-geo-content-engine](https://github.com/dageno-agents/seo-geo-content-engine) | A full content pipeline: research, SERP intent, article structure, draft, metadata, FAQ, and GEO packaging / 完整内容流水线：调研、搜索意图、文章结构、正文、metadata、FAQ 和 GEO 包装 |
| Write from Dageno fanout data / 用 Dageno fanout 写文章 | [geo-content-writer](https://github.com/dageno-agents/geo-content-writer) | For when Dageno already found prompt opportunities: turn fanout into a backlog, editorial brief, draft contract, and review contract / 适合已经有 Dageno prompt opportunity 的情况：把 fanout 变成选题队列、编辑 brief、草稿契约和审核契约 |
| Find why organic content is not converting / 找出自然流量内容为什么不转化 | [organic-content-intelligence](https://github.com/dageno-agents/organic-content-intelligence) | Joins GSC, GA4, crawl, intent, and AI/GEO signals to show which pages have demand but fail to answer or convert / 把 GSC、GA4、抓取、意图和 AI/GEO 信号连起来，看哪些页面有需求但没有承接住 |
| Improve a site's GEO structure / 优化网站结构以适配 GEO | [geo-site-architecture-audit](https://github.com/dageno-agents/geo-site-architecture-audit) | Starts from the existing navigation, sitemap, landing pages, and help content, then finds missing AI-answerable pages and internal links / 从现有导航、站点地图、落地页和帮助内容出发，找缺失的 AI 可引用页面和内链结构 |
| Create a client-facing AI visibility report / 做给客户看的 AI 可见性报告 | [brand-ai-performance-check](https://github.com/dageno-agents/brand-ai-performance-check) | A stable visual report template for brand AI performance, using Dageno API data or custom inputs / 稳定的品牌 AI 表现可视化报告模板，可接 Dageno API 或自定义数据 |
| Automate Dageno in workflows / 把 Dageno 接进自动化流程 | [n8n-nodes-dageno](https://github.com/dageno-agents/n8n-nodes-dageno) | Use Dageno inside n8n: brands, GEO analysis, keywords, opportunities, topics, prompts, SEO, and citations / 在 n8n 里调用 Dageno：品牌、GEO 分析、关键词、机会、Topic、Prompt、SEO 和引用数据 |
| Learn the API and MCP growth workflow / 学 Dageno API 和 MCP 怎么用于增长 | [dageno-mcp-growth-playbook](https://github.com/dageno-agents/dageno-mcp-growth-playbook) | The practical playbook for turning Dageno API/MCP data into reports, prompt gaps, citation intelligence, and growth actions / 把 Dageno API/MCP 数据变成报告、Prompt Gap、引用分析和增长动作的实战手册 |

More projects / 更多项目: [geo-visual-content-engine](https://github.com/dageno-agents/geo-visual-content-engine), [seo-outreach-skill](https://github.com/dageno-agents/seo-outreach-skill), [geo-pre-sale-report-private](https://github.com/dageno-agents/geo-pre-sale-report-private), [GEO-SEO](https://github.com/dageno-agents/GEO-SEO).

Explore all repos / 查看全部项目: [github.com/dageno-agents](https://github.com/dageno-agents) · Product / 产品: [Dageno](https://dageno.ai/?utm_source=github&utm_medium=social&utm_campaign=official)

<!-- DAGENO_AGENT_NAV_END -->

# GEO Content Writer 中文说明

> 把 Dageno 发现的 prompt opportunity 和 fanout 数据，变成可执行的内容生产 backlog、编辑 brief、草稿包、审核包和发布前质检。

## 它解决什么问题

- 很多团队拿到 AI 搜索里的 prompt 数据后，会直接让模型写文章，结果内容很薄、角度重复，也不方便编辑审核。
- 这个项目补的是中间那一层：先把 fanout 变成可管理的生产对象，再让人或 agent 去写。

## 什么时候用它

- 你已经在 Dageno 里发现了一批 prompt opportunities。
- 你希望从真实 fanout 里挑选文章角度，而不是靠关键词或行业模板猜。
- 你想让外部写作 agent 按 section-by-section 的 contract 执行，而不是凭一个大 prompt 发挥。

## 和相邻项目有什么区别

- `dageno-online-topic-prompt-generator` 负责从真实网站生成 Topic 和 Prompt。
- `geo-content-writer` 负责在已有 Dageno fanout 的基础上，把一个具体机会变成文章生产包。
- `seo-geo-content-engine` 更偏从关键词或内容 brief 进入完整 SEO/GEO 内容生产。

## 主要输出

- fanout backlog JSON
- editorial brief
- draft package
- review package
- writer prompt
- publish-ready markdown 或 WordPress handoff

## 快速开始

1. `PYTHONPATH=src python -m geo_content_writer.cli build-fanout-backlog --days 7 --max-prompts 10`
2. `PYTHONPATH=src python -m geo_content_writer.cli select-backlog-items --top-n 10`
3. `PYTHONPATH=src python -m geo_content_writer.cli publish-ready-article --backlog-id <row-id>`

## 给中文读者的说明

这是当前公开仓库的中文本地化入口。英文 README.md 仍然保留更完整的原始说明、命令细节和历史上下文；中文版本优先帮助国内用户快速理解这个项目是做什么的、什么时候该用、以及它和其他 Dageno Agent 项目的区别。

## License

请参考英文 README 和仓库内的 LICENSE 文件。
