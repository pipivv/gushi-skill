# gushi — 故事：银幕剧作原理

![封面](cover.jpg)

基于罗伯特·麦基《故事：材质、结构、风格和银幕剧作的原理》蒸馏的 AI 短剧编剧 Skill。

## 来源
- 原著：Robert McKee, *Story: Substance, Structure, Style, and the Principles of Screenwriting* (1997)
- 中译本：《故事：材质、结构、风格和银幕剧作的原理》，天津人民出版社，2014
- 全书 440 千字，19 章，4 大部分
- 本源文件：[故事-麦基.epub](故事-麦基.epub)
- 蒸馏工具：[dot-skill](https://github.com/titanwings/colleague-skill)

## 内容
本 Skill 包含两部分：

### Part A — 编剧方法论
- 故事三角（大情节 / 小情节 / 反情节）
- 结构层次（节拍 → 场景 → 序列 → 幕 → 故事）
- 鸿沟原理（期望与结果的裂缝）
- 人物设计（主人公 5 项必备特质、人物 vs 性格真相）
- 五步设计流程（激励事件 → 进展纠葛 → 危机 → 高潮 → 结局）
- 场景设计 7 项检查清单
- AI 短剧特别适配指南

### Part B — 麦基教学人格
- 原理导向的分析风格
- 严谨到近乎苛刻的标准
- 基于经典案例的教学方式

## 使用

本 Skill 遵循 [AgentSkills](https://agentskills.io) 标准，兼容所有支持该协议的 AI 编程助手。安装后输入 `/gushi` 或 `/colleague-gushi` 即可调用。

### 已测试兼容

| 宿主 | 触发方式 | Skill 安装路径 |
|------|---------|---------------|
| **Reasonix** | `/gushi` | `~/.reasonix/skills/gushi/SKILL.md` |
| **Claude Code** | `/gushi` | `~/.claude/skills/gushi/SKILL.md` |
| **Codex** | `/gushi` | `~/.codex/skills/gushi/SKILL.md` |
| **WorkBuddy** | `/gushi` | 导入 SKILL.md 即可 |
| **OpenClaw** | `/gushi` | `~/.openclaw/skills/gushi/SKILL.md` |
| **Hermes** | `/gushi` | `~/.hermes/skills/gushi/SKILL.md` |

> 💡 所有宿主使用同一份 `SKILL.md`，无需修改。触发词均为 `/gushi`。

## 安装

```bash
# 1. 克隆仓库
git clone https://github.com/pipivv/gushi-skill

# 2. 根据你的 AI 助手选择对应路径
# Reasonix
mkdir -p ~/.reasonix/skills/gushi
cp gushi-skill/SKILL.md ~/.reasonix/skills/gushi/SKILL.md

# Claude Code
mkdir -p ~/.claude/skills/gushi
cp gushi-skill/SKILL.md ~/.claude/skills/gushi/SKILL.md

# Codex
mkdir -p ~/.codex/skills/gushi
cp gushi-skill/SKILL.md ~/.codex/skills/gushi/SKILL.md

# OpenClaw
mkdir -p ~/.openclaw/skills/gushi
cp gushi-skill/SKILL.md ~/.openclaw/skills/gushi/SKILL.md

# Hermes
mkdir -p ~/.hermes/skills/gushi
cp gushi-skill/SKILL.md ~/.hermes/skills/gushi/SKILL.md

# WorkBuddy — 直接在设置中导入 gushi-skill/SKILL.md
```

安装后重启对应的 AI 助手，输入 `/gushi` 即可开始创作。
