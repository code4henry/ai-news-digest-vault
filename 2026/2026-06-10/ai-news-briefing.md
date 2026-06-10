# AI 资讯简报 · 2026-06-10

## 🔥 今日重点

### Anthropic 发布 Claude Fable 5 / Mythos — 最强模型但限制网络安全能力
Anthropic 于周二正式推出最强模型 Claude Fable 5（此前内部代号 Mythos）。该模型拥有前沿的代码漏洞发现与利用能力，但 Anthropic 特意发布了禁用网络安全任务的受限版本，相关查询将由 Opus 4.8 处理。防护措施还覆盖生物学等敏感领域。
📎 36氪（转引新浪财经）

### Apple WWDC 2026：第三代 Foundation Models + CoreAI 端侧推理引擎 + NVIDIA 机密计算
苹果在 WWDC 2026 上发布第三代 Apple Foundation Models（AFM），涵盖 5 款从端侧到服务器的模型（与 Google 联合构建）。全新 CoreAI 推理引擎取代 CoreML 支持 Apple Silicon 端侧优化推理。同时宣布 NVIDIA GPU 机密计算将用于 Apple Private Cloud Compute，并扩展至 Google Cloud。
📎 Apple ML Research / NVIDIA Blog / Reddit r/LocalLLaMA

### CVPR 2026 落幕＋ICRA 2026 闭幕 — 多项里程碑级成果
CVPR 2026（丹佛）最佳论文由 Google DeepMind 的 D4RT（4D 动态场景重建）摘得，Oxford VGG 实现背靠背两连冠。视觉物理数据集 PhysInOne（2M 视频、150K+3D 场景）发布，VLA 论文同比增长 5 倍。ICRA 2026（维也纳）上灵巧手竞争白热化，清华高阳团队 FP3 入围最佳论文提名。Latent Labs 创始人提出 AI 进入生物学可编程时代。
📎 雷锋网（多篇）

## 🏢 大厂动态

### 美团发布 AI 浏览器 Tabbit 1.0，微信 AI 生态开放接入
美团 GN06 团队推出 AI 原生浏览器 Tabbit 1.0，内置多款头部大模型，可自动执行跨软件跨网页任务，标准版永久免费。同周，微信正式开放 AI 生态接入能力，滴滴、美团、携程等已首批接入，用户可通过微信 AI Agent 直接唤起服务。
📎 雷锋网 / 36氪

### Intel 至强 6+ 发布：Agent 时代 CPU 需求暴增，中国区需求同比 +417%
Intel 在北京数据中心创新日推出首款 18A 制程至强 6+ 处理器。数据显示中国 AI 算力需求同比暴增 417%，CPU/GPU 配比从 1:8 走向 1:2 乃至 1:1。Agent 类应用大量调用 CPU 而非 GPU（调度、记忆、工具调用），导致 CPU 开始缺货。腾讯云、阿里云、金山云已合作落地。
📎 雷锋网

### 中国软件国际签 10 亿元 AI 算力协议 / 超微电脑 70 亿美元股权融资
中国软件国际签约向第三方客户供应高端 AI 算力设备，合约总金额约 10 亿元，用于 AI 研发与算力基建。超微电脑计划进行 70 亿美元股权融资，用于采购 AI 服务器组件，盘后股价重挫逾 10%。
📎 36氪（转引公司公告 / 新浪财经）

## 🔬 研究与开源

### Cohere 发布 North Mini Code：30B 参数 Apache 2.0 开源编程模型
Cohere 正式发布 North Mini Code，30B 参数 MoE 架构（3B 激活参数），专注 Agentic Coding，Apache 2.0 协议开源。在 Artificial Analysis 编程评测中表现强劲，接近 Qwen 3.6 35B 水平。
📎 Hugging Face Blog / Reddit r/LocalLLaMA

### Furiosa AI 发布 RNGD 推理芯片 — 面向消费级市场
韩国 AI 芯片创企 Furiosa AI 发布 RNGD 推理芯片，采用台积电 5nm、Hynix HBM3 48GB 显存（1.5TB/s 带宽）、TDP 180W。若开放编程接口并支持 llama.cpp，有望成为本地 LLM 推理的革命性产品。
📎 Reddit r/LocalLLaMA

### 华为天才少年王裕鑫创业形界智能，聚焦流式视频生成
前华为天才少年、元石科技 007 号员工王裕鑫创立形界智能，方向为实时连续交互式视频生成（流式视频生成），成立首月完成数千万级融资。此前他主导了 200B+ 大模型训练与全球首个开源并行思考模型 XBai o4。
📎 雷锋网（独家）

### context-mode：AI 编程成本降低 98% 的开源 MCP 插件登顶 GitHub HN
开源项目 context-mode 专为 AI 编程优化上下文，基于 MCP 协议，能将 Token 消耗降低 98%，模型记忆力从 30 分钟提升至 3 小时。背后为跨国初创团队，登顶 GitHub Hacker News。
📎 36氪（涌现新项目）

### Latent Labs：AI 正在让生物学进入"可编程时代" — CVPR 2026 特邀演讲
前 DeepMind AlphaFold 核心成员、Latent Labs 创始人 Simon Kohl 在 CVPR 2026 发表演讲，提出从"结构预测"到"条件生成"再到"自主智能体"的药物设计跃迁路线。其 Latent-X1/X2 基础模型在湿实验室命中率上超越传统万亿级筛选。
📎 雷锋网

### Phinite — 多智能体 OS：为 Agent 提供一等公民身份
开源项目 Phinite 发布，定位为多 Agent 系统的基础设施层，每个 Agent 拥有独立 ID、版本、技能图谱和行为评估系统（而非传统功能测试），解决 Agent 系统的身份与治理缺失问题。
📎 Reddit r/MachineLearning

---

📡 12 信源 · 15 条
💰 每日 Token: ~15,000 · 成本: ~$0.005
