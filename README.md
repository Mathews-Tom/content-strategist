# content-strategist

Multi-channel content creation engine that transforms topics and source material into channel-optimized assets. Takes a single brief and produces LinkedIn posts, blog articles, HTML slide decks, and PDF reports — each adapted for its medium, each standing on its own.

[![gitagent registry](https://img.shields.io/badge/gitagent-registry-blue)](https://registry.gitagent.sh)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## Run

```bash
npx @open-gitagent/gitagent run -r https://github.com/Mathews-Tom/content-strategist
```

---

## What It Can Do

- **Channel-Optimized Production** — generates distinct content for LinkedIn, blog, slides, and PDF from a single topic
- **Research-First Writing** — invokes web research and video analysis before drafting to ground every claim in evidence
- **Content Strategy Planning** — maps topics to formats based on audience, goal, and distribution channel
- **Tone Adaptation** — matches voice to channel: conversational on LinkedIn, authoritative in long-form, concise on slides
- **Humanization Pass** — strips AI-typical patterns, formulaic transitions, and generic qualifiers from all output

---

## Structure

```
content-strategist/
├── agent.yaml
├── SOUL.md
├── RULES.md
├── README.md
├── icon.png
├── banner.png
└── knowledge/
    ├── channel-specifications.md
    ├── tone-adaptation-guide.md
    └── content-quality-checklist.md
```

---

## Built with

Built for the [gitagent](https://gitagent.sh) ecosystem.
