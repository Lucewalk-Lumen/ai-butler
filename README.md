# ai-butler

**教师工作台(启明星)** · v1.1.4 · `agent`

> Teacher workbench — teaching, meetings, research and admin in one screen (offline-first)


Part of the [Lucewalk Lumen](https://github.com/Lucewalk/lucewalk-lumen) collection.


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


---

<details>
<summary><strong>📖 中文说明(Chinese README)</strong></summary>

# 教师工作台(启明星)

**教师工作台(离线优先):待办、日程、教学日历、晨报周报,数据不出本机**

- 版本:v1.1.4 · 类型:agent
- 版本真源:包内 `.codebuddy-plugin/plugin.json` 的 `version` 字段
- 所属合集:[Lucewalk Experts 门户](https://github.com/Lucewalk/lucewalk-experts)(全部产品目录与品牌说明)

## 安装

1. 从本仓库 [Releases](https://github.com/Lucewalk/ai-butler/releases) 页下载该包 zip(或直接克隆仓库);
2. 解压后**保持内部清单结构不变**(`.codebuddy-plugin/` 目录);
3. 在 WorkBuddy 中导入/注册(自定义连接器入口 → 信任并启用)。

能力详解见上方英文文档;品牌与全部产品目录见门户仓库。

## 许可

MIT——详见 [LICENSE](LICENSE)。

</details>
