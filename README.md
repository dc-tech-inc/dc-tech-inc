# DCtech.

DCtech is a software, AI and security engineering studio · Charlotte, NC · https://dctech.live

Founded and led by **Danilo Cortes**, principal engineer.

## What we do

- **Custom software:** full-stack web applications, from database to UI.
- **AI agents and automation:** voice agents, LLM integration, Model Context Protocol (MCP) tools.
- **Cloud and DevOps:** containerized services, CI/CD pipelines, infrastructure that is easy to rebuild.
- **Security operations:** secure-by-default engineering, with a defensive focus.

## Engineering portfolio

Each repository is original, runnable and documented. More are on the way; this table lists only what is public today.

| Capability | Repository | What it shows |
|---|---|---|
| Full-stack web | [ts-fullstack-starter](https://github.com/dc-tech-inc/ts-fullstack-starter) | pnpm monorepo: React + Express 5 + PostgreSQL/Drizzle, auth, validation, OpenAPI, CI-tested API. Also a GitHub template. |
| AI voice agents | [voice-agent-reference](https://github.com/dc-tech-inc/voice-agent-reference) | Real-time voice agent service with a provider interface, two adapters, a failover state machine and typed tool calls. The adapters are untested against live APIs. |
| MCP and tool use | [mcp-tool-server](https://github.com/dc-tech-inc/mcp-tool-server) | Read-only "repo health" MCP server with typed tools, tested through an MCP client. |
| Releases | [roomly-releases](https://github.com/dc-tech-inc/roomly-releases) | Public downloads for the Roomly desktop app. |
| Inventory back office | [warehouse-inventory-platform](https://github.com/dc-tech-inc/warehouse-inventory-platform) | React + Express 5 + PostgreSQL inventory, transfers, purchasing with approval and rewards, with admin/manager/clerk roles. 133 tests and 6 Playwright e2e in CI, Docker Compose. Synthetic data only; no deployment, email, SSO or MFA. |
| Infrastructure as code | [cloud-infra-iac](https://github.com/dc-tech-inc/cloud-infra-iac) | Terraform and Ansible reference: an OCI stack plus small AWS, Azure, GCP and Cloudflare modules, checked in CI (fmt, validate, tflint, checkov, Molecule). Validate-only; nothing applied to a real cloud. |
| LLM workflows and evals | [ai-agent-workflows](https://github.com/dc-tech-inc/ai-agent-workflows) | Versioned prompts, offline evals that gate CI, and a RAG support bot over fictional docs, in strict TypeScript. Runs offline by default; the Anthropic, OpenAI and Gemini adapters are not tested against live APIs. |
| Lead automation | [lead-flow-automation](https://github.com/dc-tech-inc/lead-flow-automation) | Lead intake service with HMAC-signed webhooks, three versioned n8n workflows and an ethical Python scraper for practice sites. CRM, enrichment and email are simulated; n8n is validated on import only, not executed. |
| Security operations | [secops-playbooks](https://github.com/dc-tech-inc/secops-playbooks) | Defensive runbooks, GitHub Advanced Security config, Azure WAF/Defender as code, Sigma/YARA rules tested on synthetic data, and PCAP notebooks on public samples. 104 pytest tests; nothing deployed to Azure. |
| AI governance | [ai-governance-toolkit](https://github.com/dc-tech-inc/ai-governance-toolkit) | Static React + TypeScript app for AI system impact assessments, topic-aligned to ISO/IEC 42005:2025 without quoting the standard. Scores risks before and after mitigation and exports JSON or Markdown. Runs in the browser; [live demo on GitHub Pages](https://dc-tech-inc.github.io/ai-governance-toolkit/). Not a certification or conformity tool. |
| Multi-stack examples | [multi-stack-showcases](https://github.com/dc-tech-inc/multi-stack-showcases) | Six small tested apps in one monorepo: Next.js + GraphQL + MongoDB, Vue 3, Rails API, Shopify theme, PHP real-estate CRM and a WordPress lead plugin, each with its own CI. Synthetic data; showcase examples, not products. |
| Analytics and statistics | [analytics-labs](https://github.com/dc-tech-inc/analytics-labs) | The same penguin-species analysis in R (Quarto, testthat) and Python (scikit-learn), checked against each other, plus a GA4/Ads report pipeline on synthetic data with a static dashboard on [GitHub Pages](https://dc-tech-inc.github.io/analytics-labs/). Public CC0 dataset; the classifier scores 100% on test because the data is nearly separable. |
| POS to stock integration | [dotnet-pos-integration](https://github.com/dc-tech-inc/dotnet-pos-integration) | C#/.NET 10 worker that applies a fictional POS's sales to SQL Server stock once per sale key (idempotent), with retry, reconciliation and PowerShell tooling. 36 xUnit tests (12 against SQL Server 2022 in a container) and 13 Pester tests in CI. Sales only, no returns; demo credentials only. |
| C data structures | [c-data-structures](https://github.com/dc-tech-inc/c-data-structures) | C17 library with a linked list, vector, hash map, binary heap and AVL tree, with ownership and complexity documented in the headers. CI builds with gcc and clang (-Werror), runs ASan/UBSan, valgrind and clang-tidy, and reports 95.9% line coverage. Not thread-safe; CI runs on Linux only. |

## Stack

**React · TypeScript · Node.js · PostgreSQL · Docker**

Also: Express, Vite, Drizzle ORM, pnpm, vitest, GitHub Actions.

## Commercial products (closed source)

- **Prumo Gestão:** ERP for Brazilian small businesses.
- **C.L.A.R.A.:** AI voice receptionist for clinics.
- **Roomly:** real-time 3D social platform for the browser ([roomly.life/app](https://roomly.life/app)), desktop and Android. Downloads: [roomly-releases](https://github.com/dc-tech-inc/roomly-releases).

## Contact

https://dctech.live
