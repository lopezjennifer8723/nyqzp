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

- 家庭运动计划的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/VEu
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/550=pth
- 远程协作工具的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/xen=504
- 电动汽车充电的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/k2W=Y1C
- 街区更新实践的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/877
- 家庭用电安全的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/mnm
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/P5X
- 公园无障碍服务的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/358=fhh
- 生活服务数字化的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/zdk=755
- 社区互助网络的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/MgY=073
- 公共空间导览的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/505
- 城市公共饮水的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/fvw
- 城市博物馆活动的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/Lmf
- 科学健身方法的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/768=vco
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/gnl=917
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E8%A7%82%E7%82%B9?/OQh=tT1
- 城乡交流活动的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/203
- 城市绿道建设的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/xcb
- 公共空间休憩的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/bGp
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/382=osz
- 周末休闲规划的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/zei=534
- 非遗体验活动的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%A4%B4%E6%9D%A1?/SDo=vOY
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/626
- 垃圾分类指导的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/fff
- 学校食育活动的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/Ogv
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/736=fky
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/ggm=183
- 学校体育活动的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/7u8=ldO
- 读书会组织的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/705
- 环境教育课程的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/jos
- 社区垃圾回收的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/ILR
- 青年志愿活动的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/286=znn
- 健康信息获取的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/rcj=949
- 节能家电使用的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E8%A7%82%E5%AF%9F?/3Uu=iM6
- 老年友好服务的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/172
- 数字便民地图的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/uxj
- 校园社团活动的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/08O
- 社区公共卫生的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/541=dma
- 儿童阅读角的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/uzb=335
- 本地历史资料的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/3na=MBt
- 社会体育指导的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/069
- 节能家电使用的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/lwx
- 数据分析入门的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/XTG
- 家庭园艺实践的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/357=akc
- 数字艺术创作的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/yhq=215
- 非遗体验活动的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/ddr=ihz
- 城市水环境观察的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/654
- 社区宠物管理的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/mrn
- 亲子科普活动的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/BpN
- 公共服务评价的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/416=cmm
- 乡村公共阅读的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/wii=728
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9F%8E%E4%BA%8B?/XOP=5Gy
- 公共服务沟通的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/296
- 乡村公共服务的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/suw
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/ROq
- 数字公共文化的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/869=xpx
- 社区手工活动的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/izx=994
- 社区互助网络的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/siE=dnU
- 电动汽车充电的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/445
- 全民健身活动的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/yzq
- 社区信息发布的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/tw5
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/936=som
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/hka=515
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/ctJ=ZtA
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/982
- 老年数字阅读的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/etu
- 家庭饮食安排的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/H4t
- 线上阅读资源的便捷程度观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/220=kei
- 环境教育课程的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/dxg=072
- 课后服务体验的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E5%AE%B6%E7%94%B5?/GXN=ra5
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/389
- 生活垃圾减量的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/pux
- 城市应急科普的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/mgU
- 公共服务评价的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/051=dvm
- 智慧停车服务的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/djc=991
- 市民热线服务的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/lIK=aOu
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/014
- 社区家校合作的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/afv
- 公共场馆服务的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/523
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/442=dus
- 社区慢性病防控的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/qlp=990
- 社区老年食堂的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/HwL=eSf
- 急救知识普及的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/924
- 公共文化活动的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/vcl
- 休闲运动入门中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/sgr
- 青年职业探索的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/452=ead
- 地方文化传播的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/bsb=116
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E9%A3%9F%E5%93%81?/kZa=KS8
- 社区防暑服务的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/169
- 家庭饮食安排的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/xaf
- 城市公共空间的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/GTh
- 地方美食文化的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/679=erg
- 家庭用电安全的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/dpm=736
- 绿色快递包装的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/qZ1=AwR
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/691
- 社区老年食堂的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/nxl
- 城市宠物友好空间的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/GxY
- 软件开发学习的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/859=jsy
- 数字学习资源的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/xtf=349
- 新能源知识普及的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/9iS=Sa5
- 社区活动策划的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/075
- 家庭运动计划的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/lng
- 智慧停车服务的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/3pe
- 社区知识分享的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/386=nvv
- 家庭理财科普的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/qgi=692
- 儿童运动体验的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E9%99%85?/huq=o2g
- 口袋公园建设的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/161
- 社区老年食堂的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/ewa
- 职业技能学习的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/hkQ
- 科普展览体验的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/606=rqm
- 开放数据应用的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/ksa=939
- 全民阅读推广的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/Rya=z8c
- 本地旅行体验的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/559
- 家庭健康科普的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/bxc
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/UWh
- 乡村产业科普的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/943=zoq
- 科普展览体验的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/rjn=457
- 休闲运动入门的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/ANc=wI8
- 居家适老化改造的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/435
- 社区文化节活动的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/npd
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/M15
- 社区活动报名的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/419=xrc
- 社区教育资源的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/mom=474
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/0NL=Ami
- 社区教育资源的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/468
- 城市公共空间的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/jan
- 课后服务体验的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/19x
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/880=pft
- 城乡交流活动的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/vdz=371
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/CcT=ABy
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/594
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/rko
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/viX
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/102=tnc
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/zlv=127
- 文化遗产保护科普的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/IC0=NEN
- 安全出行教育的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/711
- 个人数据管理的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/qyj
- 儿童阅读角的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/vBk
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/596=poc
- 城市社区治理的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/jfb=132
- 家庭健康管理的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/uWr=u6r
- 乡村公共服务的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/840
- 公园亲子设施的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/lyz
- 城市水环境观察的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/p2l
- 城市生活服务的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/969=nmx
- 社区快递服务的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/vev=044
- 家庭安全提示的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%81%8C%E5%9C%BA?/8C9=MXz
- 乡村电商实践的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/293
- 文化讲座服务的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/nkv
- 科技馆参观体验的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/dfF
- 农产品消费体验的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/854=skf
- 儿童友好空间的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/jzp=184
- 社区文化传播的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/Asw=4An
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/692
- 社区消防演练的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/sau
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/iFE
- 软件开发学习的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/153=jhk
- 传统节日科普的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/pue=837
- 儿童安全出行中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/7Pz=KiB
- 无障碍信息设计的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/314
- 城市夜间照明的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/qmy
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/1TB
- 社区快递服务的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/203=iyq
- 社区信息发布中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/rmo=566
- 乡村生活观察的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/YZg=iua
- 科学运动指导的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/336
- 城市步行环境的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/zqj
- 科学信息获取的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/ssv
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/826=oju
- 公共服务评价的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/zxp=979
- 新能源知识普及的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/lki=5Zc
- 社区设施共享的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/471
- 基层医疗预约的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/rdx
- 本地消费场景的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qZU
- 家庭健康科普的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/350=xfw
- 社区邻里服务的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qhu=229
- 社区绿色空间的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/mLv=7dA
- 城市夜间照明的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/305
- 终身学习资源的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/few
- 骑行路线规划的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/CMn
- 公共场所导视的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/755=ijy
- 街道综合服务的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/vip=340
- 健康饮水科普的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/Sdb=lnU
- 街区小店体验的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/726
- 社区体育组织的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/mwe
- 社区安全巡查的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/LZN
- 节气饮食文化的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/486=vxo
- 公共服务评价的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/stu=533
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/XFr=p3l
- 数字艺术创作的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/396
- 农业科普体验的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/tkr
- 数字资源检索的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/svg
- 小区电梯维护的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/401=gym
- 家庭科学教育的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/ajj=046
- 青少年户外教育的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/tfn=7uo
- 青年志愿活动的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/611
- 公共空间导览的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/vro
- 社区老年食堂中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/Eii
- 家庭用电安全的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/738=xeq
- 药品使用科普的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/xza=244
- 个人信息保护的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E5%9C%B0%E4%BA%A7?/Juq=kPQ
- 青少年心理健康的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/350
- 儿童运动体验的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/bfd
- 社区文化节活动的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/wi5
- 社区艺术活动中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/298=wav
- 健康饮水科普的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/aes=308
- 家庭理财科普的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/9d0=hxF
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%95%99%E8%82%B2?/006
- 公共空间休憩的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%95%99%E8%82%B2?/dbq
- 科学信息获取的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%95%99%E8%82%B2?/zAz
- 数字学习资源的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%95%99%E8%82%B2?/309=prj
- 家庭阅读计划的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%95%99%E8%82%B2?/nft=909
- 个人时间管理的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%95%99%E8%82%B2?/Gae=Wje
- 邻里互助活动的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/338
- 街道综合服务的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/thd
- 全民阅读推广的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/2g0
- 城市博物馆活动的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/078=csv
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/lbf=668
- 地方旅游导览的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/H3O=KiX
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/897
- 公共健身器材的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/xwn
- 城市基础设施的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/YlT
- 科学信息获取中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/274=bzq
- 居家适老化改造的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/wtb=766
- 骑行路线规划的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/1P0=isz
- 城市步行环境的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/274
- 在线教育体验的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/fzb
- 节气饮食文化的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/NlI
- 城市展览体验的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/242=zfs
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/bke=120
- 城市休闲步道的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%90%86%E8%B4%A2?/UU6=818
- 小区公共照明的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/852
- 家庭网络使用的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/zlv
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/9ql
- 新能源出行的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/989=udl
- 青少年科技社团的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/kof=613
- 儿童友好空间的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/Oxj=Tit
- 全民健身活动的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/444
- 地方旅游导览的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/mij
- 气象科普传播的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/nL7
- 新能源知识普及的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/943=xah
- 城市骑行环境的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/kru=759
- 城市休闲步道的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/itw=Dms
- 社区运动空间的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/209
- 家庭食品保存的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/ovw
- 社区家校合作的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/FPB
- 周末休闲规划的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/826=oeq
- 社区体育组织的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/frn=269
- 在线学习体验的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/3rR=iks

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
