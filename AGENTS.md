# AGENTS.md

This is a skill library repository, not an application.

## Structure

- `skills/` — All skills with their `SKILL.md` definitions
- No build/test/lint commands exist

## Important Skills

| Skill | Purpose |
|-------|---------|
| `claude-api` | Anthropic SDK / Claude API integration |
| `skill-creator` | Creating new skills |
| `pdf`, `docx`, `xlsx`, `pptx` | Office file manipulation |
| `mcp-builder` | Building MCP servers |

## Notes

- Skills are loaded via `/skill add` command
- This repo is a library used by other projects, not standalone