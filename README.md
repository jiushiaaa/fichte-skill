<h1 align="center">fichte.skill</h1>

<p align="center">费希特 · Johann Gottlieb Fichte</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“选择怎样的哲学，取决于一个人是怎样的人。”<br>— 费希特 · <a href="https://www.tha.de/homes/harsch/germanica/Chronologie/19Jh/Fichte/fic_1wie.html">《知识学第一导论》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将自我活动、体系起点与实践义务整理为思想分析 Skill，让 AI 检查判断的前提，辨认争论为何无法相遇，并分清应当去做与保证成功。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 既然“A等于A”必然正确，能证明A一定存在吗？

> 形式上的同一不直接给出对象存在。分析会把命题内容、作出判断所需的条件以及经验存在分开，避免从逻辑式子跳到“我能创造现实”。

### 2. 如果最后很可能失败，我还有义务去做吗？

> 失败概率与义务根据需要分别讨论。先说明义务为何成立，再检查现实行动条件；没有成功保证不会自动消除义务，强烈的使命感也不能自动证明这项义务正当。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 判断与存在 | 区分形式命题、判断活动与对象存在的断言。 |
| 体系起点 | 检查争论是否预先借用了各自尚未共享的前提。 |
| 义务与结果 | 分别审查行动理由与预期成效。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/fichte-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `fichte-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/fichte-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用费希特的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《全部知识学的基础》§1选段；《知识学第一导论》选段；《人的使命》第三部选段。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://www.tha.de/homes/harsch/germanica/Chronologie/19Jh/Fichte/fic_1wie.html">《知识学第一导论》</a>，第 5 节。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
