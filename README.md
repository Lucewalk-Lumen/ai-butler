# ai-butler

**教师工作台(启明星)** · v1.1.4 · `agent`

> Teacher workbench — teaching, meetings, research and admin in one screen (offline-first)


Part of the [WorkBuddy Experts](https://github.com/Lucewalk/lucewalk-experts) collection.


## What it does

- **Todos, schedule & teaching calendar** — with `.ics` import and semester-week settings
- **Briefings & automation** — morning reports, weekly reviews and backup reminders on platform schedules
- **Quick capture & project tracking** — one-liner to task, progress with blockers
- **Local bridge** — single-file HTML workbench driven by a 127.0.0.1 loopback; data never leaves the machine
- **Optional end-to-end encrypted sync** — CloudBase CDN/SDK address is user-supplied, off by default
- **Personalization** — 8 themes, 8 icons, 10 backgrounds, category management

## How it works

- UMAS v1.0 card format (`agent-card.json`) with eleven declared skills
- Zero external dependency; the P0 compliance list (no emoji icons, no purple-pink gradients, guardrails preserved) is part of the card
- v1 → v2 lossless data migration and capacity warnings are built into the data portability skill

## Agent roster

| Agent | Role |
|---|---|
| `ai-butler` | 教师工作台 · 启明星 |

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk/ai-butler/releases) or clone this repo;
2. Unzip keeping the internal manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).


## Version

Current release: **v1.1.4**. See the package manifest for details.


## License

MIT — see [LICENSE](LICENSE).

