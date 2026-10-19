# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

---

## 🔥 今日头条

**1️⃣ Meta 发布首个前沿模型系列 Muse Wonder，全球前沿竞赛进一步多极化。** 10月12日，Meta 超级智能实验室（Meta Superintelligence Labs，AI 负责人 Alexandr Wang）正式发布 Muse Wonder 与 Muse Wonder Full 两款模型（开发代号"Watermelon"），称其在个人与专业智能体（Agentic）任务、记忆与编程场景达到业界前沿水平。Meta 公布的基准显示其性能与 Anthropic 的 Claude Fable 5.1、OpenAI 的 GPT-6 Astra 相当；在 Artificial Analysis 智能指数 v4.3 中，Wonder Full 得分 56（标准版 52），仅次于 Claude Opus 5.5（58 分）、高于 OpenAI 与 Google 的最强模型（各 53 分）；中文媒体转述称其编程智能体表现与 Claude 并列第一。定价 $4/$20 每百万 token（输入/输出），与 Opus 5.5 同价位；已通过 Meta Model API 与 Muse Code 提供（Full 版限高级订阅，新增 Active Memory / Active Focus 能力）。发布当日 Meta 股价上涨约 3.4%–4.1%（约报 $748）。[来源：TechCrunch/WIRED/NYT/The Verge/新浪科技]

**2️⃣ 微软发布第三代自研 AI 芯片 Maia 300：从"最大押注"到百万颗级部署。** 10月12日于 OCP 全球峰会（圣何塞）亮相：288GB HBM4 显存、18TB/s 带宽；微软称其每兆瓦可产出比"领先 GPU 系统"多 40% 的 token，机架级吞吐为 Maia 200 的 7 倍。微软计划 2027 年起以"多吉瓦级"规模部署超 100 万颗 Maia 300，使其成为自家 AI 服务的主要推理硬件；公司预计今年资本开支超 1,750 亿美元。纳德拉称其为"对自研芯片的最大一笔押注"；当日微软股价涨约 2.4%，英伟达、AMD 承压。[来源：GeekWire/CNBC/Reuters/HPCwire]

---

## ☝ Headlines

- **Meta·Muse Wonder**：Meta 首个前沿模型发布，对标 Claude Opus 5.5/Fable 5.1 与 GPT-6 Astra，$4/$20 定价、发布日股价涨约 3-4%
- **微软·Maia 300**：第三代自研 AI 芯片亮相，2027 年部署超百万颗、能效 +40%/MW
- **亚马逊·Decart**：洽谈约 70 亿美元收购 AI 芯片软件公司 Decart（Anthropic 尽调后退出、亚马逊接手）
- **英国 AI 安全**：白宫解除 17 天冻结，UK AISI 恢复 OpenAI/Anthropic/DeepMind 预发布模型访问；同日英国公布 AI 风险防御包
- **DeepMind·AlphaProof Nexus**：解出 9 个 Erdős 开放数学问题（2 个悬置 56 年）+ 44 个数列猜想，并通过同行评审
- **中国 AI**：大模型周调用量 86.74 万亿 Token（环比 +50.96%）连续 24 周全球第一、前五全为中国模型；美国头部两家厂商则占近九成收入

---

## 📊 分类详报

### 🧠 模型与技术

- **Meta Muse Wonder 更多细节**：该系列由 Meta 超级智能实验室开发（2025 年 6 月招入 Scale AI 创始人 Alexandr Wang 后启动 AI 重构，历时约 14 个月），定位"面向个人与专业智能体任务的前沿模型"，较前代 Muse Spark 明显升级（Artificial Analysis 智能指数 48 → 52/56）。WIRED 评价其"让 Meta 重回 AI 前沿"。社区侧：开发者对比指出 Wonder 定价与 Opus 5.5 完全持平，但在 Meta 自家 14 项基准中有 9 项落后（dev.to 分析）；Full 版目前仅限 Meta 高级 AI 编码订阅用户。[来源：TechCrunch/WIRED/NYT/Artificial Analysis/dev.to]

