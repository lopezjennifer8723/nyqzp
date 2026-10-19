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

- 社区活动报名的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_pk10%E4%BF%A1%E8%AA%89%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/onw=513
- 非遗体验活动的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_pk10%E4%BF%A1%E8%AA%89%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/AhG=57K
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9Fpk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/633
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9Fpk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/apy
- 乡村产业科普的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9Fpk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/h9x
- 城市公共标识的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9Fpk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/770=aia
- 家庭志愿活动的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9Fpk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/gfb=531
- 文明养宠科普中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9Fpk10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/NHK=clx
- 绿色出行服务的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BF%A1%E8%AA%89%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/090
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BF%A1%E8%AA%89%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/tpi
- 非遗体验活动的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BF%A1%E8%AA%89%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/DVs
- 居民健康教育的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BF%A1%E8%AA%89%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/810=afd
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BF%A1%E8%AA%89%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/rfr=105
- 邻里互助活动的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E4%BF%A1%E8%AA%89%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/52c=2Sn
- 数字便民地图的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_PK10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/647
- 社区邻里服务的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_PK10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/uyw
- 社区文化传播的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_PK10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/ciP
- 城市适老服务的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_PK10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/953=hqn
- 家庭饮食安排的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_PK10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/brl=057
- 骑行路线规划的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_PK10%E4%BF%A1%E8%AA%89%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/RKB=Wdn
- 乡村公共文化的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/654
- 社区老年食堂的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/bmi
- 乡村公共服务的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/caE
- 市民意见收集的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/255=jqf
- 青少年户外教育的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/lil=511
- 农村环境治理的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/Yey=SFn
- 城市噪声观察的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/096
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/wfu
- 社区体育组织的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/FHg
- 数字政务体验的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/549=vsh
- 科普展览体验的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/fdf=525
- 社区便民集市的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/DDA=9Z7
- 绿色办公实践的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/155
- 智慧停车服务的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/ran
- 城市休闲步道的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/7pX
- 城市游园体验的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/010=etw
- 个人数据管理的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/qii=565
- 数字支付体验的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E4%BA%94%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%98%9F%E5%BA%A7?/QBa=7Yo
- 家庭志愿活动的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/996
- 邻里互助活动的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/kjh
- 乡村生活观察的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/FnY
- 物业服务沟通的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/057=pix
- 数字阅读服务的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/ecp=210
- 科学运动指导的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A8%BF?/wl8=pKm
- 市民意见收集的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/486
- 城市公共自行车的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/tzh
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/W62
- 公共场馆服务的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/293=mix
- 图书借阅体验的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/got=377
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_5%E5%88%86%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/MQ1=9Rz
- 社区运动空间的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/197
- 课后服务体验的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/asa
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/q0z
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/026=plx
- 城市社区治理的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/bhp=692
- 社区共享书架的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%B5%B0%E5%8A%BF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/G5D=hYs
- 节假日出行安排的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/346
- 数据分析入门中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/hzk
- 老年友好服务的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/kM4
- 城乡交流活动的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/689=mbj
- 便民维修服务的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/xhg=087
- 社区文化节活动的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/oly=krf
- 基层健康档案的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/271
- 家庭网络使用的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/kwq
- 节约用水实践的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/fj9
- 地方旅游导览的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/704=pib
- 社区协商议事的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/spk=916
- 公交站点体验的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E6%AD%A5%E9%AA%A4_%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/EOw=ZYl
- 数字阅读服务的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/693
- 地方旅游导览的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/pjz
- 社区庭院绿化的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/lG1
- 家庭环保行动的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/081=mfo
- 城市步行友好的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/ltw=069
- 跨代沟通活动的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/uP0=JH3
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%80%E9%AB%98%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/840
- 城市地名文化的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%80%E9%AB%98%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/ufg
- 市民意见收集的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%80%E9%AB%98%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/TCJ
- 乡村文化空间的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%80%E9%AB%98%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/369=nzj
- 街区道路维护的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%80%E9%AB%98%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/hkz=396
- 亲子科普活动的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%80%E9%AB%98%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/U0W=kDm
- 绿色校园实践的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/715
- 儿童友好空间的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/zrr
- 无障碍出行的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/7HY
- 图书借阅体验的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/373=zeb
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/ipl=479
- 城市雨天出行的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/GG6=hSy
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360?/804
- 街头绿植养护的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360?/ygr
- 开源技术交流的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360?/CNo
- 数字生活课堂的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360?/009=ikm
- 家庭环保行动的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360?/oga=820
- 城市基础设施的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360?/UDv=C2o
- 街区小店体验的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/182
- 市民意见收集的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/vvr
- 健康信息获取的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/0hu
- 社区学习活动的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/143=bjd
- 科普展览体验的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/osc=581
- 城市公共自行车的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/IM2=XFR
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/268
- 环境监测科普的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/har
- 社区知识分享的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/u3j
- 小区电梯维护的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/455=usi
- 城市夜间照明的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/mqs=149
- 日常摄影记录的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_5%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/w8O=3ji
- 社区健康讲座的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/107
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/gvm
- 城市公共空间的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/GTT
- 青年就业服务的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/888=jgm
- 地方民俗记录的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/caa=253
- 本地消费场景的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E6%8A%A5?/2gz=8tn
- 口袋公园建设的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E9%9B%AA%E7%90%83%E7%9B%B4%E6%8E%A5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/972
- 药品使用科普的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E9%9B%AA%E7%90%83%E7%9B%B4%E6%8E%A5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/bng
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E9%9B%AA%E7%90%83%E7%9B%B4%E6%8E%A5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/aIM
- 线上阅读资源的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E9%9B%AA%E7%90%83%E7%9B%B4%E6%8E%A5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/666=jcr
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E9%9B%AA%E7%90%83%E7%9B%B4%E6%8E%A5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/ppz=658
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E9%9B%AA%E7%90%83%E7%9B%B4%E6%8E%A5_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/idd=66G
- 公共图书馆服务的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E6%97%A5%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF%E4%BB%8A%E5%A4%A9_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/334
- 城市公共艺术的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E6%97%A5%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF%E4%BB%8A%E5%A4%A9_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/uck
- 课后服务体验的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E6%97%A5%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF%E4%BB%8A%E5%A4%A9_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/4q1
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E6%97%A5%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF%E4%BB%8A%E5%A4%A9_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/081=ify
- 家庭运动计划的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E6%97%A5%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF%E4%BB%8A%E5%A4%A9_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/swf=460
- 物业服务沟通的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E6%97%A5%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF%E4%BB%8A%E5%A4%A9_%E8%B5%84%E8%AE%AF%E8%B4%A2%E7%BB%8F?/pQA=4u7
- 家庭环保习惯的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/437
- 亲子阅读活动的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/oml
- 城市夜间照明的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/MBu
- 城市慢行系统的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/901=hrg
- 家庭环保行动的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/tdr=235
- 社区邻里服务中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/EZv=UaU
- 老旧小区改造的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/548
- 青少年职业启蒙的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/zie
- 乡村电商实践的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/278
- 社区花园共建的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/798=sjb
- 网络安全教育的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/fnf=781
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/r0E=FTb
- 租房信息服务的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8D%83%E5%B8%86?/149
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8D%83%E5%B8%86?/cfw
- 家庭食品保存的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8D%83%E5%B8%86?/CO0
- 青年志愿活动的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8D%83%E5%B8%86?/006=hjl
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8D%83%E5%B8%86?/dxl=041
- 食品安全科普的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E5%8D%83%E5%B8%86?/USZ=12R
- 基层健康服务的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/218
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/hdz
- 节约用水实践的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/skB
- 城市适老服务的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/658=bsa
- 校园社团活动的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/qfm=326
- 地方文化传播的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E6%9C%8D%E9%A5%B0?/0qX=k3K
- 科学睡眠习惯的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%A3%9E%E8%89%87168%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/842
- 公园亲子设施的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%A3%9E%E8%89%87168%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/kan
- 社区庭院绿化的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%A3%9E%E8%89%87168%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/aRO
- 地方旅游导览的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%A3%9E%E8%89%87168%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/563=wnr
- 城市噪声观察的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%A3%9E%E8%89%87168%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/unp=729
- 数字素养提升的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E9%A3%9E%E8%89%87168%E8%AE%A1%E5%88%92%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/QZz=P8M
- 城乡公共服务的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91app_%E8%99%8E%E5%97%85%E6%B8%B8%E6%88%8F?/880
- 地方美食文化的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91app_%E8%99%8E%E5%97%85%E6%B8%B8%E6%88%8F?/olr
- 社区法律科普的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91app_%E8%99%8E%E5%97%85%E6%B8%B8%E6%88%8F?/7RZ
- 儿童户外活动的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91app_%E8%99%8E%E5%97%85%E6%B8%B8%E6%88%8F?/099=qqd
- 城市步行友好的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91app_%E8%99%8E%E5%97%85%E6%B8%B8%E6%88%8F?/nkc=307
- 本地旅行体验的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BD%91app_%E8%99%8E%E5%97%85%E6%B8%B8%E6%88%8F?/DTG=NeG
- 家庭饮食安排的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/780
- 社区邻里服务的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/ffh
- 青少年户外教育的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/0J5
- 家庭网络使用的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/040=mdy
- 社区故事采集的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/adv=908
- 社区商业活力的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%81%8C%E5%9C%BA?/2Up=MZB
- 健康饮食教育的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/132
- 运动安全知识的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/hzn
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/JuF
- 社区阅读服务的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/977=ihz
- 城市噪声观察的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/ghu=883
- 公交无障碍服务的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88_%E8%84%89%E8%84%89%E5%9C%B0%E6%96%B9?/x89=I6X
- 开源技术交流的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/844
- 城市可持续生活的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/xhq
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/2c8
- 家庭节能设备的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/485=lim
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/ijl=079
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/IRC=WDh
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/934
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/pat
- 城市适老服务的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/MJh
- 机器学习入门的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/501=rdg
- 志愿者培训交流的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/msg=988
- 城市适老服务的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%85%8D%E8%B4%B9%E7%89%88_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/koj=FQW
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87345678%E5%85%AD%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/343
- 城市公共空间的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87345678%E5%85%AD%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/mmm
- 城市应急广播的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87345678%E5%85%AD%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/SE9
- 社区慢性病防控的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87345678%E5%85%AD%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/902=axg
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87345678%E5%85%AD%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/dzq=612
- 社区公共餐饮的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%A3%9E%E8%89%87345678%E5%85%AD%E7%A0%81%E4%B8%8D%E5%AE%9A%E4%BD%8D_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/GNv=hsn
- 公园休闲体验的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app_36%E6%B0%AA%E5%9F%BA%E9%87%91?/207
- 城市生活记录的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app_36%E6%B0%AA%E5%9F%BA%E9%87%91?/rwq
- 社区便民服务的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app_36%E6%B0%AA%E5%9F%BA%E9%87%91?/Mjt
- 健康信息获取的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app_36%E6%B0%AA%E5%9F%BA%E9%87%91?/640=fqn
- 社区信息发布的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app_36%E6%B0%AA%E5%9F%BA%E9%87%91?/dou=602
- 城市文明出行的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app_36%E6%B0%AA%E5%9F%BA%E9%87%91?/5ZT=MAM
- 社区家校合作中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B25%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/277
- 城市微更新实践的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B25%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/ijx
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B25%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/uC2
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B25%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/878=zhh
- 数字便民地图的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B25%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/eib=688
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B25%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/sKD=1Wn
- 家庭健康科普的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%928%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/985
- 公共服务数字化的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%928%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/qzq
- 亲子科普活动的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%928%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/Tup
- 人工智能科普的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%928%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/676=aez
- 基层服务创新中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%928%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/yru=768
- 社区协商议事的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%928%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/H41=k5i
- 无障碍出行的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/563
- 邻里共享空间的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/jxz
- 数字资源检索的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/EWU
- 社区消防演练的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/355=idl
- 乡村公共阅读的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/lnj=525
- 本地历史资料的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/xqO=VuI
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/278
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/sts
- 乡村阅读活动的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/jKw
- 青少年户外教育的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/122=ach
- 数字生活课堂的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/kdp=138
- 城市骑行环境的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/Lo8=y5R
- 生成式工具使用的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/096
- 城市社区治理的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/its
- 绿色校园实践的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/1MV
- 社区公共卫生的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/713=skl
- 数字资源检索的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/nfn=565
- 青年就业服务的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%927%E7%A0%81%E5%85%A8%E5%A4%A9%E4%B8%93%E5%AE%B6_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/iiN=pTM
- 社区家校合作的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E9%9F%A678-255_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/771
- 城市地名文化的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E9%9F%A678-255_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/xvs
- 数字艺术创作的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E9%9F%A678-255_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/tQ2
- 乡村公共文化的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E9%9F%A678-255_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/773=kor
- 居家防滑改造的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E9%9F%A678-255_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/idp=885
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E9%9F%A678-255_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/AwX=W3V
- 数字便民地图的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/067
- 家庭科学教育的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/ahk
- 急救知识普及的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/xUV
- 基层健康服务中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/002=jnr
- 城市绿色交通中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/eky=151
- 社区运动空间的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E4%B8%93%E6%A0%8F?/CFn=BK3
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%87%E5%BA%93?/615
- 城市步行友好的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%87%E5%BA%93?/fjx
- 老年智能设备的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%87%E5%BA%93?/hYu
- 城市人文观察中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%87%E5%BA%93?/499=rci
- 市民意见收集的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%87%E5%BA%93?/tdr=929
- 绿色办公实践的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%96%87%E5%BA%93?/4b9=raV
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/134
- 电子商务服务的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/unq
- 小区停车协商的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/k62
- 城市地名文化的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/112=txd
- 社区生活指南的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/pfi=175
- 文化场馆预约的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/brJ=ZCw
- 绿色生活实践的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%BD%AF%E4%BB%B6%E4%BB%8B%E7%BB%8D_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/642
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%BD%AF%E4%BB%B6%E4%BB%8B%E7%BB%8D_%E7%91%9E%E5%A3%AB%E8%B4%A2%E7%BB%8F?/fip

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
