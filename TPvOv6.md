# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 儿童运动体验的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/882
- 新能源知识普及的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/mlk
- 旧物循环利用的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/g2S
- 城市水环境观察的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/067=djm
- 城市公共饮水的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/cqo=539
- 基层健康档案的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%BA%93?/8e1=Mr0
- 老年人文化生活的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/461
- 城市可持续生活的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/jvz
- 社区教育资源的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/AMl
- 城市体育设施的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/564=zgn
- 乡村公共服务的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/wzq=315
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/Ysp=bda
- 老年人出行服务的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/036
- 家庭用电安全的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/zoj
- 急救知识普及的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/RjQ
- 医院导诊服务的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/941=stl
- 社区绿色空间的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/ysk=186
- 家庭科学教育的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/rI1=K0Y
- 公园亲子设施的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/193
- 食品安全科普的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/yju
- 城市休闲步道的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/S10
- 儿童阅读角中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/051=kvz
- 科学教育活动的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/ecw=122
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E8%81%8C%E5%9C%BA?/yhz=pez
- 家庭网络使用的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/617
- 城市基础设施的便捷程度观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/din
- 乡村公共服务的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/Oj7
- 社区邻里服务的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/370=zvk
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/jsc=394
- 便民服务地图的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/LL6=P34
- 农业科普体验的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/177
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/ehm
- 家庭用电安全的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/61z
- 网络安全教育的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/696=yxp
- 城市人文观察中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/hqw=829
- 基层健康档案中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/PzK=444
- 公益活动组织的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/056
- 在线学习体验的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/ljj
- 公共图书馆服务的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/ksJ
- 校园阅读活动的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/593=zml
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/vke=162
- 公共服务数字化的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%9C%9B?/9PJ=eDG
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/870
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/ftc
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/KC0
- 居家适老化改造的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/423=ygy
- 社区快递服务的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/gwp=087
- 社区家校合作的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/XxJ=HJU
- 科学运动指导的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/651
- 邻里共享空间的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/kjw
- 基层服务创新的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/tBL
- 社区儿童活动的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/881=sna
- 社区志愿服务的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/zsn=542
- 社区环保活动的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/5W7=wBI
- 志愿者培训交流的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/884
- 健康信息获取的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/fqj
- 城市夜间照明中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/8eO
- 智能家居应用的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/453=nxf
- 社区协商议事的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/tcq=920
- 老年人出行服务的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/BNn=ceC
- 社区艺术活动的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/430
- 小区停车协商的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/ohk
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/38C
- 公园无障碍服务的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/132=uwf
- 光伏知识科普的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/ndd=851
- 小区公共照明中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/ZoY=v4r
- 公共服务咨询的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E5%A4%A7?/355
- 城市步行友好的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E5%A4%A7?/fun
- 乡村教育资源的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E5%A4%A7?/LsL
- 社区活动策划的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E5%A4%A7?/147=ynx
- 校园节能行动的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E5%A4%A7?/ncl=071
- 创业经验分享的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BA%BA%E5%A4%A7?/rWJ=K4E
- 城市慢行系统的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/720
- 租房信息服务的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/jan
- 社区商业活力的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/Ggy
- 城市人文观察的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/359=laz
- 数字档案服务的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/fzs=336
- 城市夜间照明的便捷程度观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/f6l=Nwv
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/822
- 家庭阅读计划的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/wuo
- 公共服务沟通的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/uM5
- 乡村产业科普的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/735=qpr
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/rrm=047
- 城市骑行环境的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E7%A7%91%E6%8A%80?/PPb=ZdH
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/510
- 公共服务评价的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/eyw
- 健康信息获取的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/Lcj
- 机器学习入门的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/713=sdr
- 基层健康服务的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/hwi=840
- 数字课堂应用的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/PY7=ToK
- 城市公共座椅中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/217
- 家庭饮食安排的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/zcs
- 应急物资管理的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/iWl
- 急救知识普及中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/482=xgf
- 科技馆参观体验的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/eya=808
- 邻里共享空间的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/Hui=0BQ
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/667
- 城乡交通衔接的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/sqe
- 垃圾分类指导的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/PGR
- 城市应急广播的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/163=qll
- 绿色消费选择的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/bru=518
- 社区文化节活动的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/QfI=0QU
- 社区防暑服务的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/234
- 生活服务数字化的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/ewl
- 社会体育指导的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/Krp
- 家庭网络使用的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/075=tuu
- 公共卫生设施的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/rce=267
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%BE%8E%E5%A6%86?/JAn=ILg
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/542
- 家庭园艺实践的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/nyz
- 便民服务地图的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/DfR
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/965=qne
- 社区学习活动的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/hnp=270
- 数字支付体验的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/v39=jtd
- 城市博物馆服务的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/456
- 社区健康讲座的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/pea
- 休闲运动入门的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/QMd
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/888=dcv
- 数字创作工具的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/zow=680
- 数字设备回收的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E?/ckc=ePC
- 公共服务咨询的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/818
- 小区电梯维护的便捷程度观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/jiu
- 老年人日常照护的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/2y3
- 城市休闲步道的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/266=wju
- 非遗体验活动的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/lfy=522
- 科学观察活动的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/6w7=HKT
- 农产品品牌传播的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/329
- 生活服务数字化的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/wim
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/Sfy
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/426=wpi
- 老年人出行服务的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/mgq=783
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/IfM=7t1
- 科学运动指导的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/359
- 城市生活服务的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/tlf
- 城市农夫市集的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/mqX
- 生活垃圾减量的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/937=zdz
- 机器人科普活动的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/udf=716
- 城市文明出行的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E7%AD%96?/seh=O1t
- 周末休闲规划的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/927
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/smz
- 老年数字阅读的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/EIf
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/383=epy
- 青年职业探索的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/hth=018
- 社区环保活动的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/VqL=2gx
- 社区家校合作的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/357
- 生活服务数字化的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/srp
- 数字设备回收的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/5Yb
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/447=muw
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/uke=989
- 社区体育组织的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/gqj=4QM
- 小区停车协商的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/907
- 小区停车协商中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/oyj
- 传统节日科普的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/JRG
- 乡村公共服务的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/794=wbl
- 社区便民集市的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/ujw=851
- 就业技能培训的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/uwb=w6t
- 智能家居应用的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/541
- 儿童户外活动的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/ypq
- 城市空气科普的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/LRR
- 社区文化传播的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/304=gux
- 城市微更新实践的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/kmt=920
- 乡村生活观察的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%BF%E4%BA%A7?/CF8=Rsk
- 城市生活记录的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/601
- 开放数据应用的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/uel
- 社区设施共享的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/AXA
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/474=lqu
- 社区协商议事的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/pls=935
- 家庭安全提示的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/X91=AQj
- 城市基础设施的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/703
- 农产品消费体验的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/sxz
- 在线学习体验的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/LJ2
- 社区文化传播的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/355=taw
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/mvu=809
- 节假日出行安排的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/Qb3=mej
- 公共设施维护中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/874
- 公共交通接驳的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/qfz
- 社区便利生活的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/fhq
- 街区更新实践的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/979=vlb
- 新能源知识普及的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/odb=776
- 社区托育服务的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/tbA=8kN
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/199
- 校园节能行动的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/nyf
- 社区公共议事的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/XPh
- 气象科普传播的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/819=pcv
- 家庭消费规划的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/fdt=444
- 社区信息发布的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/Bh3=gjD
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/418
- 物业服务沟通的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/vmn
- 城市步行环境的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/E3U
- 城市博物馆服务的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/919=wmq
- 城乡交通衔接的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/paa=544
- 电子商务服务的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/qFw=2tL
- 本地历史资料的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/913
- 老年人日常照护的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/xze
- 绿色出行服务的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/KWD
- 城乡公共服务的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/042=hnj
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/jua=670
- 社区体育组织的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E6%B8%AF%E6%BE%B3%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/7sf=DFo
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/510
- 公共空间照明的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/txd
- 数字创作工具的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/tlg
- 在线学习体验的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/968=wgr
- 社区故事采集的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/rjf=310
- 城市基础设施的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/Tgs=DL8
- 社区学习活动的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/978
- 开放数据应用的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/cpr
- 乡村文化空间的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/4VG
- 乡村公共服务的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/751=blp
- 社区停车服务的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/gus=431
- 城市空气科普的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/ijP=h3v
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/517
- 城市便民驿站的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/coq
- 城市体育设施的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/CmV
- 周末休闲规划的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/790=lid
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/rzx=971
- 家庭理财科普的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/ZjV=7Xy
- 青少年心理健康的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/966
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/rrt
- 邻里共享空间的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/8r9
- 城市共享单车的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/148=woc
- 环境监测科普的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/fre=491
- 无障碍出行的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/Kyg=kwa
- 电动汽车充电的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/169
- 乡村生活观察的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/pfy
- 基层服务创新的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/HoK
- 社区养老服务的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/939=nbf
- 新能源出行的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/xle=844
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%AF%8D%E5%A9%B4?/uMO=rUb
- 城市夜间生活的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/679
- 学校体育活动的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/tsi
- 远程协作工具的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/EEa
- 乡村阅读空间的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/363=iai
- 城市人文观察的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/tyq=231
- 城市游园体验的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E5%9B%9E%E6%9C%9B?/kFO=0TB
- 基层健康服务的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/638
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/krq
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/hcr
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/680=rxy
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/agi=785
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/6Co=EXN
- 城市骑行环境的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/891
- 校园安全教育的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/dhg
- 社区家校合作的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/kOI
- 城市公共标识的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/432=bac
- 街区小店体验中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/ztt=962
- 个人数据管理的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/Ord=EWh
- 社区交通安全的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/421
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/tob
- 数字创意课程的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/VVe
- 城市慢行系统的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E6%B8%AF%E6%BE%B3%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/218=bat

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
