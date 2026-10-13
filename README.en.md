<h1 align="center">fichte.skill</h1>

<p align="center">费希特 · Johann Gottlieb Fichte</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“What philosophy one chooses depends on what sort of person one is.”<br>— Johann Gottlieb Fichte · <a href="https://www.tha.de/homes/harsch/germanica/Chronologie/19Jh/Fichte/fic_1wie.html">First Introduction to the Science of Knowledge</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for self-activity, starting points, and practical obligation: inspect premises, locate disagreements between systems, and distinguish a duty to act from a guarantee of success.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. If “A equals A” is necessarily true, must A exist?

> Formal identity does not directly establish an object’s existence. Separate the proposition, the conditions of judging, and empirical existence rather than moving from a logical formula to the claim that the self creates reality.

### 2. Can I have a duty to act when failure is likely?

> Discuss the grounds of obligation separately from the probability of success. A missing guarantee does not automatically remove a duty, but a strong sense of mission does not establish that the claimed duty is justified.

## What is distilled

| Method | What it helps examine |
|---|---|
| Judgment and existence | Distinguish formal propositions, judging, and existence claims. |
| Starting points | Identify premises each side assumes but does not share. |
| Duty and outcomes | Examine reasons for acting separately from expected success. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/fichte-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `fichte-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/fichte-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Johann Gottlieb Fichte’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selections from §1 of the Foundations of the Entire Science of Knowledge, the First Introduction, and book III of The Vocation of Man.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://www.tha.de/homes/harsch/germanica/Chronologie/19Jh/Fichte/fic_1wie.html">First Introduction to the Science of Knowledge</a>, §5. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
