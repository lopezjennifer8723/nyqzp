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

- 家庭园艺实践的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/950
- 社区停车服务的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/sja
- 社区慢性病防控的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/UUp
- 便民信息查询的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/504=abb
- 城市适老服务的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/zuh=854
- 生活垃圾减量的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E6%BC%AB%E8%AF%84?/blS=H7S
- 社区宠物管理的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/806
- 校园节能行动的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/mxk
- 家庭阅读计划的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/sEd
- 科学教育活动的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/195=bqk
- 地方美食文化的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/zzm=240
- 公共图书馆服务的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/H8D=W3x
- 城市空气科普的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/916
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/gmx
- 城市公共自行车的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/cHp
- 社区宠物管理的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/609=vhq
- 智慧城市体验的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/nje=296
- 家庭节能设备的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/rIw=H6B
- 城市人文观察的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/633
- 城市树木认养的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/fow
- 社区家政服务的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/UrL
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/935=egy
- 城市夜间照明的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/oqt=548
- 文化讲座服务的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/fzu=h6o
- 乡村文化空间的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/557
- 数字创意课程的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/lvf
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/sMj
- 社区手工活动的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/855=bbk
- 便民服务地图的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/jar=856
- 医院导诊服务的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/Ihe=Q6h
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/806
- 社区生活指南的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/erb
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/t8G
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/006=wym
- 电动汽车充电的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/yxd=934
- 社区公共议事的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/1dg=vzf
- 社区商业活力的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/870
- 全民阅读推广的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/lhp
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/sMG
- 家庭节能实践的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/813=ycc
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/uas=270
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/iid=9pi
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/511
- 健康饮水科普的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/tey
- 社区科普课堂的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/dl9
- 绿色消费选择的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/255=xeo
- 社区知识分享的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/mth=274
- 校园节能行动的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/glW=GAZ
- 运动安全知识的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/090
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/soy
- 绿色校园实践的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/vHu
- 老年人日常照护的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/332=dtz
- 城市文明出行的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/fxy=065
- 文化场馆预约的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/7J5=DbE
- 社区学习活动的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/054
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/hiq
- 城市公共自行车的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/pvB
- 家庭运动计划的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/787=alq
- 城市游园体验的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/fhn=067
- 家庭食品保存中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/jIk=r98
- 职业技能学习的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/315
- 健康步道使用的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/mno
- 远程协作工具的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/WMp
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/418=mvd
- 街区绿化养护中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/ppy=044
- 城市慢行系统的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/VAu=NcT
- 城市绿道建设的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/553
- 家庭用电安全的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/xxx
- 基层健康服务的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/cTv
- 社区快递服务的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/139=qzk
- 街道综合服务的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/gqr=880
- 公共空间安全的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/8YN=gGn
- 绿色快递包装的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/517
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/dot
- 非遗体验活动的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/0gq
- 社区花园共建的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/041=yrf
- 节约用水实践的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/vbq=952
- 社区故事采集的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/ueB=ijK
- 老年人出行服务的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/972
- 城市公共厕所的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/myx
- 学校体育活动的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/P7A
- 社区活动空间的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/225=bko
- 家庭志愿活动的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/nro=950
- 数字素养提升的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/skG=EZX
- 家庭收纳实践的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/182
- 社区活动策划的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/fkq
- 健康步道使用的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/XjD
- 社区故事采集的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/914=yod
- 低碳社区实践的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/woa=749
- 社区垃圾分类的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/WMS=kaR
- 租房信息服务的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/774
- 物业服务沟通的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/sdr
- 社区故事采集的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/yJ6
- 休闲运动入门中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/461=egb
- 户外活动组织的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/xxm=308
- 居家适老化改造的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/B1G=dfR
- 社区共享书架的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/254
- 家庭运动计划的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/xrf
- 家庭理财科普的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/InT
- 地方文化传播的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/667=alw
- 机器学习入门的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/pva=045
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/tUY=AUX
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/992
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/zcv
- 图书馆数字服务的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/23b
- 社区故事采集的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/294=ddb
- 绿色出行服务的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/jif=960
- 居民健康教育的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/tMe=BFR
- 社区共享书架的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/455
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/klt
- 便民维修服务的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/K9k
- 居民健康教育的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/266=tqs
- 社区体育组织的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/rme=903
- 乡村公共服务中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/ozc=Xgn
- 社区便民集市的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/182
- 城市慢行系统的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/taw
- 社区信息发布的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/Ftv
- 便民服务窗口的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/179=xqz
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/csy=790
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/sKZ=FpL
- 公共服务预约的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/096
- 社区养老服务的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/nmj
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/ssx
- 城市公共艺术的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/927=zou
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/jrb=552
- 家庭环保行动的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/3FT=kK9
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/572
- 基层健康档案的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/ugw
- 家庭用电安全的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/txK
- 城市空气科普的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/087=ihy
- 社区便民服务的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/fvl=460
- 城市建设科普的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/1RU=fcr
- 地方戏曲体验的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/210
- 城市共享单车的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/ftj
- 数字便民地图的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/huf
- 基层健康服务的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/177=leb
- 绿色生活实践的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/jkn=370
- 便民服务窗口的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/lAv=aEJ
- 文明养宠科普的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/201
- 志愿服务平台的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/iew
- 网络安全教育的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/2SS
- 社区家校合作的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/333=ziq
- 社区志愿服务的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/rmh=568
- 城市共享单车的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/0lT=fC2
- 街区道路维护的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/189
- 新能源知识普及的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/pyw
- 小微企业服务的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/gvJ
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/799=qub
- 公共卫生宣传的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/sza=502
- 通勤路线规划的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/nbF=OEY
- 数字地图应用的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/333
- 儿童友好空间的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/xvn
- 乡村产业科普的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/jXg
- 城市生活记录的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/451=uex
- 城市运动公园的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/jlo=286
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%93%94%E5%93%A9%E5%8E%BF%E5%9F%9F?/ONs=VeH
- 校园阅读活动的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/552
- 邻里互助活动的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/alt
- 社区共享书架的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/V4Y
- 城市便民驿站的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/069=gxm
- 在线教育体验的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/lrc=226
- 网络安全教育的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E5%8C%96?/JLy=spd
- 乡村生态观察的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/593
- 城市绿色交通的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/xxw
- 城市文化路线的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/wFS
- 生活服务数字化的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/141=lle
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/tbn=271
- 城市骑行环境的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/aoT=aj3
- 乡村公共服务的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/517
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/kjy
- 数字支付体验的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/ALR
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/056=sgb
- 城市体育设施的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/yas=351
- 城市适老服务的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/lix=qVD
- 城市文化路线的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/638
- 城市基础设施的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/wfr
- 亲子阅读活动的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/Peg
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/263=iye
- 租房信息服务的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/ngz=556
- 居家防滑改造中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/n3a=5fx
- 软件开发学习的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/903
- 街区更新实践的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/pqh
- 城乡交通衔接的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/oDt
- 垃圾分类指导的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/089=ihy
- 城市公共标识的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/kqq=376
- 老年学习活动的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%AF%84%E8%AE%BA?/X6K=WI3
- 农村环境治理的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/754
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/ije
- 公共服务沟通的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/Qqb
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/324=rgq
- 社区知识分享的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/six=596
- 城市骑行环境的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/9Jv=RwD
- 健康信息获取的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/664
- 社区知识分享的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/vha
- 数字素养提升的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/Gs7
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/527=stm
- 社区公共议事的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/hbs=452
- 周末休闲规划的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/myQ=NOV
- 电动汽车充电的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/446
- 无障碍出行的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/eip
- 数字政务体验中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/Cj5
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/154=wug
- 校园社团活动的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/thj=617
- 社区科普课堂的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/f2X=tto
- 便民服务地图的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/350
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/xax
- 社区运动空间的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/Tu6
- 生成式工具使用的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/307=qft
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/omq=754
- 社区儿童活动的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%A4%B4%E6%9D%A1%E5%A4%B4%E6%9D%A1?/fbX=VU1
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/259
- 社区法律科普的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/xws
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/vTJ
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/062=woa
- 智能家居应用的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/irh=540
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%9A%E5%BB%BA?/Xtg=DZW
- 城市游园体验的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/352
- 城市地名文化的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/jkk
- 社区艺术活动中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/c26
- 乡村产业科普的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/740=pmz
- 节能家电使用的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/vrr=633
- 城市步行友好的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/XCd=Oxo
- 街区绿化养护的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/097
- 城市建设科普的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/bwp
- 亲子阅读活动的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/rA3
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/356=ctf
- 儿童友好空间的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/rfy=877
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/2lV=VFf
- 城市绿道建设的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/748
- 社区教育资源的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/hsh
- 儿童阅读角的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/WGP
- 节日文化体验的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/402=ptb
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/emq=950
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/VqJ=Dlu
- 城市共享单车的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/502
- 个人时间管理的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/zlc
- 文明养宠科普的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/Xu7
- 城市绿色交通的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/985=xrx
- 家庭养老规划的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/hvd=128
- 城市应急科普的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/orp=irP
- 科普展览体验的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/121
- 地方旅游导览的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/ker
- 社区活动空间的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/f7P
- 社区共享书架的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/220=cav
- 图书借阅体验的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/mle=442
- 社区绿色空间的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/uZf=adR
- 社区修缮行动的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/375
- 社区运动空间中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/iei
- 数字课堂应用的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/7k4
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%8E%A2%E5%BA%97?/551=cqf

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
