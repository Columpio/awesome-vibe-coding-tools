# Awesome Vibe Coding Tools ✨

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Last Updated](https://img.shields.io/badge/updated-2026--03--22-blue)](#data-policy)

[简体中文](README_zh.md)

> A curated list of AI coding workflow systems, agent harnesses, spec-driven development stacks, and orchestration projects for vibe coding.

<a id="scope"></a>
## Scope

- Focus on reusable workflow infrastructure, not generic AI IDE or product catalogs.
- Covers open-source or public workflow systems for Codex, Claude Code, OpenCode, Cursor, Gemini CLI, and adjacent agent ecosystems.
- Descriptions are normalized from the imported CSV plus current GitHub metadata when older wording was stale or too terse.

## Table of Contents

- [Agent Runtimes & Enhancers](#agent-runtimes)
- [Methods, Spec-Driven Development & Planning](#methods-planning)
- [Multi-Agent Orchestration & Collaboration](#multi-agent-orchestration)
- [Task, Memory & Workspace Management](#task-memory-workspaces)
- [Skills, Agent Packs & Config Kits](#skill-packs)
- [Visual & IDE Workflow Tooling](#visual-tooling)
- [Historical Notes](#historical-notes)
- [Data Policy](#data-policy)
- [Contributing](#contributing)

<a id="agent-runtimes"></a>
## Agent Runtimes & Enhancers

- **[anomalyco/opencode](https://github.com/anomalyco/opencode)** `127.5k stars` - The open source coding agent.
- **[code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent)** `42.2k stars` - Agent harness for OpenCode and related coding agents, with async subagents, curated tools, and a stronger out-of-the-box operator experience.
- **[charmbracelet/crush](https://github.com/charmbracelet/crush)** `21.8k stars` - The glamourous AI coding agent for your favourite terminal.
- **[UfoMiao/zcf](https://github.com/UfoMiao/zcf)** `5.8k stars` - Zero-Config Code Flow for Claude Code and Codex.
- **[Yeachan-Heo/oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex)** `2.3k stars` - Codex enhancement layer that adds hooks, agent teams, HUDs, and other workflow primitives on top of OpenAI Codex CLI.
- **[alvinunreal/oh-my-opencode-slim](https://github.com/alvinunreal/oh-my-opencode-slim)** `2.3k stars` - Slimmed, cleaned, and fine-tuned oh-my-opencode fork that consumes much less tokens.
- **[feiskyer/claude-code-settings](https://github.com/feiskyer/claude-code-settings)** `1.3k stars` - Claude Code settings, commands and agents for vibe coding.
- **[agent-sh/agentsys](https://github.com/agent-sh/agentsys)** `622 stars` - Automation layer for Claude Code, OpenCode, Codex, Cursor, and Kiro with 19 plugins, 47 agents, and 39 skills around the idea that AI writes code while the system automates everything else.
- **[zhukunpenglinyutong/ai-max](https://github.com/zhukunpenglinyutong/ai-max)** `203 stars` - Boost Claude Code with production-grade agents, skills, hooks, commands, rules, and MCP configurations in one click.

<a id="methods-planning"></a>
## Methods, Spec-Driven Development & Planning

- **[obra/superpowers](https://github.com/obra/superpowers)** `103.7k stars` - An agentic skills framework and software development methodology that works.
- **[github/spec-kit](https://github.com/github/spec-kit)** `79.5k stars` - Toolkit to help you get started with Spec-Driven Development.
- **[bmad-code-org/BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD)** `41.7k stars` - Breakthrough Method for Agile AI Driven Development.
- **[gsd-build/get-shit-done](https://github.com/gsd-build/get-shit-done)** `38.2k stars` - A light-weight and powerful meta-prompting, context engineering and spec-driven development system for Claude Code by TACHES.
- **[Fission-AI/OpenSpec](https://github.com/Fission-AI/OpenSpec)** `33.0k stars` - Spec-driven development (SDD) for AI coding assistants.
- **[OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files)** `16.7k stars` - Claude Code skill implementing Manus-style persistent markdown planning - the workflow pattern behind the $2B acquisition.
- **[Pimzino/spec-workflow-mcp](https://github.com/Pimzino/spec-workflow-mcp)** `4.0k stars` - A Model Context Protocol (MCP) server that provides structured spec-driven development workflow tools for AI-assisted software development, featuring a real-time web dashboard and VSCode extension.
- **[Pimzino/claude-code-spec-workflow](https://github.com/Pimzino/claude-code-spec-workflow)** `3.6k stars` - Automated workflows for Claude Code, featuring spec-driven development for new features and a streamlined bug-fix workflow.
- **[gotalab/cc-sdd](https://github.com/gotalab/cc-sdd)** `2.9k stars` - Spec-driven development for your team's workflow, transforming AI coding agents into production-ready requirements -> design -> tasks -> implementation pipelines.
- **[Q00/ouroboros](https://github.com/Q00/ouroboros)** `1.6k stars` - Stop prompting. Start specifying.
- **[papaoloba/spec-based-claude-code](https://github.com/papaoloba/spec-based-claude-code)** `118 stars` - Implementation of a Spec-Driven Development workflow in Claude Code using custom slash commands.
- **[pdoronila/cc-sdd](https://github.com/pdoronila/cc-sdd)** `57 stars` - Spec Driven Development Workflow inside Claude-Code.
- **[kellemar/claude-code-specs-generator](https://github.com/kellemar/claude-code-specs-generator)** `38 stars` - Documentation and context management system inspired by Amazon Kiro that generates structured specification documents for Claude Code.

<a id="multi-agent-orchestration"></a>
## Multi-Agent Orchestration & Collaboration

- **[affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code)** `94.9k stars` - The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor, and beyond.
- **[msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)** `58.6k stars` - A complete AI agency at your fingertips - from frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.
- **[wshobson/agents](https://github.com/wshobson/agents)** `31.9k stars` - Intelligent automation and multi-agent orchestration for Claude Code.
- **[paperclipai/paperclip](https://github.com/paperclipai/paperclip)** `31.2k stars` - Open-source orchestration for zero-human companies.
- **[Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)** `10.9k stars` - Teams-first multi-agent orchestration layer for Claude Code, with modes such as Autopilot, Ultrapilot, Swarm, Pipeline, and Ecomode.
- **[fengshao1227/ccg-workflow](https://github.com/fengshao1227/ccg-workflow)** `4.2k stars` - A multi-model collaborative development system with Claude orchestration, Codex backend support, Gemini frontend support, and a full-stack command set.
- **[stellarlinkco/myclaude](https://github.com/stellarlinkco/myclaude)** `2.5k stars` - Multi-agent orchestration workflow for Claude Code, Codex, Gemini, and OpenCode.
- **[bfly123/claude_code_bridge](https://github.com/bfly123/claude_code_bridge)** `1.7k stars` - Real-time multi-AI collaboration for Claude, Codex, and Gemini with persistent context and minimal token overhead.
- **[catlog22/Claude-Code-Workflow](https://github.com/catlog22/Claude-Code-Workflow)** `1.5k stars` - A JSON-driven multi-agent development framework with intelligent CLI orchestration, context-first architecture, and automated workflow execution.
- **[Ido-Levi/Hephaestus](https://github.com/Ido-Levi/Hephaestus)** `1.1k stars` - Semi-Structured Agentic Framework. Workflows build themselves as agents discover what needs to be done, not what you predicted upfront.
- **[williamnie/aegisFlow](https://github.com/williamnie/aegisFlow)** `38 stars` - Multi-agent CLI workflow that turns an idea into a PRD, technical design, review artifacts, and then orchestrates local development tools to build it.
- **[N1nEmAn/acca](https://github.com/N1nEmAn/acca)** `14 stars` - A multi-AI collaborative workflow system that lets Antigravity orchestrate Claude CLI and Codex CLI together.

<a id="task-memory-workspaces"></a>
## Task, Memory & Workspace Management

- **[eyaltoledano/claude-task-master](https://github.com/eyaltoledano/claude-task-master)** `26.0k stars` - An AI-powered task-management system you can drop into Cursor, Lovable, Windsurf, Roo, and others.
- **[BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban)** `23.6k stars` - Get 10X more out of Claude Code, Codex or any coding agent.
- **[steveyegge/beads](https://github.com/steveyegge/beads)** `19.5k stars` - Beads - A memory upgrade for your coding agent.
- **[steveyegge/gastown](https://github.com/steveyegge/gastown)** `12.7k stars` - Gas Town - multi-agent workspace manager.
- **[snarktank/ai-dev-tasks](https://github.com/snarktank/ai-dev-tasks)** `7.6k stars` - A simple task management system for managing AI dev agents.

<a id="skill-packs"></a>
## Skills, Agent Packs & Config Kits

- **[ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)** `46.7k stars` - A curated list of awesome Claude Skills, resources, and tools for customizing Claude AI workflows.
- **[garrytan/gstack](https://github.com/garrytan/gstack)** `35.7k stars` - Reproduces Garry Tan's current Claude Code stack with 15 opinionated role tools spanning CEO, design, engineering management, release, docs, and QA.
- **[muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering)** `14.1k stars` - A comprehensive collection of Agent Skills for context engineering, multi-agent architectures, and production agent systems.
- **[diet103/claude-code-infrastructure-showcase](https://github.com/diet103/claude-code-infrastructure-showcase)** `9.3k stars` - Examples of my Claude Code infrastructure with skill auto-activation, hooks, and agents.
- **[OneRedOak/claude-code-workflows](https://github.com/OneRedOak/claude-code-workflows)** `3.7k stars` - The best workflows and configurations I've developed from heavy Claude Code usage, based on learnings from an AI-native startup.
- **[avivl/claude-007-agents](https://github.com/avivl/claude-007-agents)** `242 stars` - A unified AI agent orchestration system featuring dozens of specialized agents across 14 categories for modern software development.
- **[quboqin/template-agenticide-vibecoding](https://github.com/quboqin/template-agenticide-vibecoding)** `51 stars` - A customized Claude Code R&D workflow system and AI team collaboration framework based on spec-driven and test-driven development.

<a id="visual-tooling"></a>
## Visual & IDE Workflow Tooling

- **[breaking-brake/cc-wf-studio](https://github.com/breaking-brake/cc-wf-studio)** `4.5k stars` - Visual workflow editor for AI agents with natural-language editing, export, and run support.
- **[OleynikAleksandr/antigravity-subagents](https://github.com/OleynikAleksandr/antigravity-subagents)** `52 stars` - Antigravity SubAgents provides the infrastructure for Antigravity IDE to utilize specialized Sub-Agents.

<a id="historical-notes"></a>
## Historical Notes

- **zengruifeng56-del/auto-dev-scheduler** `historical` - An AI concurrent auto-scheduling tool deeply integrated with OpenSpec. GitHub returned `404 Not Found` on March 22, 2026, so it is kept here as a historical reference from the imported CSV.

<a id="data-policy"></a>
## Data Policy

- Stars were refreshed from GitHub on March 22, 2026.
- Entries inside each category are ordered roughly by current GitHub stars.
- This snapshot currently covers 48 live repositories plus 1 historical reference retained from the imported CSV.
- Repository availability was checked at refresh time; unavailable projects are kept in a separate historical section instead of being mixed into live recommendations.
- This repository is README-first: new curation should land in both `README.md` and `README_zh.md` together.

<a id="contributing"></a>
## Contributing

- Prefer projects that materially change how coding agents plan, coordinate, remember context, or execute work.
- Add the official repository URL, a one-line description, and the best-fit category.
- When refreshing existing entries, verify stars and availability instead of copying stale descriptions forward.
