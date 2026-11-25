# Skills

Personal collection of reusable `SKILL.md` workflows for AI coding agents (Claude Code, OpenAI Codex, Gemini CLI, Cursor, Antigravity, and GitHub Copilot).

## Available Skills

- **`to-hexagonal-architecture`**: Analyzes an existing codebase in any language or framework and produces a phased, zero-breaking-change refactoring plan to migrate it to Hexagonal Architecture (Ports and Adapters).
- **`jira-ticket-creator`**: Creates well-structured Jira tickets (defaulting to Story) via the Atlassian MCP server. Gathers codebase/technical context, enforces repository naming conventions, separates Acceptance Criteria from DoD, and generates all ticket content in Spanish.

## Installation

### Multi-agent CLI (`skills.sh`)
Works across Claude Code, Codex, Gemini CLI, Cursor, Antigravity, and GitHub Copilot:
```bash
npx skills add gabrandalisse/skills