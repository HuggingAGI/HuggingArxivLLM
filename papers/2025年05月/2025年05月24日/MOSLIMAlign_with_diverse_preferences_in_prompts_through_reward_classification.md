# MOSLIM：通过奖励分类实现对多样化提示偏好的精准对齐

发布时间：2025年05月24日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的多目标对齐问题，提出了一种新的方法MOSLIM，旨在通过单个奖励模型和策略模型来处理多样化目标。论文详细描述了方法的创新点、实现细节以及实验结果，属于对LLM理论的深入研究和改进。因此，这篇论文应归类为LLM理论。` `机器学习`

> MOSLIM:Align with diverse preferences in prompts through reward classification

# 摘要

> 大型语言模型（LLMs）的多目标对齐至关重要，以确保基础模型符合多样化的人类偏好。当前该领域的研究通常涉及针对各种偏好的多策略或多奖励模型，或者需要为特定偏好训练监督微调（SFT）模型。本研究中，我们提出了一种新颖的多目标对齐方法MOSLIM，该方法仅使用单个奖励模型和策略模型即可应对多样化目标。MOSLIM通过提示灵活控制这些目标，且在SFT阶段无需进行偏好训练，从而允许直接利用数千个现成模型在此训练框架中。MOSLIM采用多头奖励模型对问答对进行分类而非评分，然后通过映射函数将奖励模型的分类结果转换为奖励分数，以此标量奖励优化策略模型。我们在多个多目标基准上验证了该方法的有效性，并对不同规模的奖励模型及策略优化方法进行了消融研究。实验结果表明，MOSLIM在大多数情况下优于现有方法，同时相比现有策略优化方法，其所需的GPU计算资源显著减少。

> The multi-objective alignment of Large Language Models (LLMs) is essential for ensuring foundational models conform to diverse human preferences. Current research in this field typically involves either multiple policies or multiple reward models customized for various preferences, or the need to train a preference-specific supervised fine-tuning (SFT) model. In this work, we introduce a novel multi-objective alignment method, MOSLIM, which utilizes a single reward model and policy model to address diverse objectives. MOSLIM provides a flexible way to control these objectives through prompting and does not require preference training during SFT phase, allowing thousands of off-the-shelf models to be directly utilized within this training framework. MOSLIM leverages a multi-head reward model that classifies question-answer pairs instead of scoring them and then optimize policy model with a scalar reward derived from a mapping function that converts classification results from reward model into reward scores. We demonstrate the efficacy of our proposed method across several multi-objective benchmarks and conduct ablation studies on various reward model sizes and policy optimization methods. The MOSLIM method outperforms current multi-objective approaches in most results while requiring significantly fewer GPU computing resources compared with existing policy optimization methods.

[Arxiv](https://arxiv.org/abs/2505.20336)