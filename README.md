# Smolnikov Research Skill - `promo-video-maker`

> **Category:** Video & Audio Production · **License:** MIT · **Author:** [Smolnikov Research Center](https://github.com/SmolnikovResearch)

**EN:** Storyboard-driven 1080p launch promo video builder.

**RU:** Сборка бит-синхронных 1080p промо-роликов по JSON-раскадровке с обложкой и постом анонса.

---

## On-Demand Activation & Lazy Loading (`on-demand.json`)

This skill stays **disabled by default** (`auto_load_on_startup: false`) and loads dependencies/checkpoints strictly when you enable and run it:

| Component | Requirement |
|---|---|
| System binaries | `ffmpeg` |
| Python packages | `pillow` |
| Model checkpoints | `none` |

## Installation in CapyAgent

```bash
capyagent skills install SmolnikovResearch/promo-video-maker/skills/promo-video-maker
```

Or copy this directory into `~/.capyagent/skills/` (or `~/.agents/skills/`).

## Check Status & Bootstrap Dependencies

```bash
python3 scripts/optional_skill_bootstrap.py promo-video-maker --status
python3 scripts/optional_skill_bootstrap.py promo-video-maker --install
```

See [`SKILL.md`](SKILL.md) for agent instructions and workflow examples.

## Related

- Full multi-skill catalog: [SmolnikovResearch/skills](https://github.com/SmolnikovResearch/skills)
- License: [MIT](LICENSE)
