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

- 城市文化路线的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%AD%A2%E6%8D%9F%E7%90%86%E8%AE%BA_%E5%93%94%E5%93%A9%E9%80%9A%E4%BF%A1?/cnx=345
- 机器学习入门的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%AD%A2%E6%8D%9F%E7%90%86%E8%AE%BA_%E5%93%94%E5%93%A9%E9%80%9A%E4%BF%A1?/PqI=79O
- 城市公共艺术的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E6%AD%A2%E6%8D%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/820
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E6%AD%A2%E6%8D%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/hjs
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E6%AD%A2%E6%8D%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/ZZx
- 城市骑行环境的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E6%AD%A2%E6%8D%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/726=dzm
- 绿色生活实践的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E6%AD%A2%E6%8D%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/kqm=019
- 文明养宠科普的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BF%AB3%E5%A6%82%E4%BD%95%E6%AD%A2%E6%8D%9F_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/rVP=z4i
- 社区防暑服务的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%9A%E5%B0%91%E5%80%8D%E6%AD%A2%E6%8D%9F_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/913
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%9A%E5%B0%91%E5%80%8D%E6%AD%A2%E6%8D%9F_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/xtq
- 城市社区治理的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%9A%E5%B0%91%E5%80%8D%E6%AD%A2%E6%8D%9F_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/jtM
- 农业科普体验的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%9A%E5%B0%91%E5%80%8D%E6%AD%A2%E6%8D%9F_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/142=wdt
- 绿色生活实践的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%9A%E5%B0%91%E5%80%8D%E6%AD%A2%E6%8D%9F_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/lwd=457
- 城市展览体验的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%9A%E5%B0%91%E5%80%8D%E6%AD%A2%E6%8D%9F_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/9kI=ofk
- 家庭教育交流中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/412
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/yfn
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/AVK
- 社区互助网络的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/710=cam
- 劳动教育实践的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/vjg=760
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/c0m=3Hy
- 数字创作工具的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E4%BA%8F%E6%8D%9F%E7%9A%84%E5%BB%BA%E4%BB%93%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/097
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E4%BA%8F%E6%8D%9F%E7%9A%84%E5%BB%BA%E4%BB%93%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/kzd
- 城市应急广播的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E4%BA%8F%E6%8D%9F%E7%9A%84%E5%BB%BA%E4%BB%93%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/g3M
- 亲子科普活动的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E4%BA%8F%E6%8D%9F%E7%9A%84%E5%BB%BA%E4%BB%93%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/864=wck
- 城市公共厕所的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E4%BA%8F%E6%8D%9F%E7%9A%84%E5%BB%BA%E4%BB%93%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/dza=851
- 气象科普传播的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%B0%B8%E4%B8%8D%E4%BA%8F%E6%8D%9F%E7%9A%84%E5%BB%BA%E4%BB%93%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/cwG=Gji
- 农产品消费体验的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A2%E6%8D%9F3%E4%B8%AA%E7%82%B9%E6%AD%A2%E7%9B%886%E4%B8%AA%E7%82%B9_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/465
- 数字政务体验的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A2%E6%8D%9F3%E4%B8%AA%E7%82%B9%E6%AD%A2%E7%9B%886%E4%B8%AA%E7%82%B9_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/gvb
- 儿童友好空间的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A2%E6%8D%9F3%E4%B8%AA%E7%82%B9%E6%AD%A2%E7%9B%886%E4%B8%AA%E7%82%B9_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/TXW
- 城市公共空间的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A2%E6%8D%9F3%E4%B8%AA%E7%82%B9%E6%AD%A2%E7%9B%886%E4%B8%AA%E7%82%B9_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/076=jdv
- 老旧小区改造的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A2%E6%8D%9F3%E4%B8%AA%E7%82%B9%E6%AD%A2%E7%9B%886%E4%B8%AA%E7%82%B9_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/nor=665
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%AD%A2%E6%8D%9F3%E4%B8%AA%E7%82%B9%E6%AD%A2%E7%9B%886%E4%B8%AA%E7%82%B9_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/1a7=ihO
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/522
- 个人信息保护的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/mdj
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/WTE
- 医院导诊服务的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/964=oqy
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/hvv=441
- 智能手机助老的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/g4I=oVX
- 城市噪声观察的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E5%A6%82%E4%BD%95%E8%AE%BE%E7%BD%AE%E6%AF%94%E8%BE%83%E5%90%88%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/372
- 科学健身方法的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E5%A6%82%E4%BD%95%E8%AE%BE%E7%BD%AE%E6%AF%94%E8%BE%83%E5%90%88%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/yvx
- 社区手工活动的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E5%A6%82%E4%BD%95%E8%AE%BE%E7%BD%AE%E6%AF%94%E8%BE%83%E5%90%88%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/60d
- 公共设施使用的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E5%A6%82%E4%BD%95%E8%AE%BE%E7%BD%AE%E6%AF%94%E8%BE%83%E5%90%88%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/889=hky
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E5%A6%82%E4%BD%95%E8%AE%BE%E7%BD%AE%E6%AF%94%E8%BE%83%E5%90%88%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/xfe=495
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E5%A6%82%E4%BD%95%E8%AE%BE%E7%BD%AE%E6%AF%94%E8%BE%83%E5%90%88%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/W5s=iKr
- 数字资源检索中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E5%90%88%E7%90%86%E7%9A%84%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%AF%94%E4%BE%8B_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/611
- 数字创意课程的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E5%90%88%E7%90%86%E7%9A%84%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%AF%94%E4%BE%8B_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/eew
- 文化场馆预约的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E5%90%88%E7%90%86%E7%9A%84%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%AF%94%E4%BE%8B_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/WjK
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E5%90%88%E7%90%86%E7%9A%84%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%AF%94%E4%BE%8B_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/903=bdo
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E5%90%88%E7%90%86%E7%9A%84%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%AF%94%E4%BE%8B_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/rlh=812
- 老年友好服务的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9C%80%E5%90%88%E7%90%86%E7%9A%84%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%AF%94%E4%BE%8B_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/nF9=x6h
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/215
- 信息无障碍体验的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/hyi
- 老年人出行服务的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/zJz
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/270=fdr
- 绿色建筑理念的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/kxt=491
- 家庭照护支持的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%9C%80%E4%BD%B3%E6%AF%94%E4%BE%8B_36%E6%B0%AA%E6%9C%AD%E8%AE%B0?/aXd=npg
- 城市共享单车的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%9F%AD%E7%BA%BF3%E7%82%B9%E6%AD%A2%E7%9B%883%E7%82%B9%E6%AD%A2%E6%8D%9F%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/449
- 青少年科技社团的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%9F%AD%E7%BA%BF3%E7%82%B9%E6%AD%A2%E7%9B%883%E7%82%B9%E6%AD%A2%E6%8D%9F%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/hhk
- 全民健身活动的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%9F%AD%E7%BA%BF3%E7%82%B9%E6%AD%A2%E7%9B%883%E7%82%B9%E6%AD%A2%E6%8D%9F%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/xXr
- 绿色建筑理念的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%9F%AD%E7%BA%BF3%E7%82%B9%E6%AD%A2%E7%9B%883%E7%82%B9%E6%AD%A2%E6%8D%9F%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/170=zei
- 城市文化路线的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%9F%AD%E7%BA%BF3%E7%82%B9%E6%AD%A2%E7%9B%883%E7%82%B9%E6%AD%A2%E6%8D%9F%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/quz=160
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E7%9F%AD%E7%BA%BF3%E7%82%B9%E6%AD%A2%E7%9B%883%E7%82%B9%E6%AD%A2%E6%8D%9F%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/v7i=Jo5
- 环境教育课程的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%AD%A2%E7%9B%88%E6%9C%80%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_360%E5%AE%89%E9%98%B2?/229
- 公共服务沟通的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%AD%A2%E7%9B%88%E6%9C%80%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_360%E5%AE%89%E9%98%B2?/ibd
- 无障碍出行的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%AD%A2%E7%9B%88%E6%9C%80%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_360%E5%AE%89%E9%98%B2?/QEj
- 城市展览体验的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%AD%A2%E7%9B%88%E6%9C%80%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_360%E5%AE%89%E9%98%B2?/028=mze
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%AD%A2%E7%9B%88%E6%9C%80%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_360%E5%AE%89%E9%98%B2?/fcg=107
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%AD%A2%E7%9B%88%E6%9C%80%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_360%E5%AE%89%E9%98%B2?/1LX=PGF
- 低碳社区实践的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E8%82%A1%E7%A5%A8%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/264
- 城市公共饮水的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E8%82%A1%E7%A5%A8%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/ams
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E8%82%A1%E7%A5%A8%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/VUp
- 志愿者培训交流的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E8%82%A1%E7%A5%A8%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/865=hxr
- 公益活动组织的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E8%82%A1%E7%A5%A8%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/veq=398
- 城市可持续生活的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E8%82%A1%E7%A5%A8%E6%8A%80%E5%B7%A7%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/63b=evQ
- 社区养老服务的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%8F%B7%E7%AE%97%E6%B3%95_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/839
- 节气饮食文化的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%8F%B7%E7%AE%97%E6%B3%95_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/dcy
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%8F%B7%E7%AE%97%E6%B3%95_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/9Ge
- 数字档案服务的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%8F%B7%E7%AE%97%E6%B3%95_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/475=quj
- 乡村文化空间的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%8F%B7%E7%AE%97%E6%B3%95_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/bhy=091
- 城市文明出行的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%908%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%8F%B7%E7%AE%97%E6%B3%95_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/1le=Mam
- 节约用水实践的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/218
- 节能生活方式的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/gfz
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/47f
- 社区公共卫生中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/822=wyd
- 公共服务指南的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/wfk=591
- 青年就业服务的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E5%AE%9A%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/Ho3=2K9
- 安全出行教育的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/471
- 青少年心理健康的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/xzz
- 数据分析入门的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/XE5
- 乡村产业科普的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/325=gje
- 城市步行友好的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/car=818
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/zkh=mPR
- 数字阅读服务的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B4%9F%E7%9B%88%E5%88%A9%E8%AF%A6%E7%BB%86%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/377
- 学校体育活动的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B4%9F%E7%9B%88%E5%88%A9%E8%AF%A6%E7%BB%86%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/zqj
- 骑行路线规划的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B4%9F%E7%9B%88%E5%88%A9%E8%AF%A6%E7%BB%86%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/FKP
- 数字生活课堂的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B4%9F%E7%9B%88%E5%88%A9%E8%AF%A6%E7%BB%86%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/472=esv
- 老年人文化生活的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B4%9F%E7%9B%88%E5%88%A9%E8%AF%A6%E7%BB%86%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/yzj=253
- 城市共享单车的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E8%B4%9F%E7%9B%88%E5%88%A9%E8%AF%A6%E7%BB%86%E6%89%93%E6%B3%95_%E8%B1%86%E7%93%A3%E7%90%86%E8%B4%A2?/cnk=PDw
- 家庭节能实践的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B4%9F%E7%9B%88%E5%88%A9%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E5%AF%B9%E5%88%B7_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/005
- 老年人文化生活的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B4%9F%E7%9B%88%E5%88%A9%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E5%AF%B9%E5%88%B7_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/rsg
- 邻里共享空间的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B4%9F%E7%9B%88%E5%88%A9%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E5%AF%B9%E5%88%B7_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/3GB
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B4%9F%E7%9B%88%E5%88%A9%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E5%AF%B9%E5%88%B7_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/440=bjz
- 科学教育活动的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B4%9F%E7%9B%88%E5%88%A9%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E5%AF%B9%E5%88%B7_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/fva=125
- 休闲运动入门的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B4%9F%E7%9B%88%E5%88%A9%E5%A6%82%E4%BD%95%E6%AD%A3%E7%A1%AE%E5%AF%B9%E5%88%B7_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/AeR=ieN
- 家庭阅读计划的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BB%80%E4%B9%88%E6%98%AF%E8%B4%9F%E7%9B%88%E5%88%A9%E6%A8%A1%E5%BC%8F_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/866
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BB%80%E4%B9%88%E6%98%AF%E8%B4%9F%E7%9B%88%E5%88%A9%E6%A8%A1%E5%BC%8F_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/bdq
- 健康饮食教育的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BB%80%E4%B9%88%E6%98%AF%E8%B4%9F%E7%9B%88%E5%88%A9%E6%A8%A1%E5%BC%8F_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/H8R
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BB%80%E4%B9%88%E6%98%AF%E8%B4%9F%E7%9B%88%E5%88%A9%E6%A8%A1%E5%BC%8F_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/975=jek
- 生活服务数字化的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BB%80%E4%B9%88%E6%98%AF%E8%B4%9F%E7%9B%88%E5%88%A9%E6%A8%A1%E5%BC%8F_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/awo=743
- 城乡公共服务中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E4%BB%80%E4%B9%88%E6%98%AF%E8%B4%9F%E7%9B%88%E5%88%A9%E6%A8%A1%E5%BC%8F_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/T7E=Mg9
- 便民维修服务的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/068
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/bit
- 绿色出行服务的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/WFV
- 新能源出行的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/963=vde
- 小区停车协商的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/mdm=666
- 医院导诊服务中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E5%8D%B7?/XiK=E3k
- 邻里共享空间的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%AE%9A%E4%BD%8D%E4%B8%83%E7%A0%81%E5%BF%85%E4%B8%AD6_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/710
- 城市公共厕所的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%AE%9A%E4%BD%8D%E4%B8%83%E7%A0%81%E5%BF%85%E4%B8%AD6_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/nfx
- 乡村生态观察的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%AE%9A%E4%BD%8D%E4%B8%83%E7%A0%81%E5%BF%85%E4%B8%AD6_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/KBV
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%AE%9A%E4%BD%8D%E4%B8%83%E7%A0%81%E5%BF%85%E4%B8%AD6_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/972=dey
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%AE%9A%E4%BD%8D%E4%B8%83%E7%A0%81%E5%BF%85%E4%B8%AD6_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/jyf=238
- 居家防滑改造的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%AE%9A%E4%BD%8D%E4%B8%83%E7%A0%81%E5%BF%85%E4%B8%AD6_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/Osa=QKf
- 城市游园体验的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%973%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/418
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%973%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/oxa
- 城市文明出行中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%973%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/HDE
- 休闲运动入门的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%973%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/585=yzo
- 数字生活课堂的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%973%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/cin=378
- 休闲运动入门的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%8E%92%E5%88%973%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/N1D=aYx
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/668
- 家庭急救准备的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/ikq
- 图书借阅体验的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/WA4
- 地方旅游导览的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/711=jye
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/hos=430
- 儿童运动体验的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/vrQ=rVE
- 街区更新实践的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/715
- 老年智能设备的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/ogy
- 公共交通接驳的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/PlN
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/136=liz
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/kvj=637
- 新能源知识普及的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E8%AE%AF?/3lG=8eI
- 便民服务地图的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/307
- 社区环保活动的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/bdt
- 公共交通接驳的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/QCN
- 电子商务服务的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/671=jlq
- 生活技能分享的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/oiu=012
- 软件开发学习的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%AD%A3%E8%A7%84%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/IRR=cg4
- 本地历史资料的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/985
- 社区文化传播的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/ifp
- 社区便利生活的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/Wub
- 数字创作工具的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/428=gxg
- 远程协作工具的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/tog=964
- 科学运动指导的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%A5%BC%E5%B8%82?/t8H=EmG
- 校园节能行动的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/877
- 科学信息获取的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/eop
- 城市建设科普的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/fny
- 职业技能学习中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/411=hpu
- 节能生活方式的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/duf=290
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/t0h=zKN
- 社区家校合作的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/210
- 医院导诊服务有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/vnu
- 社区便利生活的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/GVl
- 邻里共享空间的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/822=ebh
- 老年友好服务的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/qoj=484
- 公共服务数字化的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_1%E5%88%86%E9%92%9F%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/Yqc=R3y
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/831
- 校园阅读活动的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/mps
- 数字艺术创作的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/HHR
- 公共服务咨询的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/963=swb
- 城市绿道建设的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/qsw=635
- 社区便民集市的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/FuN=aNV
- 开放数据应用的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/050
- 健康信息获取的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/kvb
- 城市展览体验的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/Zh1
- 街区道路维护的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/295=irc
- 城市建设科普的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/ylr=825
- 家庭安全提示的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/GSR=Y94
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/434
- 儿童友好空间的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/xgv
- 便民服务地图的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/I8Y
- 城市夜间照明的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/360=lbw
- 社区便利生活的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/mtg=778
- 数字课堂应用的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3-%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/Ijk=YHr
- 社区应急准备的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A8%B3%E8%B5%9A1-0%E5%A4%A7%E6%8A%80%E5%B7%A7_360%E6%97%B6%E6%8A%A5?/602
- 城市博物馆活动的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A8%B3%E8%B5%9A1-0%E5%A4%A7%E6%8A%80%E5%B7%A7_360%E6%97%B6%E6%8A%A5?/rmz
- 地方民俗记录的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A8%B3%E8%B5%9A1-0%E5%A4%A7%E6%8A%80%E5%B7%A7_360%E6%97%B6%E6%8A%A5?/2yJ
- 城市社区治理的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A8%B3%E8%B5%9A1-0%E5%A4%A7%E6%8A%80%E5%B7%A7_360%E6%97%B6%E6%8A%A5?/684=mut
- 城市运动公园的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A8%B3%E8%B5%9A1-0%E5%A4%A7%E6%8A%80%E5%B7%A7_360%E6%97%B6%E6%8A%A5?/eve=255
- 数字设备回收的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%BF%AB3%E7%A8%B3%E8%B5%9A1-0%E5%A4%A7%E6%8A%80%E5%B7%A7_360%E6%97%B6%E6%8A%A5?/nyE=9Sa
- 地方旅游导览的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E4%BB%A5%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/692
- 健康步道使用的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E4%BB%A5%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/cfu
- 安全出行教育的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E4%BB%A5%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/j3o
- 城市公共座椅的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E4%BB%A5%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/590=ehx
- 公共服务沟通的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E4%BB%A5%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/wiy=394
- 健康饮水科普的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E4%BB%A5%E5%8F%8A%E9%A2%84%E6%B5%8B_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/VNx=Y1z
- 传统节日科普的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/070
- 街区道路维护的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/wmd
- 社区设施共享的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/XYJ
- 城市步行友好中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/003=kwl
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/dfx=417
- 城市体育设施的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/2Pf=zUN
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/301
- 乡村电商实践的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/wzs
- 地方民俗记录的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/lfV
- 公园亲子设施中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/441=cuf
- 社区家校合作的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/der=390
- 口袋公园建设的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E7%AE%97_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/gW0=MWL
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%92%8C%E5%80%BC18%E6%8E%A8%E7%AE%97_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/939
- 家庭阅读计划的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%92%8C%E5%80%BC18%E6%8E%A8%E7%AE%97_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/kbc
- 社区文化传播的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%92%8C%E5%80%BC18%E6%8E%A8%E7%AE%97_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/SaG
- 社区艺术活动的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%92%8C%E5%80%BC18%E6%8E%A8%E7%AE%97_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/336=wvy
- 家庭安全提示的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%92%8C%E5%80%BC18%E6%8E%A8%E7%AE%97_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/qnj=329
- 健康信息获取的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%92%8C%E5%80%BC18%E6%8E%A8%E7%AE%97_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/GTC=eV5
- 休闲运动入门的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BF%AB3%E5%BF%85%E8%B5%A2%E7%A7%98%E7%B1%8D_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/678
- 公共设施维护的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BF%AB3%E5%BF%85%E8%B5%A2%E7%A7%98%E7%B1%8D_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/ova
- 数字创意课程的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BF%AB3%E5%BF%85%E8%B5%A2%E7%A7%98%E7%B1%8D_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/uiA
- 公共服务数字化的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BF%AB3%E5%BF%85%E8%B5%A2%E7%A7%98%E7%B1%8D_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/075=nsy
- 生活服务数字化的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BF%AB3%E5%BF%85%E8%B5%A2%E7%A7%98%E7%B1%8D_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/wlf=474
- 社区教育资源的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BF%AB3%E5%BF%85%E8%B5%A2%E7%A7%98%E7%B1%8D_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/bKZ=Q1D
- 邻里共享空间的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_13458%E4%B8%87%E8%83%BD%E4%B9%B0%E6%B3%95%E5%9B%BE%E7%89%87_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/173
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_13458%E4%B8%87%E8%83%BD%E4%B9%B0%E6%B3%95%E5%9B%BE%E7%89%87_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/iue
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_13458%E4%B8%87%E8%83%BD%E4%B9%B0%E6%B3%95%E5%9B%BE%E7%89%87_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/xNC
- 乡村生活观察的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_13458%E4%B8%87%E8%83%BD%E4%B9%B0%E6%B3%95%E5%9B%BE%E7%89%87_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/125=urc
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_13458%E4%B8%87%E8%83%BD%E4%B9%B0%E6%B3%95%E5%9B%BE%E7%89%87_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/jzt=784
- 生活垃圾减量的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_13458%E4%B8%87%E8%83%BD%E4%B9%B0%E6%B3%95%E5%9B%BE%E7%89%87_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/CUO=CXN
- 社区花园共建的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/782
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/ghs
- 城市人文观察的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/poD
- 地方美食文化的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/782=nve
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/qyl=781
- 城市雨天出行的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/ZK5=Xi3
- 家庭饮食安排的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/325
- 公共服务预约的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/ape
- 社区养老服务的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/igz
- 家庭园艺实践的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/611=kmk
- 城市适老服务的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/wmn=167
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%BF%85%E4%B8%AD%E5%B9%95%E5%90%8E%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/TIj=WsY
- 绿色办公实践的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/247
- 口袋公园建设的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/oky
- 公共服务数字化的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/82F
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/954=wcm
- 公共空间安全的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/qdk=301
- 乡村公共阅读的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/JXu=USn
- 公共场馆服务的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%9F%E5%AF%BC%E5%B8%88%E5%81%9A%E4%BB%BB%E5%8A%A1%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/819
- 通勤路线规划的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%9F%E5%AF%BC%E5%B8%88%E5%81%9A%E4%BB%BB%E5%8A%A1%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/nol
- 城市应急科普的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%9F%E5%AF%BC%E5%B8%88%E5%81%9A%E4%BB%BB%E5%8A%A1%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/odY
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%9F%E5%AF%BC%E5%B8%88%E5%81%9A%E4%BB%BB%E5%8A%A1%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/143=kon
- 公共服务评价的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%9F%E5%AF%BC%E5%B8%88%E5%81%9A%E4%BB%BB%E5%8A%A1%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/dhp=301
- 软件开发学习的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B7%9F%E5%AF%BC%E5%B8%88%E5%81%9A%E4%BB%BB%E5%8A%A1%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/CZR=d9z
- 城市公共标识的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/859
- 城市水环境观察的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/sdy

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
