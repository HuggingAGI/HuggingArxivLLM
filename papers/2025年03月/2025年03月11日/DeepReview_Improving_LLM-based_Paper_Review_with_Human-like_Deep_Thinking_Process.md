# # DeepReview：利用人类般的深度思考过程优化基于LLM的论文评审

发布时间：2025年03月11日

`LLM应用` `科学研究评估` `自动论文评审`

> DeepReview: Improving LLM-based Paper Review with Human-like Deep Thinking Process

# 摘要

> 大型语言模型（LLMs）正被广泛应用于科学研究评估，尤其是在自动论文评审领域。然而，现有的基于LLM的评审系统仍面临诸多挑战，包括领域专业知识有限、推理出现幻觉以及缺乏结构化评估。为了解决这些问题，我们推出了DeepReview，一个多阶段框架，通过结构化分析、文献检索和基于证据的论证来模拟专家审稿人的行为。我们利用DeepReview-13K这一精选数据集（包含结构化注释）训练了DeepReviewer-14B，其表现优于CycleReviewer-70B，且使用了更少的令牌。在最佳模式下，DeepReviewer-14B在评估中对GPT-o1和DeepSeek-R1的胜率分别高达88.21%和80.20%。我们的研究为基于LLM的论文评审设立了新的基准，所有相关资源均已公开。代码、模型、数据集及演示均可在http://ai-researcher.net获取。

> Large Language Models (LLMs) are increasingly utilized in scientific research assessment, particularly in automated paper review. However, existing LLM-based review systems face significant challenges, including limited domain expertise, hallucinated reasoning, and a lack of structured evaluation. To address these limitations, we introduce DeepReview, a multi-stage framework designed to emulate expert reviewers by incorporating structured analysis, literature retrieval, and evidence-based argumentation. Using DeepReview-13K, a curated dataset with structured annotations, we train DeepReviewer-14B, which outperforms CycleReviewer-70B with fewer tokens. In its best mode, DeepReviewer-14B achieves win rates of 88.21\% and 80.20\% against GPT-o1 and DeepSeek-R1 in evaluations. Our work sets a new benchmark for LLM-based paper review, with all resources publicly available. The code, model, dataset and demo have be released in http://ai-researcher.net.

[Arxiv](https://arxiv.org/abs/2503.08569)