- **Claude Opus 5.5 Max 首次登顶 Arena 智能体榜**：Anthropic 新模型首次入榜即夺得智能体榜第一，工具幻觉率仅 0.37%；综合榜由 Google gemini-4-argon-high 居首；国产模型 kimi-k3-max 稳居综合榜前 20，qwen3.8-max 等多款保持中上游。[来源：Arena AI 周榜（网易/搜狐转载）]

- **OpenRouter 周度调用数据（10月5日-11日）**：全球总调用量 172 万亿 Token（环比 +3.61%）；中国大模型 86.74 万亿（+50.96%），连续 24 周超过美国（18.97 万亿，+17.1%），约为其 4.6 倍；全球前五全为中国模型——DeepSeek V4.1 Flash（41 万亿、+60%）、智谱 GLM 5.3 Flash（12.2 万亿）、小米 MiMo-V2.6-Flash（11.5 万亿）、阶跃星辰 Step 5 Preview（8.84 万亿）、腾讯 Hy4 preview（8.28 万亿）；Claude Opus 5.5 居第八（5.02 万亿）。[来源：每日经济新闻/OpenRouter 测算]

### 📋 政策与监管

- **英国恢复前沿模型预发布访问权（10月12日）**：白宫逆转此前"企业须先获美国批准才能向英方共享模型"的政策，为期 17 天的冻结解除。英国 AI 部长 Kanishka Narayan 确认：UK AISI 将继续对 OpenAI、Anthropic、Google DeepMind 的最强模型进行发布前安全评估（正评估 Gemini 4 Argon 等系统）；其称目标是让英国"成为全球最难被 AI 攻击的国家之一"。[来源：Quartz/Bloomberg/Firstpost/TheNextWeb]

- **英国公布 AI 风险防御包（10月12日）**：追加系列国家级防御措施——延长"用前沿 AI 审计政府代码"试点（既有两轮试点已发现 1,000+ 潜在漏洞；其中已公布一轮以约 £13,000 的 token 成本发现 407 处弱点）；政府表示或立法保护关键基础设施免受 AI 网络威胁，并着手准备"自主系统脱离人类控制"类事件的应急机制（有专家呼吁"终止开关"）。[来源：Unite.AI/TheNextWeb/bankinfosecurity/resiliencemedia]

- **美国 CAISI 拟"并入"白宫**：路透报道，特朗普政府计划将商务部 AI 标准与创新中心（CAISI）的三名高级官员转入白宫编制、直接向白宫汇报（重组仍在敲定中）；CAISI 此前负责与 OpenAI、Google、微软等开展自愿性模型评估。[来源：Reuters/US News/cryptobriefing]

- **Brad Smith："牛奶受到的监管都比 AI 多"**：微软副董事长兼总裁 Brad Smith 呼吁建立全球统一的 AI 安全规则，包括独立评估机构与面向开发者的"紧急刹车"机制——并称当前 AI 的安全要求比一盒牛奶还少。[来源：Reuters/Fox Business]

- **比尔·盖茨警告（10月11-12日）**：在 CNN 采访中称 AI 是"人类发明过的最危险的技术"，最紧迫威胁是"未来一年内 AI 驱动的网络攻击"；强调不能让企业"自我监管"，并提到社会需讨论如何对 AI 与机器人的使用征税。[来源：CNN/Yahoo Finance]

- **中国：《关于发展新质生产力的意见》持续发酵**：中共中央、国务院 10 月 9 日印发该文件，明确"全面实施'人工智能+'行动"、加快推进 AI 手机/电脑等新一代智能终端应用，并建立技术监测、风险预警与应急响应体系、确保 AI"安全、可靠、可控"；本周进入配套落实期（如工信部"AI 应用服务商培育专项行动"）。[来源：国家发改委/财新/VOA]

- **布鲁金斯学会：AI 智能体（Agent）的全球治理**：发文探讨 AI 智能体跨境运行带来的治理缺口（责任归属、跨国部署合规）。[来源：Brookings]

### 💰 产业与商业

- **亚马逊洽购 Decart（约 70 亿美元）**：WSJ 首发（10月11日晚）——Decart 开发让 AI 模型跨不同芯片高效运行的软件，并研发"世界模型"（模拟 3D 环境）；公司 2023 年成立，今年 5 月估值近 40 亿美元（若按 70 亿成交，较该估值高出约 75%）。此前 Anthropic 8 月曾洽谈约 60 亿美元收购、9 月尽调后放弃；亚马逊为其战略客户并给予 Trainium 芯片早期访问。交易若落地将强化 AWS 自研芯片生态、进一步对冲英伟达依赖。[来源：WSJ/Bloomberg/Calcalist/Quartz]

