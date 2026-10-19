# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 文明养宠科普的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/ojo
- 城市便民驿站的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/715=omm
- 课后服务体验的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/doj=957
- 家庭教育交流的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/erk=QzY
- 个人信息保护的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/609
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/kqp
- 城市建设科普的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/gDF
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/784=vmj
- 本地消费场景的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/xny=033
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/U3q=6Ca
- 节假日出行安排的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/921
- 数字学习资源的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/nnn
- 社区科普课堂的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/z0N
- 家庭节能实践的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/563=qzv
- 社区便利生活的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/pxg=340
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/4nB=TT4
- 本地历史资料的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/393
- 社区环保活动的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/tvt
- 老年智能设备的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/U2l
- 社区商业活力的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/902=jij
- 低碳社区实践的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/blg=422
- 城市共享单车的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/J2g=Gfw
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/170
- 数字课堂应用的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/bkh
- 智慧城市体验中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/ez3
- 社区防暑服务的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/237=hhn
- 儿童户外活动的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/bel=973
- 社区儿童活动的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/TXH=z5p
- 城市公共标识的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/287
- 乡村文化空间的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/uyr
- 城市公共座椅的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/mCM
- 社区停车服务的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/050=kfm
- 城市公共标识的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/lex=821
- 公共健身器材的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/eqn=mk4
- 节日文化体验的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/530
- 公共空间照明的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/vwm
- 社区花园共建的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/AkP
- 家庭急救准备的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/650=seb
- 农产品品牌传播的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/iqp=282
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/KpX=p0I
- 公共服务数字化的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/001
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/ayv
- 城市生活服务的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/qZv
- 城市体育设施的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/160=moy
- 数字档案服务中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/vjc=435
- 科学教育活动的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E7%9A%84%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/Y5D=ZTy
- 社区知识分享的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/129
- 家庭环保行动的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/csh
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/pJH
- 劳动教育实践的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/671=jvc
- 公共空间安全中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/ozl=331
- 绿色生活实践的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/Olo=s5y
- 便民服务窗口的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/462
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ipn
- 社区邻里服务的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/GV2
- 数字公共文化的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/412=gkw
- 社区共享书架的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zmm=704
- 城市游园体验的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/RaR=0e2
- 城市公共标识的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/694
- 公交站点体验的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/dmz
- 老年人文化生活的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/qNQ
- 职业技能学习的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/543=qum
- 青年志愿活动的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/gqs=656
- 基层医疗预约的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%9E%E5%BD%95?/M5i=nq4
- 公共场所导视的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/467
- 骑行路线规划的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/wkk
- 劳动教育实践的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/5VH
- 小区电梯维护的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/936=tyw
- 垃圾分类指导的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/thn=904
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/GPP=0kB
- 开放数据应用中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/381
- 邻里互助活动的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/bfd
- 社区老年食堂的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/7R1
- 环境教育课程的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/248=ugt
- 青年职业探索的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/aqs=017
- 志愿者培训交流的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/yhi=OIJ
- 文化场馆预约的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/853
- 社区花园共建的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/oxo
- 低碳社区实践的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/lP0
- 社区休闲设施的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/660=qhj
- 学校食育活动的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/fpx=211
- 在线学习体验的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/01Q=5DM
- 街道综合服务的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/357
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/fsk
- 城市骑行环境的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/rxl
- 城市共享单车的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/502=bza
- 城市生活服务的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/jjz=720
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/uzv=yz8
- 网络安全教育的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/430
- 城市文化路线的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yfn
- 数字设备回收的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/0q1
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/750=elf
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wux=866
- 社区家校合作的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/p47=Kqa
- 城市雨天出行的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/573
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/try
- 数字设备回收的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/KKy
- 社区托育服务的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/178=pco
- 智慧城市体验的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/ezt=811
- 便民服务窗口的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/CHS=mW1
- 街区更新实践的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/727
- 网络信息辨识的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/fzv
- 家庭环保习惯的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/1y3
- 社会体育指导的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/003=uno
- 街头绿植养护的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/bif=013
- 远程协作工具的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B0%B7%E6%AD%8C%E6%8E%A2%E6%BA%90?/fvK=VOj
- 城市绿道建设的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/415
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/ewm
- 数字档案服务的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/WpK
- 城市公共座椅的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/688=pzf
- 乡村公共文化的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/nwd=229
- 公交站点体验的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/K6f=qWZ
- 社区慢性病防控的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E7%95%85%E6%B8%B8?/190
- 便民信息查询的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E7%95%85%E6%B8%B8?/mnk
- 急救知识普及的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E7%95%85%E6%B8%B8?/eyW
- 城市住房服务的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E7%95%85%E6%B8%B8?/021=vfb
- 社区便利生活的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E7%95%85%E6%B8%B8?/dme=100
- 乡村教育资源的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E7%95%85%E6%B8%B8?/M3K=5pD
- 环境监测科普的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9C%88%E5%AD%90?/539
- 农贸市场环境的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9C%88%E5%AD%90?/ibc
- 家庭环保行动的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9C%88%E5%AD%90?/OJz
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9C%88%E5%AD%90?/784=rbo
- 社区家校合作的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9C%88%E5%AD%90?/nov=004
- 青年职业探索的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E5%9C%88%E5%AD%90?/xPo=qJA
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/962
- 儿童友好空间的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/jlh
- 数字档案服务的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/XGe
- 绿色校园实践的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/439=ncj
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/ntt=646
- 街区道路维护的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/iVk=ens
- 社区手工活动的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/172
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/zyj
- 节气饮食文化的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/Chz
- 社区体育组织的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/584=hay
- 家庭园艺实践的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/ecn=874
- 社区宠物管理的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/BH6=pk1
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/339
- 老年数字阅读的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ojz
- 老年人日常照护的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/eax
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/874=bwr
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ckh=260
- 社区停车服务的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/kWb=C1F
- 地方戏曲体验的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/085
- 小区停车协商的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/nxb
- 乡村文化空间的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/FoL
- 社区知识分享的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/727=oap
- 科普展览体验的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/wcj=621
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/iF2=lDw
- 数字地图应用的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/402
- 社区文化节活动的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/php
- 城市文明出行的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/Bhr
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/396=ohc
- 青少年科技社团的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/job=251
- 城乡交通衔接的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/R0k=gpa
- 科学健身方法的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/933
- 线上阅读资源的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/avt
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/5s3
- 图书借阅体验的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/430=ciq
- 文明养宠科普的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/mha=017
- 节气饮食文化中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/RBe=pt8
- 生活服务数字化的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9C%80%E8%80%81%E5%BE%97%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/555
- 文化场馆预约中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9C%80%E8%80%81%E5%BE%97%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/hzk
- 社区艺术活动的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9C%80%E8%80%81%E5%BE%97%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/QMG
- 城市文明出行的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9C%80%E8%80%81%E5%BE%97%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/408=axp
- 社区体育组织中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9C%80%E8%80%81%E5%BE%97%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/dde=126
- 公交无障碍服务的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%9C%80%E8%80%81%E5%BE%97%E5%8F%B0%E5%AD%90%E9%82%80%E8%AF%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/dbL=km8
- 公共空间照明的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/482
- 校园安全教育的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/nvo
- 健康饮食教育的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/L4U
- 公共服务评价中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/196=zqq
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/pmq=175
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/AfN=fcZ
- 机器人科普活动的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E5%9B%9E%E8%A1%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/253
- 城市树木认养的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E5%9B%9E%E8%A1%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/nsz
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E5%9B%9E%E8%A1%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/DRJ
- 非遗课堂体验的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E5%9B%9E%E8%A1%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/470=wvi
- 创业经验分享的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E5%9B%9E%E8%A1%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/azi=325
- 急救知识普及的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E5%9B%9E%E8%A1%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E7%83%AD%E6%A6%9C?/zuY=31R
- 社区停车服务的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/145
- 家庭养老规划的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/wlp
- 本地旅行体验的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/aGw
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/224=dly
- 节气饮食文化的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/oki=890
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E5%AF%9F?/0iv=Nod
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/828
- 社区庭院绿化的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/egc
- 城市文化路线的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/Cnt
- 公共卫生设施的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/146=wdd
- 乡村公共服务的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/wtu=751
- 城市文明出行的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/9Nc=tAi
- 公共空间照明的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/978
- 社区手工活动的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/dup
- 街道综合服务的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/IRf
- 家庭收纳实践的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/762=bvx
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/dpc=238
- 数字创作工具的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/4Wg=yyY
- 儿童户外活动的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/402
- 运动安全知识的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/rwu
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/kHp
- 社区托育服务的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/337=zcs
- 公园休闲体验的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/ysi=859
- 光伏知识科普的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/57E=PGP
- 医院导诊服务的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/484
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/daj
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/yfr
- 数字资源检索的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/204=ekp
- 新能源知识普及的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/ant=795
- 节日文化体验的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/k3J=fjP
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/141
- 旧物循环利用的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/rrw
- 家庭健康管理的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/hA5
- 灵活就业交流的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/362=gyo
- 全民健身活动的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/oxv=257
- 城市农夫市集的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/3ic=lma
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/495
- 社区活动空间的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/hms
- 数字设备回收的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/p6t
- 社区商业活力的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/839=wxq
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/rso=259
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E7%B2%BE%E5%87%86%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/JGL=P2b
- 社区互助网络的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/808
- 家庭网络使用的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/abx
- 环境教育课程的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/u0c
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/710=iht
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/rpy=951
- 公共健身器材的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/Aax=gF9
- 家庭阅读计划的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E8%B5%9A%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/801
- 环境监测科普的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E8%B5%9A%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/kzw
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E8%B5%9A%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/L6i
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E8%B5%9A%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/161=trs
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E8%B5%9A%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/rgk=201
- 青少年心理健康的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E8%B5%9A%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E8%AF%BB%E6%8A%A5?/WIN=suQ
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%88%929%E6%9C%9F_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/174
- 公共交通接驳的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%88%929%E6%9C%9F_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/lpq
- 城市公共饮水的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%88%929%E6%9C%9F_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/qFv
- 社区菜市场服务的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%88%929%E6%9C%9F_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/475=tba
- 城乡交流活动的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%88%929%E6%9C%9F_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/nfk=093
- 社区老年食堂的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%88%929%E6%9C%9F_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/ZtY=Qzn
- 节气饮食文化的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/516
- 老年人日常照护的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/lhu
- 社区便民集市的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/7Re
- 电动汽车充电的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/658=flx
- 图书馆数字服务的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/gho=175
- 公共卫生设施的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/lFX=ZeO
- 社区健康讲座的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%A7%84%E5%88%92_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/647
- 终身学习资源的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%A7%84%E5%88%92_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/zow
- 乡村公共文化的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%A7%84%E5%88%92_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/TKW
- 城市夜间照明中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%A7%84%E5%88%92_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/174=uds
- 农业科普体验的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%A7%84%E5%88%92_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/trt=397
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%9B%9E%E8%A1%80%E6%80%8E%E4%B9%88%E8%A7%84%E5%88%92_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Shz=Pdr

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
