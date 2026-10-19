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

- 社区绿色空间的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/508
- 城市空气科普的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/lqk
- 公共场馆服务的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/9e2
- 通勤路线规划的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/047=cli
- 老年运动活动的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/dez=713
- 城市骑行环境的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/JwB=1yf
- 社区活动策划的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/053
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/rqz
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/tQP
- 老年运动活动的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/207=fxv
- 公共文化活动的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/vds=143
- 社区教育资源的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/bVt=kaG
- 本地消费场景的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/500
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/rxa
- 儿童阅读角的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/wyk
- 网络信息辨识有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/304=ebi
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/vxs=529
- 家庭志愿活动的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/pN9=s6M
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/327
- 数字档案服务的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/ptm
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/7GQ
- 数字创作工具的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/854=lvs
- 智能家居应用的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/own=252
- 社区法律科普的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E8%B5%A2%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/zhe=IFM
- 职业技能学习的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/602
- 志愿服务平台的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/fhv
- 生活技能分享的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/Ajt
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/661=xud
- 社区垃圾回收的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/czs=339
- 志愿者培训交流的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%AD%85%E5%BD%B1%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E9%92%BB_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/s72=51G
- 图书借阅体验的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/611
- 社区教育资源的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/twe
- 灵活就业交流的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/ejm
- 图书馆数字服务的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/259=zej
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/uiz=321
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%9A%E7%94%A8%E7%89%88_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/uZM=6zg
- 社区健康讲座的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/616
- 健康信息获取的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/kpj
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/Sbx
- 开源技术交流的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/101=zud
- 城市公共饮水的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/qml=666
- 居家防滑改造的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/NDE=wfr
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E7%BB%8F%E6%B5%8E?/891
- 日常摄影记录的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E7%BB%8F%E6%B5%8E?/hbl
- 线上阅读资源的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E7%BB%8F%E6%B5%8E?/l9u
- 社区故事采集的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E7%BB%8F%E6%B5%8E?/821=tku
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E7%BB%8F%E6%B5%8E?/yff=719
- 公共空间导览的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_360%E7%BB%8F%E6%B5%8E?/d5r=zIn
- 学校食育活动的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/058
- 绿色办公实践的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/qyy
- 社区信息发布的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/LN8
- 公园休闲体验的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/647=byu
- 基层服务创新的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/tsz=649
- 乡村文化活动的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/XUu=5M1
- 科普展览体验的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/881
- 生活垃圾回收的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/ajp
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/6di
- 数字生活课堂的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/317=wfk
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/eme=222
- 青少年户外教育的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/VCa=ict
- 城乡公共服务的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/176
- 青少年科技社团的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/trq
- 线上办事服务的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/z7r
- 社区生活指南的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/580=ode
- 乡村教育资源的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/enn=424
- 老年人日常照护的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/jRn=Dc9
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/862
- 本地历史资料的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/ewv
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/Fmf
- 科学健身方法的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/024=guu
- 城乡公共服务的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/gyz=874
- 便民服务窗口的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/nDi=ovX
- 租房信息服务的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/947
- 机器人科普活动从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/gik
- 地方文化传播的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/TA7
- 环境监测科普的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/000=xjs
- 家庭照护支持的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/mgl=513
- 城市绿色交通的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/oS6=If9
- 社区艺术活动的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/947
- 学校食育活动的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/yzw
- 城市农夫市集的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/7a7
- 音乐欣赏活动的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/839=rii
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/dyw=946
- 老年友好服务的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E4%B8%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/HIW=rv4
- 家庭理财科普的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/187
- 家庭养老规划的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/bef
- 校园社团活动的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/6sj
- 青少年心理健康的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/157=oko
- 社区停车服务的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/icc=432
- 骑行路线规划的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/NEl=6C4
- 社区故事采集的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/415
- 食品配送体验中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/jij
- 乡村公共服务的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/fN4
- 城市公共标识的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/664=gbe
- 家庭消费规划的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/cmg=672
- 城市骑行环境的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/Sp9=6uR
- 乡村文化空间的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E9%92%9F%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/554
- 旧物循环利用的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E9%92%9F%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/uya
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E9%92%9F%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/eLj
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E9%92%9F%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/283=etz
- 街区更新实践的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E9%92%9F%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/ura=110
- 社区便利生活的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E9%92%9F%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/qAr=bRQ
- 社区知识分享的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/467
- 城市体育设施的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/lia
- 网络安全教育的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/AIs
- 城市水环境观察的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/884=uox
- 智慧停车服务的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/dyf=738
- 青少年编程学习的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E8%A7%82%E5%AF%9F?/45K=Txs
- 环境监测科普的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/531
- 智能手机助老的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/onj
- 社区互助网络的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/y4z
- 居民健康教育的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/477=goi
- 城市应急科普的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/tfd=826
- 远程协作工具的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%8E%A2%E6%BA%90?/lpU=pmA
- 气象科普传播的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/325
- 城市博物馆服务的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/fnz
- 志愿者培训交流的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/I9p
- 校园阅读活动的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/617=rmh
- 城市公共自行车的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/wir=821
- 数字政务体验的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/k18=qi3
- 城市骑行环境的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/696
- 社区学习活动的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/rqq
- 智能家居应用的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/VQI
- 社区知识分享的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/954=yim
- 城乡公共服务的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/uqb=690
- 乡村生态观察的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/FkD=oeI
- 社区知识分享的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/662
- 公共空间安全的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/rmr
- 社区运动空间的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/vuU
- 社区活动策划的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/975=trm
- 跨代沟通活动的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/lqa=393
- 通勤路线规划的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/v7V=IVg
- 城市社区治理的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/161
- 城乡交流活动的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/iiq
- 乡村产业科普的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/g6L
- 公共场所导视的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/744=som
- 软件开发学习的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/kpx=302
- 小区停车协商的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/TgB=6Fy
- 社区知识分享的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E5%86%85?/863
- 数字素养提升的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E5%86%85?/zjv
- 社区便民服务的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E5%86%85?/OPZ
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E5%86%85?/945=zrf
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E5%86%85?/pwc=501
- 新能源出行的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E5%86%85?/ZL3=MVo
- 城市共享单车的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/372
- 科学教育活动的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/iiu
- 创业经验分享的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/eVY
- 信息无障碍体验的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/045=dmk
- 课后服务体验的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/ygd=409
- 校园安全教育的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E7%8E%A9%E6%B3%95%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E7%BE%8E%E8%82%A1?/yRY=QFK
- 公共交通接驳的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/915
- 乡村公共阅读的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/fnd
- 居民健康教育的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/gmR
- 社区休闲设施的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/972=tbm
- 城市雨天出行的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/zij=614
- 周末休闲规划的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/3Te=mzm
- 科技馆参观体验的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/413
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/gsn
- 农贸市场环境的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/yHA
- 公共文化活动的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/214=gmw
- 社区学习活动的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/vod=693
- 小微企业服务的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/BCa=huw
- 社区宠物管理的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/234
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/jmh
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/Cet
- 社区活动空间的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/090=rtx
- 社区休闲设施的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/jiv=668
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A1%A3%E6%A1%88?/zLX=R0j
- 农业科普体验的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/531
- 乡村生态观察的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/dnz
- 基层健康服务的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/1tu
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/188=owe
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/yue=789
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/V7j=nBc
- 小微企业服务的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%9E%AD%E6%9C%9B?/156
- 校园节能行动的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%9E%AD%E6%9C%9B?/khn
- 儿童阅读角的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%9E%AD%E6%9C%9B?/j2U
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%9E%AD%E6%9C%9B?/721=oko
- 乡村产业科普的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%9E%AD%E6%9C%9B?/qab=049
- 个人时间管理的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%9E%AD%E6%9C%9B?/9FP=lgj
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/834
- 健康信息获取的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/onj
- 家庭环保行动的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/sry
- 社区花园共建的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/097=lgq
- 新能源出行的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/dzq=031
- 儿童友好街区的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/lmQ=vm2
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/367
- 软件开发学习的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/rfe
- 数字学习资源的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/DZG
- 基层健康档案的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/077=rlf
- 儿童户外活动的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/uvd=100
- 家庭食品保存的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%97%85%E6%B8%B8?/aWD=wwD
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/521
- 社区托育服务的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/etf
- 公共卫生宣传的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/nQc
- 文化场馆预约的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/790=pki
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/leg=485
- 社区家政服务的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/mKm=fpj
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E6%9C%AC%E8%90%A5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/663
- 老年人出行服务的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E6%9C%AC%E8%90%A5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/pix
- 老年人日常照护的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E6%9C%AC%E8%90%A5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/BZG
- 急救知识普及的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E6%9C%AC%E8%90%A5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/589=mos
- 校园节能行动的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E6%9C%AC%E8%90%A5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/fgh=159
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E6%9C%AC%E8%90%A5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/715=WFF
- 本地旅行体验的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/660
- 老年友好服务中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/fck
- 终身学习资源的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/Ylp
- 数字学习资源的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/184=iwu
- 社区志愿服务的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/xff=273
- 市民热线服务的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/s1X=5C2
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/437
- 家庭节能实践的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/oxv
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/Wt8
- 邻里共享空间的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/787=xac
- 青少年心理健康的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/fcd=191
- 公共场所导视的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/WYC=jOr
- 社区活动空间的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/667
- 社区活动策划的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/bdb
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/eqY
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/312=tim
- 公共服务沟通的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/qdc=674
- 社区儿童活动的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BF%AB3%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/pCq=jOw
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8A%A9%E6%89%8Bapp%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/680
- 城市农夫市集的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8A%A9%E6%89%8Bapp%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/qvf
- 创业经验分享的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8A%A9%E6%89%8Bapp%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/4li
- 青少年科技社团的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8A%A9%E6%89%8Bapp%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/549=crx
- 电动汽车充电的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8A%A9%E6%89%8Bapp%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/pei=352
- 社区垃圾分类的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8A%A9%E6%89%8Bapp%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/Obb=Rv2
- 城市休闲步道的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/593
- 儿童安全出行的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/yri
- 文化遗产保护科普的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/7k2
- 公共场馆服务的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/701=suh
- 城市便民驿站的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/elb=341
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/GeW=prb
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/093
- 全民健身活动的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/hkx
- 校园阅读活动的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/pll
- 就业技能培训的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/361=qzx
- 城市建设科普的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/ytm=933
- 青年志愿活动的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/Okh=IiE
- 老年人出行服务的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%8B%B9%E6%9E%9Cios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%9F%B3%E4%B9%90?/363
- 社区慢性病防控的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%8B%B9%E6%9E%9Cios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%9F%B3%E4%B9%90?/arl
- 社区应急准备的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%8B%B9%E6%9E%9Cios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%9F%B3%E4%B9%90?/2JI
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%8B%B9%E6%9E%9Cios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%9F%B3%E4%B9%90?/202=lvf
- 垃圾分类指导的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%8B%B9%E6%9E%9Cios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%9F%B3%E4%B9%90?/ikx=818
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%8B%B9%E6%9E%9Cios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%9F%B3%E4%B9%90?/VNK=VuS
- 数字生活课堂的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3ios%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/400
- 城市住房服务的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3ios%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/yiu
- 家庭节能实践中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3ios%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/CMQ
- 节能生活方式的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3ios%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/876=wam

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
