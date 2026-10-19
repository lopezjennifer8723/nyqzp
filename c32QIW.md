# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 健康步道使用的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/cw4
- 基层健康档案的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/580=wsp
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/gsw=604
- 个人数据管理的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/t0a=Epa
- 网络安全教育的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/997
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/zsr
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/q3r
- 药品使用科普的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/244=ypv
- 城市文明出行的社区行动案例 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/apx=493
- 数字阅读服务的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/dgL=uPX
- 数字素养提升的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/487
- 运动安全知识的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/zqr
- 家庭健康科普的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/2uS
- 信息无障碍体验的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/889=xfx
- 本地旅行体验的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/bpg=842
- 城市运动公园的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/2hY=ifX
- 药品使用科普的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/837
- 家庭环保行动的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/cfh
- 节能家电使用的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/Eww
- 市民热线服务的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/166=ibo
- 公园亲子设施的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/gqv=733
- 科普展览体验的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/GBO=SPC
- 公共空间照明的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/340
- 传统手工艺体验的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/kdw
- 健康饮水科普的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/srQ
- 城市微更新实践的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/955=tai
- 基层服务创新的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/dch=177
- 数字创作工具的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/fPI=ckB
- 社区儿童活动的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/391
- 家庭食品保存的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/xzt
- 公园无障碍服务的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/QHq
- 家庭消费规划的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/881=ibf
- 数字阅读服务的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/skq=392
- 职业技能学习的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%AE%B2%E5%9D%9B?/hgR=HgY
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/018
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/fon
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/SO8
- 城市公共饮水的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/431=lbv
- 家庭收纳实践的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/fog=429
- 个人数据管理的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/AXz=JlK
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/228
- 公益活动组织的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/tao
- 老旧小区改造的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/ItN
- 城市绿色交通的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/390=jdf
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/jgw=898
- 公共服务沟通的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/Og9=DQs
- 公共空间导览的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/789
- 数据分析入门的执行流程参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/pql
- 社区公共卫生的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/FkM
- 家庭阅读计划的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/888=bvz
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/hdm=449
- 科学运动指导从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%8E%86%E5%8F%B2?/MBi=0YA
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/643
- 软件开发学习的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/tkr
- 城市体育设施的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/ypK
- 节约用水实践的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/475=nbd
- 公共交通信息服务的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/amt=081
- 老年人日常照护的便捷程度观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/gtD=43Q
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/720
- 城市应急广播的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/wlk
- 城市夜间照明的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/rU2
- 城乡公共服务的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/328=esq
- 公共服务预约的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/fky=926
- 农产品消费体验的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/GZT=kHA
- 数字便民地图的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/609
- 文化场馆预约的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/hgb
- 在线学习体验的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/RVo
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/951=bfv
- 在线教育体验的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/ptx=569
- 图书馆活动策划的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E6%95%B0%E7%A0%81?/CGx=FXm
- 社区儿童活动中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/316
- 社区儿童活动的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/hke
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/zPQ
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/537=uuw
- 基层健康档案的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/xkf=073
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/JVz=L1D
- 青少年编程学习的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/764
- 读书会组织从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/gka
- 老年智能设备的安全使用提示 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/hFj
- 通勤路线规划的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/048=rxg
- 图书馆活动策划的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/pou=131
- 社区故事采集的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/I5K=ZFt
- 社区花园共建的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/742
- 青年就业服务的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/hkp
- 社区菜市场服务的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/cwO
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/653=kos
- 社区教育资源的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/fwy=833
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/cNx=pHK
- 公共交通接驳的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/918
- 家庭节能实践中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/rlw
- 校园安全教育的服务信息整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/z5I
- 儿童运动体验的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/988=sbw
- 环境教育课程的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/lxq=707
- 家庭环保行动的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AF%84?/2Uj=aKu
- 社区庭院绿化的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/314
- 乡村文化空间的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/oir
- 乡村产业科普的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/FXB
- 乡村公共文化的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/040=evc
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/tob=827
- 数据分析入门的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E5%A6%86?/fll=Pe8
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/748
- 医院导诊服务的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/fuk
- 社区老年食堂的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/Oym
- 数字设备回收的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/859=cko
- 家庭运动计划的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/nqa=076
- 骑行路线规划的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/xHI=aUY
- 生活服务数字化的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/721
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/kqe
- 旧物循环利用的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/Pew
- 家庭环保行动的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/198=iho
- 社区互助网络的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/kte=707
- 志愿服务平台的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/Z7t=VLn
- 在线学习体验的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/767
- 公园亲子设施的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/crj
- 家庭饮食安排的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/qw2
- 城市绿色交通中的沟通与协作 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/327=fwo
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/aot=547
- 节能生活方式的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/cAg=PC2
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/874
- 城市社区治理的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/pjx
- 社区体育组织的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/AaI
- 社区托育服务的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/187=jxr
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/ekd=170
- 家庭科学教育的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/zve=7Q7
- 公益活动组织的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%85%AC%E7%9B%8A?/786
- 家庭消费规划的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%85%AC%E7%9B%8A?/coi
- 城市慢行系统的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%85%AC%E7%9B%8A?/HeC
- 社区学习活动的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%85%AC%E7%9B%8A?/856=dbu
- 城市绿道建设的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%85%AC%E7%9B%8A?/ijf=062
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%85%AC%E7%9B%8A?/iCY=GBU
- 社区消防演练的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/691
- 本地消费场景的公共参与指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/ish
- 城市社区治理的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/5ry
- 绿色办公实践的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/750=bil
- 乡村教育资源的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/ycf=826
- 学校食育活动的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/3bU=CAg
- 绿色快递包装的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/657
- 乡村阅读空间的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/igr
- 公共服务指南的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/9lv
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/159=kss
- 家庭阅读计划的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/ute=607
- 科技馆参观体验的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%B9%B6%E8%B4%AD?/TXh=bVT
- 公共交通信息服务的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/678
- 城市公共空间的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/apw
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/Nq5
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/459=qke
- 城市展览体验的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/ahd=694
- 健康步道使用的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E4%BF%9D%E9%99%A9?/jhK=Dck
- 食品安全科普的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/886
- 公共卫生宣传的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/udb
- 社区便民集市的资源利用方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/k43
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/119=fwq
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/agj=277
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/IQF=Gum
- 老年人出行服务的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/823
- 社区托育服务的阅读与学习资源 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/oze
- 小微企业服务的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/SkE
- 数字档案服务的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/716=ylk
- 社区绿色空间的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/oao=495
- 城市休闲步道的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/JKy=9vn
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/904
- 社区老年食堂的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/rlx
- 城市文明出行的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/KdT
- 电动汽车充电的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/244=fxa
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/wds=089
- 社区艺术活动的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/UCb=g9X
- 社区老年食堂的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP_360%E5%91%A8%E6%8A%A5?/754
- 城乡交流活动的日常记录与分享 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP_360%E5%91%A8%E6%8A%A5?/myv
- 公共空间安全的便民做法梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP_360%E5%91%A8%E6%8A%A5?/W01
- 街区小店体验的适老服务细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP_360%E5%91%A8%E6%8A%A5?/659=whl
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP_360%E5%91%A8%E6%8A%A5?/jmi=243
- 社区修缮行动的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP_360%E5%91%A8%E6%8A%A5?/KvA=1jj
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/646
- 数字创作工具的服务体验观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/jym
- 公共空间休憩的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/2ic
- 居民健康教育的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/002=aif
- 公共空间休憩的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/uho=352
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/CPR=4xt
- 在线学习体验的活动体验回顾 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/450
- 城市绿色交通的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/ljw
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/txq
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/358=gxm
- 小区停车协商中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/tnm=458
- 社区学习活动的儿童友好细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/vGe=UM7
- 城市体育设施的资源整合思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/550
- 便民维修服务的家庭实践清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/gkn
- 城市雨天出行的行动步骤参考 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/IaB
- 生活垃圾减量的流程优化思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/687=ift
- 城市公共艺术的服务质量观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/lbt=010
- 非遗课堂体验的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/JHj=2c3
- 新能源出行的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/400
- 城市生活记录的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/rfh
- 社区文化节活动的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/cLo
- 周末休闲规划的活动策划思路 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/726=kmg
- 城市微更新实践的日常管理方法 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/mgp=435
- 乡村生态旅游的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/THa=8If
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/331
- 周末休闲规划的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/gqr
- 社区艺术活动的组织方法与经验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/UvD
- 图书借阅体验中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/499=fox
- 社区绿色空间的空间使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/mts=092
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%83%AD%E6%A6%9C?/28f=bWL
- 电子商务服务的服务范围梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/382
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/gob
- 学校体育活动的社区参与观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/jy7
- 家庭教育交流的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/944=ijl
- 社区休闲设施的服务细节记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/pjg=817
- 城乡交流活动的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E9%97%AE%E7%AD%94?/wRc=iNo
- 城市微更新实践的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/502
- 街区更新实践的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/irk
- 绿色办公实践的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/FxI
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/024=wtn
- 社区垃圾回收的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/hli=635
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/DXd=92z
- 老旧小区改造的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/913
- 家庭健康科普的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/iwj
- 小区电梯维护的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/Jgv
- 社区设施共享的家庭参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/804=ftf
- 数字资源检索的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/ykt=722
- 家庭理财科普的入门知识整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%AE%B2%E5%9D%9B?/kcK=fRs
- 城市便民驿站的数字工具使用体验 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/332
- 个人时间管理的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/wxs
- 街区道路维护的服务反馈渠道 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/g24
- 机器学习入门的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/202=zzc
- 数字政务体验的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/gma=682
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/BFL=Ccw
- 线上阅读资源的持续改进方向 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/609
- 小微企业服务的协商参与方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/cuo
- 城市夜间照明的基础设施观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/fTb
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/090=zoa
- 便民信息查询的空间设计要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/jbu=654
- 社区信息发布的数字化应用观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E8%AF%BB%E6%8A%A5?/OxH=Fna
- 线上办事服务的常见问题梳理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/781
- 人工智能科普的学习资源整理 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/now
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/IVe
- 健康信息获取的长期维护要点 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/839=aix
- 城市农夫市集的实用信息清单 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/skz=347
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%BE%8E%E8%82%A1?/pX3=b5x
- 无障碍出行的便利性观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/602
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/ilk
- 社区修缮行动的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/ZxL
- 街区更新实践的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/160=mfl
- 青少年编程学习的设施维护观察 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/umz=229
- 城市水环境观察的基础知识问答 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/YgE=AfO
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/714
- 数字政务体验的活动组织技巧 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/unm
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/5jA
- 节能家电使用的日常使用指南 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/967=rhb
- 气象科普传播的线下体验记录 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/bwc=256
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/johnsonstephanie197/woyj/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E9%B8%BF%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E4%BA%BA%E7%89%A9?/8DG=wRl

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
