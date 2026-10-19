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

- 智能家居应用的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/344
- 家庭饮食安排的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/xgp
- 乡村公共服务的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/bQC
- 城市公共标识的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/746=egp
- 城市地名文化的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/tet=517
- 邻里共享空间的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%A5%96%E5%A8%B1%E4%B9%90%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/gpx=5nr
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/854
- 街区绿化养护的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/nvi
- 青少年户外教育的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/esK
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/347=kxw
- 城市公共自行车的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/rmm=538
- 市民意见收集的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E6%98%8E%E7%BB%86_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/IgV=ig2
- 公交站点体验的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/048
- 休闲运动入门的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/rsi
- 居家适老化改造的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/j0k
- 城市应急科普的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/047=kii
- 文化讲座服务的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/upv=759
- 乡村公共服务的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E8%AE%BF%E8%B0%88?/YJN=25Q
- 家庭健康管理中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/823
- 数字地图应用的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/amd
- 低碳社区实践的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/hYA
- 社区健康讲座的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/714=trq
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/dst=419
- 城市公共饮水的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/WL6=LCo
- 城市夜间生活的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/596
- 就业技能培训的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/yob
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/2VO
- 乡村教育资源的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/403=tsg
- 公共设施使用的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/avy=695
- 家庭健康管理的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_500%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/m7P=myc
- 家庭运动计划的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/839
- 节能生活方式的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/zen
- 校园阅读活动的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/HJW
- 城市生活记录的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/945=vmd
- 家庭阅读计划的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/wrz=572
- 周末休闲规划的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%BD%91%E5%9D%80_%E9%A1%BA%E4%B8%B0%E8%82%A1%E7%A5%A8?/Krn=PSd
- 节假日出行安排的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/498
- 城市公共座椅的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lnp
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/9D6
- 口袋公园建设的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/361=ohz
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/plj=805
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Igg=0Ki
- 物业服务沟通的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/616
- 社区文化节活动的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/eop
- 家庭养老规划的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/dyi
- 校园阅读活动的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/949=oig
- 老年友好服务的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/cnz=137
- 社区快递服务的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B9%88_%E7%BD%91%E6%98%93%E8%83%BD%E6%BA%90?/6cq=XQ7
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/423
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/wxw
- 社区知识分享的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/j2Z
- 城市公共饮水的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/671=vjc
- 节假日出行安排的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/dnz=089
- 街道综合服务的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%A4%A7%E7%A5%9E%E6%8E%A5%E5%BE%85QQ_%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/6JD=TVG
- 志愿服务平台的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/314
- 健康饮食教育的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/nea
- 公交站点体验的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/Ybr
- 市民意见收集的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/112=qeq
- 社区垃圾回收的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/dhy=102
- 数字创意课程的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E7%A5%9E%E6%8F%AD%E7%A7%98%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/ZCg=L4K
- 城市空气科普的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/115
- 青年就业服务的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/ixt
- 城乡公共服务的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/Kfq
- 本地旅行体验的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/470=dms
- 本地消费场景的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/xee=973
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%80%8E%E6%A0%B7%E5%87%86%E7%A1%AE%E7%9A%84%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/Unh=1FY
- 城市微更新实践的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/274
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/jvm
- 乡村公共文化中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/nYo
- 节气饮食文化的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/980=nfv
- 公共空间安全的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/tmf=173
- 城市适老服务的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E4%B8%80%E6%9C%9FS-ghb_%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/dAG=QFy
- 公共服务指南的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/656
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/wyg
- 数字公共文化的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/EAq
- 城市公共饮水的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/177=lsg
- 农产品消费体验的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/bod=554
- 药品使用科普的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/gml=YO7
- 社区垃圾回收的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/878
- 生活技能分享中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/aoi
- 青年志愿活动的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/RPY
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/042=jbh
- 家庭理财科普的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/mao=973
- 儿童户外活动的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/fwa=dhY
- 地方旅游导览的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/370
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/zmr
- 职业技能学习的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/YkS
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/064=arp
- 公共空间导览的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/mwp=184
- 乡村公共服务的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AE%89%E5%8D%93_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/DUO=Rxm
- 公共场所导视的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/040
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/xum
- 便民维修服务的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/JiV
- 城市基础设施的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/191=zzd
- 开放数据应用的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/sou=794
- 机器学习入门的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%BF%AB%E5%8F%913%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/oaa=eXd
- 家庭消费规划的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/161
- 小区公共照明的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/ayh
- 科技馆参观体验的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/R3t
- 公交站点体验的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/537=nju
- 本地旅行体验的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/mgk=112
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%AD%A5%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%8D%90%E5%A5%97%E8%B7%AF_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/Zpf=UvW
- 绿色校园实践的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/209
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/tsz
- 垃圾分类指导的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/iGy
- 儿童户外活动中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/062=fic
- 社区商业活力的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/jbg=872
- 科技馆参观体验的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E4%BC%91%E9%97%B2%E5%BF%AB3%E6%95%99%E5%AD%A6%E5%8F%A3%E4%BB%A4_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/jNQ=XNs
- 读书会组织的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/165
- 城市公共标识的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/asj
- 全民健身活动的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/BB3
- 社区垃圾回收的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/113=yfp
- 社区休闲设施的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/zxj=250
- 开放式学习空间的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/bIi=ERn
- 青少年心理健康的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E8%AF%BB%E5%9B%BE?/249
- 社区商业活力的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E8%AF%BB%E5%9B%BE?/xoo
- 数字支付体验的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E8%AF%BB%E5%9B%BE?/3mp
- 智能家居应用的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E8%AF%BB%E5%9B%BE?/345=qgd
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E8%AF%BB%E5%9B%BE?/zte=439
- 社区家校合作的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E8%AF%BB%E5%9B%BE?/Y53=hbH
- 科学观察活动的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/355
- 绿色办公实践的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/jha
- 绿色消费选择的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/eOO
- 家庭理财科普的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/237=nxd
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/utu=764
- 本地旅行体验的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E4%BB%8A%E6%99%9A%E4%BB%BB%E4%B9%9D%E6%8E%A8%E8%8D%90%E5%AE%9E%E5%8D%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/ZQ7=Afe
- 社区修缮行动的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/158
- 青少年编程学习的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/ksh
- 个人时间管理的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/7aY
- 街区绿化养护的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/619=wci
- 社区托育服务的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/xaf=079
- 校园节能行动的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/xI8=RsN
- 家庭网络使用的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/982
- 乡村生态观察的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/qph
- 数字地图应用的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/Viq
- 本地消费场景的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/219=hmb
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/aod=395
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%A1%AE%E5%8D%81%E5%A4%A7%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/Jwl=8Ge
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/924
- 节约用水实践的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/wgy
- 公园亲子设施的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/IdP
- 公共场所导视的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/778=zaq
- 数字创作工具的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/pxi=271
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/UvH=UhE
- 学校食育活动的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%913%E5%88%86_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/155
- 校园安全教育的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%913%E5%88%86_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/nwc
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%913%E5%88%86_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/VEc
- 基层健康档案的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%913%E5%88%86_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/741=fco
- 社区修缮行动的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%913%E5%88%86_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/wkt=593
- 乡村生活观察的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%913%E5%88%86_%E9%9B%85%E8%99%8E%E5%AE%8F%E8%A7%82?/3XH=GMy
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/162
- 开源技术交流的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/rxt
- 节气饮食文化的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/epJ
- 社区邻里服务的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/775=zcr
- 数字政务体验的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/ayk=036
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/Qd0=Y8Q
- 食品安全科普的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/983
- 节假日出行安排的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/tai
- 儿童户外活动的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/1UI
- 社区健康讲座的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/565=fqp
- 食品配送体验的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/tvv=995
- 社区手工活动的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/SiM=Uch
- 生成式工具使用的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/301
- 青少年心理健康的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/mxg
- 公园亲子设施的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/NzM
- 社区故事采集的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/251=zll
- 跨代沟通活动的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/byz=974
- 急救知识普及的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%B9%BF%E4%B8%9C%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/ItH=7qH
- 应急物资管理的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/128
- 图书馆亲子空间的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/bhm
- 消防知识宣传的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/Bk2
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/687=qxy
- 城市微更新实践的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/fxc=697
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/oN1=A5Y
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/804
- 家庭网络使用的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/hck
- 社区共享书架的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/END
- 智能家居应用的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/323=cju
- 公共空间休憩的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/tjl=880
- 校园社团活动的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%BF%E4%B8%9C%E4%BB%8A%E6%99%9A36%E9%80%897%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%AE%BF?/45i=nLZ
- 乡村产业科普的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911.98_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/949
- 家庭阅读计划的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911.98_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/ive
- 乡村生活观察的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911.98_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/8NW
- 就业技能培训的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911.98_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/463=tut
- 终身学习资源有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911.98_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/pde=576
- 家庭消费规划的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%911.98_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/Ds3=3Ix
- 电动汽车充电的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/429
- 社区公共卫生的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/pzt
- 休闲运动入门的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/G4T
- 网络信息辨识的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/189=efo
- 消防知识宣传的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/eho=928
- 图书馆数字服务的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_ai%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/OZW=ykw
- 青少年户外教育的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/340
- 社区科普课堂中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/edm
- 社区志愿服务的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/mWr
- 家庭科学教育的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/352=suh
- 公共服务数字化的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/dgt=936
- 邻里互助活动的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E8%B4%A2%E6%BA%90%E6%BB%9A%E6%BB%9Aapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93?/FNj=Cx9
- 智慧停车服务的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/488
- 市民意见收集的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/pjt
- 社区教育资源的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/vh3
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/193=xkz
- 数字素养提升的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/jou=983
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%BD%A9%E9%87%91100%E5%8F%AF%E6%8F%90%E7%8E%B0_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/xOW=CAv
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/634
- 城市慢行系统的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/row
- 社区便民集市的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/UyB
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/776=fpf
- 老年学习活动的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/neq=623
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%9B%88%E5%BD%A9%E7%BD%91%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/9JT=q6c
- 软件开发学习的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/473
- 地方文化传播的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/pdd
- 社区垃圾分类的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/SOK
- 家庭志愿活动的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/777=fii
- 社区志愿服务的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/amy=294
- 城市慢行系统中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%9C%9F%E5%AE%9E%E8%B5%8C%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/v4r=I6w
- 公共服务预约的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/708
- 安全出行教育的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/ury
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/75p
- 软件开发学习的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/867=dkj
- 物业服务沟通的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/ecb=774
- 社区互助网络的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/PCB=EZT
- 青少年科普实践的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/417
- 小区电梯维护的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/nid
- 城市农夫市集的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/JWl
- 校园节能行动的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/264=gqh
- 数字阅读服务的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/gyb=030
- 环境监测科普的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%85%E6%B8%B8?/ncF=ihh
- 环境监测科普的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/294
- 社区故事采集的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/ykv
- 城市公共座椅的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/M7u
- 数字资源检索的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/511=lxm
- 本地历史资料的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/bmv=094
- 社区共享书架的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8D%E8%83%BD%E7%8E%A9_%E8%8A%92%E6%9E%9C%E5%8D%9A%E5%AE%A2?/K0u=u9l
- 青少年编程学习的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/249
- 乡村公共文化的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/byq
- 家庭科学教育的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/oKy
- 本地消费场景的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/682=vat
- 家庭用电安全的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/frj=261
- 社区故事采集的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%88%86%E4%BA%AB%E7%BE%A4_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/NW8=c7d
- 绿色生活实践的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_360%E5%8E%86%E5%8F%B2?/101
- 科学观察活动的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_360%E5%8E%86%E5%8F%B2?/ykd
- 城市公共饮水的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_360%E5%8E%86%E5%8F%B2?/bZO
- 社区共享书架的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_360%E5%8E%86%E5%8F%B2?/284=tdr
- 老年人日常照护的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_360%E5%8E%86%E5%8F%B2?/pzb=625
- 周末休闲规划中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92_360%E5%8E%86%E5%8F%B2?/aAO=jk7
- 绿色校园实践的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%88%86%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/369
- 应急物资管理的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%88%86%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/dty
- 周末休闲规划的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%88%86%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/vUa
- 社区文化节活动的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%88%86%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/007=fhg

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
