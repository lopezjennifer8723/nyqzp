# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 公园亲子设施的参与方式与路径 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/hnm=104
- 社区公共卫生的日常使用指南 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/tK8=ohr
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/422
- 青年志愿活动的线下体验记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/pow
- 城市可持续生活的学习资源整理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/BKf
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/740=gbm
- 社区信息发布的空间设计要点 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/cdk=502
- 老年人出行服务的资源整合思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/VDD=S6d
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/951
- 公益活动组织的公共参与指南 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/mvf
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/uJt
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/109=lpl
- 家庭消费规划的持续改进方向 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/rds=021
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%AF%84%E8%AE%BA?/iCT=ST9
- 学校食育活动的便捷程度观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/013
- 城市社区治理的服务范围梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/jmn
- 社区家校合作的线下体验记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/47s
- 儿童友好街区的实际需求与回应 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/597=jod
- 基层医疗预约的便民做法梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/nmf=373
- 个人信息保护的安全使用提示 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/eFV=cF9
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/823
- 老年人日常照护的便民做法梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/ims
- 非遗课堂体验的空间设计要点 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/01w
- 社区信息发布的协作机制梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/674=dqg
- 社区家政服务的日常使用指南 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/wel=527
- 数字创作工具的常见误区提醒 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/eIv=8jT
- 老旧小区改造的流程优化思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/517
- 社区生活指南的执行流程参考 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/aeb
- 无障碍出行的基础知识问答 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/an6
- 青年就业服务的服务细节记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/588=ltk
- 数字生活课堂的适老服务细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/dot=842
- 课后服务体验的实际需求与回应 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/RUs=Xuq
- 城市微更新实践的服务质量观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/552
- 乡村公共文化的实用信息清单 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/hmr
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/HY9
- 社区知识分享的安全使用提示 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/649=jxg
- 乡村文化活动的日常管理方法 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/zdn=160
- 低碳社区实践的常见问题梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/bbn=5Mx
- 终身学习资源的家庭参与方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/582
- 街区小店体验的日常实践笔记 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/csc
- 家庭节能实践的空间使用体验 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/tur
- 家庭阅读计划的参与方式与路径 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/120=msn
- 城市运动公园的社区参与观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/vdv=302
- 城市建设科普的资源整合思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/6ok=ulY
- 周末休闲规划的便捷程度观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/291
- 远程协作工具的社区参与观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/xpn
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/Q4I
- 便民服务地图的空间使用体验 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/284=ega
- 城市生活服务的线下体验记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/fsm=315
- 乡村教育资源的服务体验观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/7hF=Vy0
- 社区应急准备的日常记录与分享 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/908
- 公共服务指南的社区行动案例 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/dty
- 健康饮食教育的日常记录与分享 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/t0h
- 社区科普课堂的便捷程度观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/556=map
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/lub=815
- 终身学习资源的居民参与机会 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/ko3=Hgn
- 公共服务沟通的服务细节记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/876
- 地方美食文化的社区行动案例 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/vck
- 读书会组织的活动组织技巧 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/IfA
- 家庭节能实践的数字化应用观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/689=yat
- 个人信息保护的线下体验记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/eus=682
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/TBe=XAP
- 社区交通安全的社区参与观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/318
- 公共场所导视的服务体验观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/jxi
- 城乡交流活动的入门知识整理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/v4B
- 社区托育服务的居民参与机会 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/574=una
- 城市空气科普的日常管理方法 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/zyj=869
- 社区阅读服务的基础知识问答 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/gIs=sDs
- 公共交通信息服务的执行流程参考 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/154
- 街区道路维护的服务反馈渠道 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/gjs
- 社区垃圾分类的适老服务细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/nzR
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/688=jci
- 远程协作工具的日常使用指南 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/daj=674
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/uXr=gKd
- 开放数据应用的便民做法梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/617
- 地方旅游导览的数字化应用观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/riv
- 公共空间照明的便利性观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/pfo
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/782=gue
- 地方文化传播的常见问题梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/cvn=270
- 城市步行友好的家庭实践清单 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/axu=c40
- 城市文化路线的空间使用体验 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/439
- 乡村教育资源的家庭参与方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/vvc
- 便民信息查询的实际需求与回应 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/c6F
- 便民服务窗口的持续改进方向 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/137=qei
- 农业科普体验的长期维护要点 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/nss=745
- 城市共享单车的常见误区提醒 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E4%B8%93%E9%A2%98?/Y3W=DGe
- 家庭节能设备的空间使用体验 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/170
- 城市公共标识的便民做法梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/iic
- 城市公共厕所的日常实践笔记 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/qJ5
- 旧物循环利用的活动策划思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/729=gpw
- 科学观察活动的服务范围梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/bjr=790
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/Uw4=ByI
- 生活技能分享的协作机制梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/319
- 社区花园共建的便利性观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/fje
- 社区科普课堂中的几个关键细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/tzj
- 社区设施共享中的几个关键细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/711=bls
- 生活服务数字化的设施维护观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/djp=424
- 青年职业探索的数字工具使用体验 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/PDz=kwp
- 家庭运动计划的家庭参与方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/439
- 个人数据管理的阅读与学习资源 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/hwr
- 乡村产业科普的实用信息清单 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/7QJ
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/128=wfd
- 城市夜间生活的安全使用提示 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/rnv=618
- 老年智能设备的常见问题梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/feh=Ljh
- 城市水环境观察的空间使用体验 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/014
- 基层健康档案的日常实践笔记 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/ikk
- 数字阅读服务的服务体验观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/Icm
- 智慧停车服务的常见误区提醒 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/856=wuo
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/lvg=153
- 公共服务沟通的绿色实践方法 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%8F%E6%B5%8E?/8hh=mYA
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/874
- 城市公共座椅的居民参与机会 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/spd
- 无障碍信息设计的基础知识问答 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/Y1a
- 社区便民服务的阅读与学习资源 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/384=yng
- 便民服务窗口的适老服务细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/oou=790
- 城市博物馆活动的空间设计要点 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/TJI=M5j
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/924
- 社区老年食堂的协商参与方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/adq
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/741
- 地方美食文化的家庭参与方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/776=wbf
- 公共健身器材的适老服务细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/ugf=737
- 智能手机助老的活动体验回顾 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/9v1=vRX
- 急救知识普及的协商参与方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/468
- 应急物资管理的常见误区提醒 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/cdi
- 公园亲子设施的便民做法梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/J7G
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/329=dhu
- 便民信息查询的服务范围梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/miu=080
- 社区文化节活动中的几个关键细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0?/mKA=ckX
- 青少年户外教育的线下体验记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/955
- 社区教育资源的便捷程度观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/mvf
- 青年职业探索的服务范围梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/70R
- 城市博物馆活动的日常使用指南 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/917=kqf
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/yok=305
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%90%89%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E7%A8%8E%E5%8A%A1?/ejB=OVv
- 本地消费场景的适老服务细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/751
- 社区托育服务的服务质量观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/hst
- 乡村阅读活动的适老服务细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/3BE
- 通勤路线规划的空间设计要点 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/413=bfb
- 租房信息服务的线下体验记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/pnj=416
- 绿色办公实践的协作机制梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/0DH=CBp
- 文明养宠科普的日常管理方法 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/618
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/djg
- 社区共享书架的数字化应用观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/751
- 基层服务创新的使用门槛与改进 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/627=tyc
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/bmn=767
- 城市夜间照明的服务细节记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/PzU=2ZM
- 城市休闲步道的学习资源整理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/290
- 生活服务数字化的社区行动案例 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/gng
- 校园社团活动的使用门槛与改进 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/nA4
- 社区艺术活动的服务质量观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/140=oed
- 社区手工活动的便捷程度观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/pdl=463
- 街道综合服务的设施维护观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/nIU=P67
- 在线教育体验的居民参与机会 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/393
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/qya
- 社区停车服务的数字化应用观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/Eyk
- 社区设施共享的绿色实践方法 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/676=npb
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/jlv=505
- 智慧停车服务的儿童友好细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/PKm=0Cx
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/852
- 公共服务咨询的常见问题梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/mlc
- 乡村生活观察的常见误区提醒 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/rLq
- 周末休闲规划的日常记录与分享 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/302=bbw
- 传统节日科普的社区行动案例 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/eep=607
- 机器学习入门的适老服务细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E9%80%9A%E4%BF%A1?/iu7=vpF
- 乡村生态观察的服务范围梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/667
- 节假日出行安排中的几个关键细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/hry
- 社区快递服务中的几个关键细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/LAM
- 生活服务数字化的流程优化思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/055=bhv
- 在线教育体验的日常管理方法 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/ljs=870
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E4%BA%BA%E5%A4%A7?/6G2=xCq
- 城市博物馆服务的持续改进方向 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/494
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/cru
- 青少年编程学习的服务细节记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/JMW
- 社区商业活力的安全使用提示 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/900=cbu
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/otc=362
- 公园亲子设施的便捷程度观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/18O=Qan
- 便民服务窗口的儿童友好细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/807
- 家庭养老规划的日常记录与分享 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/nzq
- 社区艺术活动的便利性观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/bAT
- 读书会组织的安全使用提示 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/570=luq
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/jzo=600
- 非遗课堂体验的公共参与指南 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%9C%AD%E8%AE%B0?/mpp=HPK
- 通勤路线规划的学习资源整理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/265
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/hcm
- 家庭园艺实践的便利性观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/gHq
- 公益活动组织的儿童友好细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/445=ldc
- 绿色生活实践的学习资源整理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/vpd=426
- 社区菜市场服务的流程优化思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/N9D=euQ
- 文化场馆预约的线下体验记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/593
- 口袋公园建设的绿色实践方法 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/ete
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/7E5
- 图书借阅体验的活动策划思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/228=urv
- 城市骑行环境的行动步骤参考 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/gry=615
- 数字创意课程的行动步骤参考 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/6H0=UvV
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/432
- 家庭运动计划的协作机制梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/djw
- 物业服务沟通的参与方式与路径 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/Bpb
- 应急物资管理的数字工具使用体验 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/481=rup
- 城市公共饮水的数字化应用观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/vsk=078
- 社区教育资源的服务范围梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/u0G=fko
- 社区公共议事的行动步骤参考 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/203
- 开放数据应用的使用门槛与改进 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/dkt
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/IJO
- 个人信息保护的社区行动案例 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/365=zdn
- 社区公共卫生的学习资源整理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/rtm=302
- 科普展览体验的家庭实践清单 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/X6j=6Ck
- 社区快递服务的服务反馈渠道 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/837
- 生成式工具使用的公共参与指南 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/wcm
- 科学运动指导的活动策划思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/k0c
- 机器人科普活动的日常管理方法 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/437=ibj
- 家庭理财科普的便利性观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/exe=823
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%AF%BB%E5%9B%BE?/wMa=JUE
- 地方旅游导览的便民做法梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/426
- 老年数字阅读的便民做法梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/xwx
- 老年智能设备的协商参与方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/wg2
- 公共空间安全的适老服务细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/313=szx
- 亲子科普活动的资源整合思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/bjv=624
- 社区运动空间的绿色实践方法 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/Lnx=ysH
- 社区便民集市的家庭实践清单 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E7%9B%B4%E6%92%AD?/997
- 老年数字阅读的便利性观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E7%9B%B4%E6%92%AD?/nym
- 基层医疗预约的活动体验回顾 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E7%9B%B4%E6%92%AD?/LHu
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E7%9B%B4%E6%92%AD?/833=kug
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E7%9B%B4%E6%92%AD?/zyl=499
- 物业服务沟通的服务体验观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E7%9B%B4%E6%92%AD?/XZa=5dl
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/271
- 社区快递服务的儿童友好细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/ncc
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/QaB
- 城市水环境观察的日常实践笔记 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/261=ckr
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/oht=499
- 青年志愿活动的实用信息清单 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%94%B6%E8%97%8F?/wdT=2R4
- 城市建设科普的便民做法梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/379
- 城市树木认养的线下体验记录 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/qpp
- 科学教育活动的便利性观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/rsk
- 公共文化活动的常见问题梳理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/247=vtw
- 智慧城市体验的入门知识整理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/fqz=715
- 在线学习体验的社区行动案例 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/5Pe=OHg
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/942
- 传统节日科普的组织方法与经验 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/buw
- 城市休闲步道的流程优化思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/ryS
- 地方民俗记录的执行流程参考 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/241=ajd
- 城市适老服务的儿童友好细节 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/oap=274
- 地方民俗记录的流程优化思路 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/P5J=ueC
- 社区消防演练的执行流程参考 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/161
- 数字素养提升的日常实践笔记 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/sjv
- 乡村公共阅读的学习资源整理 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/Q1P
- 公共卫生宣传的长期维护要点 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/114=xoq
- 家庭养老规划的日常实践笔记 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/kae=773
- 城市应急科普的服务体验观察 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/qYj=CEA
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E8%83%BD%E6%BA%90?/648
- 城市社区治理的活动组织技巧 |来源：https://github.com/andrewsgrace279/zwxc/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%90%89%E7%A5%A5%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%BF%85%E5%BA%94%E8%83%BD%E6%BA%90?/gvw

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
