# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 智慧停车服务的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/Hra
- 社区共享书架的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/674=opc
- 社区庭院绿化的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/jpp=024
- 城市雨天出行的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/Alr=EnG
- 校园节能行动的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/878
- 城市公共座椅的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/yil
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/Qum
- 社区消防演练的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/168=xrr
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/jeg=891
- 开源技术交流的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/aVO=E8i
- 家庭环保行动的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/139
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/nid
- 旧物循环利用的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/njN
- 数字素养提升的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/668=haf
- 公共设施使用的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/rdw=647
- 社区艺术活动的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%A4%B4%E6%9D%A1?/BZC=PzS
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/576
- 家庭节能实践的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/iex
- 地方文化传播的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/CEv
- 在线学习体验的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/326=fbu
- 家庭节能实践的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/chs=543
- 乡村阅读活动的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/Rys=gbg
- 科学观察活动的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/079
- 社区垃圾分类的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/hbp
- 医院导诊服务的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/krP
- 城市文明出行中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/726=hbx
- 无障碍信息设计的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/uoa=684
- 公共场所导视的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%B0%8A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/LM0=TNK
- 城市文化路线的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/846
- 城市公共自行车的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/ndm
- 老年人出行服务的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/JBi
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/359=vxt
- 家庭照护支持的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/qra=550
- 社区儿童活动的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/xMV=JRG
- 青年志愿活动的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/602
- 城乡交流活动的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/jkx
- 在线教育体验的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/JAj
- 休闲运动入门的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/020=bnq
- 无障碍出行的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pbu=782
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Qy4=Jjn
- 公园亲子设施的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/073
- 社区活动报名的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/min
- 公交站点体验的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/gox
- 青少年科普实践的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/004=kfx
- 公共卫生宣传的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/gpo=723
- 城市绿色交通的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/KDH=I4M
- 城市体育设施的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/907
- 城市水环境观察中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/xec
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/Sdz
- 社区老年食堂的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/131=xsk
- 机器学习入门的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/fnx=612
- 城市文化路线的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/8Fk=zo9
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/767
- 社区心理支持的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/myb
- 职业技能学习的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/oh6
- 社区故事采集的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/434=zbq
- 青年职业探索的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/hic=368
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E7%BE%8E%E8%82%A1?/58Q=R5S
- 社区公共卫生的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/401
- 城市共享单车的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/ipt
- 城市公共空间的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/1jV
- 科学教育活动的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/204=tzz
- 社区庭院绿化的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/ycs=915
- 家庭饮食安排的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/vOy=cLp
- 社会体育指导的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/718
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/jdp
- 老年人文化生活的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/Jry
- 城市地名文化的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/475=zqg
- 农产品消费体验的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/yzo=092
- 城市公共艺术的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B0%8A%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/vAd=rO5
- 校园节能行动的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/148
- 街道综合服务的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/sys
- 城市步行友好的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/vDI
- 城市地名文化的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/227=rjr
- 家庭饮食安排的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/pxx=417
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/ONo=hto
- 社区活动报名的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/860
- 社区活动空间的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/gog
- 社区教育资源的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/dz2
- 社区托育服务的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/643=opv
- 志愿服务平台的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/fzn=748
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%B0%8A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/3nW=xwY
- 家庭网络使用的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/104
- 灵活就业交流的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/mrl
- 开放数据应用的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/OG3
- 城市噪声观察的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/471=buw
- 社区体育组织的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/yhg=510
- 食品安全科普的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/mRR=le2
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/564
- 周末休闲规划的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/mhg
- 城市慢行系统的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/Tl8
- 城市住房服务的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/209=yue
- 城市公共标识的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/odw=385
- 家庭用电安全的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%80%BA%E5%B8%82?/6JR=t3Z
- 科学观察活动的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/284
- 社区活动策划的便捷程度观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/quv
- 基层健康服务的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/JM3
- 社区手工活动的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/090=jzp
- 智慧停车服务的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/xog=130
- 就业技能培训的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/oFf=l3Z
- 学校食育活动的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/993
- 节能生活方式的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/sru
- 校园社团活动的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/QUD
- 乡村阅读空间的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/818=sjl
- 家庭收纳实践的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/yki=576
- 数字支付体验的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/YRu=amv
- 青少年心理健康的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/956
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/zfm
- 地方文化传播的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/p20
- 学校食育活动的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/011=oyo
- 城市共享单车的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/guj=284
- 城市游园体验的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/75n=tCh
- 公共空间休憩的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/674
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/prd
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Fa6
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/390=ogi
- 社区协商议事中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/gln=399
- 公园亲子设施的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%AD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/aCO=tOI
- 终身学习资源的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/850
- 社区垃圾分类的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/dew
- 光伏知识科普的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/1V1
- 家庭收纳实践的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/923=sog
- 电子商务服务的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/zro=697
- 儿童友好空间的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/GcG=r4l
- 气象科普传播的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/875
- 终身学习资源的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/efe
- 老年数字阅读的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/afQ
- 社区文化传播的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/149=unr
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/nim=469
- 居家适老化改造的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/AdO=x54
- 绿色消费选择的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/418
- 农产品消费体验的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/xjf
- 线上办事服务的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/o7s
- 儿童友好空间的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/800=qxb
- 儿童安全出行的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/bob=402
- 城市住房服务的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/BHc=hV5
- 公共交通信息服务的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/981
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/uif
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Ohb
- 社区邻里服务的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/269=bor
- 城市微更新实践的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fem=726
- 本地旅行体验的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/P9D=2XE
- 城市慢行系统的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/004
- 数字政务体验的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/pxg
- 生活垃圾减量的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/4MG
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/782=typ
- 社区家校合作的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/ome=430
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/hF9=erg
- 公共服务预约的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/640
- 社区信息发布的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/hec
- 科学运动指导中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/f7A
- 社区防暑服务的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/347=avl
- 科学信息获取的便捷程度观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/lku=860
- 数字政务体验的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E7%83%AD%E6%A6%9C?/gKQ=7Oj
- 公共服务预约的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/280
- 基层健康服务的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/ijo
- 环境教育课程的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/Hcf
- 老年友好服务的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/942=sdv
- 全民阅读推广的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/fka=935
- 城市农夫市集的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%B6%88%E8%B4%B9?/ss5=cb1
- 消防知识宣传的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/269
- 公共服务咨询的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/hvm
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/rZ3
- 便民服务窗口的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/914=svm
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/vff=086
- 城市噪声观察的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/L7y=QEp
- 个人时间管理的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/788
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/ouw
- 智慧城市体验的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/hQ8
- 基层健康服务的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/714=bef
- 校园节能行动的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/qsp=191
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/ya3=850
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/444
- 青年职业探索的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/jph
- 校园社团活动的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/m0L
- 健康信息获取的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/453=mub
- 电子商务服务的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/dri=645
- 新能源知识普及的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/4Rq=IWg
- 学校食育活动的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/377
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/asf
- 新能源出行中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/f64
- 青年职业探索的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/399=xpc
- 城乡公共服务的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/wnm=545
- 新能源知识普及的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/Xbg=ckG
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/287
- 数字创意课程的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/qds
- 乡村公共阅读的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/dhM
- 口袋公园建设的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/970=vvn
- 家庭运动计划的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/jbl=508
- 文明养宠科普中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/OsY=IuH
- 城市步行环境的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/207
- 家庭食品保存的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/xjh
- 居民健康教育的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/w1D
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/245=gdx
- 社区活动报名的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/ahm=131
- 便民维修服务的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B0%8A%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/8QW=v0B
- 节假日出行安排的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/529
- 城市文明实践的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/aqe
- 家庭急救准备的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/2fD
- 城市文明出行的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/853=err
- 户外活动组织的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/gmt=990
- 公共服务预约的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/Jn0=Om3
- 社会体育指导的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/630
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/jfo
- 家庭运动计划的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/0kk
- 社区共享书架的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/673=jks
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/omm=368
- 学校食育活动的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/QjY=xmb
- 图书借阅体验的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/039
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/hle
- 城市便民驿站的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/W6k
- 网络信息辨识的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/194=opr
- 社区故事采集从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/dkn=982
- 城乡交流活动的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/p99=WoF
- 生成式工具使用的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/144
- 老年数字阅读的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/hlp
- 家庭健康科普的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/V6L
- 市民意见收集的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/204=ksc
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/ttt=083
- 社区手工活动的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/l1V=L2y
- 青少年心理健康的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/846
- 社区运动空间的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/kxj
- 旧物循环利用的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/oEE
- 公共空间休憩的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/988=zxz
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/wqz=917
- 街道综合服务的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/xPL=ts2
- 网络安全教育的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/058
- 校园社团活动的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/mbv
- 社会体育指导的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/99h
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/323=awz
- 乡村公共服务的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/ybu=455
- 老年人日常照护的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%A1%A3%E6%A1%88?/x4u=odQ
- 学校食育活动的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/603
- 城市公共自行车的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/sbt
- 城市微更新实践的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/70x
- 医院导诊服务的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/455=eti
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/sho=925
- 城市慢行系统的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/qB3=oaf
- 节假日出行安排的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/134
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/jwu
- 社区运动空间中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/Q4D
- 社区运动空间的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/084=jof
- 家庭环保习惯的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/jpf=088
- 读书会组织的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ljJ=aQm
- 城市可持续生活的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/822
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/dcn
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/hig
- 城市生活记录的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/679=spy
- 人工智能科普的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/ois=879
- 居家适老化改造的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E4%B8%AD%E5%85%B4%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/b8M=3hm

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
