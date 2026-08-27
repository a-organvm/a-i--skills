# Discovery: organvm/a-i--skills

**Discovered:** 2026-06-22 | **Status:** PROMOTED — real value confirmed

## Value Thesis

`a-i--skills` is the capability registry for the entire ORGANVM estate — the authoritative catalog that defines *what agents can do*, distributed across every AI runtime in active use (Claude Code, Codex, Gemini CLI, Claude API). Its 171+ skills are structured instruction modules with YAML frontmatter that enable automated discovery, activation-condition matching, and multi-runtime bundle generation from a single source of truth. The repo's highest latent value is its live MCP server (`scripts/mcp-skill-server.py`), which turns the static library into a queryable capability API that any ORGANVM agent can call at runtime to discover, plan, and compose skills. Promoting it from a developer tool to a shared estate-wide service provides every orchestration-layer agent real-time visibility into the full capability surface, enabling dynamic skill selection.

## Highest Latent Value

**Multi-runtime capability registry with a live MCP discovery interface** — the authoritative estate asset where agent capabilities are codified, validated, versioned, and distributable across all AI runtimes simultaneously.

## Best Concrete First Task

Wire `scripts/mcp-skill-server.py` as a shared MCP server registered in the estate's agent configuration (`.claude/settings.json` or equivalent), so ORGAN-IV orchestration agents can query the skill registry at runtime rather than requiring per-session manual skill installation.
