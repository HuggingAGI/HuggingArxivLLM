# PhishIntentionLLM：通过多智能体检索增强生成技术挖掘网络钓鱼网站意图信息

发布时间：2025年07月21日

`LLM应用` `网络安全` `网络威胁检测`

> PhishIntentionLLM: Uncovering Phishing Website Intentions through Multi-Agent Retrieval-Augmented Generation

# 摘要

> 钓鱼网站依然是网络安全的主要威胁，但现有方法主要集中在检测上，而对背后恶意意图的识别研究仍然较少。为了解决这一问题，我们提出了PhishIntentionLLM——一个多智能体检索增强生成框架，能够从网站截图中发现钓鱼意图。通过利用大型语言模型的视觉语言能力，我们识别了四种关键钓鱼目标：凭证窃取、金融欺诈、恶意软件分发和个人信息收集。我们构建并发布了首个钓鱼意图真实数据集（约2000个样本），并使用四个商用LLM对框架进行了评估。实验结果显示，PhishIntentionLLM在GPT-4o上实现了0.7895的微精度，相比单智能体基线提升了约95%。与之前的工作相比，它在凭证窃取方面达到了0.8545的精度，提升了约4%。此外，我们还生成了一个更大的数据集（约9000个样本），用于跨行业的大规模钓鱼意图分析。这项工作为意图感知的钓鱼分析提供了一个可扩展且可解释的解决方案。

> Phishing websites remain a major cybersecurity threat, yet existing methods primarily focus on detection, while the recognition of underlying malicious intentions remains largely unexplored. To address this gap, we propose PhishIntentionLLM, a multi-agent retrieval-augmented generation (RAG) framework that uncovers phishing intentions from website screenshots. Leveraging the visual-language capabilities of large language models (LLMs), our framework identifies four key phishing objectives: Credential Theft, Financial Fraud, Malware Distribution, and Personal Information Harvesting. We construct and release the first phishing intention ground truth dataset (~2K samples) and evaluate the framework using four commercial LLMs. Experimental results show that PhishIntentionLLM achieves a micro-precision of 0.7895 with GPT-4o and significantly outperforms the single-agent baseline with a ~95% improvement in micro-precision. Compared to the previous work, it achieves 0.8545 precision for credential theft, marking a ~4% improvement. Additionally, we generate a larger dataset of ~9K samples for large-scale phishing intention profiling across sectors. This work provides a scalable and interpretable solution for intention-aware phishing analysis.

[Arxiv](https://arxiv.org/abs/2507.15419)