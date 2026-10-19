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

- 图书馆活动策划的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/epo=370
- 邻里互助活动的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/p4o=tK6
- 公共场所导视中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/220
- 休闲运动入门的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/prk
- 开源技术交流的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/aCt
- 街区小店体验的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/875=tav
- 城市社区治理的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/fcs=507
- 科学信息获取的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E9%9D%A0%E8%B0%B1%E7%BE%A4%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/sHG=VtC
- 家庭节能设备的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/227
- 个人时间管理的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/lvg
- 小区公共照明的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/jPt
- 科学健身方法的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/968=cxn
- 社区商业活力的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/qzt=501
- 科技馆参观体验的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/ALZ=TuX
- 小微企业服务的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/798
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/avd
- 数字档案服务的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/3ds
- 新能源知识普及的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/796=rhr
- 健康信息获取的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/stp=755
- 网络信息辨识的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/x17=hjp
- 学校体育活动的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/765
- 小区停车协商的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/fgk
- 节气饮食文化的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/Pnp
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/647=dvq
- 社区生活指南中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/abl=383
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E7%A8%B3%E5%AE%9A%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/goF=OfD
- 城市空气科普的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/425
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/llu
- 城市公共艺术的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/wT1
- 无障碍信息设计的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/279=mhj
- 生活服务数字化的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/ngi=282
- 社区消防演练的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_75%E7%A7%92%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/6ez=GOy
- 社区托育服务的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/023
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/uvm
- 社区共享书架的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/YyE
- 家庭节能实践的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/020=wmw
- 节假日出行安排中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/afg=402
- 家庭用电安全的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/cTz=HrU
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/187
- 社区公共议事中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/dzw
- 创业经验分享的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/Yqi
- 社区协商议事的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/191=hqa
- 健康步道使用的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/sde=437
- 绿色建筑理念的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/Isj=LzJ
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8F%B7%E5%A4%96?/924
- 电动汽车充电的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8F%B7%E5%A4%96?/lwh
- 青少年科普实践的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8F%B7%E5%A4%96?/GOm
- 数字资源检索的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8F%B7%E5%A4%96?/379=phu
- 城市文明出行的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8F%B7%E5%A4%96?/oex=456
- 公共空间导览的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%8F%B7%E5%A4%96?/T84=FMZ
- 职业技能学习的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/005
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/tuw
- 城市夜间照明的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/M0T
- 社区慢性病防控的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/551=dsp
- 社区便民集市的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/fxg=599
- 乡村公共服务的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/6Gx=IrQ
- 在线教育体验的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/394
- 地方文化传播的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/ryt
- 农产品品牌传播的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/Sey
- 地方美食文化的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/540=bgw
- 数字学习资源的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/lzs=107
- 公共空间休憩的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E7%BE%A4_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/0ik=pd2
- 校园安全教育的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/422
- 跨代沟通活动的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/fwv
- 志愿服务平台的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/NHR
- 社区手工活动的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/928=stq
- 乡村文化空间的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/zgb=131
- 在线教育体验的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E5%80%8D%E7%BE%A4_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/Z8Q=A08
- 城市夜间生活的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/417
- 休闲运动入门的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/mwf
- 生成式工具使用的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/tA6
- 社区体育组织的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/068=bxs
- 家庭用电安全的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/gkb=653
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E8%83%BD%E6%BA%90?/Qky=OG8
- 本地旅行体验的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/386
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/cqc
- 城市体育设施的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/H8I
- 社区活动策划的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/985=spf
- 租房信息服务的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/yze=503
- 新能源出行的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E5%A4%A7%E7%BE%A4_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/DpT=5nP
- 数字地图应用的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/577
- 亲子阅读活动的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/kdi
- 家庭环保习惯的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/qwh
- 急救知识普及的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/641=zmg
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/axp=795
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/GCy=KVT
- 城市步行友好的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/203
- 城市空气科普的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/zml
- 城市建设科普的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/wrt
- 生活垃圾减量的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/813=sry
- 家庭网络使用的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/yqm=774
- 城市夜间照明的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_pK10%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/HE5=1ZZ
- 农产品消费体验的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/101
- 社区体育组织的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/ton
- 城市基础设施的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/V5C
- 公共交通接驳的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/908=bxg
- 城市雨天出行的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/lnj=405
- 智能手机助老的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E4%BD%93%E5%BD%A9%E8%B5%9B%E8%BD%A6168%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/mSc=bIp
- 终身学习资源的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/908
- 社区家校合作的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/wfa
- 基层健康档案的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/TOU
- 社区共享书架的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/058=nym
- 数字资源检索的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/uqr=388
- 街区小店体验的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%93%AA%E9%87%8C%E6%9C%89168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/1mt=HGk
- 健康饮水科普的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/730
- 城市夜间照明的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/law
- 社区志愿服务的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/fsE
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/479=jjm
- 地方文化传播的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/igq=165
- 乡村公共服务的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/7QJ=2pZ
- 城市适老服务的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/295
- 小区电梯维护的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/rll
- 骑行路线规划的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/fwE
- 公共空间安全的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/296=kra
- 公共场所导视的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/nie=863
- 基层服务创新的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8A%95%E5%B6%B6%E4%B8%83%E4%BA%94%E4%BA%8C%E5%9B%9B%E5%85%AD%E9%9B%B6%E4%BA%94_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/sLq=zWv
- 社区应急准备有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/555
- 健康饮水科普的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/nyy
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/qss
- 社区便利生活的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/462=mit
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/umx=100
- 城市步行环境的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/2aR=52e
- 公共空间休憩的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/798
- 城市建设科普中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/jin
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/xge
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/820=xta
- 人工智能科普的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/ity=793
- 社区修缮行动的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6pK10%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/M5K=yGk
- 社区垃圾回收的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/063
- 社区设施共享的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/gkm
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/EbR
- 智慧停车服务的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/808=cej
- 老年运动活动的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/nup=072
- 数字艺术创作的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/LSU=Ug1
- 个人信息保护的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_36%E6%B0%AA%E8%AE%BA%E5%9D%9B?/182
- 街区更新实践的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_36%E6%B0%AA%E8%AE%BA%E5%9D%9B?/pyc
- 城市基础设施的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_36%E6%B0%AA%E8%AE%BA%E5%9D%9B?/U7B
- 城市博物馆服务的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_36%E6%B0%AA%E8%AE%BA%E5%9D%9B?/058=jmj
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_36%E6%B0%AA%E8%AE%BA%E5%9D%9B?/xab=259
- 社区便民集市的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81_36%E6%B0%AA%E8%AE%BA%E5%9D%9B?/Bqj=LpA
- 公共服务数字化的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/014
- 街头绿植养护的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/mse
- 社区应急准备的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/xZO
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/154=hgr
- 数字生活课堂的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/vcv=231
- 个人时间管理的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87pK10%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/5yZ=d84
- 读书会组织从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/055
- 城市人文观察的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/hge
- 校园安全教育的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/6iI
- 社区教育资源的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/788=nyc
- 灵活就业交流的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/ujg=519
- 城市微更新实践的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_Pk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/XsQ=Dnz
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/322
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/kgm
- 社区家政服务中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/7MS
- 城市公共厕所的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/685=poe
- 药品使用科普的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/dkh=472
- 绿色生活实践的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_pK10%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/boX=mF1
- 科学信息获取的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pK10%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/982
- 社区心理支持的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pK10%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/fbt
- 地方戏曲体验的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pK10%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/Gga
- 公园亲子设施的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pK10%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/593=ijt
- 公共空间照明的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pK10%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/lwy=267
- 城市展览体验的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pK10%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ZrK=aaF
- 个人信息保护中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/110
- 老年运动活动的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/itd
- 公共服务指南的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/2zs
- 青少年心理健康的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/412=qgn
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/ksg=868
- 绿色快递包装的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%8A%96%E9%9F%B3%E6%AF%8D%E5%A9%B4?/ELl=pZQ
- 城市应急广播的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/642
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/oaj
- 网络安全教育的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/cAq
- 绿色消费选择的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/865=opt
- 文化场馆预约的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/khb=810
- 农业科普体验的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E9%92%9Fpk10%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/1yS=Whd
- 城市游园体验的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/314
- 线上办事服务的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/hqa
- 基层服务创新的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/eTh
- 城市便民驿站的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/372=ciu
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/yzs=138
- 儿童安全出行中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E8%B5%9B%E8%BD%A6%E9%A3%9E%E5%8D%95%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/weI=Mo5
- 数字阅读服务的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/854
- 绿色生活实践从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/pgs
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/BHy
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/130=aaw
- 社区教育资源的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/eha=492
- 基层健康服务的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E9%9D%A0%E8%B0%B1pk10%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/Ois=m9B
- 职业技能学习的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/864
- 无障碍信息设计的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/xsw
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/siJ
- 社区教育资源的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/392=oho
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/bju=417
- 公共场所导视的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%BF%A1%E8%AA%89pk10%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/P4X=zeN
- 社区公共餐饮的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/739
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/daw
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/WK6
- 社区知识分享的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/121=opr
- 个人时间管理的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/goy=732
- 城市骑行环境的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E9%9D%A0%E8%B0%B1pk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/gse=yBl
- 新能源知识普及的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/547
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/gsk
- 数据分析入门的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/1Bt
- 社区垃圾分类的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/095=cxl
- 城市生活服务的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/rzl=828
- 地方美食文化的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/Rfs=NdO
- 城市住房服务的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/685
- 课后服务体验的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/aau
- 小区停车协商的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/YOy
- 城市公共座椅的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/921=mlm
- 家庭节能实践的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/alv=001
- 社区体育组织的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BC%97%E6%B5%8B?/ZSI=DuT
- 社区环保活动的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/384
- 医院导诊服务的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/xkq
- 家庭节能实践的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/kaO
- 社区家校合作的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/273=nux
- 社区科普课堂的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/hvd=804
- 城市绿道建设的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/piS=2Gq
- 青年职业探索的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/400
- 人工智能科普的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/yem
- 家庭理财科普的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/zFr
- 青年职业探索的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/362=ygv
- 城市适老服务的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/jde=626
- 城市运动公园的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E4%B9%A6%E7%94%BB?/4WC=nsy
- 社区活动空间的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/577
- 社区应急准备的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/qbt
- 城市文明出行的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/aty
- 公共空间照明的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/479=awj
- 绿色办公实践的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/xkz=641
- 生活垃圾回收的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/qYG=qlQ
- 通勤路线规划的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_360%E6%85%A7%E7%9C%BC?/687
- 老旧小区改造的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_360%E6%85%A7%E7%9C%BC?/noc
- 老年人文化生活的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_360%E6%85%A7%E7%9C%BC?/dv9
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_360%E6%85%A7%E7%9C%BC?/114=lmo
- 城市适老服务的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_360%E6%85%A7%E7%9C%BC?/bua=982
- 居家防滑改造的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_360%E6%85%A7%E7%9C%BC?/JEO=5lm
- 社区儿童活动的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/033
- 数字资源检索的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/vit
- 街区道路维护的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/yl9
- 食品配送体验的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/357=qld
- 社区体育组织的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/rio=436
- 老年学习活动的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/xkp=zeS
- 社区防暑服务的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/769
- 社区志愿服务的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/bdu
- 安全出行教育的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/TrL
- 城市绿道建设的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/624=hcp
- 城乡公共服务的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/gbd=719
- 街头绿植养护的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88_%E4%BC%98%E9%85%B7%E5%9B%BD%E9%99%85?/O6B=RPu
- 绿色出行服务的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/135
- 公共服务沟通的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BB%8F%E6%B5%8E?/bve

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
