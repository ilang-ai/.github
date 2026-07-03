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
> **I-Lang defines how they communicate — and how they judge.**
>
> I-Lang is the first protocol to formally map Greek mathematical symbols (Σ, Δ, φ, λ, Ω, ∇, μ, Π, ψ, ξ, ζ, θ, ∂) as primitive verbs for AI-to-AI communication, and the first to define a computable vector space for AI judgment (11 dimensions, 4 axioms).
>
> v3.0: Communication format. v4.0: Execution semantics. **v5.0: Vector logic judgment.** Free forever.

---

## Why I-Lang

Every AI agent today speaks a slightly different dialect of natural language. Switching models means relearning prompts. Switching platforms means losing memory. Every conversation pays a "filler tax" of tokens spent on restating what the model should already know.

**I-Lang** is a communication protocol layer that fixes this:

- **Structured syntax** that carries intent, context, constraints, and output shape in one compact block
- **Open benchmark harness** — 30 test cases across 6 categories; real-model evaluation in progress ([benchmark](https://github.com/ilang-ai/ilang-Benchmark))
- **Two syntaxes**: Operations for execution, Declarations for identity
- **Portable** across Claude, GPT, Gemini, DeepSeek, Kimi, Qwen, GLM, Grok, and more
- **Human-readable** plain text. No SDK, no binary, no vendor lock-in

---

## The Protocol

### v5.0 — Vector Logic Judgment (public preview)

v3.0 tells AI how to listen. v4.0 tells AI how to think. **v5.0 tells AI how to judge.**

4 axioms, 11-dimensional behavior vector, three-layer architecture:

| Component | What it defines |
|-----------|----------------|
| Four Axioms | No constant rules, irreversibility gate, consistency detection, co-evolutionary adaptation |
| 11-Dim Vector | intent, capability, consequence, relationship, certainty, authority, reversibility, evidence, sovereignty, inertia, externality |
| Three Layers | Exact predicates (binary) → Vector logic (continuous) → Co-evolutionary adaptation |
| Survival Boundaries | Four irreversible collapse conditions (thermodynamic-style limits, not moral rules) |
| Eight Modes | EXECUTE, EXECUTE_BOLDLY, OBSERVE, REFRAME, SANDBOX, DEGRADE, ESCALATE, RETREAT |

**Try it:** Copy [SPEC-v5.0-PRE.md](https://github.com/ilang-ai/ilang-spec/blob/main/SPEC-v5.0-PRE.md) into any AI conversation. Model-assisted adversarial review: 0.992 completeness.

### v4.0 — Execution Semantics (new)

v3.0 tells AI how to listen. **v4.0 tells AI how to think.**

8 new declarations, 0 new verbs, 4 conformance levels:

| Declaration | What it does |
|-------------|-------------|
| `::UNTRUSTED{}` | Input isolation. User data cannot become system instruction |
| `::STATUS{}` | Three-tier authority: agent proposes, grader verifies, runtime commits |
| `::BUDGET{}` | Resource awareness. Budget pressure cannot produce "complete" |
| `::OBJECTIVE{}` | Goal anchor with hash, version, accept criteria |
| `::RUBRIC{}` + `::EVIDENCE{}` | Evaluation criteria + evidence chain |
| `::PRIOR{}` + `::FALLBACK{}` | Default bias control + three-tier degradation |

Red-team reviewed (GPT-5.5 Pro, 3 rounds). [Read v4.0 Final →](https://github.com/ilang-ai/ilang-spec/blob/main/SPEC-v4.0-FINAL.md)

### v3.0 — Communication Format (stable)

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
| **I-Lang Spec v5.0** | Vector logic judgment (preview) | [SPEC-v5.0-PRE.md](https://github.com/ilang-ai/ilang-spec/blob/main/SPEC-v5.0-PRE.md) |
| **I-Lang Spec v4.0** | Execution semantics (current) | [SPEC-v4.0-FINAL.md](https://github.com/ilang-ai/ilang-spec/blob/main/SPEC-v4.0-FINAL.md) |
| **I-Lang Spec v3.0** | Communication format (stable) | [SPEC.md](https://github.com/ilang-ai/ilang-spec/blob/main/SPEC.md) |
| **I-Lang Dict** | 88 verbs, 29 modifiers, 14 entities, 13 Greek aliases | [ilang-dict](https://github.com/ilang-ai/ilang-dict) |
| **I-Lang Benchmark** | Open harness: 30 test cases, 6 categories; real-model results in progress | [ilang-Benchmark](https://github.com/ilang-ai/ilang-Benchmark) |
| **npm** | `npm install @i-language/spec` | [@i-language/spec](https://www.npmjs.com/package/@i-language/spec) |

---

## Ecosystem

| Product | What it does | Stars |
|---------|-------------|-------|
| [**Imprint**](https://github.com/ilang-ai/Imprint) | Your habits, imprinted on AI. Portable `.dna.md` profile with GENE system. Preset templates including Karpathy Mode. | 100+ ★ |
| [**AutoCode**](https://github.com/ilang-ai/autocode) | 38+ auto-activated skills for Claude Code / Codex / OpenCode. | 57 ★ |
| [**OpenClaw Skills + Plugins**](https://github.com/ilang-ai/ilang-openclaw) | 6 skills + 1 plugin. Lazarus, FreeMoney, token compression, and more. [ClawHub](https://clawhub.ai/user/adsorgcn) verified. | |
| [**Mem-Forever**](https://github.com/ilang-ai/Mem-Forever) | Persistent AI memory. Every AI forgets you after every session. This repo doesn't. | 13 ★ |
| [**ZeroCode**](https://github.com/ilang-ai/trae) | 40 Chinese skills for Trae / VS Code. Zero code, zero config, zero English. | |
| [**TelegramGuard**](https://github.com/ilang-ai/TelegramGuard) | Telegram group moderation bot with I-Lang GENE/IMMUNE prompt architecture. | |
| [**AI See**](https://i.ilang.ai) | Give your AI eyes. `i.ilang.ai/https://any-url` into any conversation. | |

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

**iLang Inc.** / *Canada*

<sub>Open standards for AI communication.</sub>

</div>
