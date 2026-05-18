# Writing Skills

Agent skills for text transformation and writing. Installable as a plugin for Claude Code and compatible AI coding assistants.

## Skills

| Skill | Description |
|---|---|
| [humanize-text](.claude/skills/humanize-text/SKILL.md) | Rewrite AI-generated text to read as natural human prose |

## Installation

Add as a marketplace, then install the plugin:

```bash
claude plugin marketplace add tanujdargan/skills
claude plugin install writing-skills
```

## Structure

```
.claude-plugin/
  marketplace.json    # Marketplace manifest
  plugin.json         # Plugin manifest
.claude/
  skills/
    humanize-text/
      SKILL.md        # Main skill reference
      reference.md    # Detailed rules with before/after examples
```

## License

MIT
