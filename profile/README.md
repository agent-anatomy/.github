# Agent Anatomy

📊 **[Visual diagrams →](https://agent-anatomy.github.io/graphics/)**

> Ready-to-use boilerplates for every AI coding agent.
> Clone the one you use. Copy into your project. Edit. Ship.

---

## Universal config

**[agent](https://github.com/agent-anatomy/agent)** — Write `AGENT.md` once. Sync to every agent with one command.

```bash
npx @agent-anatomy/agent
```

---

## Individual boilerplates

| Agent | Config | Repo |
|-------|--------|------|
| **Claude Code** | `.claude/` + `CLAUDE.md` | [agent-anatomy/claude](https://github.com/agent-anatomy/claude) |
| **Cursor** | `.cursor/rules/` + `.cursorrules` | [agent-anatomy/cursor](https://github.com/agent-anatomy/cursor) |
| **OpenAI Codex** | `AGENTS.md` | [agent-anatomy/codex](https://github.com/agent-anatomy/codex) |
| **Windsurf** | `.windsurfrules` | [agent-anatomy/windsurf](https://github.com/agent-anatomy/windsurf) |
| **GitHub Copilot** | `.github/copilot-instructions.md` | [agent-anatomy/copilot](https://github.com/agent-anatomy/copilot) |
| **Aider** | `.aider.conf.yml` + `CONVENTIONS.md` | [agent-anatomy/aider](https://github.com/agent-anatomy/aider) |
| **Gemini CLI** | `GEMINI.md` | [agent-anatomy/gemini](https://github.com/agent-anatomy/gemini) |

---

## How to use

```bash
# Example: Claude Code
git clone https://github.com/agent-anatomy/claude.git .claude-boilerplate
cp .claude-boilerplate/CLAUDE.md ./CLAUDE.md
cp -r .claude-boilerplate/.claude ./.claude
rm -rf .claude-boilerplate
```

Each repo has copy-paste instructions for its agent.

---

## Add your agent

Using an agent not listed?

1. Fork any existing repo as a template
2. Add real, working config files for your agent
3. Open a PR to add it to this index

Every boilerplate should have real files — not just docs.
