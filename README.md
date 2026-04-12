<div align="center">

# 🎬 screenwriter-skill

### 短剧/漫剧编剧审稿 AI Skill

**让 AI 用专业编剧的标准帮你审剧本**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green.svg)](https://agentskills.io)
[![Iron Rules](https://img.shields.io/badge/Iron%20Rules-38-blue.svg)](#创作铁律)

[中文](#概述) | [English](#overview)

</div>

---

## 概述

**screenwriter-skill** 是一个面向短剧/漫剧行业的 AI 编剧审稿技能包。

它将一位拥有 5 年内容行业经验、操盘过红果平台 Top100 作品的内容负责人的**审稿方法论**，蒸馏成一套可加载的 AI Skill。

### 它能做什么

| ✅ 能做 | ❌ 不能做 |
|--------|----------|
| 按专业标准审核剧本，逐项指出问题 | 从零写出一个好剧本 |
| 检查第一集是否过"生死线" | 替代人类编剧的创意直觉 |
| 按爽感清单验证情绪兑现 | 判断一个IP的商业价值 |
| 对照人设小传检查执行落地 | 感知观众的情绪爆发点 |
| 给出结构化的改稿方向 | 写出有灵魂的台词 |

**一句话：它让 AI 从"什么都会但什么都不精"变成"按你的标准帮你干活"。**

### 谁需要这个

- 📝 **短剧/漫剧编剧** — 写完本子先自查，交稿前心里有数
- 🎯 **内容负责人/制片** — 审稿效率翻倍，从6小时压缩到2小时
- 🏢 **内容制作公司** — 统一团队的审稿标准和评价语言
- 🎓 **编剧学习者** — 37条实战铁律就是最好的教材

---

## 快速开始

### 安装

**WorkBuddy：**
```bash
cd ~/.workbuddy/skills/
git clone https://github.com/你的用户名/screenwriter-skill.git
```

**Claude Code：**
```bash
cd ~/.claude/skills/
git clone https://github.com/你的用户名/screenwriter-skill.git
```

**Cursor：**
```bash
cd .cursor/skills/
git clone https://github.com/你的用户名/screenwriter-skill.git
```

### 使用

安装后，对 AI 说以下任意触发词即可启用：

- "帮我审剧本"
- "看这个本子"
- "剧本评估"
- "改稿建议"

### 不用 AI 也能用

如果你不使用任何 AI 工具，**直接阅读 `SKILL.md` 文件**——它本身就是一份完整的编剧审稿手册。打印出来对着检查也完全可以。

---

## 核心框架

### 审稿三步法

```
第一步：选题判断 ——— 看梗概，判断值不值得做（S/A/B/C 四档）
         ↓
第二步：第一集生死线 — 逐项检查第一集是否合格（不合格=后面全白费）
         ↓
第三步：前三集信息检查 — 金手指/正反派/设定 是否在前三集交代清楚
```

### 改稿六把刀

| # | 维度 | 核心检查点 |
|---|------|----------|
| 🔪 | 故事主线 | 删无聊段落，加有效冲突，每集一个高潮+结尾钩子 |
| 🔪 | 剧情逻辑 | 世界观自洽，转折有铺垫，角色行为合理 |
| 🔪 | 主角台词 | 有辨识度，冲突用台词不用旁白，口头禅反复出现 |
| 🔪 | 人设执行对照 | 小传写了什么，剧本里就必须有什么 |
| 🔪 | 爽感兑现清单 | 不只看"有没有"，还要看"够不够重" |
| 🔪 | 感情线 | 有事件支撑，升温合理，不能只靠设定绑定 |

---

## 创作铁律

本 Skill 内置 **38 条创作铁律**，全部来自实战项目和爆款拆解。

以下是部分示例（完整版见 [SKILL.md](SKILL.md)）：

> **#F1** 第一集必须建立权力秩序
>
> **#F4** 女主从不需要被救，只需要被看见
>
> **#E2** 负反馈可以给很多，但必须在某个节点给足够强的正反馈
>
> **#G4** 女主可以很强，但代价必须可见。无代价的无敌=无聊
>
> **#M1** 设定好≠写出来了。小传标签在剧本里没体现=没有
>
> **#D1** 爽感不止看"有没有"，要看"够不够重"
>
> **#G7** 感情线终极验证=知道代价后仍然选择留下

铁律分六大类：
- 📐 结构与节奏（11条）
- 👤 角色与人设（10条）
- 💬 台词与表达（3条）
- 🔥 爽感与情绪（5条）
- 💕 感情线（4条）
- ⚙️ 金手指与设定（5条）

---

## 评级标准

| 评级 | 含义 | 特征 |
|------|------|------|
| **S+** | 现象级 | 全维度顶级，台词能记住，角色有代价 |
| **S** | 大爆款 | 选题+执行都是顶级 |
| **A** | 优质 | 有个别短板但不影响大局 |
| **B+** | 合格 | 故事讲清了，但情绪不到位 |
| **B** | 及格 | 能看，但不会追 |
| **C** | 不合格 | 故事讲不清楚 |

⚠️ **选题评级 ≠ 剧本评级。** A级选题可能被写成C级剧本。本Skill会分别评价两者。

---

## 仓库结构

```
screenwriter-skill/
├── SKILL.md                  # 核心 Skill 文件（AI可加载）
├── README.md                 # 你正在看的这个文件
├── LICENSE                   # MIT 协议
├── references/
│   └── iron_rules.md         # 37条创作铁律完整版（带分类和来源）
├── templates/
│   ├── review_template.md    # 审稿报告模板
│   └── checklist.md          # 快速检查清单（可打印）
└── examples/
    └── sample_review.md      # 示例审稿报告（脱敏）
```

---

## 实战验证

本 Skill 已通过以下实战验证：

- ✅ 审核 **5部** 不同题材的短剧/漫剧剧本（女频仙侠、男频都市、古装权谋、穿越爽文）
- ✅ 每次审核后与资深内容负责人的人工审稿意见对比，持续校准
- ✅ 所对标的作品中，有红果平台 **Top 100** 漫剧
- ✅ 铁律来源包含多部 **5000万+热度** 级别爆款的拆解

---

## 持续进化

这个 Skill 不是一次性产物。它会随着每一次新项目的复盘持续更新：

- 🔄 每审一部新剧本，校准一次审稿维度
- 📝 每上线一部新作品，从数据反馈中提炼新铁律
- 🤝 欢迎通过 Issue 和 PR 贡献你的实战经验

**目标：让这份 Skill 成为短剧/漫剧行业的公共知识库。**

---

## 贡献指南

欢迎贡献！尤其欢迎以下类型的 PR：

1. **新铁律** — 从你的实战项目中提炼的创作规则（需附来源说明）
2. **审稿维度补充** — 你发现了本 Skill 没覆盖到的检查点
3. **多语言翻译** — 帮助将本 Skill 翻译为其他语言
4. **Bug 修复** — 铁律描述不准确、格式问题等

---

## 关于

本 Skill 由 [元贞智影](https://github.com/你的用户名) 团队开发维护。

元贞智影是一家以 AIGC 技术为核心驱动力的内容创作公司，专注于 AI 漫剧和短剧制作。

**如果这个项目对你有帮助，请给个 ⭐ Star！**

---

<div align="center">

**AI造影，好戏开场。**

</div>

---

## Overview

**screenwriter-skill** is an AI skill package for reviewing scripts in the short drama / AI comic (manhua drama) industry.

It distills the script review methodology of a content director with 5+ years of industry experience and Top 100 platform hits into a loadable AI Skill.

### What it does

- ✅ Reviews scripts against professional standards with item-by-item feedback
- ✅ Checks if Episode 1 passes the "survival line"
- ✅ Validates emotional payoff against genre-specific checklists
- ✅ Cross-references character profiles against actual script execution
- ✅ Provides structured revision directions
- ❌ Cannot write scripts from scratch or replace human creative intuition

### Quick Start

```bash
# WorkBuddy
cd ~/.workbuddy/skills/ && git clone https://github.com/YOUR_USERNAME/screenwriter-skill.git

# Claude Code
cd ~/.claude/skills/ && git clone https://github.com/YOUR_USERNAME/screenwriter-skill.git
```

After installation, say "review this script" or "审剧本" to activate.

### 37 Iron Rules

The skill includes 38 battle-tested creative rules across 6 categories: Structure & Pacing, Characters, Dialogue, Emotional Payoff, Romance, and World-building. All rules are derived from real production experience and hit show analysis.

**Full documentation in Chinese.** English translation contributions welcome!

---

*MIT License · Built with 🔥 by Yuanzhen Pictures*
