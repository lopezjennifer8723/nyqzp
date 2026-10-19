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

- 小区公共照明的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A7%86%E9%A2%91?/xvy=199
- 儿童友好空间的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%A7%86%E9%A2%91?/Ztb=UEC
- 城市雨天出行的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0?/102
- 校园安全教育的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0?/myx
- 家庭科学教育的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0?/6pY
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0?/632=vts
- 安全出行教育的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0?/jry=033
- 公共空间休憩的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0?/uQa=9Hp
- 城乡公共服务的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/789
- 节假日出行安排的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/rdw
- 城市公共饮水的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/zph
- 社区花园共建的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/470=jlc
- 公共卫生设施的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/ilc=404
- 生活服务数字化的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/Yw7=okJ
- 公共交通信息服务的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/032
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/vnr
- 数字创作工具的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/hkY
- 社区安全巡查的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/435=jxs
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/iak=445
- 节约用水实践的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%88%8A%E7%99%BB?/M3X=ljZ
- 科学信息获取的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/098
- 街区小店体验的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/aos
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/4jg
- 终身学习资源的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/472=fbb
- 数字支付体验的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/xwc=299
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/pmE=Ef3
- 社区体育组织的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/455
- 公共图书馆服务的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/tpw
- 应急物资管理的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/Ynn
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/770=ylm
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/vtj=729
- 社区生活指南的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/Bro=mfP
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/862
- 个人信息保护的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/vuq
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/wBx
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/827=gbi
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/tgs=392
- 地方文化传播的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%88%86%E6%9E%90%E8%B4%A2%E7%BB%8F?/6Vt=wbS
- 老年人出行服务的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/019
- 开源技术交流的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/whd
- 图书借阅体验的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/mTH
- 家庭安全提示的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/402=hbt
- 社区公共卫生的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/pux=733
- 便民服务窗口的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/Q3R=N14
- 城市博物馆活动的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/560
- 市民意见收集的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/dsq
- 食品安全科普的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/Mhb
- 老年人日常照护的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/562=hti
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/khz=612
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/nMF=NtD
- 公共健身器材的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/667
- 节日文化体验的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/tah
- 城市夜间照明的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/v1z
- 青少年科普实践的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/918=yyh
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/meg=356
- 老年智能设备的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%B6%88%E8%B4%B9?/vnK=ERQ
- 绿色生活实践的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/943
- 公共卫生宣传的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/mov
- 街头绿植养护的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/UmQ
- 城市农夫市集的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/733=roo
- 老年人出行服务的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/psh=430
- 应急物资管理的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/BKv=ORv
- 城市水环境观察的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/522
- 食品配送体验中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/fym
- 家庭理财科普的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/rBq
- 绿色出行服务的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/151=swn
- 数字生活课堂的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/yga=795
- 基层服务创新的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/Ezz=fAu
- 社区设施共享的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/045
- 公共服务咨询的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/vsj
- 城市夜间生活的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/jJn
- 社区安全巡查的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/295=nzt
- 公交站点体验的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/hco=354
- 社区便民服务的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/N3F=qpF
- 邻里互助活动的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/693
- 科普展览体验的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/icl
- 公园无障碍服务的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/dxv
- 乡村文化空间的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/477=hmw
- 城市噪声观察的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/qgo=573
- 地方民俗记录的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9C%88%E5%AD%90?/yoq=Qro
- 软件开发学习的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/340
- 药品使用科普的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/xjb
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/1f6
- 非遗体验活动的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/636=wxo
- 社区互助网络的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/ahx=953
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/UwL=IXR
- 乡村文化活动的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E7%89%B9%E7%A8%BF?/300
- 老年运动活动的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E7%89%B9%E7%A8%BF?/nhq
- 邻里互助活动的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E7%89%B9%E7%A8%BF?/zLv
- 信息无障碍体验的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E7%89%B9%E7%A8%BF?/692=ykf
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E7%89%B9%E7%A8%BF?/svq=732
- 健康饮水科普的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E7%89%B9%E7%A8%BF?/CO9=EBe
- 社区花园共建的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/311
- 城市雨天出行中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/pqp
- 城市共享单车的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/0rG
- 数字支付体验的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/473=ujh
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/sea=869
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/gI2=OFa
- 城市休闲步道的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/539
- 节日文化体验的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/pkz
- 街头绿植养护的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/A26
- 数字创意课程的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/666=vdw
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/llh=375
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/b5X=fkz
- 城市公共艺术的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/649
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/les
- 邻里共享空间的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/XgF
- 数字学习资源的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/336=yen
- 城市博物馆服务的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/htd=798
- 老年数字阅读的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/dFu=CVQ
- 社区菜市场服务的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/356
- 急救知识普及的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/iao
- 生活垃圾减量的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/C5n
- 老年人出行服务的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/940=gyj
- 周末休闲规划的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/wvr=413
- 社区应急准备的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/WQC=MMA
- 家庭节能实践的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/953
- 乡村文化活动的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/oaz
- 城市展览体验的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/Bf3
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/175=mpe
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/elm=222
- 家庭消费规划的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/XY2=Bsf
- 就业技能培训的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/467
- 软件开发学习的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/vsd
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/4ds
- 城市公共座椅的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/780=oth
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/kfu=788
- 社区公共议事的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/maJ=l7v
- 健康饮食教育的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/480
- 社区便利生活的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/wip
- 社区故事采集的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/Bd4
- 城市适老服务中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/919=zvd
- 应急物资管理的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/mqw=742
- 城市文化路线的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/RHb=RHX
- 公共空间休憩的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/870
- 地方旅游导览的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/quo
- 图书馆数字服务的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/PX8
- 公共服务数字化的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/917=dtm
- 青少年科技社团的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/wav=337
- 便民服务地图的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/Ph1=et3
- 社区协商议事的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/884
- 绿色办公实践的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/tuq
- 节能生活方式的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/mzC
- 垃圾分类指导的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/561=izh
- 城市空气科普的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/tuh=343
- 城市公共自行车的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/yYj=C6e
- 农村环境治理的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/193
- 绿色出行服务的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/zrz
- 线上办事服务的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/mis
- 本地历史资料的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/364=cvy
- 气象科普传播的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/xdc=341
- 儿童运动体验的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/BR9=U9u
- 儿童友好空间的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%8E%92%E5%88%97%E4%B8%89%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/308
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%8E%92%E5%88%97%E4%B8%89%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/vtb
- 就业技能培训的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%8E%92%E5%88%97%E4%B8%89%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/4tJ
- 科普展览体验的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%8E%92%E5%88%97%E4%B8%89%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/374=uel
- 社区垃圾回收的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%8E%92%E5%88%97%E4%B8%89%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/gdd=343
- 老年学习活动的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%8E%92%E5%88%97%E4%B8%89%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/Z9r=gY9
- 科学观察活动的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9D%80%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/926
- 灵活就业交流的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9D%80%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/gqf
- 城乡公共服务的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9D%80%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/Jnc
- 城市绿色交通的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9D%80%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/137=yzr
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9D%80%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/jnq=844
- 口袋公园建设的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9D%80%E5%8F%B7_%E6%96%B0%E6%B5%AA%E8%B5%84%E8%AE%AF?/YVt=Bj4
- 农产品消费体验的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/404
- 低碳社区实践的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/she
- 乡村生活观察的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/4OY
- 节约用水实践的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/017=vfv
- 社区修缮行动的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/toq=305
- 社区环保活动的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E6%99%A8%E6%8A%A5?/ply=s4B
- 家庭食品保存的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/429
- 青年志愿活动的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/nxo
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/NW8
- 小区停车协商的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/172=rbz
- 城市绿道建设的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/ehs=959
- 乡村生态观察的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/jVM=Xmb
- 职业技能学习的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/773
- 社区托育服务的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/akn
- 市民热线服务的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/t1S
- 基层医疗预约的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/235=yxw
- 公共场所导视的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/fub=447
- 绿色生活实践的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%81%A5%E5%BA%B7?/SxE=5S2
- 乡村公共服务的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/184
- 小区电梯维护的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/vzf
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/jMM
- 城市休闲步道的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/609=cvx
- 非遗体验活动的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/tea=560
- 绿色快递包装的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%8E%92%E5%88%97%E4%B8%89%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/d38=sYE
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%8E%92%E5%88%97%E4%B8%89%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/215
- 全民健身活动的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%8E%92%E5%88%97%E4%B8%89%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/nxz
- 家庭健康管理的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%8E%92%E5%88%97%E4%B8%89%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/Bis
- 家庭节能实践的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%8E%92%E5%88%97%E4%B8%89%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/557=crt
- 老年数字阅读的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%8E%92%E5%88%97%E4%B8%89%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/cav=821
- 休闲运动入门的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%8E%92%E5%88%97%E4%B8%89%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/ODW=KQl
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/420
- 生成式工具使用中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/nxy
- 公共场馆服务的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/ANR
- 数字生活课堂的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/479=yak
- 数据分析入门的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/lfr=482
- 家庭环保行动的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/pUP=nm7
- 社区托育服务的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/476
- 老年人出行服务的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/txu
- 学校体育活动的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/xmZ
- 绿色校园实践的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/581=big
- 城市可持续生活的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/axt=397
- 城市地名文化的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%8E%92%E5%88%97%E4%BA%94%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/uP1=Ush
- 网络信息辨识的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%85%8D%E8%B4%B9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/667
- 科学信息获取的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%85%8D%E8%B4%B9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/dxm
- 社区绿色空间的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%85%8D%E8%B4%B9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/wtt
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%85%8D%E8%B4%B9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/680=wme
- 居家适老化改造的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%85%8D%E8%B4%B9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/ehr=830
- 城乡公共服务的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%8E%92%E5%88%97%E4%BA%94%E5%85%8D%E8%B4%B9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/nBz=VNJ
- 数字生活课堂的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/758
- 城市人文观察的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/oxm
- 药品使用科普的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/i34
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/006=wwo
- 志愿服务平台的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/hku=608
- 公交站点体验的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%BA%94%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/28l=vz1
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E8%8B%B9%E6%9E%9C%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/006
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E8%8B%B9%E6%9E%9C%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/xjt
- 环境教育课程的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E8%8B%B9%E6%9E%9C%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/8JV
- 社区花园共建中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E8%8B%B9%E6%9E%9C%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/649=cbb
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E8%8B%B9%E6%9E%9C%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/zeq=214
- 乡村电商实践的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E8%8B%B9%E6%9E%9C%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/znU=FYi
- 智慧城市体验的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/929
- 垃圾分类指导的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/ajw
- 电动汽车充电的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/gHM
- 城市运动公园的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/391=wrm
- 数字创意课程的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/ulu=992
- 文化讲座服务的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A5%87%E8%B6%A3%E8%85%BE%E8%AE%AF%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/ImB=MCH
- 城市展览体验的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%AF%B7%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83app_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/592
- 青年就业服务中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%AF%B7%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83app_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/fhi
- 节日文化体验的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%AF%B7%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83app_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/z8f
- 在线学习体验的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%AF%B7%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83app_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/175=kas
- 环境教育课程的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%AF%B7%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83app_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/qte=200
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%AF%B7%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83app_%E8%99%8E%E5%97%85%E5%AE%B6%E7%94%B5?/DKC=h6e
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/730
- 社区艺术活动的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/fso
- 科普展览体验的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/p7U
- 生活垃圾回收的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/751=uee
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/yom=176
- 城市水环境观察中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%BD%E9%99%85?/bNU=JvE
- 居民健康教育的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/446
- 便民服务地图的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/amf
- 文化场馆预约的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/WbR
- 青少年科普实践的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/965=edg
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/jcu=806
- 健康步道使用的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/uGr=IYB
- 生活服务数字化的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/505
- 乡村文化空间的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%85%A8%E6%B0%91%E5%8F%8C%E8%89%B2%E7%90%83%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/evy

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
