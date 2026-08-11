# Hi, I'm Yuanlin

## 中文导读

国内转发请优先看：**[一页纸：我做什么](docs/zh-overview.md)**。

我在语音面试里做两件事：下一句该问什么，以及分到底在量什么——不是全栈 Agent，也不是润色话术。

- **追问怎么走** → [ai-interview-decision-map](https://github.com/yuanlin-82/ai-interview-decision-map)  
- **口语能力分** → [english-speaking-assessment](https://github.com/yuanlin-82/english-speaking-assessment)  
- **整场上下文** → [docs/system-map.md](docs/system-map.md) · [题分怎么进维度](docs/item-to-dimension-score.md)

用英语聊岗位 ≠ 口语定级。公开仓只放方法论；提示词和权重不公开。

目前意向：北京全职（对话 / 测评 / AI 产品内容向）；合适的远程也可。

---

## What I Do

I'm a **Conversational AI Designer** (content / assessment side) focused on **multi-turn dialogue strategy**, **evaluable quality contracts**, and **task-based oral assessment**—especially for voice-first interview products.

**Role boundary:** I own routing contracts, failure taxonomies, probe-quality gates, and oral **construct / composition** design. I do **not** claim full-stack Agent platform ownership or model training. Production prompt bodies stay **private**; public repos are the shareable methodology.

Not “prompt copywriting”: business rules → **executable routing** (what to do next turn) and **auditable standards** (what counts as good / bad). Separately: oral scores—constructs, composition, where automation stops.

**Routing** = *what to ask next*. **Oral scores** = *how speech performed under standard tasks*. Do not merge them with English-medium competency interviews.

## Open to

**Full-time roles in Beijing** (dialogue / assessment / AI product content-science).  
Also open to well-scoped remote collaboration when it fits.

## Start here

| Link | Why |
| --- | --- |
| [中文一页纸](docs/zh-overview.md) | Beijing / referral forward sheet (Chinese) |
| [Session system map](docs/system-map.md) | Whole-session context: 组卷 → 问答/选择 → 题分 → 加权报告 |
| [Item → dimension score](docs/item-to-dimension-score.md) | Competency evidence cells → dimension roll-up (not oral bands) |
| [Decision map — visitor guide](https://github.com/yuanlin-82/ai-interview-decision-map#visitor-guide) | Overview router · stop gates · **one failure→contract path** |
| [From failure to contract](https://github.com/yuanlin-82/ai-interview-decision-map/blob/main/docs/from-failure-to-contract.md) | Wrong re-anchor target: symptom → layer → principle → eval |
| [Oral assessment — reading order](https://github.com/yuanlin-82/english-speaking-assessment#reading-order) | Task vs interaction; fluency ownership; content-completeness limits |

## Current Focus

- Multi-turn follow-up under real product constraints (exceptions, ASR noise, one question per turn, TTS)
- Decision contracts that survive language / model swaps
- Quality loops: paired compares, fatal-first gates, failure taxonomy
- Stop policy as a **fast parallel brake** beside generation—not only “max rounds” in a doc
- Oral report constructs under automation limits (fluency ownership, content coverage vs examiner depth)

## Featured

**[中文一页纸](docs/zh-overview.md)** — 给内推/同事转发：我做什么、别和什么弄混、先点哪几个链接。

**[Session system map](docs/system-map.md)** — One-page product context (config → live item loop → weighted report); links into the two methodology repos below.

**[Item → dimension score](docs/item-to-dimension-score.md)** — Competency evidence cells → dimension roll-up (shape only; not oral bands).

**[AI Interview Follow-up Decision Map](https://github.com/yuanlin-82/ai-interview-decision-map)** — Dialogue **routing** methodology ([reading order](https://github.com/yuanlin-82/ai-interview-decision-map#suggested-reading-order)):

- Stem typing → abnormal families → typed normal packs  
- Stop gates: time hardest; generator ≠ stop brake ≠ offline judge  
- Field notes + [from-failure-to-contract](https://github.com/yuanlin-82/ai-interview-decision-map/blob/main/docs/from-failure-to-contract.md)  
- **Methodology only** (no production prompts)

**[English speaking assessment](https://github.com/yuanlin-82/english-speaking-assessment)** — Task-based **oral scoring** methodology ([reading order](https://github.com/yuanlin-82/english-speaking-assessment#reading-order)):

- Task-based vs interaction-based; fence from competency-in-English interviews  
- Pronunciation · fluency (in-house when vendor fails) · content completeness (automation compromise)  
- **Methodology only** (no production weights / vendor internals)

## Key Experience

- Designed and maintained a **state-machine-in-prompt** dialogue system with **10+** exception branches in a single LLM call
- Built decision taxonomies that map messy candidate behavior → structured action classes
- Prefer **observables over mind-reading** for abnormal recovery (named buckets, not open intent inference)
- Defined hearable / unhearable intent boundaries and fixed recovery moves (no invented emotion or premises)
- Shipped **stop-vs-generate in parallel**: fast classifier as a brake; missed intercept ≈ one extra probe, with time/round backstops
- Optimized for sub-second TTS latency: when “fat prompts” work vs when routing should be layered
- Delivered customer-customized follow-up policies (domain rules → enforceable dialogue strategy)
- Owned oral **fluency** when multi-vendor scores were insensitive / false-high vs expert ear; kept pronunciation and content coverage as composed inputs
- Named **content completeness** honestly as task coverage under auto-scoring limits—not examiner-style depth
- Separated oral ability reports from English-medium **competency** interview evidence in product narrative

## What I Bring

- Abstract business logic into **executable dialogue strategies**, not one-off wording
- Clear judgment on eval: judge **routes first**, then sentences; fatals before style
- Clear judgment on scores: name the **construct**, own what vendors mis-measure, fence automation limits
- Builder habit: validate with the simplest contract, then evolve from failure cases

## Background (short)

Applied Psychology (MHR), Beijing Normal University · content-side work on AI interview products (follow-up, banks, scoring) · prior education / family-guidance content craft.

## Contact

Prefer GitHub so threads stay in one place:

- Open an issue on the [Decision Map](https://github.com/yuanlin-82/ai-interview-decision-map) or [English speaking assessment](https://github.com/yuanlin-82/english-speaking-assessment) repo, or
- Use GitHub Discussions / a brief issue on this profile

I don’t monitor public inboxes regularly, so **please don’t rely on email**.
