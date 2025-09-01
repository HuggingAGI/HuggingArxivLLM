# Graph-R1：用NP难图问题激发LLM推理潜能

发布时间：2025年08月27日

`LLM应用` `基础理论`

> Graph-R1: Unleashing LLM Reasoning with NP-Hard Graph Problems

# 摘要

> 推理型大型语言模型（RLLMs）近来在复杂推理任务上大放异彩，这主要归功于其长思维链（Long CoT）能力。但培养长思维链能力高度依赖高质量数据集的后训练，而这类数据集（如数学、代码领域）往往成本高昂且需人工构建，使得可扩展的替代方案一直无人问津。为此，我们提出将NP难（NPH）图问题作为新型合成训练语料库——这类问题天生需要深度推理、大量探索和反思策略，而这些恰恰是长思维链推理的核心特质。基于这一思路，我们构建了两阶段后训练框架：（i）在拒绝采样的NPH图实例上进行长思维链监督微调（SFT），以显著加深推理深度；（ii）通过细粒度奖励设计的强化学习（RL），提升推理效率。我们的旗舰模型Graph-R1-7B在数学、编程、STEM及逻辑领域均表现出出色的泛化能力，在NPH图问题上更是以更高的准确率和推理效率超越了QwQ-32B。这些结果表明，NPH图问题可作为提升LLM长思维链推理能力的高效且可扩展资源，为LLM后训练开辟了全新方向。相关实现代码已开源（https://github.com/Graph-Reasoner/Graph-R1），模型与数据集托管于Hugging Face仓库HKUST-DSAIL/Graph-R1。

> Reasoning Large Language Models (RLLMs) have recently achieved remarkable progress on complex reasoning tasks, largely enabled by their long chain-of-thought (Long CoT) capabilities. However, developing these Long CoT behaviors relies heavily on post-training with high-quality datasets, which are typically costly and human-curated (e.g., mathematics and code), leaving scalable alternatives unexplored. In this work, we introduce NP-hard (NPH) graph problems as a novel synthetic training corpus, as they inherently require deep reasoning, extensive exploration, and reflective strategies, which are core characteristics of Long CoT reasoning. Building on this insight, we develop a two-stage post-training framework: (i) Long CoT Supervised Fine-Tuning (SFT) on rejection-sampled NPH graph instances, which substantially enhances reasoning depth, and (ii) Reinforcement Learning (RL) with a fine-grained reward design, which sharpens reasoning efficiency. Our flagship model, Graph-R1-7B, demonstrates strong generalization across mathematics, coding, STEM, and logic, and surpasses QwQ-32B on NPH graph problems in both accuracy and reasoning efficiency. These results position NPH graph problems as an effective and scalable resource for advancing Long CoT reasoning in LLMs, opening a new frontier for LLM post-training. Our implementation is available at https://github.com/Graph-Reasoner/Graph-R1, with models and datasets hosted in our Hugging Face collection HKUST-DSAIL/Graph-R1.

[Arxiv](https://arxiv.org/abs/2508.20373)