# 大型语言模型智能体社会模拟的运行验证：基于Voat v/technology的实证

发布时间：2025年08月29日

`Agent` `媒体与娱乐`

> Operational Validation of Large-Language-Model Agent Social Simulation: Evidence from Voat v/technology

# 摘要

> 大型语言模型（LLMs）赋能生成式社会模拟，能够捕捉在线社交平台上受文化影响、遵循规范的互动行为。我们构建了技术社区模拟系统，原型为Voat——这个类似Reddit的极右翼新闻聚合与讨论平台活跃于2014至2020年。借助YSocial框架，我们以从Voat共享URL中采样的固定技术链接目录（覆盖30余个领域）为模拟种子，并利用MADOC数据集样本将参数校准至Voat的v/technology板块。智能体采用基础无审查模型（Dolphin 3.0，基于Llama 3.1 8B）与简洁角色设定（含人口统计、政治倾向、兴趣、教育程度及毒性倾向），依据平台的链接文本提交规则、线程回复机制和日常活动周期生成帖子、回复与互动反应。我们运行了30天模拟，并通过对比分布特征与结构模式同匹配的Voat数据，从活动模式、互动网络、毒性水平及主题覆盖四个维度评估操作有效性。结果呈现出常见的在线社区规律：活动节奏相似、参与度呈重尾分布、互动网络稀疏且聚类度低、存在核心-边缘结构、主题与Voat高度一致，同时毒性水平偏高。当前研究的局限性在于无状态智能体设计，且评估仅基于单次30天模拟运行，这制约了外部有效性与方差估计的可靠性。模拟生成贴近现实的讨论内容，其中常出现有毒语言，话题主要围绕大型科技公司、人工智能等科技主题。该方法为在受控环境中研究毒性动态、测试内容审核策略提供了极具价值的研究手段。

> Large Language Models (LLMs) enable generative social simulations that can capture culturally informed, norm-guided interaction on online social platforms. We build a technology community simulation modeled on Voat, a Reddit-like alt-right news aggregator and discussion platform active from 2014 to 2020. Using the YSocial framework, we seed the simulation with a fixed catalog of technology links sampled from Voat's shared URLs (covering 30+ domains) and calibrate parameters to Voat's v/technology using samples from the MADOC dataset. Agents use a base, uncensored model (Dolphin 3.0, based on Llama 3.1 8B) and concise personas (demographics, political leaning, interests, education, toxicity propensity) to generate posts, replies, and reactions under platform rules for link and text submissions, threaded replies and daily activity cycles. We run a 30-day simulation and evaluate operational validity by comparing distributions and structures with matched Voat data: activity patterns, interaction networks, toxicity, and topic coverage. Results indicate familiar online regularities: similar activity rhythms, heavy-tailed participation, sparse low-clustering interaction networks, core-periphery structure, topical alignment with Voat, and elevated toxicity. Limitations of the current study include the stateless agent design and evaluation based on a single 30-day run, which constrains external validity and variance estimates. The simulation generates realistic discussions, often featuring toxic language, primarily centered on technology topics such as Big Tech and AI. This approach offers a valuable method for examining toxicity dynamics and testing moderation strategies within a controlled environment.

[Arxiv](https://arxiv.org/abs/2508.21740)