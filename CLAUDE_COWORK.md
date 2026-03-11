# Claude Cowork Guide

## What it is
Claude Cowork is Anthropic's agentic workspace inside Claude Desktop. It uses the same architecture as Claude Code to run multi-step tasks autonomously on your machine—reading/writing local files, working in Chrome, and producing finished outputs without continual prompting.

## Availability and plans (as of March 11, 2026)
- Jan 12, 2026: Research preview shipped to **Max** subscribers on macOS, running locally in an isolated VM for file and MCP access (Claude release notes).
- Jan 16, 2026: Access expanded to **Pro** plan users on macOS (release notes).
- Feb 12, 2026: **Enterprise** became self-serve; seats include Claude, Claude Code, and Cowork (release notes).
- Feb 2026: Anthropic added **Windows** (x64) support for Claude Desktop with Cowork; macOS remains fully supported (Claude Help Center).
- Current: Cowork is bundled with **Max** (5x at $100/mo, 20x at $200/mo) and available to Pro and Enterprise seats where enabled (pricing page + release notes).

## Core capabilities
- Runs agentic workflows directly on your computer: reads/writes local files and coordinates sub-agents to parallelize complex jobs (Claude docs).
- Automates web work via Claude in Chrome—clicks, forms, multi-tab navigation—and stitches results back into tasks (Claude docs).
- Produces polished deliverables (docs, spreadsheets, slide decks) rather than just draft text (Claude docs).
- Uses connector/skill/plugin system shared with other Claude products for data access and reusable workflows (Claude docs).

## Recent feature drops
- **Scheduled tasks (Feb 25, 2026):** create recurring or on-demand Cowork runs plus a consolidated “Customize” panel for skills/plugins/connectors (release notes).
- **Plugin marketplace & admin controls (Feb 24, 2026):** org-level enablement for Team/Enterprise (release notes).
- **Agentic plug-ins (Jan 30, 2026):** TechCrunch reports enterprise-focused plug-ins that let teams encode workflows and data sources without heavy engineering.

## Extensibility model
- **Connectors (MCP):** link Cowork to SaaS/data sources.
- **Skills:** reusable, parameterized instructions for repeatable workflows.
- **Plugins:** packages of skills + connectors that can be shared or open sourced; Cowork ships with sample plug-ins and supports custom ones (TechCrunch + Claude docs).
- **Monitoring:** admin view for usage and activity across the organization (Claude docs).

## Quick-start checklist for teams
1) Install Claude Desktop (macOS or Windows) and sign in with a plan that has Cowork access.
2) In Desktop, switch to **Cowork** mode; verify file access scopes are acceptable for your org.
3) Add connectors for your core tools (e.g., Drive/SharePoint, Slack, Jira) and publish org-approved skills/plugins.
4) Pilot scheduled tasks for repetitive workflows (e.g., daily report compilation) and review logs/outputs.
5) Establish admin controls: plugin allow/block lists, monitoring, and permission policies.

## Limitations and considerations
- Early Windows support: downloadable today, but the earliest releases were macOS-only; validate parity before broad rollout.
- Usage limits vary by plan; high-volume teams typically need Max 5x or 20x tiers.
- Cowork runs locally with file access—ensure endpoint security, backups, and data handling policies match your compliance posture.

## Sources
- Claude Cowork overview and capabilities — [Claude docs](https://docs.anthropic.com/en/claude-desktop/claude-cowork)
- Feature timeline and scheduled tasks — [Anthropic Release Notes](https://support.anthropic.com/en/articles/11665851-release-notes)
- Max plan pricing and desktop downloads — [claude.com/pricing](https://claude.com/pricing)
- Plug-in launch details — [TechCrunch](https://techcrunch.com/2026/01/30/anthropic-cowork-plugins/)
- Windows desktop availability — [Claude Help Center](https://support.claude.com/en/articles/10463379-get-started-with-cowork)
