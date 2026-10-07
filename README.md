# Rohith Taste Skill

An anti-slop **frontend design taste** skill for AI coding assistants (Claude Code, Cursor, Windsurf, Gemini CLI, Codex CLI, and more). It gives your AI agent real design judgement so generated landing pages, portfolios, and redesigns stop looking templated.

> **Developed / maintained by Mohammad Rohith Imdad (Rohith Scripts)**
> WhatsApp: https://wa.me/971504030778 (For Custom Projects)
> YouTube: https://www.youtube.com/@davizsolutions (Subscribe for more!)

---

## What it does

Everything ships in a single self-contained `SKILL.md`. When invoked, it reads the brief, infers the right design direction, and applies a **3-parameter "equalizer"** to tune the output:

| Dial | Range | Low → High |
|------|-------|------------|
| **DESIGN_VARIANCE** | 1–10 | Clean / centered → asymmetric, modern compositions |
| **MOTION_INTENSITY** | 1–10 | Simple hover effects → magnetic, scroll-triggered animation |
| **VISUAL_DENSITY** | 1–10 | Luxury / airy spacing → dense, compact dashboards |

Plus: brief inference, brief → design-system map, AI-tell (forbidden pattern) detection, dark-mode protocol, redesign protocol, accessibility guardrails, and a final pre-flight checklist.

**Scope:** landing pages, portfolios, and redesigns — not dashboards, data tables, or multi-step product UI.

## Install

Install into any supported AI assistant via the skills CLI:

```bash
npx skills add https://github.com/orugantirohith/Rohith-Taste-Skill --skill "design-taste-frontend"
```

Or copy `skills/design-taste-frontend/SKILL.md` into your assistant's skills folder
(e.g. `~/.claude/skills/design-taste-frontend/` for Claude Code).

## Usage

This copy is configured **manual-invoke only** — it never auto-activates. Trigger it by
mentioning **`taste`** in your request:

```
taste — redesign this landing page, premium B2B SaaS vibe
/taste DESIGN_VARIANCE 8 MOTION_INTENSITY 6 VISUAL_DENSITY 3
```

## License

[MIT](LICENSE).
