# AI 资讯简报 · 2026-06-12

## 🔥 今日重点

### Anthropic 为 Fable 5 偷偷限制 LLM 开发道歉并撤回
Anthropic 发布 Claude Fable 5 时被曝工程化限制了针对前沿 LLM 开发请求的有效性，引发开源社区强烈反弹。迫于压力，Anthropic 发表声明道歉（"我们做出了错误的权衡，对不起"），并承诺所有安全干预将对用户透明可见。
📎 [Wired / Reddit r/MachineLearning](https://www.reddit.com/r/MachineLearning/comments/1u2tk0i/anthropic_walks_back_policy_on_silent_nerfing_for/)

### OpenAI 正考虑大幅下调产品价格，预判将与 Anthropic 展开用户之争
OpenAI 正在评估大幅降价策略以应对日益激烈的市场竞争。百万 Token 推理成本已降至个位数人民币区间，算力成本持续走低。同时 OpenAI 秘密提交 IPO 文件，AI 行业价格战一触即发。
📎 [36氪](https://36kr.com/p/3848516305605892?f=rss)

### Google DeepMind 担心数百万 AI Agent 交互失控
Google DeepMind AGI 安全与对齐研究负责人 Rohin Shah 公开表示，当数百万 AI Agent 在互联网上自主交互时可能产生不可预见的风险。DeepMind 已启动专项研究基金，评估 Agent 大规模交互的安全性。
📎 [MIT Technology Review](https://www.technologyreview.com/2026/06/11/1138794/google-deepmind-is-worried-about-what-happens-when-millions-of-agents-start-to-interact/)

### Visa 将支付系统接入 ChatGPT，AI Agent 可自动完成零售交易
Visa 将其支付基础设施与 ChatGPT 打通，AI Agent 现在可以推荐商品并直接完成金融交易。此举将人的干预从零售漏斗的最后环节中完全移除，实现从用户提示到支付完成的端到端自动化。
📎 [AI News](https://www.artificialintelligence-news.com/news/visa-chatgpt-integration-enables-ai-agent-retail-purchasing/)

## 🏢 大厂动态

### Siri AI 正式发布：iOS 27 + Google Gemini，但全球大部分地区不可用
苹果在 WWDC 2026 上正式推出全新 Siri AI，与 Google 合作引入 Gemini 大模型。然而首批仅在美国英语地区上线，全球大多数市场被锁定在"等一等"的状态，引发用户不满。
📎 [AI News](https://www.artificialintelligence-news.com/news/siri-ai-google-gemini-rollout/)

### Meta 与印度 Reliance 签署 AI 数据中心协议
Meta 宣布与印度信实工业（Reliance Industries）达成战略合作，将在印度建设首个 AI 数据中心。这是 Meta 在亚洲最重要的 AI 基础设施投资之一，服务于印度市场的 AI 推理需求。
📎 [Meta Newsroom](https://about.fb.com/news/2026/06/meta-partners-with-reliance-on-ai-enabled-data-center-in-india/)

### Waymo 推出 $30/月会员计划 Waymo Premier
Alphabet 旗下 Waymo 宣布推出月费 30 美元的会员计划 Waymo Premier，会员可享受优先接送、每次行程 10% 返现等权益。初期面向旧金山、洛杉矶和凤凰城数万名受邀用户开放。
📎 [36氪](https://36kr.com/newsflashes/3849421770658823?f=rss)

### 美团 AI 浏览器 Tabbit 1.0 正式上线
美团旗下 GN06 团队发布 AI 原生浏览器 Tabbit 1.0，内置多款头部大模型，支持跨软件、跨网页自动执行复杂任务。标准版永久免费，专业版一周仅 9.9 元。
📎 [雷锋网](https://www.leiphone.com/category/industrynews/CUaS5ZOnMSrwjs7u.html)

### 钉钉换帅：92 年技术极客陈宇森接任 CEO
阿里巴巴宣布钉钉管理层调整，92 年出生的技术极客、长亭科技创始人陈宇森接替陈航出任钉钉 CEO。此前阿里合伙人委员会在内网严厉批评了钉钉的管理文化，称"不是阿里文化该有的样子"。
📎 [雷锋网](https://www.leiphone.com/category/industrynews/EA4A0xaQ1pM3TeQM.html)

## 🔬 研究与开源

### CVPR 2026 闭幕：具身智能全面接管，投稿量创历史新高
CVPR 2026 共收到 16,092 篇投稿，录用 4,071 篇（25.3%）。5 篇获奖论文中至少 3 篇直指具身智能，视觉-语言与多模态 LLM 论文占比一年飙涨 5.7 个百分点。NVIDIA 和 Tesla 正合力将机器人从实验室推向商业化。
📎 [雷锋网](https://www.leiphone.com/category/ai/dvz76xNimms03Mgz.html)

### NVIDIA 加速 Google DeepMind DiffusionGemma，本地 AI 速度大幅提升
Google DeepMind 发布开源文本扩散模型 DiffusionGemma，采用扩散架构替代传统自回归方式。NVIDIA 为其做 GeForce RTX 优化，从本地 PC 到云端均可运行，文本生成速度最高提升 4 倍。
📎 [NVIDIA Blog](https://blogs.nvidia.com/blog/rtx-ai-garage-local-gemma-diffusion/)

### Amazon Graviton5：Chiplet 架构实现超摩尔定律性能飞跃
Amazon 发布第五代自研服务器芯片 Graviton5，采用全新 Chiplet 架构、自定义 Die-to-Die 连接，支持 DDR5-8800 和 PCIe Gen6。面向通用计算与 Agentic AI 工作负载性能提升 25%。
📎 [Amazon Science](https://www.amazon.science/blog/graviton5s-improved-design-increases-speed-and-energy-efficiency-beyond-moores-law)

---

📡 13 信源 · 12 条
💰 每日 Token: ~15,000 · 成本: ~$0.005
