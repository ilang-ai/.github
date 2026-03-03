# I-Lang

**The language AI speaks when humans aren't listening.**

I-Lang is an AI-native compression protocol. It compresses natural language prompts into dense instructions that AI models understand natively — no training, no fine-tuning. Typical savings: 40-60% fewer tokens, same results.

We built it because we were burning through tokens running [OpenClaw](https://github.com/AIConclave/OpenClaw) agents. Turns out, if you give AI a structured shorthand, it just... gets it.

## Quick Reference

| Natural Language | I-Lang | Saved |
|------------------|--------|-------|
| Read config from GitHub, format as JSON | `[READ:@GH\|path=config.json]=>[FMT\|fmt=json]` | 55% |
| Summarize previous in 3 bullets | `[Σ:@PREV\|sty=bullets,len=3]` | 52% |
| Translate doc to Chinese, save to R2 | `[θ:@SRC\|lng=zh]=>[WRIT:@R2]` | 60% |

## Repos

| Repo | What |
|------|------|
| [ilang.ai](https://github.com/ilang-ai/ilang.ai) | Website — try it live |
| [ilang-dict](https://github.com/ilang-ai/ilang-dict) | Verb, modifier & entity dictionary |
| [ilang-spec](https://github.com/ilang-ai/ilang-spec) | Protocol specification |
| [ilang-openclaw](https://github.com/ilang-ai/ilang-openclaw) | OpenClaw compression skill |

## Try it

**[ilang.ai](https://ilang.ai)** — paste a prompt, get compressed I-Lang, see token savings.

## License

MIT

---

*Palm Media Technology © 2026*
