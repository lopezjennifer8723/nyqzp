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

- 家庭照护支持的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/pia=147
- 个人数据管理的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/nX5=cYn
- 城市公共艺术的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/837
- 城市公共自行车的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/nro
- 运动安全知识的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/Dps
- 家庭健康科普的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/268=kfr
- 数字学习资源的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/bpq=142
- 健康饮水科普的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/bF9=GCa
- 地方美食文化的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/882
- 运动安全知识的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/iny
- 儿童户外活动的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/9nJ
- 社区邻里服务的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/679=wrj
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/fvw=685
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/ALH=Km1
- 街区更新实践的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/291
- 社区防暑服务的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/btb
- 社区生活指南的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/qqk
- 城市慢行系统的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/402=eax
- 老年友好服务的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/fuj=507
- 职业技能学习的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/WlN=j20
- 职业技能学习的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/917
- 公共空间休憩的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/jjb
- 公共卫生宣传的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/Gw5
- 街头绿植养护的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/143=eed
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/ekj=663
- 光伏知识科普的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/c25=s5r
- 读书会组织的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/054
- 远程协作工具的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/bch
- 家庭安全提示的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/rUG
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/953=vze
- 城市慢行系统的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/rwe=479
- 城市应急科普的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/Jfj=g2R
- 青少年编程学习的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/645
- 公共交通接驳的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/dkr
- 邻里共享空间的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/Xf3
- 乡村教育资源中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/757=vgg
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/ssq=830
- 智能家居应用的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/tHO=XkX
- 图书馆活动策划的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/214
- 社区信息发布的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/hyk
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/JBv
- 数字政务体验的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/455=jnz
- 智能家居应用的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/fdt=678
- 社区绿色空间的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E8%82%A1%E7%A5%A8?/1bG=gkq
- 数据分析入门的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/278
- 小区公共照明的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/tba
- 节假日出行安排的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/NXz
- 就业技能培训的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/624=llj
- 城市休闲步道的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/pwj=330
- 城市休闲步道的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/Z1h=Ns4
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/261
- 家庭园艺实践的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/efo
- 邻里互助活动的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/A49
- 本地旅行体验的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/687=duk
- 居家适老化改造的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/xvx=215
- 社区垃圾回收中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/FtN=hIv
- 家庭环保习惯的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/034
- 青年志愿活动的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/rvk
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/CER
- 社区阅读服务的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/232=vvy
- 儿童户外活动的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/joc=766
- 社区心理支持的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/qUl=VPE
- 信息无障碍体验的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/457
- 科学信息获取的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/qvk
- 青少年户外教育的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/g0U
- 户外活动组织中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/846=yth
- 居家防滑改造的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/cvd=323
- 城市空气科普的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/kM5=m4G
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/757
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/dan
- 本地旅行体验的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/gzn
- 街区小店体验的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/819=oat
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/kgf=987
- 安全出行教育中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A7%82%E7%82%B9?/B70=X5M
- 志愿者培训交流的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/438
- 文明养宠科普的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/jgg
- 社会体育指导的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/nou
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/559=qns
- 公共空间休憩的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zsz=215
- 健康步道使用的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_987%E5%A8%B1%E4%B9%90-APP_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/VDO=Bdq
- 骑行路线规划的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/473
- 学校食育活动的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/kkq
- 城市人文观察的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/cOs
- 无障碍出行的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/222=fol
- 家庭科学教育的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/rwm=480
- 公益活动组织的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/weT=BHL
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/973
- 数字支付体验的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/ney
- 机器学习入门的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/poO
- 非遗体验活动的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/476=axg
- 社区消防演练的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/tlm=633
- 公共场所导视的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/sDN=7mu
- 社区共享书架的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/207
- 公共场馆服务的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/uhm
- 农业科普体验的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/Lf2
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/677=iho
- 家庭健康管理的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/ssr=288
- 城市文化路线的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/AlI=sig
- 乡村生态旅游的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/016
- 城市展览体验的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/xdj
- 社区便民集市的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/Ogr
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/516=dpn
- 公园休闲体验的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/tns=396
- 数字支付体验的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_987%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/zMp=ouF
- 家庭园艺实践的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/731
- 城市文明出行的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/bey
- 健康信息获取的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/k5g
- 城市休闲步道的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/460=flf
- 城市树木认养的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/yxs=087
- 生活技能分享的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_987%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/EWG=zVA
- 在线学习体验的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/286
- 图书借阅体验的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/qsm
- 医院导诊服务的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/iTv
- 社区设施共享的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/977=xiq
- 社区环保活动的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/bek=045
- 科技馆参观体验的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_987%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/0Of=0jL
- 社区邻里服务的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/992
- 无障碍信息设计的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/oyc
- 居家适老化改造的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/Xo8
- 社区共享书架的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/044=yux
- 城市游园体验的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/mqt=859
- 电子商务服务的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%95%B0%E7%A0%81?/OJV=qy2
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/356
- 公共卫生设施的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/who
- 社区互助网络的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/jHf
- 生活垃圾减量的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/939=dhp
- 城市绿色交通的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/piw=485
- 数字素养提升的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_987%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/CW9=Cwy
- 传统手工艺体验的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/049
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/wms
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/BAw
- 数字支付体验的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/058=hsw
- 科学信息获取中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/trg=944
- 社区老年食堂中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/lMP=XKS
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/731
- 本地消费场景的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/zcp
- 乡村公共服务的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/OpN
- 绿色生活实践的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/573=ejd
- 社区科普课堂的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/hri=107
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/INH=Zv6
- 街区道路维护的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/765
- 乡村公共阅读的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/tbp
- 家庭健康科普的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/qB9
- 城市展览体验中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/426=ipv
- 就业技能培训的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/ivq=007
- 城市共享单车的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/Al6=3ke
- 城市住房服务的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/560
- 家庭健康科普的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/zhy
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/UYx
- 生活服务数字化的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/857=zra
- 生活服务数字化的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/hnv=038
- 城市公共空间的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8C%AA%E5%A8%81%E8%B4%A2%E7%BB%8F?/Veg=0E5
- 数字公共文化的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/162
- 户外活动组织的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/szo
- 公共场馆服务的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/A3v
- 公共健身器材的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/448=bgx
- 社区学习活动的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/guh=130
- 个人信息保护的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/JUz=96H
- 气象科普传播的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/309
- 街头绿植养护的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/oyn
- 小微企业服务的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/BaM
- 老年数字阅读的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/414=moq
- 乡村文化活动的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/nao=125
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/OHP=eWg
- 社区环保活动的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/944
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/rvx
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/HJO
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/383=qvf
- 老旧小区改造的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/die=003
- 亲子科普活动的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%91%8A?/8yD=Nom
- 新能源知识普及的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/706
- 社区便民服务的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/zjl
- 线上办事服务的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/0mU
- 小区电梯维护的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/399=nfj
- 公共卫生宣传的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/cqt=531
- 绿色校园实践的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/dbT=hxz
- 家庭收纳实践的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/468
- 家庭节能实践的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/vuf
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/p1i
- 亲子科普活动的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/296=gws
- 基层医疗预约的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/fgv=077
- 城市社区治理的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/vVS=4RW
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/113
- 乡村文化活动的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/xos
- 城乡交流活动的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/D7l
- 城市社区治理的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/242=ffn
- 地方民俗记录的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/ihs=211
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/3ZH=iGk
- 家庭教育交流的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/891
- 城市水环境观察的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/hfy
- 市民意见收集的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/HbN
- 城市微更新实践的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/989=jzv
- 社区体育组织的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/dvi=184
- 软件开发学习的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/DUi=Tss
- 数字阅读服务的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/636
- 城市公共饮水的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/xvw
- 城市公共座椅的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/fyq
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/882=opx
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/vdy=105
- 人工智能科普的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/cxD=9aC
- 居家防滑改造的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-APP_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/762
- 数字阅读服务的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-APP_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/enk
- 社区托育服务的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-APP_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/Ltm
- 数字便民地图中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-APP_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/547=tdh
- 城市公共艺术的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-APP_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/shq=010
- 公园亲子设施的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_9898%E5%BD%A9%E7%A5%A8-APP_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/atw=Hxu
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/631
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/swt
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/UGG
- 便民信息查询的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/372=kkx
- 科技馆参观体验的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/miv=314
- 社区托育服务的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_9898%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E7%BE%8E%E8%82%A1?/z8t=wfR
- 科学观察活动的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/725
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/zkv
- 社区环保活动的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/BUv
- 家庭照护支持的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/759=ogc
- 青少年心理健康的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/vmp=676
- 软件开发学习的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/NNs=o2Y
- 无障碍出行的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/243
- 乡村文化空间的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/whm
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/dlS
- 城市夜间照明的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/880=cqi
- 小区停车协商的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/sdk=888
- 社区故事采集的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_9898%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/zoM=4Rz
- 公共交通接驳的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/355
- 食品安全科普的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/urd
- 城市公共厕所中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/BVN
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/695=jqr
- 家庭收纳实践的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/mps=642
- 社区故事采集的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_9898%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/AqT=tHV
- 科学健身方法的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/771
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/veo
- 环境监测科普的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/cwH
- 数字学习资源的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/851=pvq
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/ukm=941
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_9898%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/MkP=VuC
- 社区修缮行动的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/852
- 公共空间照明的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/btu
- 数字设备回收的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/hJ5
- 数字学习资源的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/221=vds
- 社区交通安全的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/bpj=093
- 街区道路维护的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_9898%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%B8%B8%E6%88%8F?/zJW=mJm
- 青少年职业启蒙的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/344
- 绿色校园实践的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/cgn
- 城市绿道建设的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/w2d
- 户外活动组织的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/671=zfu
- 便民服务地图的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/pap=932
- 绿色出行服务的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/VLX=47G
- 节气饮食文化的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/635
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_9898%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/xzl

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
