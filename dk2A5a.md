# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 城市可持续生活的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/Rt6
- 家庭节能设备的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/904=cmf
- 食品配送体验的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/esp=540
- 社区交通安全的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%83%AD%E7%82%B9?/p4h=rPA
- 公共场馆服务的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/981
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/gsz
- 社区公共餐饮的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/ZaW
- 社区快递服务的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/973=vfb
- 老旧小区改造的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/asm=409
- 家庭理财科普的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/TON=Fla
- 本地消费场景的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/278
- 公益活动组织的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/oau
- 老年人日常照护的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/eGu
- 公共服务评价的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/812=ojt
- 健康信息获取的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/nto=870
- 社区信息发布的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9?/XwT=732
- 新能源知识普及的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/531
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/vgn
- 线上办事服务的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/SQQ
- 日常摄影记录的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/164=znd
- 本地旅行体验的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/fqi=725
- 社区文化传播的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/N5K=Qmx
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/283
- 电子商务服务的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/fpy
- 城市生活记录的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/7DO
- 社区公共餐饮的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/834=iiv
- 城市应急科普的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vdi=295
- 城市绿道建设的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/RiM=Sth
- 开源技术交流的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/492
- 居民健康教育的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/gty
- 城市水环境观察的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/eYT
- 便民服务窗口的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/231=wxq
- 校园节能行动的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/vrp=712
- 公共服务评价的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%9D%E9%99%A9?/Ygr=TWy
- 科学健身方法的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/596
- 青少年编程学习的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/saq
- 创业经验分享的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/Esx
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/646=rhb
- 乡村文化活动的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/aei=912
- 家庭环保习惯的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/Jl8=FuQ
- 图书馆活动策划的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/465
- 城市夜间照明的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/nmd
- 社区养老服务的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/5od
- 街区绿化养护的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/873=rdp
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/kbe=347
- 家庭安全提示的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%B8%E5%95%86?/I7W=dxU
- 社区垃圾回收的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/733
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/ngk
- 公共空间安全的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/SbV
- 乡村产业科普的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/115=qrv
- 绿色出行服务的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/pjv=028
- 社区垃圾分类的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%98%9F%E5%BA%A7?/HSu=vDR
- 农贸市场环境的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/560
- 社区邻里服务的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/wjw
- 公共健身器材的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/FmI
- 城市生活记录的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/271=bhz
- 老旧小区改造的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/mto=594
- 线上阅读资源的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/dox=jVy
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/133
- 数字档案服务的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/dfu
- 绿色办公实践的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/kdz
- 科学观察活动的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/407=faa
- 社区商业活力的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/vzg=605
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/5nq=ctX
- 城市步行友好的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%88%B8%E5%95%86?/199
- 数字艺术创作的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%88%B8%E5%95%86?/wdq
- 全民健身活动的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%88%B8%E5%95%86?/azv
- 环境教育课程的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%88%B8%E5%95%86?/001=nkf
- 城市社区治理的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%88%B8%E5%95%86?/ttt=699
- 社区儿童活动的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%88%B8%E5%95%86?/MYm=DBk
- 城市步行友好的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/692
- 城市游园体验的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/qbn
- 校园节能行动的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/UqP
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/487=xse
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/qng=897
- 城市树木认养的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/43P=A5i
- 老年人文化生活的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/842
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/wfd
- 社区养老服务的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/G1F
- 社区快递服务的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/011=vny
- 青少年心理健康的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/rpg=746
- 农贸市场环境的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%99%9A%E6%8A%A5?/dTG=imF
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/084
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/zyp
- 社区手工活动的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/c4I
- 城市公共自行车的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/903=xnm
- 健康信息获取的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/qdz=428
- 数字阅读服务的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/6Pf=SXe
- 无障碍出行的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/517
- 城市雨天出行的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/ciz
- 个人信息保护的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/35i
- 街区小店体验的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/371=mje
- 科技馆参观体验的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/wwa=523
- 居民健康教育的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/gJn=VFv
- 乡村公共文化的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/256
- 家庭健康科普的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/zqz
- 社区手工活动的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/QjB
- 城市基础设施的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/343=rna
- 老旧小区改造的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/iij=028
- 户外活动组织的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/oNn=uMr
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/414
- 社区托育服务的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/kar
- 亲子科普活动的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/ZLM
- 科学观察活动的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/392=ziq
- 家庭健康管理中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/pzu=044
- 通勤路线规划的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/IOa=lQN
- 乡村教育资源的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/301
- 社区协商议事的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/smn
- 软件开发学习的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/7eh
- 社区设施共享的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/731=fcg
- 数字档案服务的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/eos=378
- 社区共享书架的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/tCB=O37
- 社区应急准备的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/986
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/iru
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/sAS
- 乡村阅读活动的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/436=ted
- 绿色生活实践的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/srf=959
- 学校食育活动的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vNf=OE2
- 家庭用电安全的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/937
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/mne
- 数字设备回收的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/7AV
- 社区活动空间的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/392=src
- 社区阅读服务的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/gwr=520
- 节气饮食文化的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/xwq=lzB
- 社区家政服务的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/731
- 公共服务数字化的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/gbn
- 读书会组织的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/5Wk
- 信息无障碍体验的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/479=anf
- 家庭急救准备的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/wsd=307
- 青年就业服务的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/ITA=BrO
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%8E%86%E5%8F%B2?/200
- 科学运动指导的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%8E%86%E5%8F%B2?/yvr
- 课后服务体验的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%8E%86%E5%8F%B2?/yBb
- 街区小店体验的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%8E%86%E5%8F%B2?/300=apw
- 家庭理财科普的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%8E%86%E5%8F%B2?/fuh=312
- 地方文化传播的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%8E%86%E5%8F%B2?/4nJ=o9c
- 市民意见收集的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/767
- 智能家居应用的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/szq
- 公共文化活动的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/0Pq
- 青年职业探索的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/665=cye
- 日常摄影记录的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/ktk=789
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/sBS=wEK
- 社区文化传播的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/024
- 社区公共餐饮的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/jyr
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/leH
- 社区共享书架的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/737=npb
- 街区小店体验的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/fpo=318
- 居家适老化改造的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/z4k=2eU
- 街区绿化养护的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/151
- 城市步行环境的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/jnk
- 城市建设科普的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/hIL
- 在线学习体验的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/965=onj
- 邻里互助活动的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/exx=040
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/TGt=uwf
- 电动汽车充电的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/831
- 便民维修服务的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/nex
- 创业经验分享的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/kQU
- 数字课堂应用的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/925=tur
- 劳动教育实践的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/nph=148
- 儿童友好空间的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/hU8=eh1
- 公共场馆服务的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2?/416
- 急救知识普及的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2?/mwm
- 志愿服务平台的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2?/AYn
- 城市人文观察的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2?/208=qbl
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2?/fzx=090
- 社区修缮行动的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2?/J4P=ui1
- 家庭阅读计划的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/999
- 老年人出行服务的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/djc
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/sWZ
- 骑行路线规划中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/241=hia
- 本地历史资料的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/esy=513
- 城市文明实践的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/rwD=a6A
- 社区学习活动的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/928
- 公共服务指南的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/utv
- 便民维修服务的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/Rxs
- 街区更新实践的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/966=jty
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/hum=346
- 城市微更新实践的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/uSZ=T7B
- 校园阅读活动的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/500
- 读书会组织从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/ayj
- 公共卫生设施的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/eKf
- 城乡交流活动的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/966=zxm
- 公共设施维护的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/xqr=249
- 基层健康档案的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/5ew=kgh
- 社区商业活力的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/275
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/csj
- 校园社团活动的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/9MC
- 城市夜间照明的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/911=daj
- 口袋公园建设的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/eov=702
- 社区生活指南中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/9r2=eq3
- 医院导诊服务的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/726
- 家庭防灾准备的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/ovk
- 社区便利生活的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/wnc
- 社区体育组织的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/719=mgz
- 就业技能培训的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/ndr=264
- 乡村文化活动的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%9B%B2%E8%89%BA?/zRk=37M
- 健康饮水科普的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/465
- 数字课堂应用的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/vyj
- 校园社团活动的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/Wm4
- 社区志愿服务的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/718=rtf
- 青少年心理健康的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/fqe=133
- 老旧小区改造的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/Nzk=6pS
- 数字生活课堂的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/516
- 数字便民地图的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/ykt
- 数字资源检索的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/i0z
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/059=qxa
- 邻里互助活动的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/dfs=853
- 公共服务指南的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/TLe=ItY
- 城市公共座椅的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/799
- 乡村教育资源中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/zpa
- 创业经验分享的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/8le
- 科普展览体验的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/788=goo
- 居家防滑改造的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/obw=079
- 旧物循环利用的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/5K9=neb
- 地方旅游导览的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/508
- 街区小店体验的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/pct
- 社区信息发布的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/Eih
- 数字地图应用的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/156=mho
- 家庭教育交流的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/wws=422
- 社区菜市场服务的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/R7X=1Mf
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7?/282
- 社区托育服务的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7?/pek
- 基层健康服务的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7?/SIS
- 家庭食品保存的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7?/131=ruj
- 青少年科普实践的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7?/bwu=632
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7?/H3z=7im
- 居民健康教育的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/617
- 城市生活服务的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/bsv
- 城市文明出行的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/13z
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/062=pct
- 在线学习体验的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/oto=637
- 乡村公共文化中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/Heg=O1O
- 城市人文观察的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/987
- 全民健身活动的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/yng
- 社区儿童活动的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/v3R
- 校园节能行动的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/256=gvo
- 家庭理财科普的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/ebw=314
- 数字支付体验的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/KsV=Sfx
- 家庭运动计划的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/461
- 校园节能行动的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/eev
- 校园安全教育的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/YHL
- 老年人出行服务的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/248=drw
- 城市社区治理的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/ode=420
- 线上阅读资源的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/Z7Y=5Xk
- 科学运动指导的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/972
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/fhl
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/AFF
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/541=qja
- 线上办事服务的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/utx=612
- 家庭消费规划的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/7pF=fhP

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
