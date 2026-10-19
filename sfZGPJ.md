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

- 日常摄影记录的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_369cc-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/yet=755
- 全民阅读推广中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_369cc-%E7%99%BB%E5%BD%95_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/6zv=frA
- 城市生活服务的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_369cc-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/969
- 志愿服务平台的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_369cc-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/hhj
- 城市公共饮水的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_369cc-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/2p5
- 社区宣传栏更新的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_369cc-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/876=wnx
- 节约用水实践的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_369cc-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/flg=406
- 全民阅读推广的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_369cc-%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/6fr=LQc
- 数字素养提升的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/420
- 乡村公共阅读的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/pkp
- 社区活动空间的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/sdU
- 社区托育服务的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/508=frf
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/gii=184
- 农业科普体验的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/ZxY=sld
- 开放数据应用的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_369cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/664
- 科普展览体验的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_369cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/fst
- 读书会组织的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_369cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/Knj
- 社区便民服务的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_369cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/722=ijd
- 城市步行环境的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_369cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/wli=935
- 数字公共文化的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_369cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/UnL=ZhL
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_369cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/420
- 数字学习资源的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_369cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/lid
- 公共空间休憩的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_369cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/M95
- 机器学习入门的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_369cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/205=zpq
- 城市生活服务的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_369cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/zar=160
- 公共空间照明的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_369cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/170=U1g
- 公共设施使用的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/764
- 开放式学习空间的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/lku
- 市民热线服务的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/ZXp
- 社区活动策划的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/994=bge
- 亲子科普活动的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/olf=114
- 社区活动策划的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/PLK=06J
- 小区公共照明的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_369cc-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/468
- 数字便民地图的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_369cc-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/gab
- 公共服务指南的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_369cc-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/iAP
- 乡村公共阅读的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_369cc-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/248=psp
- 个人时间管理的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_369cc-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/aqo=761
- 便民服务窗口的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_369cc-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E8%AF%BB%E5%9B%BE?/1Jv=XoE
- 社区运动空间的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_369cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/598
- 城市建设科普的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_369cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/iqj
- 数字公共文化的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_369cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/w8b
- 节能家电使用的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_369cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/559=dgt
- 科技馆参观体验的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_369cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/wqk=118
- 社区设施共享的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_369cc-%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/9b2=y3u
- 生活技能分享的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/776
- 城市公共标识的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/set
- 城市绿道建设的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/pxN
- 社区健康讲座的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/500=jfz
- 社区公共餐饮的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/nrs=368
- 社区慢性病防控的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/WHG=I4p
- 社区生活指南的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/169
- 街区小店体验的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/mub
- 社区防暑服务的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/wbX
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/395=rbf
- 社区修缮行动的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/kzr=100
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/3w5=dei
- 节日文化体验的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/246
- 青年志愿活动的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/edg
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/9SI
- 城市农夫市集的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/294=zlo
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/cph=141
- 城市慢行系统的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/G4q=I3T
- 公共文化活动的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%9B%98%E7%82%B9?/007
- 社区手工活动的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%9B%98%E7%82%B9?/usa
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%9B%98%E7%82%B9?/L6N
- 数字便民地图的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%9B%98%E7%82%B9?/303=ejo
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%9B%98%E7%82%B9?/fmm=333
- 社区生活指南的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E7%9B%98%E7%82%B9?/NHu=SqK
- 休闲运动入门的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E9%97%AE%E5%8D%B7?/798
- 劳动教育实践的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E9%97%AE%E5%8D%B7?/zdn
- 居家防滑改造的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E9%97%AE%E5%8D%B7?/yw8
- 社区教育资源的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E9%97%AE%E5%8D%B7?/826=qqb
- 城市文明出行的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E9%97%AE%E5%8D%B7?/sbq=037
- 社区应急准备的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E9%97%AE%E5%8D%B7?/gbn=Mii
- 家庭节能设备中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/446
- 社区法律科普的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/sgb
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/E0z
- 开源技术交流的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/228=sqr
- 网络安全教育的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/ycp=405
- 本地历史资料的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_369cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/GNp=ZMA
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E4%BF%A1%E6%89%98?/953
- 老年友好服务的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E4%BF%A1%E6%89%98?/tdh
- 乡村公共服务的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E4%BF%A1%E6%89%98?/ms0
- 公共服务沟通的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E4%BF%A1%E6%89%98?/012=zox
- 绿色办公实践的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E4%BF%A1%E6%89%98?/wie=426
- 居民健康教育中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E4%BF%A1%E6%89%98?/WNe=v53
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/716
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/mbo
- 数据分析入门的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/qUG
- 社区垃圾回收的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/532=cex
- 城市展览体验从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/fin=071
- 节假日出行安排的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/0MX=dC2
- 老年数字阅读的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%88%9B%E6%8A%95?/897
- 药品使用科普的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%88%9B%E6%8A%95?/jxr
- 城市基础设施的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%88%9B%E6%8A%95?/PEj
- 绿色消费选择的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%88%9B%E6%8A%95?/354=rxv
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%88%9B%E6%8A%95?/ufh=172
- 创业经验分享的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%88%9B%E6%8A%95?/oBN=Pf3
- 数字政务体验的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/175
- 社区体育组织的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/lln
- 节能家电使用的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/azQ
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/982=oqu
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/est=589
- 本地旅行体验的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/Iu9=oiQ
- 小区电梯维护的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/867
- 社区健康讲座中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/xxq
- 城市绿色交通中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/w2B
- 老年人文化生活的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/541=xey
- 城市公共标识的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/gsd=331
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/kIA=oaH
- 乡村公共服务的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/874
- 开放数据应用的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/lbf
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/iAL
- 儿童阅读角的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/251=fgn
- 节假日出行安排的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/ltc=353
- 课后服务体验中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/Whc=5TU
- 智慧城市体验的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/566
- 公共文化活动的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/jrf
- 社区科普课堂的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/jC0
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/197=dsc
- 线上办事服务的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/sce=158
- 儿童户外活动的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%BF%B0%E8%AF%84?/wYO=DnX
- 校园安全教育的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/244
- 校园节能行动的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/blz
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/WrN
- 科学健身方法的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/542=iwk
- 城市运动公园的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/glx=293
- 低碳社区实践的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E5%8D%B7?/cxJ=NTM
- 公园无障碍服务的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_369cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B5%84%E6%9C%AC%E8%B4%A2%E7%BB%8F?/585
- 绿色出行服务的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_369cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B5%84%E6%9C%AC%E8%B4%A2%E7%BB%8F?/wvp
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_369cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B5%84%E6%9C%AC%E8%B4%A2%E7%BB%8F?/hL4
- 社区教育资源的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_369cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B5%84%E6%9C%AC%E8%B4%A2%E7%BB%8F?/994=ihr
- 城市文明出行的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_369cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B5%84%E6%9C%AC%E8%B4%A2%E7%BB%8F?/gxj=363
- 儿童友好空间的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_369cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B5%84%E6%9C%AC%E8%B4%A2%E7%BB%8F?/d2R=J3z
- 个人时间管理的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_369cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/403
- 城市应急科普的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_369cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/ueg
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_369cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/f5O
- 青少年心理健康的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_369cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/407=ezc
- 公共卫生宣传的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_369cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/hpm=239
- 急救知识普及的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_369cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/GJU=d1P
- 城市慢跑路线的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/818
- 读书会组织的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/ppq
- 新能源出行的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/DDJ
- 环境教育课程的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/050=nzx
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/rpm=614
- 节假日出行安排的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/0LL=O9B
- 开放数据应用的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/563
- 家庭照护支持的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/nmi
- 街道综合服务的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/X8N
- 城市基础设施的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/284=jyd
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/flj=029
- 农贸市场环境的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_369cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/7Pl=GZI
- 社区协商议事的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_369cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/433
- 社区老年食堂的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_369cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/rzi
- 科学健身方法的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_369cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/Z8u
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_369cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/119=aot
- 人工智能科普的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_369cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/egh=796
- 社区商业活力的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_369cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E9%9F%B3%E4%B9%90?/U07=n3I
- 非遗体验活动的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/246
- 小微企业服务的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/pkl
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/qm2
- 城市公共座椅的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/284=noa
- 社区运动空间的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/whx=556
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_369cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/Dsl=GQh
- 社区知识分享的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/550
- 城市生活记录的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/hwh
- 家庭科学教育的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/qaJ
- 社区公共卫生的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/276=ngj
- 社区便利生活的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/rta=176
- 新能源知识普及的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_369cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A1%8C%E6%83%85?/6Pb=OtQ
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_3799%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%89%8B%E8%AE%B0?/380
- 校园节能行动的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_3799%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%89%8B%E8%AE%B0?/sxw
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_3799%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%89%8B%E8%AE%B0?/1JJ
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_3799%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%89%8B%E8%AE%B0?/333=jgy
- 开放式学习空间的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_3799%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%89%8B%E8%AE%B0?/lgi=815
- 智能家居应用的长期维护要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_3799%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%89%8B%E8%AE%B0?/9EB=lWc
- 社区宠物管理中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/737
- 学校体育活动的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/kce
- 公共服务预约的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/WxF
- 学校体育活动的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/784=bwr
- 城乡交通衔接的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/sqe=772
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/EW0=CiU
- 城市树木认养的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/270
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/bcr
- 城市文明出行中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/Qoy
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/119=dnc
- 公共文化活动的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/yxy=936
- 农村环境治理的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E4%BD%93%E8%82%B2?/w7n=JEE
- 劳动教育实践的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/436
- 乡村阅读空间的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/ekj
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/n0w
- 家庭运动计划的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/486=hac
- 乡村公共文化的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/wzq=425
- 健康信息获取的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E6%9B%B2%E8%89%BA?/KEE=3dE
- 家庭阅读计划的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%96%87%E5%8C%96?/104
- 社区设施共享的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%96%87%E5%8C%96?/ope
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%96%87%E5%8C%96?/fHb
- 健康步道使用的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%96%87%E5%8C%96?/054=cqm
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%96%87%E5%8C%96?/lkq=608
- 软件开发学习的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3799%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_360%E6%96%87%E5%8C%96?/1sU=tlS
- 青年就业服务中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/289
- 药品使用科普的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/dpx
- 城市公共空间的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/oXQ
- 公共文化活动的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/644=vzn
- 周末休闲规划的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/tki=298
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/s0X=4rX
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/777
- 城市水环境观察的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/oqg
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/CRl
- 智能家居应用的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/495=oga
- 数字地图应用的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/jch=810
- 青年职业探索的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%8E%AF%E7%90%83%E8%B4%A2%E7%BB%8F?/TbB=Ts1
- 生活技能分享的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/686
- 开放数据应用中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/rqy
- 社区慢性病防控的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/sbS
- 图书馆活动策划的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/063=dto
- 无障碍信息设计的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/zqy=945
- 节约用水实践的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3799%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9B%BD%E6%B3%B0%E8%B4%A2%E7%BB%8F?/n6h=7hx
- 本地历史资料的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/335
- 校园阅读活动的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/nzc
- 开放数据应用的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/Fhg
- 市民热线服务的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/778=mot
- 社区活动策划的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/bwo=529
- 社区便民集市的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_3799%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/9vE=Mfj
- 城市步行环境的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_3799%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/326
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_3799%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/jdy
- 公益活动组织的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_3799%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/ybw
- 校园阅读活动的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_3799%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/046=ggq
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_3799%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/tdj=540
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_3799%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/X12=iEs
- 物业服务沟通的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/868
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/hgw
- 个人信息保护的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/Zlq
- 城乡交通衔接的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/541=twj
- 社区知识分享的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/lmn=312
- 节约用水实践的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_3799%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/Cxz=HvQ
- 绿色出行服务的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3799%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/003
- 电动汽车充电的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3799%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/vto
- 城市文明实践的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3799%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/jsY
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3799%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/317=bpw
- 社区活动策划的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3799%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/yli=541
- 垃圾分类指导的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_3799%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/laG=iia
- 青少年户外教育的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_3799%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/209
- 社区公共餐饮的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_3799%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/atb
- 社区修缮行动的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_3799%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/zeY
- 城市慢行系统的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_3799%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/291=shg
- 地方文化传播的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_3799%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/kfr=271
- 城市夜间照明的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_3799%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%94%BF%E7%AD%96?/8po=bKB
- 公共设施维护的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_3799%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/768
- 公共卫生设施的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_3799%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/vnh

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
