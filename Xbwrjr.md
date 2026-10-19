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

- 便民服务窗口的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/kAL
- 绿色办公实践的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/451=cbl
- 社区生活指南的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/dob=951
- 城市生活服务的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/WKF=ohv
- 文明养宠科普中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/736
- 光伏知识科普的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/jde
- 创业经验分享的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/ZhD
- 社区交通安全的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/331=xye
- 终身学习资源的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/bmt=767
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/QPB=rwO
- 城市文明出行的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/196
- 城乡交流活动的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/two
- 运动安全知识的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/mw9
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/809=pjv
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/shq=806
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/3gj=nDY
- 节日文化体验的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/065
- 基层健康档案的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/wsc
- 城市建设科普的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/9fV
- 家庭食品保存的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/011=acu
- 物业服务沟通的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/okf=793
- 城乡交流活动的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv1.0%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF_%E8%84%89%E8%84%89%E8%AF%84%E8%AE%BA?/ZEU=0M1
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E7%88%86%E6%96%99?/561
- 食品配送体验的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E7%88%86%E6%96%99?/jjj
- 家庭节能实践的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E7%88%86%E6%96%99?/Ofa
- 居民健康教育的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E7%88%86%E6%96%99?/970=scy
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E7%88%86%E6%96%99?/ssu=828
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E7%88%86%E6%96%99?/PIw=4jP
- 社区读书角建设的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/092
- 光伏知识科普的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/zzz
- 社区便利生活的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/fmk
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/045=jvi
- 环境监测科普的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/xmz=173
- 家庭园艺实践的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/MAp=UfH
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/417
- 家庭节能实践的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/szv
- 数字设备回收的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/ByC
- 生活垃圾减量的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/158=wwo
- 职业技能学习的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/sek=687
- 社区运动空间的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/TAg=5jV
- 老年人出行服务的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/160
- 本地历史资料的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/xhj
- 校园阅读活动的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/TZa
- 社区活动空间中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/326=cjp
- 老年人日常照护的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/vik=242
- 节能家电使用的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_901%E5%BD%A9%E7%A5%A8cc525%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/3QV=a5D
- 农产品消费体验的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/239
- 节能家电使用的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/jpq
- 基层服务创新的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/Zuj
- 社区运动空间的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/156=qqp
- 社区知识分享的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/bhg=986
- 全民健身活动的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/ox1=28n
- 家庭用电安全的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/429
- 社区消防演练的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/nnc
- 终身学习资源的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/FxY
- 公共服务咨询的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/838=hhe
- 社区家政服务的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/tao=449
- 电子商务服务的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/zFD=UeK
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/563
- 数字创意课程的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/wgm
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/mYV
- 读书会组织的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/508=kfn
- 公共场所导视的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/mst=187
- 乡村阅读空间的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/uMd=Yko
- 公共空间导览的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/201
- 社区老年食堂的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/msa
- 应急物资管理的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/RJ9
- 跨代沟通活动的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/071=gpb
- 邻里共享空间的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/pzn=284
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A8%BF?/QT9=HoM
- 数字学习资源的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/554
- 信息无障碍体验的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/pse
- 公共场所导视的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/s4r
- 生成式工具使用的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/698=wyo
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/njz=240
- 家庭急救准备的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_5G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA%E6%9C%AD%E8%AE%B0?/Xiw=6qJ
- 公交站点体验的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/881
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/ugu
- 社区手工活动的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/uRQ
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/727=odm
- 校园社团活动的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/dhj=808
- 数字资源检索的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD300%E4%B8%87_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/k7V=t6e
- 本地旅行体验的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/943
- 城市公共艺术的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/bav
- 个人数据管理的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/dnG
- 家庭用电安全的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/245=zik
- 社区公共议事的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/vyr=736
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E7%9C%8B%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/fUo=9zh
- 街区小店体验的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/354
- 无障碍信息设计的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/uls
- 社区信息发布的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/IVb
- 生活技能分享的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/004=hxf
- 城市环境志愿行动的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/opu=011
- 城市便民驿站的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85v98_%E6%90%9C%E7%8B%97%E9%80%9A%E4%BF%A1?/Pe6=HJ6
- 节日文化体验的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/377
- 街区绿化养护的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/gsg
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/mRt
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/499=vbp
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/ycd=197
- 市民意见收集的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E6%90%9C%E7%8B%90%E5%9B%AD%E8%89%BA?/Xwp=b7N
- 校园安全教育的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/064
- 家庭运动计划的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/mpq
- 基层医疗预约的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/f0T
- 邻里互助活动的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/876=xje
- 家庭教育交流的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/wva=681
- 终身学习资源的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E6%9C%80%E5%A4%A7%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%BD%A9%E7%A5%A8?/9AP=ygS
- 数字课堂应用的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A95%E5%BD%A9%E7%A5%A8iOS%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/715
- 数字课堂应用中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A95%E5%BD%A9%E7%A5%A8iOS%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/bli
- 公共文化活动的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A95%E5%BD%A9%E7%A5%A8iOS%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/Zcn
- 读书会组织的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A95%E5%BD%A9%E7%A5%A8iOS%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/144=vhr
- 青少年心理健康的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A95%E5%BD%A9%E7%A5%A8iOS%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/lqn=463
- 图书借阅体验的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A95%E5%BD%A9%E7%A5%A8iOS%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/gDj=eIA
- 应急物资管理的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%80%81%E7%89%88106cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/398
- 社区便民集市的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%80%81%E7%89%88106cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/qjj
- 家庭科学教育的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%80%81%E7%89%88106cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/Yxx
- 邻里互助活动的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%80%81%E7%89%88106cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/855=nom
- 城市可持续生活的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%80%81%E7%89%88106cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/lsv=656
- 公共交通接驳的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E8%80%81%E7%89%88106cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/ocs=dId
- 老年人出行服务的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDbuild_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/387
- 数字生活课堂的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDbuild_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/lfk
- 公益活动组织的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDbuild_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/Rvi
- 节能生活方式的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDbuild_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/881=tdw
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDbuild_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/dgb=275
- 公共卫生宣传的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDbuild_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/ukR=2uH
- 社区垃圾回收的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/914
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/puk
- 租房信息服务的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Gks
- 新能源知识普及的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/678=trr
- 社区绿色空间的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/fnq=388
- 光伏知识科普的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/2Vq=qgI
- 乡村生态旅游的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/203
- 社区手工活动的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/vpz
- 社区老年食堂的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/vni
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/655=pny
- 乡村公共服务的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/fqk=068
- 健康饮食教育的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%89%E5%8D%93%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/HT8=s2l
- 小区公共照明的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88500%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/055
- 生成式工具使用的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88500%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/mxq
- 社区菜市场服务的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88500%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/6aP
- 公共卫生宣传的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88500%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/523=ult
- 社区体育组织的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88500%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/gbd=241
- 日常摄影记录的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%96%B0%E7%89%88500%E5%BD%A9%E7%A5%A8%E7%BD%91%E8%B4%AD%E4%B9%B0%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/mOX=eMp
- 基层健康服务的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/459
- 口袋公园建设的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/kzz
- 城市树木认养的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/wzj
- 社区休闲设施的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/194=hqn
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/phk=617
- 小微企业服务的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_500%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/8MM=6HE
- 城市运动公园的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv4-2.0._%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/890
- 绿色办公实践中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv4-2.0._%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/pso
- 消防知识宣传的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv4-2.0._%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/LKo
- 家庭阅读计划的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv4-2.0._%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/751=hui
- 文化讲座服务的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv4-2.0._%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/nrj=225
- 环境监测科普的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDv4-2.0._%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/2nI=hgs
- 公共卫生设施的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/237
- 在线学习体验的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/ihf
- 邻里共享空间的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/o5R
- 社区交通安全的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/434=eco
- 人工智能科普的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/box=622
- 在线学习体验的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/dxy=aGC
- 小区停车协商的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_500VIP%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/364
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_500VIP%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/dui
- 老年智能设备的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_500VIP%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/tfP
- 志愿服务平台的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_500VIP%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/237=akz
- 家庭教育交流的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_500VIP%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/ovj=866
- 数字创作工具的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_500VIP%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/sWU=DTh
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_0500%E5%BD%A9%E7%A5%A8%E9%9B%B6%E5%94%AE%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/135
- 老年人日常照护的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_0500%E5%BD%A9%E7%A5%A8%E9%9B%B6%E5%94%AE%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/bic
- 社区家校合作的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_0500%E5%BD%A9%E7%A5%A8%E9%9B%B6%E5%94%AE%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/Bwr
- 城市微更新实践有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_0500%E5%BD%A9%E7%A5%A8%E9%9B%B6%E5%94%AE%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/874=scz
- 开放式学习空间的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_0500%E5%BD%A9%E7%A5%A8%E9%9B%B6%E5%94%AE%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/dta=860
- 家庭急救准备的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_0500%E5%BD%A9%E7%A5%A8%E9%9B%B6%E5%94%AE%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%89%8B%E8%AE%B0?/9PT=vEM
- 城市休闲步道的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2020_%E7%9F%A5%E4%B9%8E?/824
- 数字阅读服务的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2020_%E7%9F%A5%E4%B9%8E?/jai
- 青少年科普实践的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2020_%E7%9F%A5%E4%B9%8E?/Zxu
- 小区停车协商的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2020_%E7%9F%A5%E4%B9%8E?/573=psx
- 社区安全巡查的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2020_%E7%9F%A5%E4%B9%8E?/uez=656
- 社区应急准备的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2020_%E7%9F%A5%E4%B9%8E?/oPk=lAV
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_4G%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/666
- 市民热线服务的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_4G%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/won
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_4G%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/Evd
- 城市公共标识的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_4G%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/706=ied
- 灵活就业交流的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_4G%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/mbi=975
- 绿色出行服务的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_4G%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%99%BE%E7%A7%91?/wRh=KzD
- 青少年心理健康的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/208
- 社区教育资源的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/lsb
- 学校体育活动的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/XYg
- 社区应急准备的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/625=miu
- 数字课堂应用的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/tkr=403
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E8%AE%BA%E5%9D%9B?/M53=vX7
- 社区公共卫生的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDy%E2%85%B0ng_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/515
- 环境教育课程的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDy%E2%85%B0ng_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/lsi
- 家庭饮食安排的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDy%E2%85%B0ng_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/Ab4
- 社区便民服务的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDy%E2%85%B0ng_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/821=tkg
- 城市基础设施的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDy%E2%85%B0ng_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/yjb=945
- 基层服务创新的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDy%E2%85%B0ng_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/ysi=S7z
- 就业技能培训的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD1.00_%E6%96%B0%E6%B5%AA%E5%9F%BA%E9%87%91?/599
- 数字素养提升的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD1.00_%E6%96%B0%E6%B5%AA%E5%9F%BA%E9%87%91?/ibo
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD1.00_%E6%96%B0%E6%B5%AA%E5%9F%BA%E9%87%91?/Evn
- 社区公共议事的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD1.00_%E6%96%B0%E6%B5%AA%E5%9F%BA%E9%87%91?/544=kpc
- 社区心理支持的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD1.00_%E6%96%B0%E6%B5%AA%E5%9F%BA%E9%87%91?/ack=911
- 旧物循环利用的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD1.00_%E6%96%B0%E6%B5%AA%E5%9F%BA%E9%87%91?/I2q=XYO
- 节日文化体验的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BA%B2%E5%AD%90?/357
- 城市社区治理的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BA%B2%E5%AD%90?/mit
- 家庭运动计划的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BA%B2%E5%AD%90?/3r9
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BA%B2%E5%AD%90?/206=gkv
- 城市绿道建设的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BA%B2%E5%AD%90?/apk=259
- 数字政务体验的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%BA%B2%E5%AD%90?/ag8=fbM
- 居家防滑改造的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_105%E5%AE%98%E7%BD%91%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/340
- 软件开发学习的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_105%E5%AE%98%E7%BD%91%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/bbt
- 城市便民驿站的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_105%E5%AE%98%E7%BD%91%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/pMQ
- 食品配送体验的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_105%E5%AE%98%E7%BD%91%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/829=fjp
- 青少年心理健康的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_105%E5%AE%98%E7%BD%91%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/vup=781
- 老年智能设备的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_105%E5%AE%98%E7%BD%91%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/upL=L2P
- 社区协商议事的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/207
- 节能生活方式的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/oyf
- 公共交通接驳的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/9Pe
- 城市步行友好的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/811=khd
- 社区防暑服务的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/amd=570
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/1DC=bqc
- 城市文明出行的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/997
- 城市夜间照明的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/pma
- 家庭急救准备的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/VxD
- 社区设施共享的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/690=krj
- 城市人文观察的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/wae=418
- 家庭养老规划的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E6%96%B0%E6%B5%AA%E6%97%B6%E5%B0%9A?/bFW=56u
- 社区健康讲座中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/798
- 公共服务沟通的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/vxu
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/mXd
- 光伏知识科普的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/507=cuw
- 公共场所导视的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/jfi=106
- 城市基础设施的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/8B8=gil
- 地方美食文化的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_c5vip%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/991
- 社区商业活力的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_c5vip%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/kzv
- 城市建设科普的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_c5vip%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/DJg
- 创业经验分享的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_c5vip%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/192=jcv
- 数据分析入门中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_c5vip%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/dtp=245
- 城市文化路线的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_c5vip%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/s4z=0JO
- 家庭健康科普的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/840
- 通勤路线规划的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/muy
- 社区运动空间中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/LNX
- 社区垃圾回收的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/307=pqc
- 地方文化传播的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/rxk=128
- 街区道路维护的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_4g%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/TE8=mFQ
- 小区公共照明的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/021
- 家庭食品保存的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/oqy
- 社区慢性病防控的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/3q7
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/935=evc
- 数字支付体验的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/mqn=105
- 劳动教育实践的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_9055%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/ttR=eao

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
