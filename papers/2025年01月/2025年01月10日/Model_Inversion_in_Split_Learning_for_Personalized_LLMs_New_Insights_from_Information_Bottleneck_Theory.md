# # 分割学习中的模型反演：信息瓶颈理论为个性化LLMs带来的新洞见

发布时间：2025年01月10日

`LLM应用

理由：这篇论文主要讨论了在移动设备上部署大型语言模型（LLMs）时面临的安全问题，特别是分割学习框架中的模型反转攻击。研究提出了新的攻击方法和防御策略，旨在解决隐私泄露问题。这些内容直接涉及LLMs在实际应用中的部署和安全问题，因此应归类为“LLM应用”。` `隐私保护` `边缘计算`

> Model Inversion in Split Learning for Personalized LLMs: New Insights from Information Bottleneck Theory

# 摘要

> # 个性化大型语言模型（LLMs）日益普及，GPT-4等模型展现了强大的能力。这一趋势也推动了在移动设备上部署LLMs的研究热潮。边缘-云部署的可行方案之一是分割学习，但此前研究大多忽略了设备到服务器传输的中间表示可能导致的隐私泄露。本研究首次在LLMs的分割学习框架中识别出模型反转攻击，凸显了安全防御的重要性。我们首次引入互信息熵，用于理解基于Transformer的LLMs的信息传播，并评估LLM块的隐私攻击性能。针对表示比嵌入更稀疏、信息量更少的问题，我们提出了两阶段攻击系统：第一阶段将表示投影到嵌入空间，第二阶段通过生成模型从嵌入中恢复文本。这一设计简化了复杂性，在多种场景下实现了38%-75%的攻击成功率，较现有技术提升了60%以上。本研究全面揭示了在边缘端部署个性化LLMs时潜在的隐私风险。

> Personalized Large Language Models (LLMs) have become increasingly prevalent, showcasing the impressive capabilities of models like GPT-4. This trend has also catalyzed extensive research on deploying LLMs on mobile devices. Feasible approaches for such edge-cloud deployment include using split learning. However, previous research has largely overlooked the privacy leakage associated with intermediate representations transmitted from devices to servers. This work is the first to identify model inversion attacks in the split learning framework for LLMs, emphasizing the necessity of secure defense. For the first time, we introduce mutual information entropy to understand the information propagation of Transformer-based LLMs and assess privacy attack performance for LLM blocks. To address the issue of representations being sparser and containing less information than embeddings, we propose a two-stage attack system in which the first part projects representations into the embedding space, and the second part uses a generative model to recover text from these embeddings. This design breaks down the complexity and achieves attack scores of 38%-75% in various scenarios, with an over 60% improvement over the SOTA. This work comprehensively highlights the potential privacy risks during the deployment of personalized LLMs on the edge side.

[Arxiv](https://arxiv.org/abs/2501.05965)