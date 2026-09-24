# 一页纸：我做什么

下面用中文把边界说清楚。更细的说明多半是英文，都挂在链接里；你可以从这里决定先点哪几个。

---

## 一句话

我在语音面试产品里做内容 / 测评产品设计：候选人说完 **下一句该问什么**，报告上的分 **到底在量什么**，以及整场面试 **怎么从谈需求串到开面**。尽量写成能换模型、能验收的规则，而不是靠临场改提示词。

我不是全栈 Agent 负责人，也不是专门润色话术的人。

---

## 做什么 / 不做什么

| 做 | 不做（或不对外这么说） |
| --- | --- |
| 多轮追问怎么分支：答偏了怎么拉回来、按作答深浅调节问法、不同题型怎么往下挖、什么时候停、怎样算问得好 | 生产环境完整提示词、客户原题、打分权重表 |
| 任务型英语口语怎么设计、怎么合成报告；厂商流利度不准时，我们自己认哪一套 | 宣称对等雅思/CEFR，或说语音厂商内部算法是我做的 |
| 把常被混在一起的「英语面试」分开：测口语能力，和用英语聊岗位经历，不是一回事 | 宣称「对话式口语定级」已经能当正式测评卖（公开材料里写的是难点和门槛） |
| 会话级整场：跟 HR 谈需求 → 离线整理 → 确认考察重点与题目 → 开启候选人对话（探索设计） | 宣称这套探索设计已是上线生产配置 |
| 线上翻车了，从失败回合倒推该改哪条规则 | 模型训练或推理平台的负责人角色 |

公开仓里：决策图 / 口语仓以**方法**为主，不放生产正文；[full-session-interview](https://github.com/yuanlin-82/full-session-interview) 另有**模拟实验用** prompt，方便复现——不是客户上线包。

---

## 四条线，别混着看

| | 它回答什么 | 去哪看 |
| --- | --- | --- |
| **追问怎么走** | 说完下一句问什么、难度是否贴着作答层次、何时结束这道题 | [ai-interview-decision-map](https://github.com/yuanlin-82/ai-interview-decision-map) |
| **口语能力分** | 在标准口语题里，发音、流利、内容覆盖大致怎样 | [english-speaking-assessment](https://github.com/yuanlin-82/english-speaking-assessment) |
| **现有产品：整场到报告** | 怎么组卷、作答、打题分、再汇总成维度报告 | [system-map.md](system-map.md) · [题分怎么进维度](item-to-dimension-score.md) |
| **探索：会话级整场对话** | HR 需求访谈 → 离线变量 → 确认重点与题目 → 开启整场对话 | [full-session-interview](https://github.com/yuanlin-82/full-session-interview) |

用英语做的岗位胜任力面试，跟的是「追问怎么走」那条线：英语只是交流手段，要的是经历和判断有没有说清楚。  
追问问得好、聊得顺，都不等于口语定了级；口语任务分也不能直接当成「这人能不能录用」。  
`system-map` 和 `full-session-interview` 都谈「整场」，但一个偏**现有组卷—报告产品图**，一个偏**会话级探索设计**，不要当成同一个仓。

---

## 若只有几分钟，建议按这个顺序

1. 先看本页（边界）  
2. [system-map.md](system-map.md)（现有产品整场长什么样）  
3. 若关心「从谈需求到开面」的探索链路 → [full-session-interview](https://github.com/yuanlin-82/full-session-interview)  
4. 决策图：从 [Visitor guide](https://github.com/yuanlin-82/ai-interview-decision-map#visitor-guide) 进，再随便点一篇 [失败怎么改成规则](https://github.com/yuanlin-82/ai-interview-decision-map/blob/main/docs/from-failure-to-contract.md)  
5. 口语仓：按 [Reading order](https://github.com/yuanlin-82/english-speaking-assessment#reading-order)，优先看 `task-vs-interaction`

---

## 相近的工作我也能沾边

能力相近，但交付物不一样，别按错岗位理解我：

| 场景 | 我比较能帮上的 | 别把我理解成 |
| --- | --- | --- |
| AI 面试 / 人事科技 | 追问规则、何时停、口语和胜任力怎么分开报、整场怎么串 | 只写面试话术的运营 |
| 口语评测 / 英语伴学 | 题型与构念、自动分能量到哪、厂商分怎么用 | 交互考官引擎已经做完能上线 |
| 智能陪练（销售、模拟面试等） | 情景里下一问怎么问、练完按什么标准打分 | 只写人设和开场白的闲聊机器人 |
| 企业培训 / 学习发展 | 学会了没有的标准、答歪了怎么收回来、报告别夸大 | 通用大模型应用开发 |

---

## 目前在看什么机会

希望在北京找全职，方向是对话、测评、或 AI 产品里偏内容与评价的工作。若内容匹配，远程协作也可以谈。

联系方式：请在上面的 GitHub 仓库开 Issue。