- **微软 Maia 300 详细规格与部署计划**：288GB HBM4、18TB/s 带宽；每兆瓦 token 数 +40% vs 领先 GPU 系统、机架吞吐 7× vs Maia 200；2027 年"多吉瓦"部署、逾 100 万颗；年内资本开支预期超 1,750 亿美元。市场解读：微软推理算力从"英伟达为主"转向"自研为主"的转折点。[来源：The Verge/Notebookcheck/The Tech Portal/Reuters]

- **英伟达联合 AMD、Google、Meta 发布"开放数据中心规范 v0.7"**：在 OCP 全球峰会上联合发布统一 AI 工厂设施蓝图（覆盖电力架构、冷却、物理布局）；Google、Meta、微软、英伟达另发布"OCP 电网韧性规范"（应对公用事业扰动、快速恢复）；英伟达同时通过 MGX 1.2 开放 Vera Rubin NVL72 机架设计（支持 250kW 级机架），并宣布 ConnectX-10 / BlueField 支持 Google Falcon 传输协议（开放互联再进一步）。[来源：NVIDIA博客/StorageReview/Yahoo Finance]

- **Salesforce 收购以色列 AI 分析公司 Loops（约 3,000 万美元）**：并入 Tableau，主打"agentic analytics"（解释业务指标变动并给出行动建议）；预计 11 月初交割；消息后 CRM 涨约 3%。[来源：CTech/Globes/Proactive Investors]

- **中美 AI 商业化分化（分析）**：Menlo Ventures 数据显示，2025 年 OpenAI + Anthropic 合计占企业 LLM API 支出 67%；其 5 月报告显示两家在追踪的 34 家头部 AI 初创中占 89% 收入；Ramp 数据称首次采购 AI 的企业中 Anthropic 占逾 73% 支出。对照中国侧"调用量份额领先、收入份额有限"的结构——模型能力差距正快速转化为商业收入差距。[来源：新浪科技（投资者内参）]

### 🚀 应用与产品

- **Apple "Welcome Home" 发布会（今日 10月13日，9:00 ET 纽约）**：预计推出智能家居中枢（HomePad 类新品）、新一代 Apple TV 4K、HomePod mini 等；以"新闻稿 + 媒体体验"形式发布，AI 家庭中枢为核心看点。[来源：The Verge/9to5Mac/MacRumors]

- **阶跃星辰 STEPX Neo 智能体手机（今日上海发布）**：阶跃终端"Ready Builder One"发布会推出首款"大模型原生智能体手机"；同日，千问新一代 AI 眼镜现货发售；阶跃星辰将于 10月15日 正式开源 Step 5 Preview（该模型已上线腾讯 WorkBuddy）。[来源：智东西/华尔街见闻/东方财富/IT之家]

- **富士胶片 Synapse Pathology v3.0**（10月12日）：数字病理平台扩展 AI 能力。[来源：BioSpace]

### 🔬 研究前沿

- **DeepMind "AlphaProof Nexus" 解出 9 个 Erdős 开放问题（10月12日集中报道）**：从 353 个未解 Erdős 问题中解出 9 个（其中 2 个自 1970 年起悬置 56 年），另证明 44 个 OEIS 数列猜想；解法先行在线公开、成果通过同行评审——AI 数学推理从"竞赛题"走向真实开放问题的标志性一步。[来源：the-decoder/Reddit/The Daily Star]

- **TikTok CEO 周受资（Shou Zi Chew）：AI 将在 3 年内带来"重大科学突破"**（CNBC，10月12日）——认为 AI 对科学的推动（药物研发、材料等）将在三年内集中兑现。[来源：CNBC]

---

## ⚡ 明日关注

