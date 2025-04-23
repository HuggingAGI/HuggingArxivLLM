# # **DianJin-R1：大型语言模型的财务推理评测与优化**

发布时间：2025年04月22日

`LLM应用` `金融推理`

> DianJin-R1: Evaluating and Enhancing Financial Reasoning in Large Language Models

# 摘要

> 在金融领域，有效推理仍是大型语言模型（LLMs）面临的核心挑战，这些任务通常需要特定领域的知识、精确的数值计算以及严格遵守合规规则。为此，我们提出了DianJin-R1，一个通过推理增强监督和强化学习来解决这些挑战的推理增强框架。我们的方法的核心是DianJin-R1-Data，一个从CFLUE、FinQA和一个专有的合规语料库（中文合规检查，CCC）构建的高质量数据集，结合了多样的金融推理场景和经过验证的标注。我们的模型DianJin-R1-7B和DianJin-R1-32B是从Qwen2.5-7B-Instruct和Qwen2.5-32B-Instruct微调而来的，使用了一种生成推理步骤和最终答案的结构化格式。为了进一步优化推理质量，我们应用了组相对策略优化（GRPO），这是一种结合了双重奖励信号的强化学习方法：一种鼓励结构化输出，另一种奖励答案正确性。我们在五个基准上评估了我们的模型：三个金融数据集（CFLUE、FinQA和CCC）和两个通用推理基准（MATH-500和GPQA-Diamond）。实验结果表明，DianJin-R1模型在复杂金融任务上始终优于其非推理版本。此外，在真实世界的CCC数据集上，我们的单次调用推理模型与需要显著更多计算成本的多智能体系统相比，表现相当甚至更优。这些发现证明了DianJin-R1通过结构化监督和奖励对齐学习在增强金融推理方面的有效性，为实际应用提供了一个可扩展和实用的解决方案。

> Effective reasoning remains a core challenge for large language models (LLMs) in the financial domain, where tasks often require domain-specific knowledge, precise numerical calculations, and strict adherence to compliance rules. We propose DianJin-R1, a reasoning-enhanced framework designed to address these challenges through reasoning-augmented supervision and reinforcement learning. Central to our approach is DianJin-R1-Data, a high-quality dataset constructed from CFLUE, FinQA, and a proprietary compliance corpus (Chinese Compliance Check, CCC), combining diverse financial reasoning scenarios with verified annotations. Our models, DianJin-R1-7B and DianJin-R1-32B, are fine-tuned from Qwen2.5-7B-Instruct and Qwen2.5-32B-Instruct using a structured format that generates both reasoning steps and final answers. To further refine reasoning quality, we apply Group Relative Policy Optimization (GRPO), a reinforcement learning method that incorporates dual reward signals: one encouraging structured outputs and another rewarding answer correctness. We evaluate our models on five benchmarks: three financial datasets (CFLUE, FinQA, and CCC) and two general reasoning benchmarks (MATH-500 and GPQA-Diamond). Experimental results show that DianJin-R1 models consistently outperform their non-reasoning counterparts, especially on complex financial tasks. Moreover, on the real-world CCC dataset, our single-call reasoning models match or even surpass the performance of multi-agent systems that require significantly more computational cost. These findings demonstrate the effectiveness of DianJin-R1 in enhancing financial reasoning through structured supervision and reward-aligned learning, offering a scalable and practical solution for real-world applications.

[Arxiv](https://arxiv.org/abs/2504.15716)