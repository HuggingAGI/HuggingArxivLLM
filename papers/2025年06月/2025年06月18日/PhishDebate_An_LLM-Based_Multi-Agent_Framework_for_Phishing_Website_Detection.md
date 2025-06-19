# PhishDebate：基于LLM的多智能体钓鱼网站检测框架。

发布时间：2025年06月18日

`Agent` `网络安全` `网络犯罪`

> PhishDebate: An LLM-Based Multi-Agent Framework for Phishing Website Detection

# 摘要

> 网络钓鱼网站持续构成严重的网络安全威胁，它们通常利用欺骗性结构、品牌冒充和社交工程手段来规避检测。尽管大语言模型（LLMs）在理解上下文方面取得了进展，但现有方法仍存在局限性——依赖单一智能体分类，面临幻觉风险，且缺乏可解释性和鲁棒性。为解决这些问题，我们提出PhishDebate——一个基于模块化多智能体LLM的网络钓鱼网站检测框架。PhishDebate采用四个专业化智能体，在协调员和仲裁员的配合下，分别独立分析网页的四个文本维度：URL结构、HTML组成、语义内容和品牌冒充。通过结构化辩论和发散性思考，该框架能够生成更准确且可解释的决策。在商用LLMs上的广泛评估表明，PhishDebate在真实网络钓鱼数据集上实现了98.2%的召回率和98.2%的真正阳性率（TPR），超越了单智能体和Chain of Thought（CoT）基线方法。此外，其模块化设计支持智能体级别的配置调整，能够适应不同的资源和应用场景需求。

> Phishing websites continue to pose a significant cybersecurity threat, often leveraging deceptive structures, brand impersonation, and social engineering tactics to evade detection. While recent advances in large language models (LLMs) have enabled improved phishing detection through contextual understanding, most existing approaches rely on single-agent classification facing the risks of hallucination and lack interpretability or robustness. To address these limitations, we propose PhishDebate, a modular multi-agent LLM-based debate framework for phishing website detection. PhishDebate employs four specialized agents to independently analyze different textual aspects of a webpage--URL structure, HTML composition, semantic content, and brand impersonation--under the coordination of a Moderator and a final Judge. Through structured debate and divergent thinking, the framework delivers more accurate and interpretable decisions. Extensive evaluations on commercial LLMs demonstrate that PhishDebate achieves 98.2% recall and 98.2% True Positive Rate (TPR) on a real-world phishing dataset, and outperforms single-agent and Chain of Thought (CoT) baselines. Additionally, its modular design allows agent-level configurability, enabling adaptation to varying resource and application requirements.

[Arxiv](https://arxiv.org/abs/2506.15656)