- **10月14日：Anthropic 上市前投资者日（Investor Day）**——已向机构投资者发出邀请（Bloomberg）；正式 IPO 营销或于 11月9日当周启动、目标感恩节前挂牌。市场关注其 ARR 指引与算力承诺兑现节奏（22V Research 视其为"市场内部结构与 AI 前景的重要节点"）。
- **10月15日：台积电 Q3 财报**（14:00 台北时间）——营收预计 NT$1.49 万亿（约 $467 亿、同比 +51%，创纪录）、净利润预计同比 +65%；AI 需求风向标；同周还有 ASML 财报。
- **10月15日：阶跃星辰正式开源 Step 5 Preview**（600B 稀疏 MoE，面向 Agentic 任务）。
- **10月13-16日：TechCrunch Disrupt 2026（旧金山）与 OCP 全球峰会持续**——更多 AI 基础设施/芯片发布与创业公司动向。
- **持续跟踪**：① 英伟达-Reflection AI 谈判进展；② Anthropic IPO 流程（投资者日 → 路演）；③ 英国 AI 立法动向（关键基础设施保护）。

---

## ⚡ 其他新闻

- 社区阅读服务的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/8A4
- 城市应急广播的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/367=qyc
- 在线教育体验的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/kub=710
- 家庭节能设备中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC%E5%8F%B7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/SHY=UQC
- 绿色生活实践从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/541
- 城乡交流活动的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/gft
- 环境教育课程的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/Ba5
- 网络安全教育的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/627=hkd
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/blh=370
- 老年人出行服务的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%82%A1%E7%A5%A8?/Fhk=CFj
- 便民服务地图的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/137
- 节假日出行安排中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/trf
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/ihV
- 社区慢性病防控的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/101=rxm
- 社区公共卫生的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/oku=611
- 社区消防演练的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/QXR=wrZ
- 公共服务评价的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/905
- 医院导诊服务的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/dhh
- 灵活就业交流的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/M9r
- 社区志愿服务的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/077=uni
- 社区消防演练的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/dgm=704
- 劳动教育实践的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/FFJ=yL6
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/320
- 物业服务沟通的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/xmd
- 户外活动组织的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/ZtD
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/923=eyy
- 安全出行教育的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/iwo=786
- 医院导诊服务的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/9Gl=Tyk
- 节能家电使用的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/227
- 数字公共文化的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/hze
- 公共服务数字化的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/Syk
- 数字阅读服务的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/256=oro
- 个人时间管理的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/sre=954
- 乡村教育资源的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/GYB=tfn
- 城市绿色交通的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/598
- 志愿者培训交流的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/sjh
- 社区交通安全的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/1Xk
- 本地旅行体验的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/330=vyy
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/tvb=591
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/PRE=suc
- 食品配送体验的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/538
- 老年数字阅读的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/til
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/MSI
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/257=vrm
- 租房信息服务的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/wau=769
- 乡村文化活动的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/Wqn=1tH
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/982
- 安全出行教育的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/fzg
- 城市公共艺术的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/blC
- 公共空间导览的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/504=blp
- 家庭科学教育的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/gde=627
- 乡村教育资源的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%95%B0%E7%A0%81?/xwu=T8F
- 城市公共厕所从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/590
- 新能源出行的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/zsi
- 街道综合服务的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/joh
- 公共服务评价的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/205=ivc
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/gsx=421
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/Im6=X4i
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_360?/769
- 街道综合服务的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_360?/bho
- 青少年科技社团的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_360?/c8n
- 儿童户外活动的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_360?/857=wpr
- 科技馆参观体验的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_360?/mfc=579
- 城市微更新实践的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_360?/P9z=mlF
- 生活技能分享的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/904
- 小区停车协商的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/upz
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/rPn
- 社区协商议事的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/931=wyp
- 全民健身活动的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/lea=037
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/Cfy=jPk
- 社区商业活力的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/250
- 环境监测科普的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/lpf
- 全民健身活动的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/dVb
- 环境教育课程的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/955=srn
- 街区小店体验的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/bbw=661
- 低碳社区实践的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A4%BE%E5%8C%BA?/UVz=GBr
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/492
- 公交站点体验中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/gwx
- 网络信息辨识的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/MDD
- 社区应急准备的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/442=wzm
- 公共空间导览的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/uyh=342
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/6OG=jZP
- 乡村电商实践中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/629
- 老年学习活动的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/qad
- 儿童运动体验的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/Krw
- 软件开发学习的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/005=ped
- 社区科普课堂的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/ioo=105
- 社区安全巡查的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E7%BB%8F%E6%B5%8E?/H8t=gTD
- 乡村生活观察的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/484
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kjy
- 地方文化传播的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kUt
- 城市雨天出行的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/334=suw
- 本地历史资料的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/npk=346
- 个人数据管理的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/9av=ZPU
- 城市噪声观察的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/635
- 社区故事采集的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/vkq
- 乡村文化空间的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/l3N
- 基层健康服务的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/806=naz
- 城乡公共服务的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/rlt=938
- 口袋公园建设的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/Ggj=HM6
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/701
- 急救知识普及的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/aiq
- 人工智能科普的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/47M
- 城乡公共服务中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/243=ofk
- 老旧小区改造的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/koe=991
- 课后服务体验的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/KcL=xvq
- 小微企业服务的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/314
- 街区道路维护的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/kkm
- 数字设备回收的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/2pW
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/082=jnd
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/chf=375
- 城市休闲步道的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/BXH=OsY
- 基层健康档案的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/263
- 数字创意课程的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/zvk
- 公共健身器材的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/c3f
- 公共空间导览的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/158=mmy
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/jmq=856
- 城市地名文化的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/9Nz=CuQ
- 社区科普课堂中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/560
- 地方美食文化的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/mfv
- 公共空间休憩的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/2TF
- 智慧城市体验的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/871=thk
- 无障碍出行的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/yjc=579
- 青年职业探索的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%BA%AA%E5%AE%9E?/zkO=N2X
- 开放数据应用的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/057
- 社区环保活动的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/gmm
- 健康步道使用的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/VxS
- 社区便民集市的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/818=oqq
- 读书会组织的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/ckq=155
- 社区健康讲座的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/Mma=6y6
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/113
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/suv
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/luB
- 机器学习入门的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/821=uli
- 社区防暑服务的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/wsh=760
- 绿色快递包装的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/XUE=8jp
- 公交无障碍服务的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/821
- 青年职业探索的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/nqx
- 绿色快递包装的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/x0e
- 数字支付体验的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/773=zbl
- 社区快递服务的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/fjv=692
- 个人数据管理的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%98%9F%E5%BA%A7?/bu3=k91
- 消防知识宣传的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/355
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/ciq
- 农贸市场环境的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/ESf
- 个人数据管理的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/642=qok
- 城市生活服务的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/pis=887
- 公园休闲体验的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/aJD=jDJ
- 社区公共餐饮的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%AD%85%E5%BD%B1%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/581
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%AD%85%E5%BD%B1%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/dtx
- 城市博物馆服务的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%AD%85%E5%BD%B1%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/5bX
- 租房信息服务的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%AD%85%E5%BD%B1%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/565=zkq
- 社区安全巡查的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%AD%85%E5%BD%B1%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/oqq=148
- 家庭照护支持的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E9%AD%85%E5%BD%B1%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/piN=3XQ
- 健康饮食教育的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/774
- 公共服务数字化的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/lzn
- 社区协商议事的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/QeF
- 街道综合服务的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/267=hrx
- 市民热线服务的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/tdu=555
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/cFf=VuQ
- 城乡公共服务的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/513
- 城市水环境观察的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/azk
- 社区活动报名的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/Wi0
- 传统手工艺体验的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/428=oyc
- 公共健身器材的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/kbg=807
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/vI2=8DU
- 在线教育体验的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/678
- 网络信息辨识的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/yde
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/YQt
- 环境监测科普的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/245=ptj
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/wjd=701
- 数字艺术创作的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%9C%B0%E6%96%B9?/Gq1=Ml1
- 公交站点体验的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/352
- 校园安全教育的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/pph
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/ejo
- 城市共享单车的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/102=rkh
- 光伏知识科普的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/ncp=788
- 机器学习入门的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/wV6=Rvu
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/858
- 社区花园共建的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/ehh
- 社区公共卫生的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/OCt
- 城市树木认养的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/845=isl
- 在线学习体验的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/pvq=780
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/11M=Ouc
- 城市公共自行车的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/255
- 乡村文化活动的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/fha
- 公共服务指南的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/28f
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/075=eci
- 社区手工活动的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/nzt=726
- 公共设施维护的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E7%8E%AF%E7%90%83%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E6%91%84%E5%BD%B1?/maM=Wqe
- 运动安全知识的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/682
- 城市体育设施的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/idv
- 基层服务创新的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/5Ij
- 公共空间导览的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/999=ebs
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/mmt=568
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/F03=aml
- 科学信息获取的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/449
- 社区消防演练的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/zji
- 社区艺术活动的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/bWp
- 城市公共座椅的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/619=xfg
- 学校食育活动的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/zrq=583
- 绿色出行服务的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/S6f=ysS
- 市民意见收集的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/727
- 城市公共厕所的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/xxi
- 公共空间休憩的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/vco
- 个人信息保护的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/398=iup
- 家庭用电安全的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/umk=019
- 健康步道使用的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%98%9F%E5%BA%A7?/GMg=fQA
- 校园节能行动中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/721
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/egg
- 社区运动空间的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/BmS
- 非遗课堂体验的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/442=eqz
- 口袋公园建设的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/dnp=689
- 小区停车协商的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/GQZ=aI5
- 城市步行环境中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/204
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/olp
- 青年志愿活动的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/3px
- 城市公共饮水的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/264=hjp
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/olb=636
- 城乡公共服务的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%91%84%E5%BD%B1?/5PX=45X
- 数字公共文化的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/708
- 数字生活课堂的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/jzw
- 城市公共厕所的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/EPc
- 居家防滑改造的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/495=xvn
- 绿色快递包装的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/wss=971
- 社区科普课堂的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/8Vv=ccx
- 公共服务指南的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A5%87%E8%B6%A3%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/556
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A5%87%E8%B6%A3%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/aod
- 数字艺术创作的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A5%87%E8%B6%A3%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/d61
- 全民阅读推广的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A5%87%E8%B6%A3%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/328=yvj
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A5%87%E8%B6%A3%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/hyc=163
- 文明养宠科普的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A5%87%E8%B6%A3%E5%88%86%E5%88%86%E5%BD%A9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/u5t=APy
- 公共空间休憩中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/540
- 城市噪声观察的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/toh
- 城市公共空间的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/9Dl
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/882=owo
- 公共设施使用的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/vwv=619
- 非遗体验活动的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/rcr=R0f
- 市民意见收集的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/929
- 公共设施维护的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/wfi
- 老年学习活动的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/iFu
- 城市绿道建设的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/255=qoi
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/dbz=510
- 绿色校园实践的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%AF%8D%E5%A9%B4?/txS=Arq
- 科技馆参观体验的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/055
- 社区便利生活的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/pse
- 数字档案服务的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/bf6
- 基层医疗预约的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/166=czl
- 开放式学习空间的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/cuj=504
- 青少年心理健康的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/iY6=v8P

