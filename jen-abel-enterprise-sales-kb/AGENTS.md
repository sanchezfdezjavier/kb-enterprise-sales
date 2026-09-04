# AGENTS.md

## What this is

A set of Markdown files capturing Jen Abel's enterprise sales philosophy. It is sourced from her public X/Twitter posts (551 posts, May 2024–May 2026) and three public talks/podcasts. There is no software to build, run, or test.

## Navigation

Start at `00 Start Here.md`, which links to the index at `05 Maps/Jen Abel Enterprise Sales Map.md`. That map is the primary index for all content.

Content layers:

- `01 Source Notes/` — provenance, X post captures, video notes, thematic syntheses
- `02 Core Concepts/` — three foundational mental models
- `03 Playbooks/` — tactical execution guides covering the buyer journey
- `04 Hiring/` — first sales hire guidance
- `05 Maps/` — master navigation index

## Conventions

Every note declares type and provenance in YAML frontmatter:

```yaml
---
type: hub | concept | playbook | source-note | map
person: Jen Abel
tags: [tag1, tag2, ...]
created: YYYY-MM-DD
---
```

Cross-references use standard Markdown relative links. When a path contains spaces, wrap the destination in angle brackets:

```markdown
[Founder-Led Sales](<../02 Core Concepts/Founder-Led Sales.md>)
[Qualification Signals](<Qualification Signals.md>)
```

Link to the target file relative to the current file. Do not use wiki-link syntax (`[[Note]]`).

When creating new notes, follow the existing frontmatter schema, use standard Markdown links, and place the file in the numbered folder that matches its type.
