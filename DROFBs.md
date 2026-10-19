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

- 科普展览体验的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/aek=962
- 口袋公园建设的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%97%A5%E6%8A%A5?/FsT=E7M
- 农产品消费体验的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/152
- 社区文化节活动的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/eix
- 家庭阅读计划的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/GzL
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/240=gjh
- 便民服务窗口的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/gpu=780
- 志愿服务平台的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%81%A5%E8%BA%AB?/ZHy=6Px
- 社区故事采集的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/002
- 口袋公园建设的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/bxu
- 青少年科普实践的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/6HX
- 地方旅游导览的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/648=rws
- 城市雨天出行的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/dzz=440
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/rI7=RgB
- 小区停车协商的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%90%8D%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/624
- 儿童友好空间的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%90%8D%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/dzi
- 科学健身方法的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%90%8D%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/4Q9
- 社区科普课堂的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%90%8D%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/964=gav
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%90%8D%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/wzk=256
- 城乡公共服务的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%90%8D%E5%A0%82-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%9A%E6%8A%A5?/7xL=9RE
- 智能手机助老的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/065
- 社区快递服务的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/ypw
- 灵活就业交流的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/W6B
- 公共卫生设施的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/858=mbf
- 绿色出行服务的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/zkx=224
- 生成式工具使用的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP_%E7%95%8C%E9%9D%A2%E8%AE%BA%E5%9D%9B?/mLm=cr9
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/272
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/kuf
- 科学观察活动中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/9V0
- 社区托育服务的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/264=gvy
- 公共设施使用的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/qzw=849
- 城市生活服务的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/8gU=zWQ
- 公共交通信息服务的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/689
- 本地消费场景的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/ctj
- 老年人日常照护的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/yPO
- 青少年编程学习的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/286=yio
- 数字学习资源的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/jtc=978
- 食品安全科普的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/WiP=vFb
- 科学运动指导的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/322
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/lvr
- 图书馆数字服务的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/A7l
- 社区停车服务的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/418=ndz
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/hlf=565
- 儿童友好空间的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E7%99%BB%E5%BD%95_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/13j=2yn
- 绿色出行服务的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%B3%A8%E5%86%8C_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/091
- 公共空间休憩的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%B3%A8%E5%86%8C_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/mir
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%B3%A8%E5%86%8C_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/2E9
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%B3%A8%E5%86%8C_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/738=gil
- 文化场馆预约的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%B3%A8%E5%86%8C_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/zwi=660
- 城市文化路线的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%B3%A8%E5%86%8C_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/GWX=qZ9
- 家庭健康科普的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/006
- 儿童安全出行的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/eqa
- 日常摄影记录的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/ltt
- 城市基础设施的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/784=gfc
- 青少年科普实践的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/nak=468
- 市民热线服务的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/Nh8=ktv
- 家庭节能设备的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/892
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/gyp
- 城市住房服务的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/KyK
- 社区垃圾分类的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/591=hxo
- 社区生活指南的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/vnk=928
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E5%8C%BA?/Bvg=1hd
- 社区应急准备的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/460
- 文明养宠科普的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/dse
- 城乡交流活动的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/T7F
- 公园亲子设施的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/932=ndr
- 城市可持续生活的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/dxx=142
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/pcf=2he
- 数字档案服务从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/951
- 社会体育指导的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/mgx
- 社区健康讲座的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/o5x
- 城市文明实践的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/427=jvu
- 本地消费场景的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/niq=210
- 社区慢性病防控的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/zy3=CP9
- 街区道路维护的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/080
- 运动安全知识的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/juk
- 邻里共享空间的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/TGd
- 物业服务沟通的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/917=rml
- 城市博物馆活动的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/jbn=950
- 数字支付体验的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/6kZ=Lj8
- 乡村公共服务的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/981
- 家庭健康科普的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/oku
- 城乡交通衔接的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/3Xi
- 城市噪声观察的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/670=ukf
- 城市游园体验的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/jla=368
- 公共设施维护的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E5%90%8D%E5%A0%82-%E5%AE%98%E6%96%B9_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/gDT=6TR
- 日常摄影记录的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/114
- 社区运动空间的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/clu
- 市民意见收集的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/9dY
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/867=klv
- 公共服务沟通的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/rlo=983
- 青少年心理健康的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/8mC=2fR
- 开放式学习空间的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/606
- 城市噪声观察的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/hsm
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/cDo
- 新能源出行的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/398=gqg
- 社区邻里服务的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/unf=955
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/rnl=Jq5
- 公共服务数字化的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/730
- 创业经验分享的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/gfr
- 休闲运动入门的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/0FY
- 市民热线服务的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/455=vmd
- 城市共享单车的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/bxm=223
- 乡村公共文化中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/eTR=9Am
- 老年智能设备的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/769
- 城市基础设施的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/bkg
- 青年志愿活动的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/dKH
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/861=fhs
- 社区安全巡查的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/rat=500
- 公共场所导视的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/Tbw=OMZ
- 家庭网络使用的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/766
- 家庭用电安全的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/soh
- 科学教育活动的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/r2g
- 智能手机助老的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/494=qtw
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/wll=691
- 城市展览体验的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%9E%E5%BD%95?/Vxt=qDB
- 社区文化传播的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/713
- 健康步道使用的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/hgk
- 城市应急广播中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/BUq
- 网络信息辨识的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/922=opn
- 乡村电商实践的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/icj=327
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A1%BA%E4%B8%B0%E5%AE%A0%E7%89%A9?/I5O=7bl
- 城市绿道建设的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/995
- 健康步道使用的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/igp
- 地方民俗记录的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/lbz
- 老年人出行服务的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/017=qtq
- 社区体育组织的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/gwa=625
- 社区科普课堂的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/mwo=W6J
- 城市树木认养的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/505
- 城市绿道建设的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/uux
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/vbS
- 社区托育服务的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/025=psd
- 口袋公园建设的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/tnh=799
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%9A%E5%BB%BA?/IhY=N1g
- 老年学习活动的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/613
- 城市公共自行车的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/yjt
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/vWU
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/723=gea
- 通勤路线规划的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/izs=238
- 社区文化节活动中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/yAc=gw8
- 环境教育课程的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/176
- 城市夜间照明的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/dds
- 社区庭院绿化的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/QH2
- 绿色出行服务的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/220=spi
- 全民阅读推广的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/omy=502
- 非遗体验活动的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E7%99%BE%E7%A7%91?/MlR=RSg
- 传统手工艺体验的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/344
- 乡村教育资源的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/ece
- 城市生活记录的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/3At
- 公共服务咨询的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/691=rrh
- 数字创意课程的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/wqx=743
- 老年数字阅读的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%8A%95%E8%B5%84?/Bgg=ddU
- 社区活动策划的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/464
- 家庭健康管理的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/qlt
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/izn
- 城市休闲步道的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/842=wvc
- 新能源出行的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/beo=611
- 网络信息辨识的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/FOQ=7kU
- 便民信息查询的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/051
- 城市公共饮水的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/gls
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/Bbe
- 周末休闲规划的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/689=gns
- 社区生活指南中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/ong=798
- 公共空间安全的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/DhI=X3c
- 便民服务地图的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/266
- 城市公共饮水的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/nyd
- 校园社团活动的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/LNl
- 城市适老服务的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/017=qel
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/wew=979
- 老年数字阅读的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%9C%88%E5%AD%90?/xty=ptw
- 图书馆活动策划的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E4%BD%93%E8%82%B2?/368
- 社区活动报名的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E4%BD%93%E8%82%B2?/sja
- 城市适老服务的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E4%BD%93%E8%82%B2?/hN8
- 急救知识普及的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E4%BD%93%E8%82%B2?/247=wws
- 社区教育资源的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E4%BD%93%E8%82%B2?/pul=300
- 数字生活课堂的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E4%BD%93%E8%82%B2?/vdP=CLB
- 休闲运动入门中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/681
- 文化场馆预约的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/qty
- 街区小店体验的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/YO3
- 数字政务体验的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/379=ckb
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/mvx=733
- 校园社团活动的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/jsW=Hv8
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/350
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/nyi
- 社区学习活动的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/gTE
- 食品配送体验的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/342=ocz
- 远程协作工具的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/ckr=405
- 公共服务预约的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/7lO=gtf
- 智能家居应用的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E5%9B%BE?/580
- 志愿者培训交流的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E5%9B%BE?/paz
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E5%9B%BE?/ADi
- 物业服务沟通的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E5%9B%BE?/617=faz
- 传统节日科普的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E5%9B%BE?/fhx=512
- 公共健身器材的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E5%9B%BE?/Qfy=VbH
- 老年人出行服务的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/706
- 社区托育服务的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/hpg
- 老年友好服务的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/4Cl
- 校园阅读活动的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/738=jmw
- 开源技术交流的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/rgw=497
- 食品安全科普的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/P1Y=lPN
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/565
- 青年职业探索中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/qts
- 公共设施使用的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/6OW
- 儿童安全出行的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/567=ogi
- 社区心理支持的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/vxn=087
- 社区活动报名的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/ZlM=ZZx
- 节能家电使用的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/737
- 家庭养老规划的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/nex
- 老年友好服务中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/0nH
- 社区手工活动的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/230=mni
- 个人信息保护的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/ndr=343
- 老年友好服务的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/gey=2ye
- 绿色办公实践中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/869
- 终身学习资源的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/wla
- 生活技能分享的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/1d0
- 家庭志愿活动的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/922=hwd
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/zen=947
- 机器人科普活动中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E5%90%8D%E5%A0%82%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/7Xy=LXZ
- 城市公共艺术的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/396
- 社区绿色空间的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/lec
- 新能源知识普及的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/J3M
- 数字设备回收的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/923=ejw
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/gsm=363
- 乡村公共阅读的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/ubx=ctq
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C?/536
- 休闲运动入门的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C?/elv
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C?/GFZ
- 智慧停车服务的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C?/303=twf
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C?/uoy=085
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C?/7tX=Xvz
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/389
- 节约用水实践的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/ltt
- 老年友好服务的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/vo5
- 社区快递服务的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/687=fbl
- 邻里互助活动的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/kql=105
- 家庭急救准备的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/MgW=s2B
- 城市共享单车的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/209
- 公共图书馆服务的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/yyp
- 家庭急救准备的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/g2T
- 便民服务窗口的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/402=lmj
- 健康信息获取的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/bcb=150
- 老年数字阅读的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E6%9C%AD%E8%AE%B0?/xZ3=L6C
- 本地旅行体验的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/083
- 骑行路线规划的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/vzp
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/Upb
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/939=gqv
- 邻里互助活动的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/oup=633
- 生活垃圾减量的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/3Pk=0oJ
- 个人时间管理的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/005
- 非遗体验活动的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/tof

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