---

## 📈 关键数据（10月11-13日）

| 指标 | 数值 | 变化/说明 |
|------|------|------|
| 全球大模型周调用量（10/5-11） | 172 万亿 Token | 环比 +3.61%（OpenRouter 测算） |
| 中国大模型周调用量 | 86.74 万亿 Token | 环比 +50.96%；连续 24 周全球第一 |
| 美国大模型周调用量 | 18.97 万亿 Token | 环比 +17.1% |
| Meta Muse Wonder 定价 | $4 / $20（每百万 Token 入/出） | 与 Claude Opus 5.5 同价位 |
| Meta / 微软股价（10/12） | Meta 约 $748（+3.4%–4.1%）；MSFT +2.4% | 模型与自研芯片发布驱动 |
| 微软 Maia 300 | 288GB HBM4；18TB/s；+40% tokens/MW | 2027 年部署超 100 万颗；资本开支预期 >$1750 亿（今年） |
| 亚马逊洽购 Decart | 约 $70 亿 | 较 5 月估值（近 $40 亿）高约 75% |
| AlphaProof Nexus 成果 | 9 个 Erdős 问题 + 44 个数列猜想 | 其中 2 题悬置 56 年；已通过同行评审 |
| 英国网络防御试点 | 累计发现 1,000+ 潜在漏洞 | 单轮试点：407 处弱点/£13,000 token 成本 |

---

*本简报由 Hermes Agent 自动生成*  
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  @PHWT7等*  
*仅供参考，不构成投资建议*
