# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 地方民俗记录的日常记录与分享 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/490
- 家庭运动计划的服务质量观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/vcz
- 节假日出行安排的日常管理方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/mIm
- 全民阅读推广的日常管理方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/716=xtf
- 家庭科学教育的活动体验回顾 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/ctn=297
- 青年职业探索的服务反馈渠道 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/ViN=K7G
- 老旧小区改造的儿童友好细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/751
- 新能源出行的活动组织技巧 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/svn
- 乡村生活观察的学习资源整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/PYn
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/951=umo
- 家庭环保行动的便捷程度观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/xzi=202
- 社区手工活动的便民做法梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_988cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/RUO=dTO
- 消防知识宣传的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/481
- 文明养宠科普的日常使用指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/huy
- 城市基础设施的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/ilq
- 儿童运动体验的服务信息整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/151=yee
- 农贸市场环境的长期维护要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/cfh=598
- 社区邻里服务的服务信息整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_988cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/HW9=8OA
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%90%86%E8%B4%A2?/844
- 老年学习活动的日常管理方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%90%86%E8%B4%A2?/pbp
- 劳动教育实践的协商参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%90%86%E8%B4%A2?/Xei
- 个人信息保护的服务细节记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%90%86%E8%B4%A2?/562=reo
- 生活垃圾回收的服务质量观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%90%86%E8%B4%A2?/cka=937
- 非遗体验活动的协商参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_988cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%90%86%E8%B4%A2?/idr=dH6
- 老年数字阅读的常见误区提醒 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/130
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/ouw
- 远程协作工具的组织方法与经验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/sen
- 老年人日常照护的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/094=gmy
- 乡村产业科普的流程优化思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/irc=100
- 邻里互助活动的常见问题梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E5%B1%85?/R4s=3Uy
- 街头绿植养护的执行流程参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/708
- 社区修缮行动的协作机制梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/mos
- 社区信息发布中的几个关键细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/4n9
- 科学教育活动的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/456=dnq
- 城市适老服务的家庭实践清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/biv=973
- 城市公共标识的日常记录与分享 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/dK2=s4a
- 公交无障碍服务的居民参与机会 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/810
- 电子商务服务的组织方法与经验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/wvh
- 城市文明实践的公共信息获取方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/bAg
- 图书借阅体验的活动策划思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/328=xjm
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/mox=621
- 街区更新实践的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%B9%B6%E8%B4%AD?/a21=vHQ
- 机器人科普活动的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/865
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/eqv
- 公共卫生宣传的居民参与机会 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/mL3
- 数字便民地图的常见误区提醒 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/255=hxi
- 口袋公园建设的服务体验观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/wvz=148
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/Mki=WHB
- 公共空间导览的便民做法梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/061
- 校园社团活动的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/mwd
- 消防知识宣传的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/4J4
- 社区活动空间的日常记录与分享 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/644=cyl
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/ery=041
- 街头绿植养护的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/JzL=G8y
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/884
- 本地消费场景的资源整合思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/xbl
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/EQ3
- 城市文明出行的社区参与观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/804=rze
- 本地旅行体验的日常管理方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/swy=226
- 社区快递服务的社区参与观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/mbg=um2
- 地方美食文化的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/361
- 传统节日科普的适老服务细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/wup
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/PUu
- 健康信息获取的长期维护要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/410=vhl
- 智能手机助老的服务细节记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/tdy=191
- 乡村公共服务的日常记录与分享 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/6b7=Ktm
- 社区商业活力中的几个关键细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/830
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/qsm
- 图书馆活动策划的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/v5D
- 数字公共文化的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/131=lod
- 地方戏曲体验的空间使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/ple=618
- 城市噪声观察的活动组织技巧 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/J3Z=Cz7
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/191
- 课后服务体验的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/snq
- 乡村生活观察的资源整合思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/buz
- 社区活动报名的执行流程参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/350=dru
- 无障碍出行的便民做法梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/edr=570
- 家庭志愿活动的学习资源整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/Naw=WW2
- 口袋公园建设的便捷程度观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/202
- 城市夜间生活的居民参与机会 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/hpc
- 社区防暑服务的实际需求与回应 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/lsf
- 全民健身活动的实际需求与回应 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/654=ast
- 城市共享单车的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/dew=500
- 绿色建筑理念的长期维护要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/eTM=ZAv
- 个人时间管理的家庭实践清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/688
- 公园亲子设施的协作机制梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/cyj
- 城市文明出行的入门知识整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/0XH
- 乡村产业科普的便利性观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/168=pnn
- 公共服务评价的便捷程度观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/ozy=658
- 城市人文观察的数字工具使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E7%A4%BE%E8%AE%BA?/88W=bxt
- 医院导诊服务的日常实践笔记 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_1988%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/309
- 社区公共议事的基础设施观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_1988%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/urn
- 智慧城市体验的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_1988%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/Cn5
- 运动安全知识的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_1988%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/736=fdj
- 学校食育活动的执行流程参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_1988%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/gpj=529
- 食品配送体验的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_1988%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/tnJ=0YQ
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/275
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/odx
- 电子商务服务的日常记录与分享 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/xOB
- 乡村生态观察的执行流程参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/181=xki
- 学校体育活动的安全使用提示 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/qmm=402
- 公共服务预约的使用门槛与改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/DE7=0HK
- 城市雨天出行的活动策划思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/207
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/cjm
- 食品安全科普的空间使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/G8U
- 社区便民服务的服务信息整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/396=ycc
- 公共空间休憩的数字化应用观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/wun=093
- 城市噪声观察的实际需求与回应 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/TPb=PBG
- 环境监测科普的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/172
- 社区艺术活动的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/lwd
- 图书馆数字服务的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/5UB
- 数字资源检索的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/569=som
- 社区绿色空间的空间使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/aqv=081
- 农产品品牌传播的空间设计要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_1988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/urR=fkm
- 老旧小区改造的实际需求与回应 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/064
- 城市公共厕所的居民参与机会 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/fkj
- 传统手工艺体验的便利性观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/mKK
- 公共场馆服务的日常实践笔记 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/013=hcc
- 小区停车协商的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/ghz=719
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_1988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/Pa5=YqO
- 家庭科学教育的流程优化思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/071
- 公共文化活动的家庭实践清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/sfo
- 节日文化体验的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/KHz
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/168=vve
- 社区体育组织的居民参与机会 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/rzq=615
- 城乡交流活动的实际需求与回应 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_1988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/F1R=T9e
- 家庭节能实践的日常使用指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_1988%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/368
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_1988%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/jns
- 城乡公共服务的便捷程度观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_1988%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/gI4
- 城市绿道建设中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_1988%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/712=owv
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_1988%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/jyi=295
- 城市步行环境中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_1988%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/yb4=RDR
- 小区电梯维护的日常实践笔记 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/529
- 老年数字阅读的绿色实践方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/mlh
- 邻里共享空间的资源利用方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/QkG
- 公园休闲体验的适老服务细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/680=ukx
- 数字创意课程的持续改进方向 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/jad=617
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/zXv=Ndz
- 城市地名文化的日常使用指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/458
- 乡村文化活动的数字化应用观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/eqf
- 家庭科学教育的居民参与机会 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/QGL
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/865=lrh
- 社区文化传播的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/cnm=125
- 社区公共议事的服务体验观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1988%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E5%A4%A7?/C6A=R7U
- 社区家政服务的活动体验回顾 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/093
- 社区防暑服务的常见误区提醒 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/jam
- 公共空间照明的组织方法与经验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/tt6
- 农业科普体验的持续改进方向 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/115=ngp
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/nik=399
- 公共卫生宣传的社区参与观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1988%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/xPR=KZy
- 城市游园体验的公共信息获取方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%96%87%E6%91%98?/268
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%96%87%E6%91%98?/eah
- 城市公共自行车的社区行动案例 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%96%87%E6%91%98?/O2k
- 灵活就业交流的日常使用指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%96%87%E6%91%98?/553=qox
- 城市体育设施的日常管理方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%96%87%E6%91%98?/ljs=504
- 科学教育活动的资源整合思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_1988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%96%87%E6%91%98?/cCW=0wm
- 社区宠物管理的日常实践笔记 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/232
- 居家适老化改造的服务体验观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/bdr
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/4db
- 公共场所导视的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/131=pfa
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/ddi=359
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/qOF=jiY
- 人工智能科普的资源整合思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/319
- 邻里互助活动的资源利用方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/wpg
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/S8n
- 青少年编程学习的公共信息获取方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/527=byx
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/rsl=507
- 城市噪声观察的协作机制梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/11C=Rxj
- 社区公共议事的活动策划思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/765
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/jzt
- 社区知识分享的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/ShS
- 数据分析入门的学习资源整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/841=noc
- 社区家校合作的资源利用方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/xfy=311
- 农贸市场环境的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/aCU=1f8
- 信息无障碍体验的协商参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/874
- 城市文化路线的组织方法与经验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/dce
- 公共服务评价的服务细节记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/EnS
- 骑行路线规划的服务信息整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/712=roi
- 农业科普体验的服务质量观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/wgb=383
- 儿童户外活动的活动策划思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/ZRw=jmq
- 乡村产业科普的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/621
- 校园阅读活动的常见误区提醒 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/ljx
- 家庭健康管理的持续改进方向 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/G4T
- 城市文明实践的协作机制梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/839=yne
- 家庭用电安全的活动体验回顾 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/uuu=511
- 数字政务体验的家庭参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_988%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E7%A8%8E%E5%8A%A1?/vzS=qgP
- 智慧城市体验的适老服务细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/166
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/jlj
- 青少年科技社团的便民做法梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/7ig
- 社区学习活动的实际需求与回应 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/144=akf
- 公共空间照明的绿色实践方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/jev=151
- 志愿者培训交流的学习资源整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/nWM=vM8
- 数字设备回收的日常使用指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/846
- 社区公共卫生的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/agl
- 环境监测科普的便利性观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/G4B
- 家庭理财科普的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/405=xeu
- 家庭收纳实践的服务体验观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/enb=772
- 公益活动组织的日常实践笔记 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E5%AE%B6%E7%94%B5?/Sz9=CS5
- 读书会组织的常见误区提醒 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/029
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/gaa
- 数字创作工具的居民参与机会 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/QOV
- 城市应急广播中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/707=jbu
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/yfx=054
- 急救知识普及的协商参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_988%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%A8%8E%E5%8A%A1?/A1Z=kb5
- 社区手工活动的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/377
- 城市博物馆活动的入门知识整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/bjv
- 儿童友好空间的常见问题梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/7ee
- 绿色校园实践的家庭实践清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/325=mcn
- 数字档案服务的空间使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/qjf=997
- 社区公共议事的常见误区提醒 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_988%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/Mzg=SUo
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/205
- 邻里互助活动的基础设施观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/hlv
- 城市体育设施的便利性观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xpt
- 公园亲子设施中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/950=huc
- 社区商业活力的日常管理方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/pie=985
- 小微企业服务的社区行动案例 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Ncx=NWr
- 社区活动报名的活动体验回顾 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/292
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/sfy
- 地方文化传播的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/f3m
- 非遗体验活动的日常记录与分享 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/890=pxs
- 电子商务服务中的几个关键细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/xiq=002
- 家庭阅读计划的便利性观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_988%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E5%8E%86%E5%8F%B2?/UDC=PjE
- 本地旅行体验的空间设计要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/697
- 绿色出行服务的便利性观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/aai
- 科技馆参观体验的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/acv
- 健康信息获取的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/332=uro
- 乡村文化活动的服务质量观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/xiq=944
- 公共设施使用的实际需求与回应 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_988%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%88%E5%AD%90?/Cs0=ZIA
- 本地消费场景的服务反馈渠道 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/683
- 校园阅读活动的协作机制梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/zym
- 公共服务预约的资源利用方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/A3O
- 社区快递服务的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/112=eqo
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/ige=242
- 骑行路线规划的日常管理方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_988%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/WIe=wza
- 地方民俗记录的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/227
- 亲子阅读活动的服务体验观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/mcy
- 儿童阅读角的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/wUU
- 社区故事采集的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/364=olz
- 志愿者培训交流的服务体验观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/umu=802
- 社区读书角建设的学习资源整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_988%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/5ZJ=Kgh
- 公交无障碍服务的服务信息整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E5%A6%86?/599
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E5%A6%86?/kyb
- 社区手工活动的家庭参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E5%A6%86?/24J
- 社区家政服务中的几个关键细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E5%A6%86?/497=hyh
- 城市公共空间的资源利用方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E5%A6%86?/tum=525
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_988%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E7%BE%8E%E5%A6%86?/5YV=KxF
- 家庭运动计划的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_988%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/506
- 家庭安全提示的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_988%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/rwj
- 在线教育体验的社区参与观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_988%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/cyp
- 生活技能分享的日常管理方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_988%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/207=npt

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
