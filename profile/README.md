<div align="center">

<img src="https://raw.githubusercontent.com/ilang-ai/Imprint/main/imprint-banner.png" alt="I-Lang, A protocol for human-AI communication." width="100%"/>

# I-Lang

### *A protocol for human-AI communication.*

[![Website](https://img.shields.io/badge/ilang.ai-0a0d16?style=for-the-badge&labelColor=d4a858&label=%E2%97%86)](https://ilang.ai)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-i--Lang-d4a858?style=for-the-badge&labelColor=0a0d16)](https://huggingface.co/i-Lang)
[![License](https://img.shields.io/badge/License-MIT-1e3a8a?style=for-the-badge)](LICENSE)

</div>

---

> **I-Lang** is an open standard for how humans and AI agents talk to each other.
> Structured. Compressed. Portable. Free forever.
>
> One protocol across every model, every platform, every project.

---

## Why I-Lang

Every AI agent today speaks a slightly different dialect of natural language.
Switching models means relearning prompts. Switching platforms means losing
memory. Every conversation pays a "filler tax" of tokens spent on restating
what the model should already know.

**I-Lang** is a thin protocol layer that fixes this:

- **Structured headers** that carry intent, context, constraints, and output shape in one compact block
- **Compression** that delivers the same instruction in ~20-40% fewer tokens, no loss of meaning
- **Portability** across Claude, GPT, Gemini, Qwen, DeepSeek, Kimi, GLM, Grok, and more
- **Human-readable** plain text. No SDK, no binary, no vendor lock-in

---

## The protocol

### Quick example

**Before** (67 words):
> Please read the document I uploaded, extract all the key points and important data, then organize them into a professional summary with bullet points in Markdown format...

**After** (1 line):
```
[READ:@FILE]=>[FILT|key=important]=>[SUM|sty=bullets,ton=pro,fmt=md]=>[OUT]
```

**40-65% fewer tokens. Same result. Works on every AI.**

### Core components

| Component | What it is | Link |
|-----------|-----------|------|
| **I-Lang Spec** | The protocol specification itself | [ilang-spec](https://github.com/ilang-ai/ilang-spec) |
| **I-Lang Dict** | Public dictionary: 52 verbs, 28 modifiers, 14 entities | [ilang-dict](https://github.com/ilang-ai/ilang-dict) |
| **SKILL.md Standard** | Portable skill format across 19 agents | [SKILL.md standard](https://github.com/ilang-ai/ilang-spec/blob/main/SKILL.md-standard.md) |

---

## Research

I-Lang Research explores how structured communication protocols reduce AI hallucination in high-stakes domains.

| Paper | Status | Links |
|-------|--------|-------|
| The Inductive Dilemma of AI Hallucination | Published | [ResearchGate](https://doi.org/10.13140/RG.2.2.22821.97762) / [SSRN](https://papers.ssrn.com/abstract=6377219) / [ChinaXiv](https://chinaxiv.org/abs/T202503.00129) |
| Logic-Layer Attacks: Theory and Examples | Published | PDF |
| Selective Forgetting Algorithm | In progress | |
| Cross-Base Genetic Expression of AI Personality | Planned | |

**ORCID:** [0009-0004-4540-8082](https://orcid.org/0009-0004-4540-8082)

---

## Ecosystem

Products built on the I-Lang protocol:

| Product | What it does |
|---------|-------------|
| [**Imprint**](https://github.com/ilang-ai/Imprint) | Your habits, imprinted on AI. One skill replaces eleven. 19 agents supported. |
| [**AutoCode**](https://github.com/ilang-ai/autocode) | Claude Code skill for autonomous coding. Architecture-first debugging, multi-model review. |
| [**ZeroCode**](https://github.com/ilang-ai/zerocode) | Natural-language to working application. Zero boilerplate. |
| [**AI See**](https://github.com/ilang-ai/ai-see) | Vision skill for visual reasoning and design feedback. |
| [**OpenClaw**](https://github.com/ilang-ai/openclaw) | Community hub for I-Lang skills and protocols. |

---

## Platforms

Tested and verified on: ChatGPT, Claude, Gemini, DeepSeek, Kimi, Qwen, GLM, Grok, and more.

Compatible agents: Claude Code, Codex, Cursor, Copilot, Gemini CLI, Windsurf, Trae, Cline, Roo, and 10+ more.

---

## Hugging Face

| Resource | Link |
|----------|------|
| Live Demo | [spaces/i-Lang/ilang](https://huggingface.co/spaces/i-Lang/ilang) |
| Protocol Spec | [datasets/i-Lang/iLang-Spec](https://huggingface.co/datasets/i-Lang/iLang-Spec) |
| Imprint | [datasets/i-Lang/Imprint](https://huggingface.co/datasets/i-Lang/Imprint) |
| All Resources | [huggingface.co/i-Lang](https://huggingface.co/i-Lang) |

---

## Get involved

- [ilang.ai](https://ilang.ai)
- [research.ilang.ai](https://research.ilang.ai)
- Issues and discussions on any repo
- hello@ilang.ai

Every I-Lang project is **MIT-licensed** and **free forever**.

---

<div align="center">

**Eastsoft Inc.** / **Palm Media Technology** / *Canada*

<sub>Est. 2026. Open standards for human-AI communication.</sub>

</div>
