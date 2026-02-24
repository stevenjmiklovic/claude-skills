# Contributing to claude-skills

Thank you for your interest in contributing! Follow the steps below to submit a new skill.

## Skill Structure

Each skill lives in its own directory under `skills/`:

```
skills/
└── your-skill-name/
    ├── README.md         # Human-readable description and usage guide
    ├── skill.yaml        # Manifest with metadata
    └── instructions.md  # Instructions consumed by Claude Code
```

### `skill.yaml` fields

| Field         | Required | Description                                      |
|---------------|----------|--------------------------------------------------|
| `name`        | ✅        | Unique kebab-case identifier matching folder name |
| `version`     | ✅        | Semantic version (e.g. `1.0.0`)                  |
| `description` | ✅        | One-sentence summary of what the skill does      |
| `author`      | ✅        | Your GitHub username                             |
| `tags`        | ✅        | List of relevant topic tags                      |

### `instructions.md`

Write your skill instructions as you would write them directly to Claude. Be clear, specific, and concise. Avoid instructions that conflict with Claude's built-in safety guidelines.

### `README.md`

Include at minimum:
- A short description of the skill
- How to activate / use it
- A link to `skill.yaml` and `instructions.md`

## Submitting a Skill

1. Fork this repository.
2. Create a new directory under `skills/` using a descriptive kebab-case name.
3. Add `skill.yaml`, `instructions.md`, and `README.md` as described above.
4. Open a pull request with a clear title and description.

## Code of Conduct

- Keep skills safe and constructive.
- Do not include instructions that could be used to cause harm.
- Respect intellectual property — only submit skills you authored or have rights to share.
