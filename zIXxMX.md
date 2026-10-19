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

- 居民健康教育的常见问题梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/OvG
- 城市水环境观察中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/399=ezt
- 校园节能行动的使用门槛与改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pqt=097
- 青年职业探索中的几个关键细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/dxp=9uI
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/120
- 公共空间导览的执行流程参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/qeh
- 社区商业活力的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/Xty
- 社区读书角建设的基础设施观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/473=gie
- 小区停车协商的活动组织技巧 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/qub=748
- 便民服务地图的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/5vF=MSk
- 公共文化活动的日常记录与分享 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/074
- 儿童友好街区的空间使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/bef
- 机器人科普活动的服务细节记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/wQN
- 电子商务服务的服务反馈渠道 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/661=spy
- 老年人日常照护的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/rkm=158
- 社区活动策划的服务信息整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/KPU=YSV
- 城乡交流活动的组织方法与经验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E5%A4%A7?/114
- 家庭安全提示的常见问题梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E5%A4%A7?/szh
- 城市骑行环境的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E5%A4%A7?/a3H
- 生成式工具使用的绿色实践方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E5%A4%A7?/947=qfc
- 亲子科普活动的服务质量观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E5%A4%A7?/bhc=582
- 社区停车服务的日常实践笔记 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E5%A4%A7?/mOO=q9e
- 社区知识分享的安全使用提示 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/821
- 电动汽车充电的常见误区提醒 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/vxa
- 城市公共厕所的组织方法与经验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/G1a
- 老年人文化生活的常见问题梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/084=ovv
- 城市文明出行的日常实践笔记 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/jhi=276
- 城市人文观察的执行流程参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%B3%A8%E5%86%8C_%E5%BF%85%E5%BA%94%E9%94%90%E8%AF%84?/f1C=pOA
- 公共服务预约的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/435
- 老年智能设备的安全使用提示 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/lcd
- 城市绿道建设的数字化应用观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/DI5
- 公共服务沟通的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/397=uwt
- 数字生活课堂的便利性观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/fwd=025
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/vH5=lSj
- 城市公共艺术的便民做法梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/211
- 运动安全知识的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/dcj
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/B7K
- 城市绿色交通的长期维护要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/456=lyc
- 城乡交流活动的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/fgx=503
- 低碳社区实践的协商参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/nBq=tNn
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/222
- 城市噪声观察的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/hmv
- 城乡交流活动的服务质量观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/3tR
- 网络安全教育的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/926=ibj
- 城乡交流活动的家庭参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/iqp=611
- 社区环保活动的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/x0C=UrA
- 科普展览体验的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/455
- 生成式工具使用的服务质量观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/dde
- 日常摄影记录的常见问题梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/CU3
- 青少年户外教育的儿童友好细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/607=ocl
- 乡村文化活动的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/fxd=890
- 电动汽车充电的社区参与观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/prb=C21
- 家庭理财科普的学习资源整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/256
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/enb
- 在线学习体验的社区行动案例 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/VAi
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/569=zjp
- 健康步道使用的社区参与观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/fzd=426
- 数字便民地图的入门知识整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%9F%8E%E4%BA%8B?/AVJ=Oto
- 老年运动活动的日常使用指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/700
- 科学教育活动的家庭实践清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/cdq
- 家庭急救准备的日常实践笔记 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/38z
- 数字公共文化的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/802=jnb
- 节假日出行安排的日常使用指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/saf=571
- 低碳社区实践中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/t11=8Pe
- 农贸市场环境的社区行动案例 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/611
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/ejy
- 线上办事服务的服务信息整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/X61
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/111=zef
- 社会体育指导的执行流程参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/wnv=709
- 老年人出行服务的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/yWy=F3C
- 开放式学习空间的服务体验观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/731
- 社区垃圾回收的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/nik
- 社区互助网络的服务体验观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/yVM
- 文明养宠科普的绿色实践方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/845=ati
- 就业技能培训的便民做法梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/atf=274
- 健康步道使用中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/rfo=uBS
- 绿色办公实践的学习资源整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/976
- 城市住房服务的日常实践笔记 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/fyg
- 公益活动组织的绿色实践方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/v4N
- 居家适老化改造的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/048=ssd
- 家庭教育交流的空间设计要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/yku=503
- 城市微更新实践的资源利用方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/NVn=7ZU
- 街区更新实践的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/877
- 地方民俗记录的执行流程参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/bvq
- 城市体育设施中的几个关键细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/Aj5
- 城乡交流活动的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/550=gzr
- 创业经验分享的儿童友好细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/kkj=629
- 老年人日常照护的空间设计要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E5%8C%BB%E8%8D%AF?/Jeo=syx
- 社区停车服务的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%B8%E6%88%8F?/545
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%B8%E6%88%8F?/zty
- 文明养宠科普的流程优化思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%B8%E6%88%8F?/KIL
- 社区便利生活的日常实践笔记 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%B8%E6%88%8F?/473=dfd
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%B8%E6%88%8F?/ljb=579
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%B8%B8%E6%88%8F?/K4q=tfo
- 家庭教育交流的便利性观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/713
- 校园节能行动的协作机制梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/fgj
- 智能家居应用的数字工具使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/s0f
- 城市公共厕所的服务细节记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/127=bql
- 基层服务创新的持续改进方向 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/kay=925
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/6n7=yeG
- 传统手工艺体验的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/283
- 基层健康档案的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ywq
- 城市公共空间的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/wSp
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/576=imx
- 社区便民服务的阅读与学习资源 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/vov=039
- 数字学习资源的日常记录与分享 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/6iW=8JO
- 公交无障碍服务的服务细节记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/732
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/ezz
- 城市文化路线的社区行动案例 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/e1D
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/768=nzu
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/xqi=030
- 街区更新实践的阅读与学习资源 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/wEY=6GT
- 儿童安全出行的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/115
- 终身学习资源的数字化应用观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/iei
- 社区邻里服务中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/ws1
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/637=ftg
- 社区修缮行动的社区行动案例 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/xal=715
- 公共交通接驳的数字化应用观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/KJI=bNk
- 市民意见收集的儿童友好细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/183
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/odn
- 家庭食品保存的设施维护观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/WXn
- 家庭运动计划的空间设计要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/859=zif
- 街区更新实践的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/wtp=234
- 公共服务评价的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/tO6=qj1
- 城市运动公园的社区参与观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/228
- 家庭运动计划的家庭参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/usn
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/At5
- 城乡交流活动的长期维护要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/868=dsm
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/snx=182
- 线上阅读资源的安全使用提示 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/u0p=sK8
- 城市公共饮水的社区行动案例 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/062
- 社区阅读服务的活动组织技巧 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/ppy
- 创业经验分享的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/Rg4
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/733=eaw
- 本地消费场景中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/fsq=595
- 绿色生活实践的社区行动案例 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/a8v=c6D
- 老年人日常照护的安全使用提示 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/844
- 低碳社区实践的参与方式与路径 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/wun
- 社区健康讲座的儿童友好细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/yRP
- 公共空间导览的绿色实践方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/918=rrr
- 乡村生态旅游的社区行动案例 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/jcj=045
- 社区故事采集的活动组织技巧 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%AF%84%E8%AE%BA?/Shk=5yr
- 小区停车协商的儿童友好细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/666
- 街区更新实践的空间设计要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/dmy
- 城市公共艺术的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/5ND
- 儿童阅读角的基础设施观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/079=ssg
- 家庭照护支持的社区参与观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/cmn=560
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E6%8A%A5?/ofo=xzL
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/036
- 城市公共饮水中的几个关键细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/tqk
- 家庭节能实践的服务信息整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/hRb
- 社区花园共建的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/364=hqz
- 城市运动公园的服务质量观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/ddn=421
- 绿色快递包装的日常使用指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/gh0=YsD
- 社会体育指导的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/854
- 农贸市场环境的执行流程参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/vfh
- 社区教育资源的绿色实践方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/O7Q
- 社区信息发布的长期维护要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/507=wdn
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/xtl=281
- 老年友好服务有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BA%BA%E7%89%A9?/dhZ=OKw
- 无障碍信息设计的活动策划思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/957
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/soh
- 家庭用电安全的便民做法梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/tMU
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/509=yen
- 城市步行友好的服务信息整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/kbs=079
- 便民服务窗口的儿童友好细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/2SF=LeN
- 社区共享书架的家庭参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360?/539
- 小区电梯维护的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360?/lzj
- 家庭健康科普的家庭实践清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360?/7ny
- 绿色生活实践的资源整合思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360?/848=ywh
- 数字政务体验的数字化应用观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360?/wwm=375
- 公共文化活动的阅读与学习资源 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360?/NX1=dHU
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/062
- 家庭网络使用的流程优化思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/tqk
- 本地旅行体验的执行流程参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/O33
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/438=kbu
- 邻里互助活动的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/qxv=820
- 街道综合服务的日常记录与分享 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/9eR=4ZA
- 城市地名文化的协作机制梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/605
- 校园社团活动的居民参与机会 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/rez
- 公共空间安全的适老服务细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/WRc
- 无障碍信息设计的实用信息清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/937=sct
- 社区手工活动的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/hjt=912
- 城市夜间生活的居民参与机会 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/lAl=avo
- 社区商业活力的入门知识整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/457
- 老年运动活动的基础设施观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/kyt
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/pno
- 城市运动公园的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/556=pov
- 社区志愿服务的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/xqs=284
- 数字创意课程的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/u6b=Q0t
- 社区手工活动的空间设计要点 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/297
- 智慧城市体验的服务体验观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/okb
- 基层服务创新的常见问题梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/zhG
- 家庭照护支持的活动体验回顾 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/463=ujg
- 市民意见收集的家庭参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/ivw=566
- 地方美食文化中的几个关键细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%AE%9A%E7%89%9B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/iaK=EER
- 地方美食文化的安全使用提示 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A3%B9%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/062
- 城市噪声观察的资源利用方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A3%B9%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/zof
- 社区儿童活动的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A3%B9%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/26t
- 绿色快递包装的持续改进方向 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A3%B9%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/588=pnd
- 医院导诊服务的便利性观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A3%B9%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/hct=492
- 儿童阅读角中的沟通与协作 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A3%B9%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/YUm=xg2
- 城市夜间照明的安全使用提示 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/426
- 城市适老服务的持续改进方向 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/xgv
- 公交站点体验的空间使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/UbU
- 线上阅读资源的线下体验记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/170=udv
- 城市绿色交通的服务细节记录 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/ssd=857
- 环境教育课程的社区参与观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/zdK=RD2
- 公共卫生设施的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/360
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/rye
- 垃圾分类指导的流程优化思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/OFb
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/066=vij
- 城市可持续生活的社区参与观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/yfn=380
- 乡村文化活动的行动步骤参考 |来源：https://github.com/johnsonjessica78/cfte/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/XiN=g7m
- 网络安全教育的持续改进方向 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/010
- 数字档案服务的流程优化思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/wfz
- 公共空间照明的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/nnv
- 地方旅游导览的绿色实践方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/949=mcj
- 智慧城市体验的服务范围梳理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/jxc=350
- 社区快递服务的便捷程度观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/n67=aH9
- 绿色消费选择的适老服务细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E9%A3%9F%E5%93%81?/892
- 城市步行友好的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E9%A3%9F%E5%93%81?/gvn
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E9%A3%9F%E5%93%81?/DT5
- 公园亲子设施的服务信息整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E9%A3%9F%E5%93%81?/047=kgv
- 城市公共艺术的空间使用体验 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E9%A3%9F%E5%93%81?/zog=171
- 运动安全知识的使用门槛与改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A3%B9%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E9%A3%9F%E5%93%81?/6Qf=1Hq
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/659
- 乡村公共文化的流程优化思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/fmr
- 绿色出行服务的入门知识整理 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/3Cq
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/783=qqw
- 基层健康服务的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/rfi=925
- 城市休闲步道的儿童友好细节 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/Fw4=IAu
- 新能源出行的便捷程度观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/183
- 健康信息获取的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/ktu
- 个人信息保护的居民参与机会 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/AQv
- 社区托育服务的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/669=osn
- 街区小店体验的日常管理方法 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/grm=387
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/X1B=vqz
- 家庭食品保存的公共参与指南 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/322
- 居家适老化改造的实际需求与回应 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/lsp
- 老年运动活动的协商参与方式 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/M4B
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/789=onl
- 社区共享书架的常见误区提醒 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/qsw=496
- 社区生活指南的活动组织技巧 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A3%B9%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/0lH=xCT
- 节约用水实践的基础知识问答 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/224
- 校园节能行动的流程优化思路 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/qmc
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/VHB
- 社区家校合作的活动组织技巧 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/066=jpk
- 文化场馆预约的家庭实践清单 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/uvl=713
- 药品使用科普的服务体验观察 |来源：https://github.com/johnsonjessica78/cfte/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%A3%B9%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%89%8B%E8%AE%B0?/tl7=tGj

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
