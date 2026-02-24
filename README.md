# claude-skills

A community-maintained skill marketplace for [Claude Code](https://claude.ai/code).

## What is a Skill?

A **skill** is a reusable set of instructions that extends Claude Code's capabilities for a specific domain or workflow. Skills are plain-text files that can be added to any Claude Code project.

## Repository Structure

```
claude-skills/
├── skills/                   # All published skills
│   └── <skill-name>/
│       ├── README.md         # Human-readable description and usage
│       ├── skill.yaml        # Skill manifest (metadata)
│       └── instructions.md   # The skill instructions consumed by Claude
├── CONTRIBUTING.md           # How to contribute a new skill
└── LICENSE                   # MIT license
```

## Using a Skill

1. Browse the [`skills/`](./skills) directory and find a skill you want to use.
2. Copy the contents of `instructions.md` into your project's `.claude/instructions.md` (or append to it).
3. Reload Claude Code and start using the skill.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on submitting a new skill.
