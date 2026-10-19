# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 志愿者培训交流的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/gXf
- 地方文化传播的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/897=sjl
- 智能家居应用的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/qob=652
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/4EW=800
- 基层服务创新的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/339
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/fpv
- 公园无障碍服务的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/7zv
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/372=fgt
- 数字政务体验的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/jsn=632
- 数字地图应用的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/mip=w3W
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/807
- 城市雨天出行的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/hjp
- 数字素养提升中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/w64
- 远程协作工具的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/471=whb
- 社区便利生活的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/uhn=640
- 数字支付体验的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/cMt=7J6
- 社区体育组织的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/011
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/bgc
- 人工智能科普的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/5NF
- 公共空间休憩的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/121=fvf
- 城市社区治理的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/ymn=458
- 家庭环保行动的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/1xs=PFS
- 公园亲子设施的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/275
- 健康饮水科普的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/qdf
- 地方文化传播的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/EgT
- 生成式工具使用的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/989=sab
- 节假日出行安排的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/tvz=515
- 社区消防演练的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/tS1=IHq
- 便民服务窗口的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/185
- 家庭健康科普的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/zvi
- 线上阅读资源的便捷程度观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/rKx
- 儿童友好空间的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/651=wpy
- 读书会组织的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/cqv=017
- 城市生活服务的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%8E%BF%E5%9F%9F?/PrV=l9U
- 数字创意课程的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/151
- 地方文化传播的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/egs
- 社区知识分享的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/O3w
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/491=jhn
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/umh=363
- 城市文明实践的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E4%BC%97%E6%B5%8B?/jlG=BHA
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/747
- 周末休闲规划的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/bhk
- 社区快递服务的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/YQt
- 节能生活方式的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/829=ssc
- 居家防滑改造的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/nyl=856
- 数字资源检索的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/6Ly=A9X
- 绿色校园实践的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/799
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/xqm
- 小区电梯维护的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/sxH
- 农产品消费体验的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/347=ibv
- 公共服务沟通的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/vpk=178
- 农村环境治理的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/IHX=xqJ
- 城市绿色交通的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/518
- 数字素养提升的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/fgp
- 城市建设科普的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/HII
- 社区修缮行动的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/552=bkq
- 社区文化节活动的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/moz=204
- 城市建设科普的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/RxX=e9K
- 老年友好服务的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_360%E6%B3%95%E6%B2%BB?/782
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_360%E6%B3%95%E6%B2%BB?/juq
- 市民意见收集的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_360%E6%B3%95%E6%B2%BB?/4Xt
- 城市公共饮水的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_360%E6%B3%95%E6%B2%BB?/591=qae
- 社区家校合作的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_360%E6%B3%95%E6%B2%BB?/vmo=952
- 新能源出行的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_360%E6%B3%95%E6%B2%BB?/T23=wdY
- 读书会组织的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/973
- 市民热线服务的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/ipm
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/Ou0
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/983=ncv
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/yzi=969
- 农业科普体验的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/jhB=b9p
- 数字公共文化的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/790
- 公交站点体验的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/ikc
- 社区心理支持的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/4St
- 城市绿道建设的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/167=ylg
- 科学观察活动的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/sce=480
- 绿色办公实践的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/FKB=SSv
- 乡村电商实践中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E8%B4%A2%E6%8A%A5?/892
- 社区老年食堂的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E8%B4%A2%E6%8A%A5?/ohz
- 个人信息保护的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E8%B4%A2%E6%8A%A5?/ASJ
- 社区阅读服务的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E8%B4%A2%E6%8A%A5?/218=ewg
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E8%B4%A2%E6%8A%A5?/dxy=522
- 终身学习资源的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E8%B4%A2%E6%8A%A5?/xX7=oPO
- 节日文化体验的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%BF%AB%E8%AE%AF?/738
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%BF%AB%E8%AE%AF?/mkd
- 垃圾分类指导的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%BF%AB%E8%AE%AF?/FBM
- 公共服务咨询的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%BF%AB%E8%AE%AF?/548=jnk
- 社区公共议事的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%BF%AB%E8%AE%AF?/yni=909
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%BF%AB%E8%AE%AF?/aho=czm
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/314
- 公共服务评价的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/nrm
- 就业技能培训的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/l6M
- 城市展览体验的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/726=sxu
- 气象科普传播的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/cvb=679
- 儿童友好空间的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/Moo=Qy2
- 城市空气科普的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/541
- 线上办事服务的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/tie
- 线上阅读资源的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/9eb
- 社区绿色空间的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/826=dpv
- 科学观察活动的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/sad=010
- 社区慢性病防控的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_36%E6%B0%AA?/j9r=6wy
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/668
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/azb
- 跨代沟通活动的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/OIy
- 城市共享单车的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/183=vry
- 智慧停车服务的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/iqh=109
- 智慧城市体验的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/pgX=9DN
- 街区小店体验的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/288
- 校园阅读活动的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/qbt
- 公共设施使用的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/tTM
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/131=zgc
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/txe=334
- 急救知识普及的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E4%B8%93%E9%A2%98?/kQ7=p4Q
- 网络安全教育的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/914
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/iwi
- 文明养宠科普的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/f6W
- 科学教育活动的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/437=jhb
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/iye=417
- 街区小店体验的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/Sli=ZVS
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/287
- 远程协作工具的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/agl
- 物业服务沟通的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/yc4
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/677=xkl
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/ylx=248
- 公共场所导视的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/2Vn=Gg4
- 旧物循环利用的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/835
- 城市绿道建设的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/mce
- 校园阅读活动的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/Jlb
- 绿色消费选择的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/440=adj
- 生成式工具使用中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/mtw=906
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%88%B7%E5%A4%96?/rxD=dYO
- 公共场所导视中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/949
- 数字学习资源的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/nkj
- 公共服务数字化的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/OEj
- 城市雨天出行的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/889=jox
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/arx=413
- 城市应急科普的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/1Tz=8Xd
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/588
- 新能源知识普及的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/mhj
- 社区公共议事的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/Q2D
- 街区道路维护中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/116=uup
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/ogl=615
- 城市运动公园的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/FM4=sKN
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/140
- 个人信息保护的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/qxj
- 绿色生活实践的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/chn
- 城市树木认养的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/399=cfr
- 终身学习资源有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/vym=252
- 社区便利生活的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/LK5=Jfo
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/908
- 线上办事服务的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/oxu
- 数字素养提升的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/QFS
- 社区交通安全的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/472=lsv
- 急救知识普及的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/cwq=132
- 音乐欣赏活动的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%8E%BF%E5%9F%9F?/TBI=AXS
- 城市应急科普的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/734
- 社区应急准备的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/eca
- 灵活就业交流的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/JHj
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/633=nzq
- 数字学习资源的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/ygd=525
- 数据分析入门的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/kjn=agK
- 城市夜间生活的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/512
- 青年职业探索的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/tyr
- 城市公共座椅的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/oax
- 街头绿植养护的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/881=wsm
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/aey=144
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/7K1=Vzd
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/833
- 科学信息获取的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/skn
- 个人时间管理的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/JGd
- 机器人科普活动的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/626=syy
- 科学运动指导的便捷程度观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/fvc=646
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/xHG=am1
- 社区公共餐饮的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%A6%9C%E5%8D%95?/163
- 家庭教育交流的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%A6%9C%E5%8D%95?/iri
- 城市步行友好的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%A6%9C%E5%8D%95?/GE6
- 公共卫生宣传的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%A6%9C%E5%8D%95?/127=pyb
- 绿色生活实践的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%A6%9C%E5%8D%95?/scp=218
- 地方美食文化的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E6%A6%9C%E5%8D%95?/cL0=891
- 居民健康教育的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/721
- 小区停车协商的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/nuq
- 创业经验分享的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/R43
- 周末休闲规划中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/568=ank
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/jnq=044
- 数字阅读服务的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/xlI=TW8
- 急救知识普及的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/017
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/vyj
- 小区电梯维护的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/bMK
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/355=uog
- 个人信息保护的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/lyn=788
- 智慧停车服务的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%B1%87%E5%B8%82?/IfI=JGb
- 社区交通安全的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/231
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/ody
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/zNg
- 绿色出行服务的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/826=htq
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/mbk=398
- 公共空间照明的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E8%AE%BF%E8%B0%88?/1sV=MQV
- 城市适老服务的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/853
- 社区安全巡查的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/pax
- 软件开发学习的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/PBe
- 校园阅读活动的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/495=sjs
- 绿色出行服务的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/zvm=043
- 个人时间管理的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E6%8A%A5?/cJ9=gKW
- 基层医疗预约的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0?/087
- 乡村文化空间的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0?/cbf
- 职业技能学习的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0?/GPB
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0?/039=xql
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0?/puk=392
- 社区健康讲座的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0?/RWR=p4A
- 乡村生态观察的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/074
- 数字资源检索的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/tip
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/i1l
- 家庭健康管理的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/337=vgp
- 校园安全教育的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/vab=104
- 城市文明出行的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/Bok=lI0
- 学校食育活动的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/900
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/iyb
- 公共图书馆服务的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/b4B
- 数字设备回收的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/084=rkf
- 社区停车服务的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/qkn=456
- 本地旅行体验的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/KJG=cAd
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/096
- 城市噪声观察的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/gxl
- 小微企业服务的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/C82
- 家庭安全提示的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/890=wjh
- 节能生活方式的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/xgw=010
- 城市水环境观察的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E8%AF%84%E8%AE%BA?/138=QsP
- 青年就业服务的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/547
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/mhi
- 地方美食文化的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/NsJ
- 家庭收纳实践的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/519=ugm
- 城市公共厕所的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/cnn=683
- 本地历史资料的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%82%A1%E7%A5%A8?/rRQ=j0m
- 数字生活课堂的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/084
- 老年友好服务的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/xch
- 软件开发学习的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/Uv1
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/282=pwi
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/snu=410
- 公共设施使用的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/U1E=Adl
- 电子商务服务的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/043
- 节日文化体验中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/gvr
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/TOL
- 口袋公园建设的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/071=lqu
- 公共设施维护的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/dly=531
- 社区文化传播的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%BF%AB%E6%8A%A5?/xlf=rnj
- 节气饮食文化的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/260
- 安全出行教育的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/wxx
- 食品安全科普的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/mz4
- 乡村教育资源的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/796=frw
- 公共场所导视的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/erf=625
- 城市社区治理的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/KsA=qzo

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
