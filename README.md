# Skills

Agent skills for AI coding assistants. Each skill is a self-contained reference guide that can be loaded into any agent session.

## Available Skills

### Writing

| Skill | Description |
|---|---|
| [humanize-text](writing/humanize-text/SKILL.md) | Rewrite AI-generated text to read as natural human prose |

## Installation

These skills can be used as a plugin with Claude Code or any compatible agent:

```bash
claude --plugin-dir /path/to/skills
```

Or reference individual skill files directly in your agent configuration.

## Structure

```
writing/
  humanize-text/
    SKILL.md        # Main skill reference
    reference.md    # Detailed rules with before/after examples
```
