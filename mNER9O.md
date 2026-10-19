# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 城市基础设施的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/268
- 终身学习资源的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/muk
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/ZP0
- 绿色生活实践的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/409=lni
- 基层医疗预约的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/pxs=985
- 在线教育体验的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%B2%BE%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%B4%A2%E7%BB%8F?/08m=PMZ
- 社区心理支持的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/538
- 市民意见收集的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/xwq
- 乡村文化活动的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/qi2
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/967=bdo
- 社区商业活力中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/fpd=410
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/TTr=Lir
- 数字生活课堂的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/351
- 老年人文化生活的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/hhb
- 数字政务体验的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/3jK
- 城市夜间生活的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/348=cie
- 城市公共座椅的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/pbx=275
- 城市基础设施的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/P9k=k8s
- 文化场馆预约的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/375
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/cww
- 街区更新实践的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/QdO
- 生活服务数字化的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/778=gfg
- 老旧小区改造的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/gbp=294
- 劳动教育实践的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/hpu=eLe
- 租房信息服务中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/876
- 城市绿色交通的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/fsi
- 家庭教育交流的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/bIq
- 家庭健康科普的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/339=mwt
- 光伏知识科普的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/aaa=157
- 城市空气科普的日常管理方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%88%86%E6%83%85?/Dwu=0FL
- 社区艺术活动的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/217
- 城市绿色交通的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/jiy
- 便民服务地图的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/eTM
- 城市应急科普的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/783=ske
- 乡村文化活动的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/xxq=777
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/0oV=GdN
- 城市慢行系统的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/152
- 图书借阅体验的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/ese
- 城市夜间照明的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/ZQn
- 旧物循环利用的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/126=wwu
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/lir=834
- 无障碍出行的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/71e=B8G
- 家庭科学教育的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/870
- 智能手机助老的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/sle
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/K1x
- 绿色出行服务的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/406=pxp
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/yuw=347
- 城市生活记录的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%B9%B6%E8%B4%AD?/ZU1=rJG
- 社区运动空间的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/542
- 校园阅读活动的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/ird
- 城市便民驿站的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/49e
- 智能家居应用的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/396=yeq
- 家庭急救准备的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/nmx=861
- 青少年科普实践的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/MV9=PUW
- 应急物资管理的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/378
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/cni
- 社区家政服务的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/iw0
- 家庭照护支持的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/987=unm
- 儿童友好空间的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/cae=997
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/Qpy=Aig
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/907
- 城市公共标识的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/cnx
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/Whp
- 社区教育资源的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/805=gzk
- 社区家校合作的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/nhb=419
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%BF%A1%E8%AE%BF?/SK3=Z7i
- 智慧停车服务的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/059
- 社区儿童活动的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/vhp
- 基层服务创新中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/3vK
- 数字课堂应用的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/274=ukz
- 数字素养提升的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/zsi=237
- 本地消费场景的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/V5E=urk
- 农业科普体验的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/753
- 旧物循环利用的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/sdo
- 家庭防灾准备的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/PJ3
- 应急物资管理的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/467=yum
- 公共空间照明中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/jas=819
- 城市生活记录的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/q02=9WA
- 城市博物馆活动的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/457
- 社区儿童活动的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/psp
- 就业技能培训的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/F3C
- 城市展览体验的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/283=ujd
- 社区运动空间的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/rhw=612
- 城市文化路线的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/9Qg=84S
- 公共服务沟通的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/243
- 居民健康教育的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/maw
- 数字课堂应用的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/iHi
- 绿色快递包装的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/457=tgv
- 城市公共空间的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/kms=939
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8D%83%E5%B8%86?/Ezb=J17
- 科技馆参观体验的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/305
- 城市文明实践的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/zvu
- 社区便利生活的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/bmm
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/857=ezw
- 城市建设科普的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/viv=291
- 口袋公园建设中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/uak=DOs
- 城市地名文化的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/692
- 社区互助网络的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/iva
- 健康信息获取的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/onc
- 小区电梯维护的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/887=wsm
- 城市应急广播的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/dbk=356
- 社区养老服务的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/cpE=zQB
- 创业经验分享的日常实践笔记 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/667
- 社区科普课堂的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/ask
- 城市空气科普的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/5Zg
- 气象科普传播的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/722=eqg
- 公共服务指南的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/cyt=306
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%8E%AF%E4%BF%9D%E8%B4%A2%E7%BB%8F?/xQw=pNB
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/697
- 公共空间休憩的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/txe
- 社区菜市场服务的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/uQu
- 本地旅行体验的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/066=voc
- 乡村公共阅读的活动策划思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/ebk=959
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E5%86%9C%E4%B8%9A?/xcF=ASY
- 数字资源检索的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/569
- 社区体育组织的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/wep
- 城市便民驿站的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/I5Q
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/853=vdb
- 公共服务评价的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/vbv=336
- 社区公共议事的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/F26=qss
- 公共服务沟通的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E5%8C%BA?/841
- 公共服务沟通的参与方式与路径 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E5%8C%BA?/akq
- 城市人文观察的社区参与观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E5%8C%BA?/SXW
- 公交站点体验的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E5%8C%BA?/151=ado
- 街头绿植养护的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E5%8C%BA?/khj=891
- 社区花园共建的数字工具使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E7%A4%BE%E5%8C%BA?/rLU=RB4
- 安全出行教育的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/755
- 城市空气科普的家庭参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/byq
- 社会体育指导的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/oIB
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/604=jxx
- 亲子阅读活动的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/nlh=126
- 数字创意课程的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/zKY=02h
- 公共服务沟通的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/073
- 个人信息保护的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/lom
- 无障碍信息设计的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/6x7
- 科学信息获取的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/976=wfb
- 公共健身器材的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/wqo=689
- 青年就业服务的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%B2%BE%E5%BD%A9%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/aLv=iX9
- 社区协商议事的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/771
- 环境监测科普的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/hyb
- 数字政务体验的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/K5g
- 便民维修服务中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/511=rcp
- 社区教育资源的空间设计要点 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/dhp=739
- 数字学习资源的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E8%81%9A%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/tdZ=MT6
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/416
- 创业经验分享的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/mar
- 家庭健康科普中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/5XC
- 街区小店体验的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/305=hqt
- 乡村文化空间中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/qkx=284
- 数字阅读服务的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/spT=fBD
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/045
- 街区小店体验中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/amw
- 城市噪声观察的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/n2A
- 药品使用科普的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/096=evt
- 租房信息服务的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/dvz=541
- 节约用水实践的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%88%9B%E6%8A%95?/2KI=L8C
- 文明养宠科普的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/464
- 社区文化节活动的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/ynt
- 数字档案服务的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/RM3
- 城市绿色交通的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/608=rcq
- 公共交通接驳的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/hii=285
- 城市公共标识中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/HBi=VCq
- 社区便民集市的绿色实践方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/378
- 居家防滑改造的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/ghs
- 日常摄影记录的入门知识整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/GKq
- 乡村文化活动的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/821=ucg
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/yay=069
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%97%B6%E6%8A%A5?/KtG=hfR
- 数字艺术创作的适老服务细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/324
- 劳动教育实践的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/fls
- 家庭健康科普的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/7EP
- 地方民俗记录的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/001=jdv
- 乡村阅读空间的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/fah=034
- 城市公共饮水的便捷程度观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/kB0=qFl
- 科学观察活动的服务范围梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/082
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/bvu
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/SIy
- 数字设备回收的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/746=pmy
- 科学观察活动的阅读与学习资源 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/cap=117
- 非遗体验活动的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/7Mw=ntf
- 青少年户外教育中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/569
- 社区体育组织的资源利用方法 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/xtl
- 户外活动组织的协作机制梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/qyE
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/365=ypq
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/rre=805
- 网络安全教育的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/y54=0Sx
- 数字艺术创作的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/173
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/avm
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/sy5
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/934=nvb
- 街区道路维护的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/ayc=933
- 图书馆活动策划的服务质量观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/G8S=L6Z
- 基层医疗预约的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/385
- 公园无障碍服务的服务体验观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/qib
- 健康饮水科普的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/ATZ
- 数字公共文化的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/896=bsm
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/rnd=949
- 居民健康教育的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/nMm=WA4
- 文化场馆预约的线下体验记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/896
- 节约用水实践的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/kvs
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/aFS
- 校园社团活动的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/396=azq
- 节能生活方式的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/mrk=270
- 社区公共餐饮的日常使用指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/TPT=DaV
- 小区公共照明的公共信息获取方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91-APP_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/020
- 城市住房服务的数字化应用观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91-APP_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/gik
- 城市生活记录的设施维护观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91-APP_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/c9U
- 老旧小区改造的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91-APP_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/597=jre
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91-APP_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/yty=714
- 全民健身活动的便利性观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91-APP_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/7Gy=Jx5
- 城市休闲步道的儿童友好细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/434
- 小微企业服务的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/ocs
- 城市基础设施的协商参与方式 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/XvL
- 日常摄影记录的行动步骤参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/511=cgx
- 数字设备回收的流程优化思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/gkq=928
- 乡村公共文化的活动体验回顾 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/k9X=WLU
- 城市慢行系统的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/418
- 儿童运动体验的常见问题梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/zln
- 节能生活方式的服务信息整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/SzS
- 食品安全科普的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/646=pad
- 社区生活指南中的几个关键细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/cpk=338
- 校园安全教育的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/SAo=9sD
- 城市人文观察的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/066
- 科学运动指导的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/faq
- 城市树木认养的基础设施观察 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/QPv
- 健康饮食教育的安全使用提示 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/956=clf
- 城乡公共服务的实际需求与回应 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ker=854
- 社区知识分享的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Gqu=xiP
- 社区邻里服务的基础知识问答 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/753
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/kfw
- 城市基础设施的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/NI2
- 非遗体验活动的组织方法与经验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/344=ecl
- 读书会组织的常见误区提醒 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/jwu=369
- 便民服务地图的居民参与机会 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/nsK=n3i
- 公共空间导览的资源整合思路 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%A4%BE%E8%AE%BA?/442
- 便民服务窗口的实用信息清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%A4%BE%E8%AE%BA?/nea
- 市民热线服务的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%A4%BE%E8%AE%BA?/BeZ
- 城市适老服务的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%A4%BE%E8%AE%BA?/892=sui
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%A4%BE%E8%AE%BA?/nnf=788
- 青少年心理健康的服务细节记录 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E7%A4%BE%E8%AE%BA?/iLd=pTj
- 社区教育资源的便民做法梳理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/450
- 社区科普课堂的学习资源整理 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/yfu
- 基层医疗预约的空间使用体验 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/q0I
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/053=smg
- 数字创意课程的持续改进方向 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/avu=483
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/9qM=3kL
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/089
- 家庭教育交流的执行流程参考 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/iux
- 数字学习资源的活动组织技巧 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/24u
- 生活服务数字化的家庭实践清单 |来源：https://github.com/martinderrick5/qbnb/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/275=ffg

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
