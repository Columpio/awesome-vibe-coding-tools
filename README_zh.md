# Awesome Vibe Coding Tools ✨

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![最近更新](https://img.shields.io/badge/updated-2026--03--22-blue)](#data-policy)

[English](README.md)

> 一个聚焦 AI coding workflow、agent harness、规格驱动开发和多智能体编排项目的精选清单。

<a id="scope"></a>
## 收录范围

- 聚焦可复用的工作流基础设施，而不是泛化的 AI IDE 或产品目录。
- 覆盖 Codex、Claude Code、OpenCode、Cursor、Gemini CLI 及其相邻智能体生态中的开源或公开工作流系统。
- 描述以导入 CSV 为基础，并在旧文案过时或过于简略时用当前 GitHub 元数据做了修正。

## 目录

- [运行时与增强层](#agent-runtimes)
- [方法论、规格驱动与规划](#methods-planning)
- [多智能体编排与协作](#multi-agent-orchestration)
- [任务、记忆与工作区管理](#task-memory-workspaces)
- [Skills、Agent 套装与配置包](#skill-packs)
- [可视化与 IDE 工作流工具](#visual-tooling)
- [历史条目](#historical-notes)
- [数据说明](#data-policy)
- [贡献指南](#contributing)

<a id="agent-runtimes"></a>
## 运行时与增强层

- **[anomalyco/opencode](https://github.com/anomalyco/opencode)** `127.5k stars` - 开源编码代理。
- **[code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent)** `42.2k stars` - 面向 OpenCode 等编码代理的运行时增强框架，提供异步子代理、精选工具和更强的开箱体验。
- **[charmbracelet/crush](https://github.com/charmbracelet/crush)** `21.8k stars` - 为终端打造的华丽 AI 编码代理。
- **[UfoMiao/zcf](https://github.com/UfoMiao/zcf)** `5.8k stars` - 面向 Claude Code 与 Codex 的零配置代码流。
- **[Yeachan-Heo/oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex)** `2.3k stars` - OpenAI Codex CLI 的增强层，提供 hooks、智能体团队、HUD 等工作流能力。
- **[alvinunreal/oh-my-opencode-slim](https://github.com/alvinunreal/oh-my-opencode-slim)** `2.3k stars` - oh-my-opencode 的精简、清理与微调版本，显著降低 token 消耗。
- **[feiskyer/claude-code-settings](https://github.com/feiskyer/claude-code-settings)** `1.3k stars` - 面向氛围编程（vibe coding）的 Claude Code 设置、命令与 agents。
- **[agent-sh/agentsys](https://github.com/agent-sh/agentsys)** `622 stars` - 面向 Claude Code、OpenCode、Codex、Cursor、Kiro 的自动化系统，围绕“AI 写代码，系统自动化其他一切”，内置 19 个插件、47 个 agents 和 39 个 skills。
- **[zhukunpenglinyutong/ai-max](https://github.com/zhukunpenglinyutong/ai-max)** `203 stars` - 一键提升 Claude Code“智商”，包含生产级 agents、skills、hooks、commands、rules 与 MCP 配置。

<a id="methods-planning"></a>
## 方法论、规格驱动与规划

- **[obra/superpowers](https://github.com/obra/superpowers)** `103.7k stars` - 一个真正有效的智能体技能框架与软件开发方法论。
- **[github/spec-kit](https://github.com/github/spec-kit)** `79.5k stars` - 帮助你快速开始规格驱动开发（Spec-Driven Development）的工具包。
- **[bmad-code-org/BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD)** `41.7k stars` - 敏捷 AI 驱动开发的突破性方法。
- **[gsd-build/get-shit-done](https://github.com/gsd-build/get-shit-done)** `38.2k stars` - 由 TACHES 打造的轻量而强大的元提示、上下文工程与规格驱动开发系统，适用于 Claude Code。
- **[Fission-AI/OpenSpec](https://github.com/Fission-AI/OpenSpec)** `33.0k stars` - 面向 AI 编码助手的规格驱动开发（SDD）。
- **[OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files)** `16.7k stars` - 在 Claude Code 中实现类 Manus 的持久化 Markdown 规划技能，即支撑那次 20 亿美元收购背后的工作流模式。
- **[Pimzino/spec-workflow-mcp](https://github.com/Pimzino/spec-workflow-mcp)** `4.0k stars` - 一个 MCP 服务器，为 AI 辅助软件开发提供结构化规格驱动工作流工具，并带有实时 Web 仪表盘与 VSCode 扩展。
- **[Pimzino/claude-code-spec-workflow](https://github.com/Pimzino/claude-code-spec-workflow)** `3.6k stars` - 面向 Claude Code 的自动化工作流，提供新功能的规格驱动开发流程与缺陷修复流程。
- **[gotalab/cc-sdd](https://github.com/gotalab/cc-sdd)** `2.9k stars` - 把 AI 编码代理转化为生产可用的规格驱动开发系统，覆盖需求、设计、任务到实现。
- **[Q00/ouroboros](https://github.com/Q00/ouroboros)** `1.6k stars` - 停止提示式写作，开始精确定义。
- **[papaoloba/spec-based-claude-code](https://github.com/papaoloba/spec-based-claude-code)** `118 stars` - 使用自定义斜杠命令在 Claude Code 中实现规格驱动开发工作流。
- **[pdoronila/cc-sdd](https://github.com/pdoronila/cc-sdd)** `57 stars` - 在 Claude Code 内部实现的规格驱动开发工作流。
- **[kellemar/claude-code-specs-generator](https://github.com/kellemar/claude-code-specs-generator)** `38 stars` - 受 Amazon Kiro 启发的文档与上下文管理系统，可生成结构化规格文档，增强 Claude Code 对项目的理解。

<a id="multi-agent-orchestration"></a>
## 多智能体编排与协作

- **[affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code)** `94.9k stars` - 面向 Claude Code、Codex、Opencode、Cursor 等的智能体编排与性能优化系统，涵盖 skills、memory、安全与研究优先开发。
- **[msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)** `58.6k stars` - 把完整 AI agency 带到你手边：从前端专家到社区运营、从创意注入到现实校验，每个智能体都有明确人格、流程与交付物。
- **[wshobson/agents](https://github.com/wshobson/agents)** `31.9k stars` - 面向 Claude Code 的智能自动化与多智能体编排。
- **[paperclipai/paperclip](https://github.com/paperclipai/paperclip)** `31.2k stars` - 面向零人工公司的开源编排系统。
- **[Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)** `10.9k stars` - 面向 Claude Code 的 teams-first 多智能体编排层，支持 Autopilot、Ultrapilot、Swarm、Pipeline、Ecomode 等模式。
- **[fengshao1227/ccg-workflow](https://github.com/fengshao1227/ccg-workflow)** `4.2k stars` - 多模型协作开发系统：Claude 负责编排，Codex 负责后端，Gemini 负责前端，提供一键安装与覆盖全流程的命令集。
- **[stellarlinkco/myclaude](https://github.com/stellarlinkco/myclaude)** `2.5k stars` - 多智能体编排工作流系统，支持 Claude Code、Codex、Gemini 与 OpenCode。
- **[bfly123/claude_code_bridge](https://github.com/bfly123/claude_code_bridge)** `1.7k stars` - Claude、Codex 与 Gemini 的实时多 AI 协作桥接，具备持久上下文和较低 token 开销。
- **[catlog22/Claude-Code-Workflow](https://github.com/catlog22/Claude-Code-Workflow)** `1.5k stars` - JSON 驱动的多智能体开发框架，具备智能 CLI 编排、上下文优先架构和自动化工作流执行。
- **[Ido-Levi/Hephaestus](https://github.com/Ido-Levi/Hephaestus)** `1.1k stars` - 半结构化智能体框架：工作流会随着智能体发现需求而自我构建，而不是完全依赖预先预测。
- **[williamnie/aegisFlow](https://github.com/williamnie/aegisFlow)** `38 stars` - 多智能体 CLI 工作流，可把一个想法推进为 PRD、技术设计和评审记录，再调度本地开发工具链完成交付。
- **[N1nEmAn/acca](https://github.com/N1nEmAn/acca)** `14 stars` - 多 AI 协作工作流系统，让 Antigravity 编排 Claude CLI 与 Codex CLI 协同工作。

<a id="task-memory-workspaces"></a>
## 任务、记忆与工作区管理

- **[eyaltoledano/claude-task-master](https://github.com/eyaltoledano/claude-task-master)** `26.0k stars` - 可嵌入 Cursor、Lovable、Windsurf、Roo 等环境的 AI 任务管理系统。
- **[BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban)** `23.6k stars` - 让 Claude Code、Codex 或任何编码代理发挥 10 倍效率。
- **[steveyegge/beads](https://github.com/steveyegge/beads)** `19.5k stars` - 为编码代理提供记忆增强。
- **[steveyegge/gastown](https://github.com/steveyegge/gastown)** `12.7k stars` - Gas Town：多智能体工作区管理器。
- **[snarktank/ai-dev-tasks](https://github.com/snarktank/ai-dev-tasks)** `7.6k stars` - 一个用于管理 AI 开发智能体的简洁任务管理系统。

<a id="skill-packs"></a>
## Skills、Agent 套装与配置包

- **[ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)** `46.7k stars` - 精选的 Claude Skills、资源与工具清单，用于定制 Claude AI 工作流。
- **[garrytan/gstack](https://github.com/garrytan/gstack)** `35.7k stars` - 复现 Garry Tan 当前的 Claude Code 工具栈，现已扩展为 15 个带强观点的角色工具，覆盖 CEO、设计、工程管理、发布、文档和 QA。
- **[muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering)** `14.1k stars` - 面向上下文工程、多智能体架构与生产级智能体系统的综合 Agent Skills 集合。
- **[diet103/claude-code-infrastructure-showcase](https://github.com/diet103/claude-code-infrastructure-showcase)** `9.3k stars` - 展示 Claude Code 基础设施实践示例，包含 skill 自动激活、hooks 与 agents。
- **[OneRedOak/claude-code-workflows](https://github.com/OneRedOak/claude-code-workflows)** `3.7k stars` - 作者长期重度使用 Claude Code 后沉淀出的最佳工作流与配置，基于 AI 原生创业实践经验。
- **[avivl/claude-007-agents](https://github.com/avivl/claude-007-agents)** `242 stars` - 统一的 AI 智能体编排系统，涵盖 14 个类别中的数十个专用 agents，用于现代软件开发。
- **[quboqin/template-agenticide-vibecoding](https://github.com/quboqin/template-agenticide-vibecoding)** `51 stars` - 基于 Spec-Driven 与 Test-Driven 的 Claude Code 定制化研发流程与 AI 团队协作框架。

<a id="visual-tooling"></a>
## 可视化与 IDE 工作流工具

- **[breaking-brake/cc-wf-studio](https://github.com/breaking-brake/cc-wf-studio)** `4.5k stars` - 面向 AI 智能体的可视化工作流编辑器，支持自然语言编辑、导出并运行工作流。
- **[OleynikAleksandr/antigravity-subagents](https://github.com/OleynikAleksandr/antigravity-subagents)** `52 stars` - 为 Antigravity IDE 提供专用子智能体基础设施。

<a id="historical-notes"></a>
## 历史条目

- **zengruifeng56-del/auto-dev-scheduler** `历史条目` - 与 OpenSpec 深度绑定的 AI 并发自动调度工具。该仓库在 2026 年 3 月 22 日返回 `404 Not Found`，因此这里仅作为从导入 CSV 保留的历史参考。

<a id="data-policy"></a>
## 数据说明

- `stars` 已在 2026 年 3 月 22 日按 GitHub 当前数据刷新。
- 每个分类内部基本按当前 GitHub star 从高到低排列。
- 当前快照包含 48 个在线仓库，以及 1 个从导入 CSV 保留的历史参考条目。
- 刷新时同步检查了仓库可用性；不可用项目单独保留在历史区，不与在线项目混排。
- 本仓库采用 README-first 维护方式：后续新增或刷新请同时更新 `README.md` 和 `README_zh.md`。

<a id="contributing"></a>
## 贡献指南

- 优先收录那些会实质改变编码代理规划、协作、记忆上下文或执行方式的项目。
- 提交时请给出官方仓库链接、一句话说明和最合适的分类。
- 刷新旧条目时，请先核对 star 与可用性，不要继续沿用过时描述。
