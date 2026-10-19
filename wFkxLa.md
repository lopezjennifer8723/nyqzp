# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:31**

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

- 老年人日常照护的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/etR
- 农贸市场环境的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/447=hhi
- 老年学习活动的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/rdd=011
- 科学观察活动的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E5%A4%AE%E8%A7%86%E5%AE%B6%E7%94%B5?/0O3=VZL
- 城市微更新实践的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/954
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/svd
- 社区家政服务中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/2eW
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/492=gle
- 城市基础设施的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/mrt=662
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%9B%BE%E9%89%B4?/W85=wDb
- 亲子科普活动的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/089
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/jhb
- 家庭急救准备的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/O3m
- 社区设施共享的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/181=yeu
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/jdd=808
- 社区志愿服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/lli=H1Y
- 家庭消费规划的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%8F%B8%E6%B3%95?/774
- 个人信息保护的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%8F%B8%E6%B3%95?/pxz
- 开放数据应用的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%8F%B8%E6%B3%95?/tBM
- 数字阅读服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%8F%B8%E6%B3%95?/216=gtk
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%8F%B8%E6%B3%95?/jqc=299
- 数字档案服务的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E5%8F%B8%E6%B3%95?/Fyg=uqe
- 社区停车服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/349
- 儿童阅读角的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/npr
- 城市建设科普的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/pda
- 公共空间照明的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/691=yie
- 农产品消费体验的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/cog=686
- 远程协作工具的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/48Z=nz3
- 城市公共厕所的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/723
- 青少年户外教育的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/gdz
- 城市建设科普的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/xry
- 公共服务评价的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/284=dmo
- 邻里共享空间的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/vok=937
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/QS2=1wr
- 科学健身方法的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/330
- 电子商务服务的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/njl
- 数据分析入门的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/ePS
- 校园节能行动的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/373=vxi
- 老年人出行服务的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/nmr=223
- 社区应急准备的便捷程度观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_1%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/blf=aAB
- 社区应急准备的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/472
- 就业技能培训的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/lkd
- 网络安全教育的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/7QA
- 老年人日常照护的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/893=xsn
- 公共设施维护的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/iea=547
- 老年人出行服务的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%8D%B3%E5%88%BB%E7%BE%8E%E5%A6%86?/fcj=TtT
- 地方美食文化的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/574
- 居家适老化改造的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/nuo
- 社区儿童活动的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/T6w
- 节能生活方式的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/533=eaa
- 智能手机助老的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/dqf=910
- 生活技能分享的服务细节记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8A%A1?/0so=G2V
- 文明养宠科普的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/210
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/qit
- 城市地名文化的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/hww
- 终身学习资源的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/699=xkz
- 青少年户外教育的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/pgq=197
- 公共空间安全的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E5%8E%86%E5%8F%B2?/tNI=Kd7
- 数字便民地图的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/397
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/hue
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/MUv
- 租房信息服务的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/029=hip
- 社区活动策划的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/jnn=801
- 乡村生活观察的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/j7L=Cx6
- 公园休闲体验的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/172
- 绿色出行服务的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/wpf
- 在线学习体验的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/pVL
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/689=zmv
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/pft=980
- 新能源知识普及的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%A1%A3%E6%A1%88?/1U7=DVm
- 市民热线服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3qq%E7%BE%A4_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/149
- 健康饮食教育的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3qq%E7%BE%A4_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/hzv
- 通勤路线规划的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3qq%E7%BE%A4_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/unD
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3qq%E7%BE%A4_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/840=fsx
- 电子商务服务的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3qq%E7%BE%A4_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/qan=037
- 科学睡眠习惯的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3qq%E7%BE%A4_36%E6%B0%AA%E5%9B%9E%E6%9C%9B?/bR9=RBN
- 远程协作工具的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/375
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/kkf
- 家庭阅读计划的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/gOl
- 农产品品牌传播的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/082=tya
- 本地消费场景中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/xkw=810
- 青年就业服务的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BA%A4%E6%B5%81%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/WCM=EDW
- 垃圾分类指导的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/333
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/eyw
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/QO7
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/311=jep
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/pdn=481
- 社区体育组织的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/8rG=u16
- 城市水环境观察的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/077
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/xpm
- 城市步行友好的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/HmX
- 家庭环保行动的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/005=xfc
- 公共设施使用的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/yqx=908
- 市民意见收集的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3qq%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E5%85%9A%E5%BB%BA?/HZL=JJf
- 乡村公共服务的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%AC%E4%B8%9C?/969
- 公共服务数字化的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%AC%E4%B8%9C?/erg
- 家庭饮食安排的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%AC%E4%B8%9C?/VZD
- 便民维修服务的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%AC%E4%B8%9C?/977=hkw
- 户外活动组织的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%AC%E4%B8%9C?/eoh=460
- 绿色办公实践的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%AC%E4%B8%9C?/aWD=sdi
- 文化场馆预约的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%BE%92_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/331
- 青少年科普实践的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%BE%92_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/ian
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%BE%92_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/OUF
- 公共服务评价的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%BE%92_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/381=uad
- 社区教育资源的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%BE%92_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/cpm=779
- 社区运动空间的实用信息清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%BE%92_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/i1n=CLV
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/015
- 无障碍出行的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/ide
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/tr4
- 数字便民地图的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/616=lch
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/ufv=481
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/L5m=D36
- 数字阅读服务的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/256
- 数字艺术创作的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/dbq
- 数字公共文化的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/EG7
- 社区应急准备的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/483=zls
- 家庭安全提示的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/zdo=453
- 数字便民地图的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%A2%AB%E9%AA%97%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/aCt=Sjq
- 家庭饮食安排的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E7%9A%84QQ%E5%8F%B7_%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/920
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E7%9A%84QQ%E5%8F%B7_%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/mkk
- 城市慢行系统的协作机制梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E7%9A%84QQ%E5%8F%B7_%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/Zux
- 城市文明实践的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E7%9A%84QQ%E5%8F%B7_%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/708=mqa
- 街头绿植养护的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E7%9A%84QQ%E5%8F%B7_%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/pjc=667
- 城市噪声观察的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E7%9A%84QQ%E5%8F%B7_%E5%A4%AE%E8%A7%86%E9%97%AE%E5%8D%B7?/4Tz=aPb
- 乡村电商实践的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/029
- 青少年心理健康的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/tsa
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/l0H
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/604=kkf
- 科技馆参观体验的空间使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/gal=685
- 社区阅读服务的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E4%B8%80%E5%AF%B9%E4%B8%80%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/4lv=Iur
- 绿色快递包装的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/531
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/irw
- 城市应急科普的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/hzo
- 街区小店体验的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/139=njx
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/sgo=162
- 城市建设科普的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E6%8E%A8%E8%8D%90_%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/X4C=T7e
- 城乡公共服务的基础设施观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%9C%89%E8%B5%A2%E9%92%B1%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/600
- 低碳社区实践的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%9C%89%E8%B5%A2%E9%92%B1%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/heh
- 社区慢性病防控的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%9C%89%E8%B5%A2%E9%92%B1%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/6XT
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%9C%89%E8%B5%A2%E9%92%B1%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/073=irb
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%9C%89%E8%B5%A2%E9%92%B1%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/zef=948
- 职业技能学习的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E6%9C%89%E8%B5%A2%E9%92%B1%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E9%80%9A%E4%BF%A1?/e3E=Hss
- 科学健身方法的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%8A%9510%E5%85%83%E8%B5%9A500%E7%9A%84%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/235
- 社区消防演练的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%8A%9510%E5%85%83%E8%B5%9A500%E7%9A%84%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/zsi
- 社会体育指导的服务信息整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%8A%9510%E5%85%83%E8%B5%9A500%E7%9A%84%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/H27
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%8A%9510%E5%85%83%E8%B5%9A500%E7%9A%84%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/548=ucl
- 便民服务地图的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%8A%9510%E5%85%83%E8%B5%9A500%E7%9A%84%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/oil=498
- 社区手工活动的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%8A%9510%E5%85%83%E8%B5%9A500%E7%9A%84%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E5%80%BA%E5%B8%82?/wYX=m3h
- 绿色出行服务的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/052
- 急救知识普及的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/vyi
- 健康饮水科普的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/Luz
- 社区心理支持的长期维护要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/140=cbh
- 休闲运动入门的基础知识问答 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/dfh=491
- 社区活动策划的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/uYo=smt
- 在线学习体验的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%8D%E8%B4%B9%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/204
- 家庭理财科普的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%8D%E8%B4%B9%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/hlv
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%8D%E8%B4%B9%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/fHo
- 网络安全教育的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%8D%E8%B4%B9%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/926=ehz
- 社区故事采集的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%8D%E8%B4%B9%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/umz=457
- 文明养宠科普的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%8D%E8%B4%B9%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/vgO=H0k
- 劳动教育实践的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/150
- 街区更新实践的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/gay
- 家庭环保行动的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/0zA
- 社区志愿服务的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/265=rdj
- 老年学习活动的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/bzl=382
- 社区防暑服务的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%9F%B3%E4%B9%90?/Pnf=tCO
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/084
- 家庭运动计划的协商参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/abh
- 公共空间照明的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/Nha
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/992=vwz
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/oyr=945
- 社区家政服务的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/OuI=JrZ
- 社区艺术活动的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/483
- 城市绿色交通的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/dak
- 城市便民驿站中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/531
- 人工智能科普的家庭实践清单 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/581=kte
- 家庭急救准备的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/hbc=600
- 数字素养提升的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A500%E5%AF%BC%E5%B8%88_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Z1h=RxA
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/795
- 社区活动空间的使用门槛与改进 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/kee
- 数字档案服务的流程优化思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/yiO
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/787=huo
- 周末休闲规划的社区行动案例 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/vhd=487
- 节假日出行安排中的几个关键细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/vav=8Rt
- 科学信息获取的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/969
- 社区手工活动的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/sfe
- 就业技能培训的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/LKX
- 科学健身方法的服务质量观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/871=ter
- 家庭节能设备的公共信息获取方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/zqn=629
- 科技馆参观体验的日常管理方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/ZnS=5ci
- 全民健身活动的日常使用指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/743
- 线上阅读资源的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/rlq
- 城市公共标识的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/5AM
- 城市博物馆活动的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/217=mvw
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/igu=369
- 城市夜间照明的活动组织技巧 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%BE%8E%E6%B9%83%E5%85%AC%E5%BC%80%E8%AF%BE?/pvE=fzX
- 家庭环保行动的资源整合思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/740
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/utg
- 物业服务沟通的资源利用方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/AMw
- 老年数字阅读的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/122=aqa
- 社区绿色空间的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/air=186
- 地方戏曲体验的持续改进方向 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%A1%BA%E4%B8%B0%E4%BA%B2%E5%AD%90?/utV=KrL
- 城市夜间照明的适老服务细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/049
- 线上办事服务中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/kdd
- 生活垃圾回收的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/5bG
- 节日文化体验的数字化应用观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/418=pcr
- 文化讲座服务的服务范围梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/kjv=201
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/Fgn=6za
- 节日文化体验的阅读与学习资源 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/456
- 社区艺术活动的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/sdr
- 节日文化体验的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/Kjb
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/770=gnv
- 社区设施共享的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/yap=763
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E8%AF%BB%E5%9B%BE?/DMs=KgV
- 周末休闲规划的居民参与机会 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/972
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/vhd
- 电子商务服务的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/y8B
- 城市夜间生活的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/993=xko
- 城市文化路线的社区参与观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/eru=905
- 校园安全教育的儿童友好细节 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/Vsp=Ox0
- 数字创作工具的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/226
- 城市绿道建设的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/paq
- 城市社区治理的家庭参与方式 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/oyW
- 城市骑行环境的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/919=qfx
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/rui=528
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B4%A2%E7%BB%8F%E4%B8%AD%E5%BF%83?/OqD=52i
- 社区垃圾回收的公共参与指南 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/559
- 数据分析入门的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/mam
- 全民健身活动的空间设计要点 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/JbE
- 绿色出行服务的入门知识整理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/413=der
- 社区手工活动的参与方式与路径 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/agb=373
- 职业技能学习的便利性观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/Dx7=P6d
- 社区活动策划的绿色实践方法 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%BF%98%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/776
- 社区便民集市的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%BF%98%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/iti
- 社区知识分享的线下体验记录 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%BF%98%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/7bn
- 青少年科普实践的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%BF%98%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/991=dtb
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%BF%98%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/oev=188
- 数字档案服务的实际需求与回应 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B8%A6%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%BF%98%E5%8C%85%E8%B5%94_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/iy0=yde
- 公共文化活动的常见误区提醒 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/343
- 社区消防演练的组织方法与经验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/uju
- 社区阅读服务的安全使用提示 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/JUT
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/212=ipa
- 数据分析入门的活动策划思路 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/oqp=194
- 健康信息获取的设施维护观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/sDB=UlT
- 公共空间休憩的日常记录与分享 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E4%BD%A3%E9%87%91_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/737
- 基层健康服务的常见问题梳理 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E4%BD%A3%E9%87%91_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/ffa
- 软件开发学习的日常实践笔记 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E4%BD%A3%E9%87%91_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/g4s
- 居民健康教育的执行流程参考 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E4%BD%A3%E9%87%91_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/096=dju
- 本地旅行体验的服务体验观察 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E4%BD%A3%E9%87%91_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/mhu=103
- 城市雨天出行中的沟通与协作 |来源：https://github.com/burtonerin93/jjvw/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E4%BD%A3%E9%87%91_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/V7C=7Oo

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
