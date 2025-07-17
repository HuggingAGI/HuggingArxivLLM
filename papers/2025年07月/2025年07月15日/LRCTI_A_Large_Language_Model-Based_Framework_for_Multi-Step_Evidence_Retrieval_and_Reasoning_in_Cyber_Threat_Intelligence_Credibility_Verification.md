# LRCTI：基于大型语言模型的网络威胁情报可信性验证多步骤证据检索与推理框架。本研究构建了一个全新的框架，旨在通过多步骤的证据检索与推理，提升网络威胁情报的可信性验证能力。

发布时间：2025年07月15日

`LLM应用` `网络安全` `网络威胁情报`

> LRCTI: A Large Language Model-Based Framework for Multi-Step Evidence Retrieval and Reasoning in Cyber Threat Intelligence Credibility Verification

# 摘要

> # 摘要  
验证网络威胁情报（CTI）的可信度对于可靠的网络安全防御至关重要。然而，传统方法通常将这一任务简化为静态分类问题，依赖手工设计的特征或孤立的深度学习模型。这些方法在处理不完整、异构或噪声情报时往往表现欠佳，并且决策过程缺乏透明度，这在现实威胁环境中显著降低了其有效性。为了解决这些问题，我们提出了LRCTI，一个基于大型语言模型（LLM）的多步骤CTI可信度验证框架。该框架首先通过文本摘要模块，将复杂的智能报告浓缩为简洁且可操作的威胁声明。随后，采用自适应多步骤证据检索机制，从特定的CTI语料库中迭代识别和优化支持信息，这一过程由LLM反馈引导。最后，基于提示的自然语言推理（NLI）模块评估每个声明的可信度，同时生成可解释的分类结果理由。实验结果表明，在CTI-200和PolitiFact两个基准数据集上，LRCTI的F1-Macro和F1-Micro得分较现有最优基线提升了5%以上，分别达到90.9%和93.6%。这些结果充分证明，LRCTI有效克服了传统方法的核心局限性，为自动化的CTI可信度验证提供了一个可扩展、准确且可解释的解决方案。


> Verifying the credibility of Cyber Threat Intelligence (CTI) is essential for reliable cybersecurity defense. However, traditional approaches typically treat this task as a static classification problem, relying on handcrafted features or isolated deep learning models. These methods often lack the robustness needed to handle incomplete, heterogeneous, or noisy intelligence, and they provide limited transparency in decision-making-factors that reduce their effectiveness in real-world threat environments. To address these limitations, we propose LRCTI, a Large Language Model (LLM)-based framework designed for multi-step CTI credibility verification. The framework first employs a text summarization module to distill complex intelligence reports into concise and actionable threat claims. It then uses an adaptive multi-step evidence retrieval mechanism that iteratively identifies and refines supporting information from a CTI-specific corpus, guided by LLM feedback. Finally, a prompt-based Natural Language Inference (NLI) module is applied to evaluate the credibility of each claim while generating interpretable justifications for the classification outcome. Experiments conducted on two benchmark datasets, CTI-200 and PolitiFact show that LRCTI improves F1-Macro and F1-Micro scores by over 5%, reaching 90.9% and 93.6%, respectively, compared to state-of-the-art baselines. These results demonstrate that LRCTI effectively addresses the core limitations of prior methods, offering a scalable, accurate, and explainable solution for automated CTI credibility verification

[Arxiv](https://arxiv.org/abs/2507.11310)