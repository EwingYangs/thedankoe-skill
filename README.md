# thedankoe Skill

> Dan Koe 方法论 — 基于 3378 条原创推文提炼的完整方法论体系。

## 概览

| 子技能 | 原子数 | 核心定位 |
|--------|-------|---------|
| One-Person Business | 381 | 一人公司、知识变现、产品化自己 |
| Content & Writing | 486 | 写作即杠杆、内容复用飞轮 |
| Focus & Philosophy | 1152 | 聚焦的艺术、意义构建、生活即游戏 |
| Personal Development | 1174 | 自我教育、技能即肌肉、拥抱不确定性 |
| Digital Leverage | 1032 | 互联网即新基建、数字财富创造 |
| Mindset & Psychology | 775 | 打破条件反射、视角决定一切 |

## 文件结构

```
thedankoe/
├── SKILL.md                    # 主技能文件（安装此文件）
├── README.md                   # 本文件
├── 高频概念词典.md               # Dan Koe 高频概念词典
├── 原子库/
│   └── atoms.jsonl             # 3378 条原子知识（JSONL 格式）
├── references/                 # 知识包（按主题分类）
│   ├── one_person_business.md
│   ├── content_and_writing.md
│   ├── focus_and_philosophy.md
│   ├── personal_development.md
│   ├── digital_leverage.md
│   └── mindset_and_psychology.md
└── data/                       # 原始数据
    ├── all-original-tweets.json
    ├── filtered-tweets.json
    ├── topics.json
    ├── topic_config.json
    └── topic_skills.json
```

## 安装

将 `SKILL.md` 放入你的 Claude Code skills 目录即可。

## 数据来源

- **Twitter**: @thedankoe
- **推文数量**: 3378 条（过滤后）
- **时间跨度**: 2020-07 至 2026-03
- **生成工具**: personality-skill-gen
