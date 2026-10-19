# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 科学睡眠习惯的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/007
- 乡村教育资源的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/hor
- 图书馆数字服务的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/IAS
- 城市地名文化的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/255=vhl
- 户外活动组织的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/wmr=368
- 光伏知识科普的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8A%A1?/HgU=xmt
- 公共服务指南的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/328
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/hsj
- 生活服务数字化中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/nRe
- 社区商业活力的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/483=ppe
- 人工智能科普的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/jsq=546
- 学校食育活动的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/fYm=KZl
- 健康饮水科普的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/182
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/gbv
- 在线教育体验的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/WsU
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/990=shb
- 数字公共文化的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/knm=591
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/Pnn=bU4
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/975
- 校园节能行动的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/fwl
- 公共服务预约的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/1Hz
- 社区环保活动的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/113=leg
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/mhp=970
- 公共服务指南的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/uud=IKB
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/143
- 城市文明出行的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/wwz
- 社区菜市场服务的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/Tt7
- 新能源出行的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/337=jma
- 家庭健康科普的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/pkg=823
- 数字档案服务的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/mHA=oxA
- 机器人科普活动的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%BF%AB%E6%89%8B%E6%BC%AB%E8%AF%84?/369
- 公共服务数字化的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%BF%AB%E6%89%8B%E6%BC%AB%E8%AF%84?/hxg
- 垃圾分类指导的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%BF%AB%E6%89%8B%E6%BC%AB%E8%AF%84?/lPB
- 生活垃圾减量的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%BF%AB%E6%89%8B%E6%BC%AB%E8%AF%84?/668=fej
- 城市适老服务的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%BF%AB%E6%89%8B%E6%BC%AB%E8%AF%84?/hbs=270
- 公共服务数字化的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E5%BF%AB%E6%89%8B%E6%BC%AB%E8%AF%84?/xUT=n53
- 智慧城市体验的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/337
- 社区活动策划的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/eul
- 绿色消费选择的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/Muv
- 地方美食文化的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/493=dhk
- 无障碍出行的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/nya=298
- 骑行路线规划的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/m7W=ddF
- 开放式学习空间的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/482
- 街区更新实践的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/xwj
- 信息无障碍体验的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/LdB
- 城市绿色交通的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/520=piv
- 图书借阅体验的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/fma=074
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%8A%92%E6%9E%9C%E7%BB%BC%E8%89%BA?/cQ8=zV3
- 城市空气科普的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/424
- 城市适老服务的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/qur
- 居家适老化改造的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/zkB
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/571=yls
- 家庭科学教育的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/rzf=514
- 城市步行环境的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/j0m=mIy
- 急救知识普及的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/794
- 节气饮食文化的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/khf
- 社区活动策划的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/8hw
- 家庭急救准备的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/554=adm
- 数字档案服务的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/qig=263
- 软件开发学习的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/6Xh=YNI
- 居家防滑改造的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/645
- 城市展览体验的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/ory
- 社区环保活动的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/Wlc
- 数字便民地图的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/289=imp
- 绿色生活实践的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/ccp=413
- 乡村公共服务的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/pih=pcr
- 家庭环保行动的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/453
- 租房信息服务的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/gpa
- 志愿服务平台的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/kdA
- 生成式工具使用的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/348=jlk
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/hbb=093
- 社区宠物管理的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/3ne=ZFG
- 老年人出行服务的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/014
- 社区活动策划的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/qxw
- 绿色快递包装的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/rUd
- 城市步行环境的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/595=skz
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/alb=937
- 公共文化活动的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E9%9B%85%E8%99%8E%E5%8D%83%E5%B8%86?/4Oq=2EK
- 乡村阅读空间的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/284
- 社区教育资源的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/yqi
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/Orh
- 电动汽车充电的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/512=tax
- 公交站点体验的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/unp=546
- 城市基础设施的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%8C%BB%E8%8D%AF?/Gsr=CUy
- 消防知识宣传的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/582
- 社区信息发布的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/ltn
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/x14
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/387=vja
- 城市体育设施的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/qsb=452
- 社区文化节活动的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/IWI=Kwc
- 个人数据管理的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/310
- 社区防暑服务的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/jao
- 城市公共自行车的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/IL0
- 药品使用科普的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/351=hzv
- 劳动教育实践的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/qkx=729
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/ofT=C19
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/243
- 机器学习入门的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/dhb
- 街头绿植养护的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/xOe
- 城市水环境观察的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/288=tom
- 开源技术交流的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/kcm=830
- 城市可持续生活的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/5Eq=HMF
- 气象科普传播的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/615
- 数字支付体验的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/kxl
- 家庭环保行动的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/txF
- 社区文化节活动的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/320=qoz
- 社区生活指南的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/xdu=859
- 邻里共享空间的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%B2%E5%9D%9B?/Jkg=XwV
- 智能家居应用的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/454
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/rwy
- 街区道路维护的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/oyP
- 家庭急救准备的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/768=vti
- 开源技术交流的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/fyu=003
- 社区设施共享的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B1%86%E7%93%A3%E6%8A%95%E8%B5%84?/YNJ=A1C
- 公共空间照明的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/259
- 线上阅读资源的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/ofm
- 网络安全教育的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/s4m
- 公共健身器材的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/258=zex
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/lfh=316
- 信息无障碍体验的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/kd1=5Nz
- 劳动教育实践的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/116
- 公益活动组织的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/ddn
- 城市博物馆服务的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/B1a
- 家庭急救准备的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/515=bal
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/fom=667
- 本地历史资料的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/EMC=atk
- 城市空气科普的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/549
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/idl
- 家庭收纳实践的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/9oI
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/295=ptz
- 城市公共座椅的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/cko=468
- 家庭食品保存的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%81%E5%8B%9F?/dLu=3ZG
- 街头绿植养护的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/547
- 数字艺术创作的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/thv
- 数字阅读服务的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/sEn
- 生活技能分享的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/522=fdj
- 社区协商议事的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/rkj=032
- 公共健身器材的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%BE%8E%E9%A3%9F?/SEP=b7R
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/959
- 儿童户外活动的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/jia
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/H1w
- 健康饮食教育的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/211=yub
- 家庭饮食安排的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/pov=732
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/scR=6yr
- 城市夜间生活的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/677
- 公交站点体验的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/eyu
- 社区手工活动的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/CiS
- 公共卫生设施的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/349=kej
- 健康饮食教育的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/fyw=257
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E5%BE%97%E7%89%A9%E5%85%9A%E5%BB%BA?/Wel=6vF
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/083
- 街区道路维护的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/vjq
- 居家适老化改造的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/bc5
- 社区便民服务的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/907=gjv
- 传统节日科普的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/glt=114
- 网络安全教育的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%AF%84%E8%AE%BA?/2v8=A22
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/472
- 社区便利生活的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/poq
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/dOT
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/789=aiy
- 远程协作工具从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/chz=515
- 乡村文化空间的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E6%90%9C%E7%8B%90%E8%AF%84%E8%AE%BA?/siE=Fw5
- 社区绿色空间的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/533
- 家庭饮食安排的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/pod
- 社区文化节活动的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/pQH
- 城市慢行系统的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/914=xiy
- 节能家电使用的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/ecs=035
- 社区艺术活动的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/8ws=wfA
- 城市公共艺术的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/724
- 邻里互助活动的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/btx
- 乡村电商实践的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/Wtk
- 农村环境治理的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/000=hae
- 健康饮食教育的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/asg=890
- 基层健康档案的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/wTy=hYj
- 城市共享单车的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/470
- 公共空间安全的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/vss
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/QCM
- 家庭志愿活动的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/832=plt
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/ydf=580
- 乡村产业科普的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/v93=Wov
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/553
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/quu
- 城市骑行环境的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/MKz
- 城乡交通衔接的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/757=gur
- 健康饮食教育的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/ezi=458
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/unV=Tnz
- 城乡交流活动的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/958
- 青年志愿活动的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/hza
- 社区志愿服务的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/bVk
- 智慧城市体验的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/622=jet
- 健康步道使用的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/rxs=317
- 网络信息辨识的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/qCx=mvz
- 新能源出行的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E6%97%A5%E6%8A%A5?/927
- 在线教育体验的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E6%97%A5%E6%8A%A5?/vva
- 小区停车协商的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E6%97%A5%E6%8A%A5?/uQW
- 智能手机助老的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E6%97%A5%E6%8A%A5?/747=rad
- 文化场馆预约的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E6%97%A5%E6%8A%A5?/okq=941
- 城市树木认养的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_360%E6%97%A5%E6%8A%A5?/BVr=nOo
- 数字设备回收的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/442
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/llp
- 城市建设科普的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/ZPR
- 公共设施使用的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/838=dqq
- 社区公共议事中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/yyz=217
- 家庭安全提示的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/sfj=3dR
- 便民服务地图的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/360
- 节假日出行安排的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/shx
- 城市公共艺术的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/qwF
- 智慧停车服务的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/163=tqq
- 城市基础设施的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/jgg=273
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/ER3=2w4
- 社区文化传播的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/635
- 读书会组织的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/hih
- 数字便民地图的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/aAq
- 公共设施维护的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/963=jng
- 开放式学习空间的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/ncf=927
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%9B%BE%E9%89%B4?/5EO=EVp
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_36%E6%B0%AA%E5%9F%BA%E9%87%91?/642
- 本地消费场景的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_36%E6%B0%AA%E5%9F%BA%E9%87%91?/exe
- 青年职业探索的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_36%E6%B0%AA%E5%9F%BA%E9%87%91?/To8
- 地方民俗记录的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_36%E6%B0%AA%E5%9F%BA%E9%87%91?/489=cxa
- 机器人科普活动的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_36%E6%B0%AA%E5%9F%BA%E9%87%91?/bod=442
- 节假日出行安排的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_36%E6%B0%AA%E5%9F%BA%E9%87%91?/hq9=h64
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/059
- 老年人文化生活的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ipw
- 人工智能科普的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Por
- 公交站点体验的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/852=pux
- 社区运动空间的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/aaw=398
- 城市绿道建设的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/o9R=jeb
- 城市绿道建设的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/814
- 人工智能科普的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/axv
- 社区公共议事的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/6uA
- 社区老年食堂的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/028=juu
- 城市博物馆活动的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/jfx=543
- 灵活就业交流的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/ggy=XzM
- 骑行路线规划的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/294
- 绿色生活实践的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/wyc
- 城市运动公园的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/orM
- 图书借阅体验的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/820=twb
- 就业技能培训的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/ile=793
- 科普展览体验的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/m6L=sE4
- 地方旅游导览的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/024
- 乡村文化空间的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/obn
- 非遗体验活动的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/d6a
- 绿色校园实践的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/700=pqy
- 公共卫生设施中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/hqx=421
- 家庭照护支持的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/D0p=gKk
- 社区休闲设施的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/276
- 社区环保活动的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/mja
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/Ci5
- 志愿服务平台的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/280=odi

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
