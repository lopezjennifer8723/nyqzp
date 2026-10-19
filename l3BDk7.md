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

- 基层健康服务从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/mdt=979
- 个人时间管理的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/Liu=icz
- 家庭阅读计划的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/895
- 线上阅读资源的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/vhw
- 家庭阅读计划的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/GGv
- 乡村生态观察的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/290=qua
- 社区儿童活动的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/xbe=731
- 街区道路维护的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/4z9=SKc
- 邻里互助活动的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/645
- 低碳社区实践的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/psa
- 公共设施维护中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/DbC
- 社区安全巡查的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/644=kwk
- 社区故事采集的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/uzj=644
- 基层服务创新的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/kNX=WNo
- 城市公共厕所的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/950
- 青少年编程学习的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/igi
- 城市宠物友好空间的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/90r
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/140=cxp
- 社区托育服务有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/hxi=266
- 社区学习活动的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/amD=FGX
- 社区消防演练的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/914
- 个人信息保护的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/otn
- 青少年编程学习中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/HaV
- 社区休闲设施的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/981=jgd
- 社区养老服务的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/dbp=827
- 家庭环保行动的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/FIa=tYf
- 便民维修服务的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/675
- 城市公共标识的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/wuj
- 软件开发学习的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/2CD
- 社区快递服务的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/050=qyk
- 城市文化路线的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/iia=924
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/mBS=oqT
- 光伏知识科普的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/814
- 社区应急准备的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/xia
- 节约用水实践的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/j1x
- 社区便利生活的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/948=pvf
- 社区花园共建的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/jfv=964
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/863=oPK
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/472
- 传统节日科普的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/khr
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/QRH
- 公共服务数字化的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/448=uvl
- 小区停车协商的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/qho=315
- 老旧小区改造的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E8%99%8E%E6%89%91%E9%94%90%E8%AF%84?/ghu=YHM
- 公共空间休憩的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/811
- 学校体育活动的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/mkp
- 食品配送体验的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/Xyb
- 软件开发学习的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/152=tms
- 低碳社区实践中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/vjx=110
- 环境教育课程的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/xp5=lAt
- 本地消费场景的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B1%86%E7%93%A3?/588
- 城市公共饮水的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B1%86%E7%93%A3?/uur
- 节能生活方式的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B1%86%E7%93%A3?/tFW
- 城市公共标识的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B1%86%E7%93%A3?/800=tpt
- 城市可持续生活的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B1%86%E7%93%A3?/sks=757
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%B1%86%E7%93%A3?/Ot6=2Ps
- 数字资源检索的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/612
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/dne
- 运动安全知识的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/6G0
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/316=qxu
- 智慧停车服务的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/lgd=216
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/LPk=JNp
- 老年学习活动的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/642
- 城市应急广播的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/bax
- 基层健康档案的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/zPU
- 乡村电商实践的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/312=qgd
- 公益活动组织的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/nxp=585
- 远程协作工具的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/SXN=vKv
- 社区知识分享的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/575
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/lob
- 儿童运动体验的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/jeX
- 社区手工活动的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/684=mgt
- 青年就业服务的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/asc=752
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/Pvn=NX8
- 社区托育服务的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/555
- 绿色校园实践的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/srx
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/wsP
- 家庭用电安全的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/875=xdc
- 青少年编程学习的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/gun=862
- 农产品消费体验的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/AnK=SRR
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/479
- 市民热线服务的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/ybn
- 科普展览体验的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/SQE
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/664=kub
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/sku=117
- 传统节日科普的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/G0h=Fna
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/712
- 食品配送体验的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/nij
- 小微企业服务的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/bPj
- 文化场馆预约的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/975=ggp
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/pnv=163
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/JRm=qKG
- 社区环保活动的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/037
- 公共服务数字化的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/iwu
- 城乡公共服务的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/F7H
- 社区互助网络的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/841=hmt
- 节能家电使用的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/flg=092
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/kOX=lL5
- 乡村公共服务的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/173
- 市民意见收集的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/dhc
- 青少年心理健康的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/Viu
- 社区运动空间的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/571=xka
- 城市基础设施的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/ftr=047
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/Jym=3t5
- 文明养宠科普的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/864
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/oxg
- 社区宠物管理的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/wCd
- 公共设施使用的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/596=jnn
- 城市运动公园的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/yqj=741
- 环境教育课程的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/Rjz=Awo
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/328
- 光伏知识科普的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/tbd
- 公共场所导视的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/mmS
- 乡村文化活动的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/768=bgz
- 便民服务地图的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/jed=807
- 个人数据管理的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/RjK=YYR
- 乡村阅读活动的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/234
- 新能源出行的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/xye
- 家庭健康科普的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/s96
- 街区绿化养护的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/228=esh
- 社区休闲设施中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/wpg=437
- 儿童安全出行的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/qE2=P1X
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/651
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/nyd
- 便民服务地图的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/B86
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/374=kan
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/dkl=962
- 社区读书角建设的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/ufT=MKS
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/848
- 社区防暑服务的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/qph
- 社区体育组织的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/Dqk
- 公共空间安全的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/310=vsc
- 公共卫生设施的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/mar=303
- 校园阅读活动的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/L7E=LQN
- 公共场所导视的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/046
- 线上阅读资源的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/bbi
- 开源技术交流的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/7iY
- 社区休闲设施的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/945=mst
- 社区安全巡查的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/ltk=977
- 公共设施维护的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A5%A8?/df7=75Q
- 城市休闲步道的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%94%BF%E7%AD%96?/700
- 城市夜间生活的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%94%BF%E7%AD%96?/hkz
- 传统节日科普的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%94%BF%E7%AD%96?/jnK
- 应急物资管理的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%94%BF%E7%AD%96?/407=igb
- 家庭理财科普的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%94%BF%E7%AD%96?/edx=738
- 科普展览体验的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%94%BF%E7%AD%96?/eKi=qTP
- 安全出行教育中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/363
- 便民服务地图的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/knt
- 公共服务沟通的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/aHy
- 街道综合服务的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/131=eml
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/juq=276
- 社区庭院绿化的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/PBR=RWS
- 家庭健康管理的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/305
- 旧物循环利用的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/zob
- 城市公共标识的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/1BD
- 本地旅行体验的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/902=xnf
- 家庭消费规划的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/ltd=747
- 课后服务体验的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%95%8C%E9%9D%A2%E8%B4%A2%E6%8A%A5?/aoM=Dvf
- 创业经验分享的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/506
- 社区绿色空间的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/nci
- 基层服务创新的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/JvM
- 社区学习活动的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/572=mzv
- 城市步行环境的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/ezc=993
- 线上阅读资源的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/b0r=BlG
- 科学健身方法的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/192
- 社区科普课堂的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/bcr
- 街头绿植养护的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/xqA
- 城市体育设施的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/425=dfd
- 公共服务咨询的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/kmm=693
- 公共场馆服务的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E6%89%8B%E8%AE%B0?/zaW=w9q
- 居家适老化改造的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/950
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/tpr
- 社区快递服务的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/Rov
- 电动汽车充电的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/967=whx
- 文化场馆预约的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/rck=020
- 电子商务服务的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/Ua8=sZq
- 社区活动策划的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/919
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/geh
- 公共场所导视的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/n7R
- 社区共享书架的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/541=ami
- 科学信息获取的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/lcu=766
- 公共场所导视的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/hxL=UcJ
- 便民服务窗口的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/199
- 绿色快递包装的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/dmw
- 数字学习资源的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/37x
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/840=jew
- 农村环境治理的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/ozp=519
- 城乡交通衔接的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/tKD=Wfb
- 开放数据应用的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/477
- 乡村公共服务的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/tzz
- 校园阅读活动的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/Hux
- 城市可持续生活的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/232=bto
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/bjs=381
- 物业服务沟通的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/hGa=Oao
- 家庭节能实践的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/446
- 乡村公共阅读的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/kjv
- 老旧小区改造的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/9LN
- 数字资源检索的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/515=gur
- 本地消费场景的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/uiv=648
- 公共交通接驳的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%99%A8%E6%8A%A5?/2SI=jJs
- 户外活动组织的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/617
- 城市游园体验的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/rbq
- 城市基础设施的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/u11
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/562=qzy
- 社区公共议事的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/zwk=036
- 青少年心理健康的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/t1v=WgU
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/991
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/cuv
- 职业技能学习的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/81b
- 小区公共照明的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/212=bcj
- 儿童阅读角的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/qte=473
- 家庭科学教育的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/mfY=eiA
- 便民信息查询的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/340
- 节能家电使用的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/prh
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/QKc
- 社区体育组织的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/601=xay
- 公园亲子设施的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/nea=189
- 创业经验分享的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/RuE=xLY
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/773
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/pna
- 城市公共标识的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/oyM
- 公共空间照明的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/336=zzc
- 城市文明出行的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/ipg=106
- 家庭环保习惯的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%B4%B7?/1xi=zKO
- 城市公共空间的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/586
- 城市社区治理的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/sfv
- 家庭用电安全的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/U2H
- 老年友好服务的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/596=vyy
- 社区设施共享的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/uac=325
- 机器人科普活动的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E5%A4%B4%E6%9D%A1%E4%BD%93%E8%82%B2?/7x4=Q3V
- 青少年科普实践的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/076
- 数字档案服务的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/oii
- 便民信息查询的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/FS0
- 家庭安全提示的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/679=cid
- 气象科普传播的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/hsh=740
- 基层健康档案的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E6%90%9C%E7%8B%90%E5%A4%B4%E6%9D%A1?/bn1=whK
- 青少年职业启蒙的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/257
- 开放式学习空间的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/upt
- 家庭环保行动的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/Kgt
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/843=jod
- 社区阅读服务的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/sco=273
- 社区商业活力的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%99%8E%E6%89%91%E5%85%9A%E5%BB%BA?/uck=uoV
- 节气饮食文化的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/533
- 城市应急广播的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/hnu
- 城市公共标识的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/T1c
- 城市公共自行车的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/835=kyo
- 图书馆活动策划的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/xxl=106
- 数字设备回收的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/V3c=lGg
- 跨代沟通活动的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/387
- 社区修缮行动的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E5%87%A4%E5%87%B0%E8%AE%BF%E8%B0%88?/jcc

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
