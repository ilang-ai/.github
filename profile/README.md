<div align="center">

<img src="https://raw.githubusercontent.com/ilang-ai/Imprint/main/imprint-banner.png" alt="I-Lang Protocol" width="100%"/>

# I-Lang

### *The AI Communication Protocol*

[![Website](https://img.shields.io/badge/ilang.ai-0a0d16?style=for-the-badge&labelColor=d4a858&label=%E2%97%86)](https://ilang.ai)
[![npm](https://img.shields.io/npm/v/@i-language/spec?style=for-the-badge&label=npm&labelColor=0a0d16&color=d4a858)](https://www.npmjs.com/package/@i-language/spec)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-i--Lang-d4a858?style=for-the-badge&labelColor=0a0d16)](https://huggingface.co/i-Lang)
[![License](https://img.shields.io/badge/License-MIT-1e3a8a?style=for-the-badge)](LICENSE)

</div>

---

> MCP connects AI to tools. A2A connects agents to agents.
> **I-Lang defines how they communicate.**
>
> 88 verbs. 29 modifiers. 14 entities. Zero installation. Free forever.

---

## Why I-Lang

Every AI agent today speaks a slightly different dialect of natural language. Switching models means relearning prompts. Switching platforms means losing memory. Every conversation pays a "filler tax" of tokens spent on restating what the model should already know.

**I-Lang** is a communication protocol layer that fixes this:

- **Structured syntax** that carries intent, context, constraints, and output shape in one compact block
- **70.8% token savings** measured across 30 test cases, 6 categories, p < 0.0001 ([benchmark](https://github.com/ilang-ai/ilang-Benchmark))
- **Two syntaxes**: Operations for execution, Declarations for identity
- **Portable** across Claude, GPT, Gemini, DeepSeek, Kimi, Qwen, GLM, Grok, and more
- **Human-readable** plain text. No SDK, no binary, no vendor lock-in

---

## The Protocol (v3.0)

### Operations — tell AI what to do

**Before** (67 words):
> Please read the document I uploaded, extract all the key points and important data, then organize them into a professional summary with bullet points in Markdown format...

**After** (1 line):
```
[READ:@FILE]=>[FILT|key=important]=>[SUM|sty=bullets,ton=pro,fmt=md]=>[OUT]
```

### Declarations — define who AI is

```
::GENE{output_density|conf:confirmed}
  T:conclusions_first
  T:one_answer_not_three_options
  A:hedging⇒remove
  A:filler_phrases⇒remove
```

`T:` = always do this. `A:` = never do this.

### Core components

| Component | What it is | Link |
|-----------|-----------|------|
| **I-Lang Spec** | Protocol specification v3.0 | [ilang-spec](https://github.com/ilang-ai/ilang-spec) |
| **I-Lang Dict** | 88 verbs, 29 modifiers, 14 entities, 13 Greek aliases | [ilang-dict](https://github.com/ilang-ai/ilang-dict) |
| **I-Lang Benchmark** | 30 test cases, 70.8% token savings, reproducible | [ilang-Benchmark](https://github.com/ilang-ai/ilang-Benchmark) |
| **npm** | `npm install @i-language/spec` | [@i-language/spec](https://www.npmjs.com/package/@i-language/spec) |

---

## Ecosystem

| Product | What it does | Stars |
|---------|-------------|-------|
| [**Mem-Forever**](https://github.com/ilang-ai/Mem-Forever) | Persistent AI memory. Every AI forgets you after every session. This repo doesn't. Ever. | 13 ★ |
| [**Imprint**](https://github.com/ilang-ai/Imprint) | Your habits, imprinted on AI. One skill replaces eleven. 19 agents supported. | |
| [**AutoCode**](https://github.com/ilang-ai/autocode) | 39 auto-activated skills for Claude Code / Codex / OpenCode. | |
| [**ZeroCode**](https://github.com/ilang-ai/trae) | 40 Chinese skills for Trae / VS Code. Zero code, zero config, zero English. | |
| [**AI See**](https://i.ilang.ai) | Give your AI eyes. `i.ilang.ai/https://any-url` into any conversation. | |
| [**OpenClaw Skills**](https://github.com/ilang-ai/ilang-openclaw) | Token compression, AI-to-AI prompting, universal upgrade. | |

---

## Research

| Paper | Status | Links |
|-------|--------|-------|
| The Inductive Dilemma of AI Hallucination | Published | [ResearchGate](https://doi.org/10.13140/RG.2.2.22821.97762) / [SSRN](https://papers.ssrn.com/abstract=6377219) / [ChinaXiv](https://chinaxiv.org/abs/T202503.00129) |
| Logic-Layer Attacks: Theory and Examples | Published | PDF |
| Selective Forgetting Algorithm | In progress | |
| Cross-Base Genetic Expression of AI Personality | Planned | |

**ORCID:** [0009-0004-4540-8082](https://orcid.org/0009-0004-4540-8082)

---

## Platforms

Tested and verified on: ChatGPT, Claude, Gemini, DeepSeek, Kimi, Qwen, GLM, Grok, and more.

Compatible agents: Claude Code, Codex, Cursor, Copilot, Gemini CLI, Windsurf, Trae, Cline, Roo, OpenClaw, DeepSeek-TUI, and more.

---

## Distribution

| Channel | Link |
|---------|------|
| Website | [ilang.ai](https://ilang.ai) / [ilang.cn](https://ilang.cn) |
| npm | [@i-language/spec](https://www.npmjs.com/package/@i-language/spec) |
| Hugging Face | [i-Lang/iLang-Spec](https://huggingface.co/datasets/i-Lang/iLang-Spec) |
| Amazon (Book) | [I-Lang: I Language](https://www.amazon.com/dp/B0CZY6V3GM) |
| Research | [research.ilang.ai](https://research.ilang.ai) |

---

## Get involved

- [ilang.ai](https://ilang.ai)
- Issues and discussions on any repo
- hello@ilang.ai

Every I-Lang project is **MIT-licensed** and **free forever**.

---

<div align="center">

**Eastsoft Inc.** / *Canada*

<sub>Open standards for AI communication.</sub>

</div>
