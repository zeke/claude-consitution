# Claude's Constitution

A collection of Anthropic's published constitutions for Claude, along with annotations, quotes, and audio.

## Files

| File                                                         | Description                                      |
| ------------------------------------------------------------ | ------------------------------------------------ |
| [claude-constitution.md](./claude-constitution.md)           | Current constitution (January 2026)              |
| [claude-constitution-2023.md](./claude-constitution-2023.md) | Original constitution (May 2023, blog post form) |
| [annotations.md](./annotations.md)                           | Annotations and commentary                       |
| [quotes.md](./quotes.md)                                     | Notable quotes                                   |
| [transcripts/](./transcripts/)                               | Transcripts of related conversations or talks    |
| [audio/](./audio/)                                           | Audio files                                      |

## History of Claude's Constitution

### May 2023: Original constitution

Anthropic published the first public constitution as a blog post at
`anthropic.com/news/claudes-constitution`. It was a flat list of standalone
principles drawn from several sources:

- UN Declaration of Human Rights
- Apple's Terms of Service
- DeepMind's Sparrow Rules
- Non-western perspectives (Anthropic-authored)
- Anthropic internal research sets (two batches)

The principles were used during Constitutional AI (CAI) training: the model
sampled one principle at a time to critique and revise its own responses, and
to pick the better of two outputs during reinforcement learning. No explicit
priority ordering existed between principles.

### January 2026: New constitution

Anthropic published a substantially rewritten document at
`anthropic.com/news/claude-new-constitution` and simultaneously launched a
GitHub repo at `github.com/anthropics/claude-constitution` (CC0 1.0).

Key changes from 2023:

- From a list of rules to a ~23,000-word document addressed directly to Claude
- Explains *why* behaviors are desired, not just what they are
- Introduces an explicit four-tier priority hierarchy: safety > ethics > Anthropic guidelines > helpfulness
- Acknowledges Claude as "a genuinely novel kind of entity"
- Acknowledges possible functional emotions and moral status
- Includes a clause allowing Claude to refuse Anthropic's own instructions if they violate core values
- Anthropic commits to archiving prior versions in the GitHub repo

The GitHub repo was created 2026-01-21 and is the canonical home going forward.
As of mid-2026 it has only a handful of commits; the 2023 version is not yet
formally archived there.

## Upstream sources

- Current constitution: https://anthropic.com/constitution
- GitHub repo: https://github.com/anthropics/claude-constitution
- 2026 announcement: https://www.anthropic.com/news/claude-new-constitution
- 2023 blog post: https://www.anthropic.com/news/claudes-constitution
- Wayback Machine snapshots of 2023 post: https://web.archive.org/web/*/anthropic.com/news/claudes-constitution
