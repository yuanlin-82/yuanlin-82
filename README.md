# Hi, I'm Yuanlin

## 中文简介

想先看个大概，打开这一页就行：**[一页纸：我做什么](docs/zh-overview.md)**。

我做语音 AI 面试这边的内容 / 测评产品设计：候选人说完下一句该问什么、分数到底在评什么，以及整场面试怎么从谈需求串到开面。不是去搭整套 Agent，也不是靠临场改提示词撑场面。

仓库大概分四块：

- **下一句怎么问**（含作答层次/难度分流） → [ai-interview-decision-map](https://github.com/yuanlin-82/ai-interview-decision-map)  
- **口语怎么打分** → [english-speaking-assessment](https://github.com/yuanlin-82/english-speaking-assessment)  
- **现有产品：整场怎么组卷到报告** → [docs/system-map.md](docs/system-map.md) · [题分怎么汇总到维度](docs/item-to-dimension-score.md)  
- **探索：会话级整场对话怎么串** → [full-session-interview](https://github.com/yuanlin-82/full-session-interview)

另外常有人弄混：用英语聊工作经历，和考英语口语水平，不是一回事。  
公开仓里主要是方法与设计；**生产提示词、权重、客户配置不公开**。另有一个探索仓带有**模拟实验用**的 prompt 全文，方便复现讨论——不是上线配置。

公开方法也可迁移到更广的对话质量问题：假共情、越界、一次多问、该不该说——同样是 Badcase → 合同 → 质检，不只服务招聘面试。

最近在看北京全职：对话 / 测评 / 内容标定，以及情感智能、垂类评测里「输出好不好、边界在哪里」一类工作；远程合适的话也可以聊。

---

## What I Do

I'm a **Conversational AI Designer** (content / assessment / session product design) focused on **multi-turn dialogue strategy**, **evaluable quality contracts**, **task-based oral assessment**, and **full-session interview assembly**—especially for voice-first interview products.

**Role boundary:** I own routing contracts, failure taxonomies, probe-quality gates, oral **construct / composition** design, and exploratory **session-level** interview architecture (HR needs → prep → live dialogue). I do **not** claim full-stack Agent platform ownership or model training. **Production** prompt bodies and scoring weights stay **private**. One public exploration repo includes **simulation prompts** for inspectability—not deployment configs.

Not “prompt copywriting”: business rules → **executable routing** (what to do next turn) and **auditable standards** (what counts as good / bad). Separately: oral scores—constructs, composition, where automation stops. Separately again: how a **whole session** is wired from hiring needs to conversation.

**Routing** = *what to ask next*. **Oral scores** = *how speech performed under standard tasks*. **Full-session exploration** = *how HR needs, plans, and live dialogue connect*. Do not merge oral bands with English-medium competency interviews.

## Open to

**Full-time roles in Beijing:** dialogue quality, assessment / content calibration, and related work on emotional-intelligence or vertical eval (what counts as good output, where boundaries sit)—not full-stack Agent ownership.  
Also open to well-scoped remote collaboration when it fits.

## Start here

| Link | Why |
| --- | --- |
| [中文简介 · 一页纸](docs/zh-overview.md) | 中文自我介绍与仓库入口 |
| [Session system map](docs/system-map.md) | Product context: 组卷 → 问答/选择 → 题分 → 加权报告 |
| [Full-session interview](https://github.com/yuanlin-82/full-session-interview) | Exploratory session pipeline: HR needs → offline prep → live dialogue |
| [Item → dimension score](docs/item-to-dimension-score.md) | Competency evidence cells → dimension roll-up (not oral bands) |
| [Decision map — visitor guide](https://github.com/yuanlin-82/ai-interview-decision-map#visitor-guide) | Overview router · answer-depth band · stop gates · failure→contract |
| [From failure to contract](https://github.com/yuanlin-82/ai-interview-decision-map/blob/main/docs/from-failure-to-contract.md) | Wrong re-anchor target: symptom → layer → principle → eval |
| [Oral assessment — reading order](https://github.com/yuanlin-82/english-speaking-assessment#reading-order) | Task vs interaction; fluency ownership; content-completeness limits |

## Current Focus

- Multi-turn follow-up under real product constraints (exceptions, ASR noise, answer-depth match, one question per turn, TTS)
- Decision contracts that survive language / model swaps
- Quality loops: paired compares, fatal-first gates, failure taxonomy
- Stop policy as a **fast parallel brake** beside generation—not only “max rounds” in a doc
- Oral report constructs under automation limits (fluency ownership, content coverage vs examiner depth)
- Full-session assembly: hiring-needs interview → confirm gates → conversational interview (exploration)

## Featured

**[一页纸：我做什么](docs/zh-overview.md)** — 中文说明：我做什么、别和什么弄混、建议先看哪些链接。

**[Session system map](docs/system-map.md)** — One-page **product** context (config → live item loop → weighted report); links into the methodology repos below.

**[Full-session interview](https://github.com/yuanlin-82/full-session-interview)** — Exploratory **session-level** design ([overview map](https://github.com/yuanlin-82/full-session-interview/blob/master/maps/overview.md)):

- HR needs interview → offline company / candidate variables → confirm focus & questions → live dialogue  
- Simulation prompts published for inspection (**not** production configs)  
- Complements turn-level routing in the Decision Map repo

**[Item → dimension score](docs/item-to-dimension-score.md)** — Competency evidence cells → dimension roll-up (shape only; not oral bands).

**[AI Interview Follow-up Decision Map](https://github.com/yuanlin-82/ai-interview-decision-map)** — Dialogue **routing** methodology ([reading order](https://github.com/yuanlin-82/ai-interview-decision-map#suggested-reading-order)):

- Stem typing → abnormal families → **answer-depth band** (scaffold / pin / deepen) → typed packs  
- Stop gates: time hardest; generator ≠ stop brake ≠ offline judge  
- Field notes + [from-failure-to-contract](https://github.com/yuanlin-82/ai-interview-decision-map/blob/main/docs/from-failure-to-contract.md) · [difficulty mismatch](https://github.com/yuanlin-82/ai-interview-decision-map/blob/main/docs/failure-case-difficulty-mismatch.md)  
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
- Explored **full-session** interview assembly (HR needs → offline prep → confirm gates → conversational interview) as an open design pilot

## What I Bring

- Abstract business logic into **executable dialogue strategies**, not one-off wording
- Clear judgment on eval: judge **routes first**, then sentences; fatals before style
- Clear judgment on scores: name the **construct**, own what vendors mis-measure, fence automation limits
- Builder habit: validate with the simplest contract, then evolve from failure cases

## Background (short)

Applied Psychology (MHR), Beijing Normal University · content-side work on AI interview products (follow-up, banks, scoring, session design) · prior education / family-guidance content craft.

## Contact

Prefer GitHub so threads stay in one place:

- Open an issue on the [Decision Map](https://github.com/yuanlin-82/ai-interview-decision-map), [English speaking assessment](https://github.com/yuanlin-82/english-speaking-assessment), or [Full-session interview](https://github.com/yuanlin-82/full-session-interview) repo, or
- Use GitHub Discussions / a brief issue on this profile
