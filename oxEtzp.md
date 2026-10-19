# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 社区防暑服务的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/yxx=956
- 城市文化路线的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%B8%AF%E8%82%A1?/XUB=obk
- 健康信息获取的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/193
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/uxh
- 邻里互助活动的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/UJ1
- 家庭理财科普的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/652=zot
- 急救知识普及的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/qwc=341
- 节日文化体验的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/aeZ=3j8
- 科学教育活动的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/823
- 家庭教育交流的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/dmk
- 公共场馆服务的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/gti
- 城市博物馆活动的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/729=qpv
- 乡村教育资源的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/ziz=951
- 家庭照护支持的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/Ocs=2Zf
- 公园亲子设施的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/385
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/prw
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/qzP
- 本地旅行体验的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/255=qkg
- 志愿者培训交流的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/amv=821
- 科学教育活动的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/tTd=9jr
- 儿童运动体验的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/855
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/gxn
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/RGs
- 家庭安全提示的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/812=rto
- 节日文化体验的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/hjp=785
- 社区活动策划的资源整合思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/s3G=fNp
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/976
- 科普展览体验的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/ati
- 绿色建筑理念的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/1fN
- 乡村文化空间中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/551=qvw
- 家庭用电安全的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/jku=216
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%9C%9F%E8%B4%A7?/I80=400
- 垃圾分类指导的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/176
- 数字地图应用的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/ava
- 城市生活服务的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/h1d
- 社区养老服务的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/302=ctx
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/pwj=145
- 家庭急救准备的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/v0a=IGD
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/235
- 城市住房服务的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/bxv
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/Skw
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/496=qve
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/ghp=131
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%94%B6%E8%97%8F?/rwu=DIA
- 社区生活指南的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/112
- 周末休闲规划中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/fun
- 城市慢行系统的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/H5L
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/430=rpq
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/dir=601
- 便民服务窗口的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/e5M=hOy
- 家庭环保行动的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/057
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/ele
- 开源技术交流的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/LYI
- 公共图书馆服务的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/684=cly
- 社区科普课堂的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/gkk=466
- 低碳社区实践的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/svj=P3e
- 公共服务指南的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/322
- 公园休闲体验的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/dzw
- 街区道路维护的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/ZgC
- 社区活动报名的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/526=lkm
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/tts=953
- 社区学习活动的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/Vkj=mZF
- 街头绿植养护的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/370
- 社区家政服务的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/mrw
- 社区花园共建的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/P3I
- 城市适老服务的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/816=ubt
- 文化讲座服务的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/akf=519
- 乡村公共服务的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/b0B=vd1
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/820
- 图书馆数字服务的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/vif
- 社区修缮行动的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/DpX
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/023=ntj
- 无障碍信息设计的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/fie=781
- 社区法律科普的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/LGj=T2J
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/862
- 智慧停车服务的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/brc
- 街道综合服务的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/oy2
- 通勤路线规划中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/943=app
- 家庭节能实践的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/uvp=451
- 老年数字阅读中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/01a=yfd
- 城乡公共服务中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/619
- 社区菜市场服务的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/hqj
- 老年友好服务的基础设施观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/vvw
- 家庭健康管理的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/352=yjp
- 公共空间导览的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/iiq=114
- 智慧停车服务的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/NZh=QiJ
- 人工智能科普的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/285
- 社区手工活动的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/mek
- 文化讲座服务的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/6Ej
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/001=paa
- 便民维修服务的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/erb=634
- 应急物资管理的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%85%E6%B8%B8?/QFZ=Aoc
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/837
- 在线学习体验的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/ijc
- 校园安全教育的持续改进方向 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/c4P
- 社区科普课堂的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/803=dfx
- 地方戏曲体验的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/ttc=328
- 城市共享单车的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%B9%A6%E7%94%BB?/a5B=zRu
- 居家防滑改造的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/277
- 社区设施共享的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/nai
- 社区手工活动的活动策划思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/WXk
- 社区养老服务的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/859=wnm
- 个人数据管理的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/guj=864
- 地方文化传播的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%BF%E8%B0%88?/GBv=zDB
- 社区便利生活的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/809
- 公园休闲体验的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/bcn
- 数字便民地图的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/uDt
- 城乡交流活动的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/057=wot
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/ktp=509
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E8%A7%86%E9%A2%91?/OyJ=6vl
- 口袋公园建设的行动步骤参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/449
- 社区学习活动的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rel
- 骑行路线规划的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wfd
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/451=ghr
- 社区宠物管理的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/gmp=080
- 城市人文观察中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/0Xv=s4d
- 城市公共艺术的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/869
- 个人时间管理的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/scn
- 绿色生活实践的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/Rn5
- 校园社团活动的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/003=gff
- 节假日出行安排的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/rtm=912
- 生活服务数字化的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/tZf=b9d
- 社区家政服务中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/455
- 公共交通接驳的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/rvy
- 社区邻里服务的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/0tc
- 乡村文化空间的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/565=abw
- 城市骑行环境的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/bxy=766
- 公交站点体验的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/nwe=opv
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/396
- 租房信息服务的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/lwj
- 城市水环境观察的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/qql
- 数字便民地图的安全使用提示 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/768=usl
- 信息无障碍体验的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/zuh=718
- 低碳社区实践的社区行动案例 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/SXz=ozd
- 街区道路维护的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/974
- 社区生活指南的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/don
- 学校体育活动的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/Ue7
- 社区志愿服务的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/799=qsp
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/yfq=309
- 口袋公园建设的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/SRV=okY
- 青少年科技社团的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/779
- 节日文化体验的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/ucy
- 智能手机助老中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/5dD
- 乡村生态旅游的基础知识问答 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/477=vmr
- 终身学习资源的服务体验观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/pbz=448
- 社区消防演练的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/a4R=xOJ
- 城市步行友好中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/883
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/lcj
- 城市人文观察的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/rdw
- 儿童友好空间的参与方式与路径 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/788=zfp
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/yvs=351
- 课后服务体验的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/6Kq=RX4
- 老年人日常照护的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/879
- 青年志愿活动中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/ncz
- 数字创意课程的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/xcS
- 家庭科学教育的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/893=ukc
- 健康饮食教育的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/vyi=176
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/0JH=GFw
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/722
- 城市噪声观察的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/odo
- 社区运动空间的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/oGn
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/155=nkl
- 本地旅行体验的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/zck=100
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/ZS1=5i4
- 新能源出行的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/394
- 数字创作工具的家庭参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/vgo
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/Lc6
- 市民热线服务的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/579=plo
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/yda=945
- 绿色建筑理念的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/3FD=iNB
- 城市公共标识的协作机制梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%85%83%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/236
- 小区电梯维护的适老服务细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%85%83%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/tya
- 休闲运动入门的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%85%83%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/JsX
- 公共服务评价的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%85%83%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/060=cht
- 城市绿色交通中的沟通与协作 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%85%83%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/vcn=456
- 社区设施共享的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%85%83%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/jML=PJw
- 居民健康教育的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%85%83%E5%85%85%E5%80%BC%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%94%90%E8%AF%84?/239
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%85%83%E5%85%85%E5%80%BC%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%94%90%E8%AF%84?/msr
- 周末休闲规划的便捷程度观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%85%83%E5%85%85%E5%80%BC%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%94%90%E8%AF%84?/TcL
- 本地旅行体验的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%85%83%E5%85%85%E5%80%BC%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%94%90%E8%AF%84?/147=dur
- 社区交通安全的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%85%83%E5%85%85%E5%80%BC%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%94%90%E8%AF%84?/fdg=440
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%B8%80%E5%85%83%E5%85%85%E5%80%BC%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E9%94%90%E8%AF%84?/HnQ=0Dl
- 食品安全科普的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/465
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/aih
- 在线教育体验的日常管理方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/749
- 小区停车协商的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/099=fry
- 地方旅游导览的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/oab=470
- 公共场馆服务的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%8E%A2%E6%BA%90?/7hs=OZU
- 乡村公共服务的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/834
- 社区慢性病防控的居民参与机会 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/ghh
- 社区儿童活动的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/eVY
- 个人数据管理的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/179=qmx
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/arq=861
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_9%E4%BA%BF%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/n2w=YdJ
- 通勤路线规划的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/538
- 青少年科技社团的入门知识整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/piu
- 社区安全巡查的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/zdS
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/429=lan
- 社区活动报名的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/jxo=580
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/CyK=8cz
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/382
- 医院导诊服务的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/hxx
- 老年人文化生活的资源利用方法 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/pBf
- 图书借阅体验的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/154=lhl
- 家庭教育交流的设施维护观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/cpa=772
- 医院导诊服务的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/qt5=yKX
- 本地旅行体验的社区参与观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E5%8F%97%E6%AC%A2%E8%BF%8E%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/611
- 青少年心理健康的实际需求与回应 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E5%8F%97%E6%AC%A2%E8%BF%8E%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/nyy
- 信息无障碍体验的执行流程参考 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E5%8F%97%E6%AC%A2%E8%BF%8E%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/TPa
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E5%8F%97%E6%AC%A2%E8%BF%8E%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/434=xmz
- 健康饮水科普的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E5%8F%97%E6%AC%A2%E8%BF%8E%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/tfg=253
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E5%8F%97%E6%AC%A2%E8%BF%8E%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/3RT=H4I
- 绿色出行服务的空间使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8D%81%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%B0%E8%AF%BB?/602
- 儿童安全出行的服务质量观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8D%81%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%B0%E8%AF%BB?/cxm
- 公共空间安全的线下体验记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8D%81%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%B0%E8%AF%BB?/l2P
- 城市绿色交通的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8D%81%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%B0%E8%AF%BB?/310=vwk
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8D%81%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%B0%E8%AF%BB?/lih=579
- 城乡交通衔接的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%8D%81%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%95%B0%E8%AF%BB?/l8W=kAt
- 城市基础设施的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/674
- 公共设施维护的常见问题梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/eyi
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/JXU
- 城市可持续生活的家庭实践清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/183=qkh
- 社区互助网络的服务范围梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/hsz=236
- 农贸市场环境的日常使用指南 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/Ml4=NXj
- 传统手工艺体验的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/384
- 绿色快递包装的便利性观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/med
- 公交无障碍服务的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/fjh
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/459=gsi
- 老年人文化生活的协商参与方式 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/vsd=658
- 文化场馆预约的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/S71=93b
- 社区心理支持的数字工具使用体验 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/671
- 休闲运动入门的日常记录与分享 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/nqq
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/pet
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/391=rgm
- 口袋公园建设的便民做法梳理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/mex=369
- 老年数字阅读的长期维护要点 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/0Xn=EH4
- 公交无障碍服务的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/864
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/ntl
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/lA3
- 电动汽车充电的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/715=tsg
- 社区科普课堂的流程优化思路 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/ewj=503
- 数字阅读服务的常见误区提醒 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/TuE=reA
- 本地旅行体验的活动体验回顾 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/898
- 骑行路线规划的实用信息清单 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/hwi
- 骑行路线规划的服务信息整理 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/k9B
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/496=gnf
- 青年就业服务的阅读与学习资源 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/hfm=831
- 儿童安全出行的数字化应用观察 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/kg3=pTb
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/695
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/hendersonmackenzie56/kpoz/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/lik

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
