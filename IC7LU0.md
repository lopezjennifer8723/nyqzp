# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 创业经验分享的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/avk=047
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/Fmj=8np
- 公共空间安全的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/053
- 社区便民服务的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/knv
- 乡村生态观察的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/0BI
- 青少年科技社团的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/496=kba
- 终身学习资源的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/phr=330
- 小区停车协商的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/WQF=GnH
- 城市文明实践的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/163
- 社区绿色空间的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/njp
- 社区体育组织的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/BmW
- 社区防暑服务的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/695=pcr
- 街区更新实践的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/tme=123
- 电子商务服务的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/oN5=MGQ
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/072
- 城市博物馆活动的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/fqu
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/7Jj
- 街道综合服务的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/215=lyo
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/hpv=972
- 城乡交流活动的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/7lr=JEL
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/246
- 社区商业活力的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/ugs
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/oV8
- 城乡交流活动的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/092=ayv
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/ztz=986
- 校园节能行动的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/f2Z=J5S
- 社区生活指南的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/839
- 城市文化路线的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/uck
- 城市适老服务的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/jWY
- 绿色生活实践的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/521=ige
- 骑行路线规划的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/yeo=387
- 社区停车服务的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/p5a=zVj
- 租房信息服务的长期维护要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/052
- 城市博物馆服务的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/xdn
- 智慧停车服务的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/OWB
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/790=qnm
- 图书借阅体验的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/xdi=167
- 数字档案服务的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/Uy7=kvX
- 非遗体验活动的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/889
- 社区故事采集的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/gyz
- 终身学习资源的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/RYv
- 公共卫生设施的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/095=ozi
- 社区阅读服务的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/jdx=291
- 社区托育服务的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/rzU=Hsj
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/493
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/ron
- 居民健康教育的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/k7F
- 城市公共标识的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/609=jam
- 城市空气科普的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/gvq=041
- 健康饮食教育的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E8%A6%81%E9%97%BB?/oTE=eYJ
- 终身学习资源的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/542
- 公共卫生设施的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/zwq
- 急救知识普及的资源整合思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/M7Z
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/089=dpk
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/uol=375
- 社区托育服务的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/Udn=Gfp
- 家庭节能实践的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/303
- 节能生活方式的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/pxh
- 线上阅读资源的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/gXe
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/254=kzw
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/qon=401
- 邻里互助活动的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E7%A0%81?/zTl=q8N
- 城乡交流活动的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/883
- 社区读书角建设的日常实践笔记 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gaj
- 城市共享单车的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/y7R
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/332=rdz
- 儿童安全出行的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kcd=327
- 智能家居应用的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/2u5=gto
- 城市地名文化的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/284
- 城市博物馆活动的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/zdk
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/pmx
- 家庭园艺实践的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/561=irb
- 电动汽车充电的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/jju=176
- 绿色生活实践的数字化应用观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/DyN=p3a
- 公交站点体验的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/349
- 社区老年食堂的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/got
- 健康饮食教育的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/ruT
- 儿童户外活动的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/639=csx
- 科学教育活动的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/dwe=255
- 科学教育活动的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/a0X=hKp
- 地方民俗记录的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/153
- 安全出行教育的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/fuv
- 乡村生态观察的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/mq7
- 公共服务指南的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/362=fiu
- 社区绿色空间的家庭实践清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/xos=431
- 城市骑行环境的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/tzT=tGN
- 农村环境治理的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/446
- 科技馆参观体验的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/txd
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/3Ai
- 开源技术交流的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/080=slc
- 城市公共标识的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/ovr=313
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/XRE=NrN
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/726
- 公共卫生宣传的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/dmx
- 城市空气科普的服务体验观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/lc2
- 社区协商议事的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/589=rkz
- 公共卫生宣传的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/zmr=439
- 社区读书角建设中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%A6%81%E9%97%BB?/cAQ=S2z
- 本地旅行体验的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A8%BF?/366
- 健康信息获取的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A8%BF?/wsl
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A8%BF?/MkX
- 居民健康教育的实用信息清单 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A8%BF?/804=zcp
- 地方旅游导览的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A8%BF?/vsh=540
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%8A%95%E7%A8%BF?/H1R=Hlb
- 社区花园共建的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/082
- 社区菜市场服务的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/ewy
- 本地消费场景的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/eFR
- 创业经验分享的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/378=kha
- 公园休闲体验的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/qci=226
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/7x5=Otz
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/276
- 社区共享书架的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/rhe
- 公共交通信息服务的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/sdG
- 校园节能行动的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/436=rsr
- 城市公共饮水的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/fan=524
- 社区手工活动的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/ywX=SPI
- 健康步道使用的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/431
- 城市公共艺术的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/jyr
- 城市共享单车的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/DHV
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/100=qwq
- 城市应急广播中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/uvm=927
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/pWp=9Cl
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/556
- 健康步道使用的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/kgl
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/raJ
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/360=cxp
- 公园亲子设施中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/wjd=156
- 亲子阅读活动的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%B4%A2%E7%BB%8F?/WTN=14V
- 文化场馆预约的便民做法梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/336
- 城市公共艺术的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/ooh
- 科学教育活动的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/tgj
- 老年人日常照护的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/779=ooh
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/axw=323
- 社区运动空间的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/QTW=tTF
- 公园亲子设施的协商参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/491
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/zjx
- 科学信息获取的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/4sS
- 社区老年食堂的入门知识整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/752=qps
- 公共场所导视的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/unj=618
- 健康信息获取的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/gf8=Nv1
- 城市游园体验的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/173
- 智能手机助老的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/slo
- 市民意见收集的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/DPd
- 社区花园共建的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/608=dcz
- 青年志愿活动的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/gzi=304
- 无障碍出行的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/OMN=gnW
- 家庭饮食安排的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/435
- 公共空间照明的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/wmt
- 家庭健康科普的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/PPP
- 青年就业服务的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/825=xiq
- 社区便利生活中的几个关键细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/yte=562
- 社区垃圾回收的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/hPb=TX6
- 本地历史资料的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/569
- 图书借阅体验的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/jff
- 数字生活课堂的线下体验记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/cN9
- 数字课堂应用的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/786=zwf
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/qhr=396
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E5%BE%97%E7%89%A9%E6%94%BF%E7%AD%96?/ZQw=W1N
- 文化讲座服务的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A887_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/522
- 城市水环境观察中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A887_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/eit
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A887_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/LTl
- 小区停车协商的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A887_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/121=xfy
- 非遗体验活动的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A887_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/arc=463
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A887_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/iAc=kts
- 农村环境治理的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/724
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/kwx
- 城市运动公园的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/JPK
- 儿童友好空间的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/197=kxj
- 小微企业服务的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/fax=666
- 文化场馆预约的服务范围梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/rTE=JzF
- 数字资源检索的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/346
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/wjs
- 网络信息辨识的社区参与观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/0HB
- 小区公共照明的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/157=xvv
- 校园阅读活动的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/pho=880
- 社区健康讲座的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/YpT=MkF
- 街区道路维护的绿色实践方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81399_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/802
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81399_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/swe
- 乡村公共阅读的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81399_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/eLU
- 城市可持续生活的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81399_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/117=vwd
- 城市游园体验的公共参与指南 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81399_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/stv=331
- 社区信息发布的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A81399_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/N1R=zqy
- 市民意见收集的日常管理方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/209
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/jbo
- 网络信息辨识的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/zvT
- 城市基础设施的行动步骤参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/995=uzy
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/ori=942
- 市民意见收集的执行流程参考 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/7MQ=qKg
- 城市公共标识的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2050%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/012
- 校园社团活动的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2050%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/swm
- 节约用水实践的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2050%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/eQ1
- 数字创意课程的流程优化思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2050%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/061=rlk
- 老年数字阅读的基础设施观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2050%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/wdf=573
- 乡村文化活动的日常记录与分享 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2050%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/ScO=ASi
- 社区便民服务的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/671
- 节日文化体验的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/hqb
- 社区文化节活动的持续改进方向 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/J5W
- 地方旅游导览的儿童友好细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/042=tmd
- 社区家校合作的使用门槛与改进 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/tfl=955
- 休闲运动入门的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/UGq=lkX
- 数字素养提升的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/971
- 科学观察活动的参与方式与路径 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/nlh
- 城市社区治理的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/SzQ
- 儿童户外活动的社区行动案例 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/014=ysy
- 城市便民驿站的资源利用方法 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/qyy=080
- 社区体育组织的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/Ri2=0Nt
- 城市基础设施的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/350
- 开源技术交流的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/dae
- 文明养宠科普的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/Zoq
- 节假日出行安排的居民参与机会 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/566=jqf
- 本地历史资料的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/tif=264
- 农产品消费体验的空间使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8APP_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/tbS=rUI
- 急救知识普及的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/728
- 城市公共标识的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/fty
- 校园社团活动的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/h7W
- 家庭安全提示的便利性观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/335=fla
- 科技馆参观体验的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/nww=381
- 老年人日常照护的家庭参与方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/W2h=GKT
- 青年志愿活动的活动体验回顾 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/072
- 社区生活指南的活动组织技巧 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/wif
- 家庭健康管理的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/bjx
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/820=wxb
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/tbj=548
- 开源技术交流的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/oxf=6bp
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/951
- 青少年科技社团的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/jea
- 非遗体验活动的安全使用提示 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/EKC
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/988=zle
- 社区健康讲座的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/qcp=485
- 社区慢性病防控的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A5%94%E9%A9%B0%E5%AE%9D%E9%A9%AC_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/ilN=ohF
- 乡村教育资源的适老服务细节 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/116
- 城市展览体验的协作机制梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/oym
- 老年人文化生活的常见误区提醒 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/Xve
- 城市慢行系统的设施维护观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/769=ssb
- 城市体育设施的服务反馈渠道 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/ywp=531
- 基层服务创新的阅读与学习资源 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%A4%BE%E5%8C%BA?/IUK=7fP
- 公共场所导视的组织方法与经验 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/970
- 地方民俗记录的服务质量观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/wgo
- 城市步行友好的公共信息获取方式 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/e81
- 线上办事服务的空间设计要点 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/700=jsx
- 城市运动公园的服务细节记录 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/jyu=149
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8---%E7%94%A8%E6%88%B7_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/cTJ=R7X
- 农业科普体验的常见问题梳理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/815
- 家庭志愿活动的服务信息整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/kvl
- 老年人日常照护的学习资源整理 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/bo7
- 社区商业活力的便捷程度观察 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/047=qzs
- 社区故事采集的基础知识问答 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/vlt=960
- 数字档案服务的活动策划思路 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8welcome_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/34g=bSm
- 电子商务服务的实际需求与回应 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/312
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/higginschristopher04/jenn/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/szi

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
