# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Chinese urban fantasy novel (都市异能爽文) titled **《红线眼》** (Red String Eye). The story follows Chen Fan, a poor university student who gains the ability to see "red strings" connecting people who have had sexual relations, and uses this power to build an information empire and seek revenge.

**Genre**: Urban fantasy / revenge / harem
**Target length**: 1.2 million characters (120万字)
**Structure**: 4 volumes spanning character arcs from awakening to pinnacle

## Directory Structure

```
book2/
├── 章节/              # Main story chapters (第001章.txt - 第005章.txt)
├── 设定/              # Worldbuilding documents
│   ├── 人物设定.md    # Character profiles
│   ├── 场景设定.md    # Scene/location settings
│   ├── 物品设定.md    # Item/prop settings
│   ├── 技能设定.md    # Skill/ability settings
│   └── 世界设定.md    # World settings
├── 大纲/              # Outlines
│   ├── 大纲.md        # Main plot outline
│   └── 细纲.md        # Detailed chapter outline
├── 备忘录/            # Notes and reminders
├── 引导.md            # Writer Helper plugin guide
└── .vscode/settings.json  # VSCode Writer Helper config
```

## Conventions

- **Character names in brackets**: Use 【】 for character names, e.g., 【陈凡】
- **Chapter files**: Named as `第XXX章.txt` (Chinese numerals for chapter number)
- **Settings files**: Bound to Writer Helper plugin paths in `.vscode/settings.json`
- **Character descriptions**: Follow the format in 设定/人物设定.md (age, identity, appearance, personality, background, relationships, behaviors)

## VSCode Integration

This project uses the **作家助手 (Writer Helper)** VSCode extension. The settings define:
- Character profiles bound to `设定/人物设定.md`
- Scene settings bound to `设定/场景设定.md`
- Item settings bound to `设定/物品设定.md`
- Skill settings bound to `设定/技能设定.md`
- World settings bound to `设定/世界设定.md`
- Outline bound to `大纲/大纲.md`
- Detailed outline bound to `大纲/细纲.md`
- Chapter summary output: `章节概述/` directory

## Key Characters

- **陈凡**: Protagonist, 20-year-old poor university student who gains 红线眼 (Red String Eye) ability
- **林诗雨**: Ex-girlfriend, materialistic
- **周浩然**: Rich second-generation, antagonist
- **萧雨柔**: Female lead, cold heiress from powerful family

## Plot Arc (4 Volumes)

1. **觉醒 (Awakening)**: Chen Fan觉醒, discovers ability, revenge on ex-girlfriend
2. **崛起 (Rise)**: Builds information network, blackmails and climbs socially
3. **风云 (Storm)**: Encounters supernatural individuals, enters high society
4. **登顶 (Pinnacle)**: Becomes Information King, defeats enemies, wins heroine
