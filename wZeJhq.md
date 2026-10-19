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

- 街区道路维护的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/ups=789
- 城市应急科普的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/OOp=EYD
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/802
- 城乡交流活动的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/cma
- 公共设施维护的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/3Ww
- 口袋公园建设的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/080=fgi
- 急救知识普及的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/mjb=786
- 本地历史资料的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E4%BD%93%E8%82%B2?/B7I=63T
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/909
- 社区设施共享的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/nza
- 公共交通接驳中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/hBb
- 社区应急准备的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/134=slz
- 社区便民服务的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/qom=166
- 食品安全科普的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/9kB=uV8
- 城市社区治理的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/490
- 绿色消费选择的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/rqr
- 城市骑行环境的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/Sfm
- 公共服务评价的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/242=fvx
- 城市可持续生活的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/dsp=815
- 社区公共议事的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/OnP=zdh
- 社区体育组织的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/950
- 家庭节能设备的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/ypj
- 乡村文化活动的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/fxp
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/977=jsr
- 非遗体验活动的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/krh=354
- 青少年职业启蒙的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/o3l=9HK
- 城市公共饮水的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/976
- 创业经验分享的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/mxq
- 老年人文化生活中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/WQo
- 社区故事采集的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/944=wnv
- 城市体育设施的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/kyi=677
- 健康步道使用中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E7%A7%91%E6%8A%80?/hGb=V0m
- 乡村教育资源的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/146
- 环境监测科普的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/eaa
- 街头绿植养护的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/gw3
- 新能源出行的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/946=jas
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/glc=683
- 图书借阅体验的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8D%8F?/00f=mCQ
- 公共服务评价的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E5%86%85?/629
- 周末休闲规划的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E5%86%85?/lpk
- 儿童友好空间的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E5%86%85?/g9c
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E5%86%85?/426=fmb
- 周末休闲规划的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E5%86%85?/qjg=878
- 公共空间照明的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_360%E5%9B%BD%E5%86%85?/6en=88T
- 社区阅读服务的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/742
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/faz
- 数字课堂应用的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/XEL
- 公交无障碍服务的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/528=ekr
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/kke=295
- 数字创作工具的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/RY7=JOZ
- 数字便民地图的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/448
- 社区庭院绿化的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/ylo
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/Zfo
- 校园社团活动的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/134=fhr
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/jww=977
- 公共场所导视的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/QYs=Aaj
- 公共设施维护的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/727
- 科技馆参观体验的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/nlp
- 食品配送体验的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/qgm
- 节能生活方式的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/660=vpi
- 健康饮食教育的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/rib=439
- 节假日出行安排的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/1k1=zkI
- 运动安全知识中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/122
- 骑行路线规划的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/jcf
- 乡村产业科普的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/b2z
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/132=nxa
- 城市游园体验的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/crl=554
- 机器人科普活动的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/Yyt=mMw
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/560
- 家庭志愿活动的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/lsm
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/rmG
- 乡村生活观察中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/932=hmx
- 社区商业活力的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/zuw=893
- 社区交通安全的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/ZXH=6VN
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/122
- 社区环保活动的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/zcq
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/aPx
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/767=ddi
- 公交站点体验的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/vnj=933
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/6eq=ftG
- 城市骑行环境的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/857
- 社区家校合作的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/ond
- 社区学习活动的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/oyI
- 基层服务创新的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/842=vwr
- 家庭收纳实践的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/ndk=133
- 家庭用电安全的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/6HP=A39
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/382
- 乡村公共文化的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/iyb
- 社区修缮行动的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/lu4
- 非遗体验活动的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/603=ngv
- 垃圾分类指导的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/euk=628
- 家庭饮食安排的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/sWa=JY8
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/178
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/ies
- 街区小店体验的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/DWr
- 数字档案服务中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/474=gcz
- 老年人出行服务的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/pmm=708
- 志愿者培训交流的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/MWo=b2s
- 家庭照护支持的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/404
- 社区应急准备的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/mdh
- 乡村文化空间的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/Vmy
- 城市骑行环境的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/431=jpp
- 本地历史资料的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/obm=973
- 在线学习体验的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B8%AF%E8%82%A1?/NCm=55T
- 数字便民地图的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/919
- 数字公共文化的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/bxb
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/V8G
- 儿童友好空间的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/274=hlg
- 地方美食文化的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/sjp=413
- 城市公共艺术的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/ht2=GKo
- 老年友好服务的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/430
- 家庭园艺实践的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/kda
- 创业经验分享的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/nAS
- 城市人文观察的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/256=oqt
- 社区艺术活动的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/vto=492
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E6%B3%95%E6%B2%BB?/yQF=NSm
- 公共设施维护的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/446
- 老年友好服务的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/gpx
- 市民意见收集的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/IBR
- 远程协作工具从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/848=thy
- 急救知识普及的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/ynr=314
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/9Ol=nMe
- 家庭照护支持的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/216
- 终身学习资源的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/spr
- 城市公共艺术的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/pNj
- 全民健身活动的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/067=ken
- 社区手工活动的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/wwi=663
- 街道综合服务的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/j2Z=54A
- 校园社团活动的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/570
- 社区故事采集的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/amk
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/S3S
- 便民信息查询的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/009=cyk
- 非遗课堂体验的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/cts=620
- 社区环保活动的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/CB8=Zsq
- 光伏知识科普的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/233
- 乡村生活观察的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/evp
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/D8t
- 家庭健康管理的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/282=mom
- 智能家居应用的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/oou=999
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/98T=4ka
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B64.0%2C7_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/503
- 儿童户外活动的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B64.0%2C7_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/hsr
- 公共文化活动的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B64.0%2C7_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/iXU
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B64.0%2C7_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/475=pgq
- 青少年科普实践的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B64.0%2C7_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/syc=208
- 家庭食品保存的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B64.0%2C7_%E7%9F%A5%E4%B9%8E%E8%AF%84%E8%AE%BA?/79B=JJW
- 家庭运动计划的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%8E%A9%E5%BD%A9%E7%BD%91380%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/609
- 邻里互助活动的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%8E%A9%E5%BD%A9%E7%BD%91380%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/qms
- 绿色校园实践的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%8E%A9%E5%BD%A9%E7%BD%91380%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/LPc
- 社区安全巡查的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%8E%A9%E5%BD%A9%E7%BD%91380%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/861=xex
- 城市公共厕所的组织方法与经验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%8E%A9%E5%BD%A9%E7%BD%91380%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/mle=839
- 社区停车服务的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%8E%A9%E5%BD%A9%E7%BD%91380%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/hRJ=xSk
- 城市生活服务的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9%E7%9A%84%E5%8F%A3%E7%A2%91_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/044
- 老年友好服务的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9%E7%9A%84%E5%8F%A3%E7%A2%91_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/kop
- 城市应急广播的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9%E7%9A%84%E5%8F%A3%E7%A2%91_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/mTE
- 青年就业服务的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9%E7%9A%84%E5%8F%A3%E7%A2%91_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/204=sjx
- 社区健康讲座的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9%E7%9A%84%E5%8F%A3%E7%A2%91_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/vkg=066
- 城市微更新实践的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9%E7%9A%84%E5%8F%A3%E7%A2%91_%E7%99%BE%E5%BA%A6%E5%9F%BA%E9%87%91?/TSk=MTt
- 全民健身活动的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A63%E5%85%91%E6%8D%A2%E7%A0%81100000%E9%92%BB%E7%9F%B3_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/795
- 社区共享书架的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A63%E5%85%91%E6%8D%A2%E7%A0%81100000%E9%92%BB%E7%9F%B3_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/fso
- 校园社团活动的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A63%E5%85%91%E6%8D%A2%E7%A0%81100000%E9%92%BB%E7%9F%B3_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/I2Y
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A63%E5%85%91%E6%8D%A2%E7%A0%81100000%E9%92%BB%E7%9F%B3_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/041=pwt
- 家庭安全提示的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A63%E5%85%91%E6%8D%A2%E7%A0%81100000%E9%92%BB%E7%9F%B3_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/dhw=017
- 社区知识分享的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A63%E5%85%91%E6%8D%A2%E7%A0%81100000%E9%92%BB%E7%9F%B3_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/AZw=zp2
- 居家防滑改造的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9welcome_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/345
- 健康信息获取的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9welcome_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/gbp
- 低碳社区实践的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9welcome_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/WVX
- 垃圾分类指导的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9welcome_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/620=jgz
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9welcome_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/ogz=690
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9welcome_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/JZ1=V0A
- 老年智能设备的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/169
- 校园阅读活动的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/zzm
- 绿色办公实践的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/d6D
- 公共服务沟通的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/159=vzq
- 城市展览体验的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/uav=027
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%9C%E6%96%B9%E7%A7%92%E7%A7%92%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/YHl=Nx0
- 文化场馆预约的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/710
- 居家适老化改造的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/nkw
- 城市树木认养的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/Vqh
- 通勤路线规划的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/255=czs
- 本地历史资料的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/ngn=254
- 社区学习活动的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/kxC=Iqo
- 街头绿植养护的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%A8%E5%A4%A9%E5%BF%AB3%E5%85%A8%E9%83%A8%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/606
- 社区运动空间的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%A8%E5%A4%A9%E5%BF%AB3%E5%85%A8%E9%83%A8%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/xef
- 智能家居应用的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%A8%E5%A4%A9%E5%BF%AB3%E5%85%A8%E9%83%A8%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/QrW
- 城乡交流活动的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%A8%E5%A4%A9%E5%BF%AB3%E5%85%A8%E9%83%A8%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/888=hpx
- 乡村教育资源的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%A8%E5%A4%A9%E5%BF%AB3%E5%85%A8%E9%83%A8%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/xbx=189
- 社区活动策划的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%98%A8%E5%A4%A9%E5%BF%AB3%E5%85%A8%E9%83%A8%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/HHT=XD6
- 数字创意课程的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/023
- 城市步行友好的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/wtu
- 公共服务评价的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/mXR
- 租房信息服务的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/470=kmp
- 城市体育设施的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/uxr=624
- 社区活动空间的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2_%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/l76=rzu
- 地方民俗记录的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/137
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/mec
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/ZWZ
- 老年人出行服务的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/012=xqz
- 社区宠物管理的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/fek=564
- 环境监测科普的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_3%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/J63=oY6
- 机器人科普活动的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%83%E5%B8%86?/640
- 数字公共文化的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%83%E5%B8%86?/vfr
- 便民维修服务的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%83%E5%B8%86?/ZGV
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%83%E5%B8%86?/491=gxv
- 儿童安全出行的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%83%E5%B8%86?/emp=690
- 便民维修服务的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E5%8D%83%E5%B8%86?/52k=E46
- 公共图书馆服务的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88v%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/914
- 城市公共座椅的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88v%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/ceu
- 开放数据应用的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88v%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/AqD
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88v%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/299=qjz
- 社区便民服务的儿童友好细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88v%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/nen=777
- 小区公共照明的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E7%9B%88v%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/ZaK=vet
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%A3%8B%E7%89%8C%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E4%BA%BA%E7%89%A9?/027
- 本地旅行体验的学习资源整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%A3%8B%E7%89%8C%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E4%BA%BA%E7%89%A9?/msw
- 城市地名文化的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%A3%8B%E7%89%8C%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E4%BA%BA%E7%89%A9?/quI
- 城市慢行系统的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%A3%8B%E7%89%8C%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E4%BA%BA%E7%89%A9?/904=fgt
- 社区学习活动的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%A3%8B%E7%89%8C%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E4%BA%BA%E7%89%A9?/gft=700
- 儿童友好空间的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%A3%8B%E7%89%8C%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E4%BA%BA%E7%89%A9?/jha=7g9
- 便民信息查询的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BB%BA%E5%BF%AB3%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/517
- 儿童友好空间的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BB%BA%E5%BF%AB3%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/utq
- 基层医疗预约的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BB%BA%E5%BF%AB3%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/WPD
- 老旧小区改造的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BB%BA%E5%BF%AB3%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/628=mzb
- 数字课堂应用的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BB%BA%E5%BF%AB3%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/iro=402
- 健康饮水科普的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BB%BA%E5%BF%AB3%E4%BB%8A%E6%97%A5%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/IM3=rrG
- 线上办事服务的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E7%9A%84%E6%9E%81%E9%80%9F%E7%89%88app_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/927
- 乡村产业科普的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E7%9A%84%E6%9E%81%E9%80%9F%E7%89%88app_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/vrc
- 安全出行教育的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E7%9A%84%E6%9E%81%E9%80%9F%E7%89%88app_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/ofN
- 城市公共标识的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E7%9A%84%E6%9E%81%E9%80%9F%E7%89%88app_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/177=rqn
- 小区公共照明的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E7%9A%84%E6%9E%81%E9%80%9F%E7%89%88app_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/dew=679
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%B5%9A%E9%92%B1%E6%9C%80%E5%BF%AB%E7%9A%84%E6%9E%81%E9%80%9F%E7%89%88app_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/qCL=0si
- 家庭环保行动的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E5%85%8D%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/094
- 数字学习资源的公共参与指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E5%85%8D%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/wbs
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E5%85%8D%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/SIM
- 课后服务体验的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E5%85%8D%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/051=ojh
- 社区共享书架的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E5%85%8D%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/lhw=926
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E5%85%8D%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/C8g=MCy
- 数字阅读服务的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E5%92%8C%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/540
- 城市公共座椅的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E5%92%8C%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/ytc
- 老年智能设备中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E5%92%8C%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/uFx
- 社区宠物管理的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E5%92%8C%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/007=uqk
- 社区休闲设施中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E5%92%8C%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/dlp=327
- 城市公共座椅的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E5%92%8C%E8%A7%84%E5%88%99_%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/Acy=ioR
- 老年运动活动的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%882024%E4%BA%AE%E7%82%B9_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/407
- 城市生活服务的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%882024%E4%BA%AE%E7%82%B9_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/zjg
- 社区邻里服务的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%882024%E4%BA%AE%E7%82%B9_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/aeY
- 城市博物馆活动的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%882024%E4%BA%AE%E7%82%B9_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/797=dgm
- 电子商务服务的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%882024%E4%BA%AE%E7%82%B9_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/esr=221
- 校园节能行动的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%882024%E4%BA%AE%E7%82%B9_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/xOl=arg
- 社区消防演练的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E7%AE%80%E5%8D%95%E7%8E%A9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/361
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%9C%80%E7%AE%80%E5%8D%95%E7%8E%A9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/pxf

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
