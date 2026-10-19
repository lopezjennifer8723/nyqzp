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

- 全民健身活动的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_pc28%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/645
- 校园安全教育的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_pc28%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/ezr
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_pc28%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/k0s
- 跨代沟通活动的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_pc28%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/973=shf
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_pc28%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/uzs=450
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_pc28%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/yBd=5om
- 儿童安全出行的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/115
- 市民热线服务的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/snc
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/MqO
- 节约用水实践的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/915=aku
- 健康步道使用中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/dfw=899
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E5%BF%AB%E6%89%8B%E6%98%9F%E5%BA%A7?/htm=FNx
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2025%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E6%96%99%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/740
- 老年数字阅读的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2025%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E6%96%99%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/gch
- 农产品消费体验的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2025%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E6%96%99%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/y3b
- 绿色出行服务的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2025%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E6%96%99%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/939=qfw
- 公共服务咨询的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2025%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E6%96%99%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/glt=560
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2025%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9%E6%96%99%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/E2A=ny9
- 个人信息保护的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_p%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/938
- 家庭健康管理的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_p%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/osp
- 小区停车协商的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_p%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/fDH
- 家庭养老规划的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_p%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/345=dkl
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_p%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/rbb=655
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_p%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/xdJ=oqL
- 居民健康教育的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/126
- 城市可持续生活的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/rnd
- 城市地名文化的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/voa
- 个人时间管理的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/021=eqk
- 食品安全科普的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/pzb=982
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%9F%B3%E4%B9%90?/zCA=lar
- 城市便民驿站的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_PC28%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/785
- 骑行路线规划的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_PC28%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/ads
- 儿童安全出行的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_PC28%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/2dR
- 数字学习资源的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_PC28%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/774=lxw
- 科学信息获取的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_PC28%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/sqw=143
- 家庭急救准备的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_PC28%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E6%BE%8E%E6%B9%83%E5%85%AC%E7%9B%8A?/EOy=4iJ
- 无障碍信息设计的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E5%A4%A7%E6%9E%81%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/255
- 科学信息获取的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E5%A4%A7%E6%9E%81%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/dtx
- 城市公共饮水的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E5%A4%A7%E6%9E%81%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/pUe
- 开放数据应用的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E5%A4%A7%E6%9E%81%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/121=iiv
- 家庭健康管理的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E5%A4%A7%E6%9E%81%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/qcq=475
- 城市文化路线的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9E%81%E5%A4%A7%E6%9E%81%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90_%E6%90%9C%E7%8B%90%E7%A7%91%E6%8A%80?/I4h=KtL
- 公园亲子设施的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_pc28%E6%9C%9F%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%8798%25_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/979
- 户外活动组织的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_pc28%E6%9C%9F%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%8798%25_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/lim
- 网络信息辨识的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_pc28%E6%9C%9F%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%8798%25_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/mm6
- 线上办事服务的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_pc28%E6%9C%9F%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%8798%25_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/241=rqx
- 儿童阅读角中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_pc28%E6%9C%9F%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%8798%25_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/aji=351
- 节日文化体验的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_pc28%E6%9C%9F%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%8798%25_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/BY8=4hq
- 城市公共饮水的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/582
- 社区互助网络的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/fbd
- 城市农夫市集的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/92o
- 智能手机助老的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/251=cox
- 公益活动组织的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/oul=032
- 社区快递服务中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/w6q=Nwd
- 城市雨天出行的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/063
- 城市住房服务的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/iid
- 智能家居应用的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/UQG
- 儿童友好空间的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/947=fmw
- 城市公共艺术的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/ueg=933
- 校园社团活动的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/ATO=Ek1
- 旧物循环利用的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E9%BC%8E%E4%BF%A1%E9%A2%84%E6%B5%8B_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/108
- 新能源出行的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E9%BC%8E%E4%BF%A1%E9%A2%84%E6%B5%8B_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rts
- 消防知识宣传的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E9%BC%8E%E4%BF%A1%E9%A2%84%E6%B5%8B_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Xgb
- 数字艺术创作的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E9%BC%8E%E4%BF%A1%E9%A2%84%E6%B5%8B_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/306=hip
- 家庭运动计划的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E9%BC%8E%E4%BF%A1%E9%A2%84%E6%B5%8B_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jbr=490
- 城市文明实践的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_pc28%E9%BC%8E%E4%BF%A1%E9%A2%84%E6%B5%8B_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zth=6tR
- 在线教育体验中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/140
- 智慧城市体验的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/gpe
- 本地消费场景的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/fFB
- 数字创意课程的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/148=ntm
- 食品配送体验的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/wzm=110
- 社区协商议事的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E9%97%AE%E5%8D%B7?/yTq=Zlc
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/352
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/uoy
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/zAC
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/224=kvo
- 安全出行教育的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/xvy=922
- 科学运动指导从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8PC%E9%A2%84%E6%B5%8B_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/PqL=o0q
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C%5B%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/680
- 亲子科普活动的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C%5B%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/snl
- 社区快递服务的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C%5B%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/dUd
- 农村环境治理的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C%5B%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/219=hzx
- 社区文化节活动的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C%5B%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/qws=684
- 社区垃圾分类的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C%5B%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E5%BF%85%E5%BA%94%E8%AF%BB%E6%8A%A5?/KSm=QA4
- 科学教育活动的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_28%E7%A5%9E%E9%80%9A%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/808
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_28%E7%A5%9E%E9%80%9A%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/ysd
- 基层健康服务的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_28%E7%A5%9E%E9%80%9A%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/LR8
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_28%E7%A5%9E%E9%80%9A%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/478=uav
- 老年数字阅读中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_28%E7%A5%9E%E9%80%9A%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/xir=790
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_28%E7%A5%9E%E9%80%9A%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/QWe=Cbv
- 公共服务预约的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/723
- 创业经验分享的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/vpm
- 公共空间休憩的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/5II
- 家庭急救准备的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/641=pwi
- 数字政务体验的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/ecx=171
- 城市基础设施的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/v8w=2Cd
- 乡村阅读空间的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%BB%91%E9%A9%AC%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/097
- 家庭饮食安排的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%BB%91%E9%A9%AC%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/cai
- 个人信息保护的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%BB%91%E9%A9%AC%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/vyM
- 新能源知识普及的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%BB%91%E9%A9%AC%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/735=zsr
- 户外活动组织的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%BB%91%E9%A9%AC%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/hmi=983
- 基层健康档案的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%BB%91%E9%A9%AC%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/3S5=vsS
- 城市空气科普的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%9128pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/098
- 数字档案服务中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%9128pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/nhk
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%9128pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wD2
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%9128pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/556=hyv
- 垃圾分类指导的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%9128pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vxn=937
- 家庭饮食安排的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%9128pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%AE%A1%E5%88%92app_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/cmS=C5C
- 周末休闲规划的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%88%98%E7%8B%BCpc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/058
- 社区艺术活动的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%88%98%E7%8B%BCpc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/xyl
- 城市公共自行车的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%88%98%E7%8B%BCpc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/Z7u
- 青少年科普实践的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%88%98%E7%8B%BCpc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/811=oak
- 社区环保活动的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%88%98%E7%8B%BCpc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/ckh=779
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%88%98%E7%8B%BCpc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%88%86%E6%96%99?/gEu=8Db
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/857
- 公共文化活动的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/bey
- 健康饮水科普的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/sG0
- 老年人出行服务的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/426=sil
- 医院导诊服务的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/sis=602
- 城市步行环境的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%89%B9%E7%A8%BF?/r7T=1M6
- 社区垃圾回收的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%8D%95%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/968
- 社区托育服务的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%8D%95%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/jpz
- 社区文化传播的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%8D%95%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/riI
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%8D%95%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/544=lzr
- 灵活就业交流的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%8D%95%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/kij=925
- 软件开发学习的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E5%8D%95%E6%9C%9F%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/YQR=KhZ
- 校园阅读活动的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/671
- 家庭科学教育的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/qad
- 数字便民地图的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/cN8
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/263=dcg
- 开放数据应用的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/xxh=437
- 数字创作工具的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/PVd=GAn
- 居家适老化改造的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/000
- 儿童安全出行的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/bke
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/Xcr
- 青年就业服务的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/998=gnl
- 城市应急广播的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/wmq=462
- 社区法律科普的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%B9%B6%E8%B4%AD?/7OE=3wj
- 城市适老服务的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/732
- 运动安全知识的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/wso
- 数字素养提升的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/ptW
- 科技馆参观体验的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/767=upf
- 老年数字阅读的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/lni=217
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/Eed=9wS
- 社区安全巡查的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/069
- 药品使用科普的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/ixq
- 社区环保活动的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/ycB
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/081=cye
- 非遗课堂体验的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/ozh=047
- 社区生活指南的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/5BU=UG6
- 家庭志愿活动的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F%E5%A4%A7%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/129
- 消防知识宣传的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F%E5%A4%A7%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/cjy
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F%E5%A4%A7%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/X6Z
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F%E5%A4%A7%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/451=azx
- 街区小店体验的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F%E5%A4%A7%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/dpt=334
- 社区停车服务的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E6%A8%A1%E5%BC%8F%E5%A4%A7%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%AE%BF?/zjM=wac
- 传统节日科普的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E7%9F%AD%E6%9C%9F%E8%AE%A1_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/712
- 家庭科学教育的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E7%9F%AD%E6%9C%9F%E8%AE%A1_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/tzn
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E7%9F%AD%E6%9C%9F%E8%AE%A1_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/j1N
- 老旧小区改造的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E7%9F%AD%E6%9C%9F%E8%AE%A1_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/553=qua
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E7%9F%AD%E6%9C%9F%E8%AE%A1_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/dzn=042
- 城市博物馆服务的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E7%9F%AD%E6%9C%9F%E8%AE%A1_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/SZ3=dtR
- 社区健康讲座的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%90%8D%E7%88%B5app%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/388
- 城市水环境观察的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%90%8D%E7%88%B5app%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/trg
- 社区活动报名的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%90%8D%E7%88%B5app%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/3Lu
- 乡村公共服务的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%90%8D%E7%88%B5app%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/303=arw
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%90%8D%E7%88%B5app%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/beo=712
- 家庭收纳实践的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%90%8D%E7%88%B5app%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E5%8D%B3%E5%88%BB%E9%80%9A%E4%BF%A1?/y53=C4A
- 城市夜间照明的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_168%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%90%9C%E7%8B%90%E6%B3%95%E6%B2%BB?/611
- 公共卫生设施的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_168%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%90%9C%E7%8B%90%E6%B3%95%E6%B2%BB?/rfu
- 城市便民驿站的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_168%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%90%9C%E7%8B%90%E6%B3%95%E6%B2%BB?/X5A
- 物业服务沟通的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_168%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%90%9C%E7%8B%90%E6%B3%95%E6%B2%BB?/780=kxo
- 基层健康服务的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_168%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%90%9C%E7%8B%90%E6%B3%95%E6%B2%BB?/vmk=774
- 社区家校合作的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_168%E5%B9%B8%E8%BF%90pk10%E9%A3%9E%E8%89%87_%E6%90%9C%E7%8B%90%E6%B3%95%E6%B2%BB?/KQ8=F3a
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/656
- 网络信息辨识的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/dfj
- 社区老年食堂的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/ff3
- 图书馆活动策划的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/145=rrv
- 社区绿色空间的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/bpa=554
- 公园无障碍服务的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/wOv=WVs
- 便民维修服务的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/877
- 远程协作工具的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/bju
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/RIn
- 街区小店体验的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/047=scz
- 非遗体验活动的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/bla=811
- 公共设施维护的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/R3L=HBT
- 小微企业服务的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E4%BD%99%E6%95%B0%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/830
- 邻里互助活动的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E4%BD%99%E6%95%B0%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/wxf
- 无障碍信息设计的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E4%BD%99%E6%95%B0%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/Nt5
- 城市步行友好的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E4%BD%99%E6%95%B0%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/265=fwq
- 课后服务体验的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E4%BD%99%E6%95%B0%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/dhx=397
- 邻里共享空间的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E4%BD%99%E6%95%B0%E9%A2%84%E6%B5%8B_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/i0P=4VO
- 社会体育指导的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/199
- 家庭志愿活动的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/goo
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/7Ui
- 周末休闲规划的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/249=fyv
- 公益活动组织的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/wsz=160
- 家庭健康科普的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E7%99%BE%E5%BA%A6%E6%B1%BD%E8%BD%A6?/mP8=Rnj
- 基层服务创新的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%902.8%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/658
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%902.8%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/hou
- 文化讲座服务的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%902.8%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/mGh
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%902.8%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/415=rsf
- 光伏知识科普的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%902.8%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/dmq=078
- 城市微更新实践的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%902.8%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/ykK=Fhl
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/448
- 青年职业探索的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/flm
- 儿童友好空间的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/bfv
- 城市博物馆服务的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/738=oes
- 公共服务评价的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/evm=784
- 社区生活指南的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/Pov=4cW
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/313
- 家庭消费规划的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/vxa
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/o51
- 城市运动公园的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/229=eyx
- 社区科普课堂中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/pal=804
- 非遗体验活动的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/pPQ=lXu
- 生活垃圾回收的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/924
- 家庭照护支持的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/imo
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/hAp
- 社区防暑服务的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/361=xbs
- 城市公共标识的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/bat=035
- 城市文明出行的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/xca=DWD
- 社区互助网络的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/952
- 社区知识分享的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/wdo
- 乡村产业科普的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/BCf
- 城市公共厕所的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/680=wxn
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/czu=880
- 社区便民集市的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/dXP=Ev2
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028PC%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/540
- 健康饮水科普的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028PC%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/vmt
- 城市农夫市集的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028PC%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/baI
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028PC%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/944=zwn
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028PC%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/yeq=910
- 智慧停车服务的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9028PC%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E6%89%8B%E8%AE%B0?/iEC=039
- 城市公共艺术的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028pc%E8%AF%B8%E8%91%9B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/132
- 居民健康教育的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028pc%E8%AF%B8%E8%91%9B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/ury
- 公共卫生宣传的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028pc%E8%AF%B8%E8%91%9B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/YX5
- 城市慢行系统的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028pc%E8%AF%B8%E8%91%9B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/178=fzv
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028pc%E8%AF%B8%E8%91%9B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/owy=022
- 本地旅行体验的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028pc%E8%AF%B8%E8%91%9B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/6Yt=39x
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%9C%9B?/323
- 公共设施使用的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%9C%9B?/qvc
- 在线教育体验的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%9C%9B?/8BW
- 小区公共照明的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%9C%9B?/387=roi
- 数字课堂应用的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%9C%9B?/obm=331
- 小微企业服务的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%9C%9B?/xjx=zh7
- 数字生活课堂的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_pc%E8%9B%8B%E8%9B%8B%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/496
- 数字艺术创作的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_pc%E8%9B%8B%E8%9B%8B%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/smo
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_pc%E8%9B%8B%E8%9B%8B%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/6j9
- 便民服务窗口的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_pc%E8%9B%8B%E8%9B%8B%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E4%BF%A1%E8%B4%B7?/999=ekd

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
