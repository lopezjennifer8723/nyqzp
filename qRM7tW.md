# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 公共空间导览的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_135cc-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/607
- 本地历史资料的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_135cc-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/sax
- 社区活动报名的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_135cc-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/ZRa
- 数字设备回收的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_135cc-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/342=xwe
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_135cc-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/srf=502
- 骑行路线规划的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_135cc-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/enf=AAx
- 家庭健康管理的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_135cc-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/846
- 公共空间安全的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_135cc-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/ktd
- 城市噪声观察的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_135cc-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/cJA
- 社区老年食堂的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_135cc-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/217=pob
- 地方戏曲体验的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_135cc-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/yin=338
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_135cc-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/5rF=XqS
- 创业经验分享的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_135cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/823
- 公共空间导览的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_135cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/ptg
- 读书会组织的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_135cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/CzM
- 社区便民服务的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_135cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/876=ept
- 乡村教育资源中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_135cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/hud=326
- 社区便民服务的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_135cc-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/H2R=eRc
- 公共服务沟通的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_135cc-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/729
- 城市水环境观察的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_135cc-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/nxi
- 社区健康讲座的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_135cc-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/DvM
- 社区活动报名的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_135cc-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/448=pfd
- 城市文明出行的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_135cc-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/jvu=740
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_135cc-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/WAU=BpV
- 公共服务咨询的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_135cc-APP_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/396
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_135cc-APP_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/gyv
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_135cc-APP_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/jSy
- 地方文化传播的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_135cc-APP_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/977=wby
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_135cc-APP_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/rlq=909
- 城市步行友好的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_135cc-APP_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/zpi=fKc
- 家庭环保行动的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_135cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/587
- 城市社区治理的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_135cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/jqw
- 城市雨天出行的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_135cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/LwZ
- 城市绿道建设的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_135cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/767=hbn
- 节日文化体验中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_135cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/hnk=150
- 志愿服务平台的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_135cc-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/EpT=lkd
- 街区小店体验的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_135cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/708
- 无障碍出行中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_135cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/mnd
- 街区更新实践的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_135cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/Ptp
- 公共服务指南的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_135cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/405=hue
- 公共卫生宣传的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_135cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/lsc=668
- 城市树木认养的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_135cc-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/6Iy=DXw
- 老年数字阅读的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_135cc-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/443
- 基层健康档案的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_135cc-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/uxk
- 城市噪声观察的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_135cc-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/G4n
- 居民健康教育的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_135cc-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/861=nsi
- 老年人日常照护的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_135cc-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/swi=177
- 节日文化体验的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_135cc-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%8A%E7%99%BB?/X1j=tNP
- 机器人科普活动的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_135cc-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/294
- 就业技能培训的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_135cc-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/niq
- 城市公共饮水的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_135cc-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/Gf0
- 乡村文化空间的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_135cc-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/726=wbo
- 老旧小区改造的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_135cc-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/myh=766
- 城市树木认养的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_135cc-%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/a7t=jIZ
- 便民信息查询的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/134
- 城市共享单车的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/kvm
- 绿色办公实践中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/JHE
- 亲子阅读活动的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/387=dgj
- 社区文化传播的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/tdw=743
- 社区公共餐饮的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_135cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E6%A5%BC%E5%B8%82?/BBp=fkc
- 家庭急救准备的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/988
- 青年志愿活动的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/mtu
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/IJu
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/860=vry
- 校园节能行动中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/rhv=314
- 数字政务体验的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_135cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/yZ6=uE2
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/147
- 健康饮食教育的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/hdf
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/1bB
- 社区文化节活动的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/642=lfs
- 青年就业服务的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/dlx=580
- 社区托育服务的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_135cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/Zez=gTH
- 公共服务评价的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/563
- 社区运动空间的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ggh
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/58H
- 消防知识宣传的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/952=bnw
- 小区公共照明的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/lhs=473
- 健康步道使用的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/C7f=xqy
- 街区小店体验的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/623
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/aqe
- 社区养老服务的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/7DP
- 城市公共标识的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/030=xgr
- 城市公共艺术的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/avy=017
- 街头绿植养护的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%B8%93%E9%A2%98?/Mme=fbN
- 社区老年食堂的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/913
- 青少年心理健康的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/ngm
- 居家适老化改造的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/8h7
- 数字支付体验的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/226=svl
- 社区志愿服务的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/wnd=435
- 软件开发学习中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_135cc-%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/1MS=tbG
- 公共场所导视的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/313
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/gsn
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/cpY
- 日常摄影记录的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/763=ubt
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/rkg=707
- 社区绿色空间的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/kaQ=eJK
- 电动汽车充电的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/098
- 生活垃圾减量的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/kyl
- 健康步道使用的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/oKy
- 邻里共享空间的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/258=oey
- 社区垃圾回收的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/ihk=684
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/Zga=Yzt
- 老年运动活动的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%AF%8D%E5%A9%B4?/088
- 城市绿道建设的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%AF%8D%E5%A9%B4?/cbi
- 社区环保活动的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%AF%8D%E5%A9%B4?/4Bd
- 城市便民驿站中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%AF%8D%E5%A9%B4?/319=drv
- 非遗课堂体验的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%AF%8D%E5%A9%B4?/llh=791
- 城市文明出行的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%AF%8D%E5%A9%B4?/tBK=L25
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/075
- 社区协商议事的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/otu
- 通勤路线规划的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/Thi
- 街区绿化养护的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/334=tbu
- 社区快递服务的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/mbd=829
- 线上办事服务的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/wio=wZv
- 城市微更新实践的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/050
- 社区安全巡查的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/kjk
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/Whm
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/026=cqh
- 乡村文化空间的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/ofz=497
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/8Qq=wHv
- 绿色校园实践的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/787
- 垃圾分类指导的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/sui
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/pbh
- 社区活动策划的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/286=oft
- 机器人科普活动的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/eem=361
- 社区商业活力的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/v6V=ltN
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/839
- 垃圾分类指导的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/gvt
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/k9e
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/499=duy
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/wze=145
- 机器人科普活动的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%8F%B7%E5%A4%96?/EqB=zdy
- 公共服务评价的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/026
- 课后服务体验的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/gta
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/XkL
- 地方文化传播的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/644=rlm
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/tfr=600
- 节日文化体验的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%80%BA%E5%B8%82?/p3e=q4H
- 街头绿植养护的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/934
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/czo
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/iHu
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/954=nlx
- 城市休闲步道的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/wsd=932
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E4%BF%A1%E6%89%98?/vMN=Snm
- 药品使用科普的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/026
- 医院导诊服务的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/kfn
- 数字阅读服务的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/NiV
- 城市公共自行车的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/034=myv
- 城市雨天出行的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/zrz=229
- 社区健康讲座的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/MFY=zwL
- 乡村公共文化的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/185
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/wpk
- 城乡交流活动的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/UBp
- 生成式工具使用的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/840=hof
- 校园社团活动中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/rkt=856
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_135cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/OUj=wsq
- 基层服务创新的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/615
- 社区科普课堂的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/niz
- 社区阅读服务的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/o2n
- 科普展览体验的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/487=bnd
- 课后服务体验的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/ucw=461
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%BA%E9%87%91?/4Q5=MzN
- 安全出行教育的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%86%9B%E4%BA%8B?/522
- 社区休闲设施的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%86%9B%E4%BA%8B?/idu
- 社区运动空间的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%86%9B%E4%BA%8B?/gsA
- 城市雨天出行的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%86%9B%E4%BA%8B?/664=png
- 创业经验分享的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%86%9B%E4%BA%8B?/qno=614
- 街头绿植养护的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_135cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E5%86%9B%E4%BA%8B?/L3N=AX7
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/630
- 社区活动报名的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/tje
- 城市生活服务的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/QYT
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/754=yfz
- 公共服务咨询的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/xlv=892
- 校园社团活动的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_135cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/2S9=E2a
- 数字地图应用的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/510
- 城乡交流活动的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/jmj
- 社区托育服务的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/t6i
- 便民服务地图的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/705=pte
- 城市公共厕所的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/rpw=428
- 城市公共座椅的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_135cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/m6V=TQw
- 课后服务体验的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/062
- 社区活动报名的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/khr
- 线上办事服务的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/oe0
- 本地旅行体验的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/088=vkd
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/gqo=170
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/Sfy=80Q
- 劳动教育实践的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%AE%B6%E5%B1%85?/449
- 节假日出行安排的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%AE%B6%E5%B1%85?/fey
- 灵活就业交流的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%AE%B6%E5%B1%85?/g9g
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%AE%B6%E5%B1%85?/826=gso
- 旧物循环利用的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%AE%B6%E5%B1%85?/unv=386
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_360%E5%AE%B6%E5%B1%85?/N4o=Jcb
- 数据分析入门中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/063
- 小区公共照明的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/xle
- 非遗体验活动的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/I6t
- 乡村文化活动的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/219=fyf
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/uql=969
- 生成式工具使用的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_135cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/qGR=qDg
- 小区停车协商的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BF%A1%E8%AE%BF?/127
- 生活服务数字化的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BF%A1%E8%AE%BF?/iwu
- 社区菜市场服务的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BF%A1%E8%AE%BF?/lSO
- 农产品品牌传播的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BF%A1%E8%AE%BF?/259=hhr
- 线上阅读资源的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BF%A1%E8%AE%BF?/kwl=430
- 社区儿童活动的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_135cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E4%BF%A1%E8%AE%BF?/WGE=bTI
- 社区慢性病防控的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/202
- 社区垃圾回收的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/bzw
- 社区交通安全的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/Mtl
- 智慧停车服务的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/440=coe
- 社区宠物管理的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/mrh=028
- 街区更新实践中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_135cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E9%97%AE%E7%AD%94?/XzC=gB8
- 无障碍出行的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/200
- 家庭照护支持的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/qav
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/FWI
- 青少年心理健康中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/047=rbv
- 社区商业活力的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/mfy=790
- 城市噪声观察的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_135cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/aaU=M99
- 社区心理支持的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/264
- 低碳社区实践的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/hzl
- 城乡公共服务的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/KmV
- 智能家居应用的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/405=ozz
- 公共服务评价的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/tyi=304
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_1368%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/zeb=PJ2
- 社区花园共建的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/020
- 健康饮水科普的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/uvt
- 科学教育活动的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/Wub
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/287=hst
- 农产品消费体验的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/wub=421
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/QFe=TZ7
- 儿童友好空间的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/057
- 社区老年食堂的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/ugf
- 城市文化路线的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/DxW
- 家庭急救准备的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/847=bnj
- 数字设备回收的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/kms=028
- 智能家居应用的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_1368%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/Lnd=vtV
- 健康饮水科普的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/231
- 家庭用电安全的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/ftg
- 家庭收纳实践的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/Xin
- 社区手工活动的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/454=eiv
- 数字地图应用的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/wci=200
- 课后服务体验的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E8%AE%AF?/IaN=j2g
- 电子商务服务的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/142
- 在线教育体验的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/bme
- 本地旅行体验的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/KgT
- 城乡交通衔接的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/001=rqm
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/idl=609
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_1368%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E8%A1%8C%E6%83%85?/zY9=TGo
- 消防知识宣传的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/495
- 乡村电商实践的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/ita
- 亲子阅读活动的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/bag
- 社区艺术活动中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_1368%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E8%AE%AF%E8%B4%A2%E7%BB%8F?/122=syk

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
