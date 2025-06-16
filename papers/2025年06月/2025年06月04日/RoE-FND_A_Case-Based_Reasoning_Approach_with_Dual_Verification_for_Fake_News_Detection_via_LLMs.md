# RoE-FND: 基于案例推理的双重验证方法，通过大型语言模型 (LLMs) 实现高效的假新闻检测

发布时间：2025年06月04日

`LLM应用` `人工智能`

> RoE-FND: A Case-Based Reasoning Approach with Dual Verification for Fake News Detection via LLMs

# 摘要

> 网络上的误导性内容激增，催生了对强大的假新闻检测 (FND) 系统的迫切需求。尽管基于证据的方法通过利用外部知识来验证声明，但现有方法仍存在关键局限：噪声证据选择、泛化能力不足以及决策过程不透明。近期将大型语言模型 (LLMs) 应用于 FND 的尝试又带来了新的挑战，包括幻觉推理和结论偏见。

为了解决这些问题，我们提出了 	extbf{RoE-FND} (	extbf{underline{R}}eason 	extbf{underline{o}}n 	extbf{underline{E}}xperiences FND)，一个通过整合大型语言模型与经验学习，将基于证据的 FND 转化为逻辑推理任务的创新框架。RoE-FND 框架包含两大核心阶段：首先，	extit{自我反思的知识构建}阶段通过分析历史推理错误来构建知识库；其次，	extit{动态标准检索}阶段从历史案例中提取经验，生成特定任务的推理指南。此外，该框架还通过独特的双通道程序将推理结果与内部经验进行交叉验证。

本研究的主要贡献包括：提出了一种针对 FND 的案例推理框架，有效应对现有挑战；设计了一种无需额外训练的自适应方法，能够灵活应对动态变化；并通过在三个数据集上的实证验证，证明了该框架在泛化能力和检测效果上显著优于现有最先进的方法。


> The proliferation of deceptive content online necessitates robust Fake News Detection (FND) systems. While evidence-based approaches leverage external knowledge to verify claims, existing methods face critical limitations: noisy evidence selection, generalization bottlenecks, and unclear decision-making processes. Recent efforts to harness Large Language Models (LLMs) for FND introduce new challenges, including hallucinated rationales and conclusion bias. To address these issues, we propose \textbf{RoE-FND} (\textbf{\underline{R}}eason \textbf{\underline{o}}n \textbf{\underline{E}}xperiences FND), a framework that reframes evidence-based FND as a logical deduction task by synergizing LLMs with experiential learning. RoE-FND encompasses two stages: (1) \textit{self-reflective knowledge building}, where a knowledge base is curated by analyzing past reasoning errors, namely the exploration stage, and (2) \textit{dynamic criterion retrieval}, which synthesizes task-specific reasoning guidelines from historical cases as experiences during deployment. It further cross-checks rationales against internal experience through a devised dual-channel procedure. Key contributions include: a case-based reasoning framework for FND that addresses multiple existing challenges, a training-free approach enabling adaptation to evolving situations, and empirical validation of the framework's superior generalization and effectiveness over state-of-the-art methods across three datasets.

[Arxiv](https://arxiv.org/abs/2506.11078)