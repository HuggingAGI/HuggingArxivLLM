# ReARTeR: 检索增强推理与可信过程奖励

发布时间：2025年01月14日

`RAG

理由：该论文主要讨论了检索增强生成（RAG）系统在处理知识密集型任务中的局限，并提出了ReARTeR框架来增强RAG系统的推理能力。论文的核心内容围绕RAG系统的改进和优化，因此应归类为RAG。` `人工智能` `推理系统`

> ReARTeR: Retrieval-Augmented Reasoning with Trustworthy Process Rewarding

# 摘要

> # 检索增强生成（RAG）系统在LLMs中展现出处理知识密集型任务的潜力，但在复杂多步推理方面仍有局限。尽管现有方法已将RAG与思维链推理或基于过程奖励模型（PRMs）的测试时搜索结合，但这些方法仍面临解释缺失、PRM训练数据偏见、早期步骤评分偏差及推理潜力训练后优化不足等问题。为此，我们提出了ReARTeR框架，通过可信过程奖励增强RAG系统的推理能力。在测试阶段，ReARTeR利用过程奖励模型进行精确标量评分，并通过过程解释模型（PEM）生成自然语言解释，优化推理步骤。训练后阶段，ReARTeR采用蒙特卡洛树搜索，结合可信过程奖励收集高质量步骤级偏好数据，并通过迭代偏好优化进行优化。ReARTeR解决了三大核心挑战：（1）PRM与PEM的不对齐，通过离策略偏好学习解决；（2）PRM训练数据偏见，通过平衡注释和强化挑战性示例的注释缓解；（3）PRM早期步骤偏见，通过基于时间差的前瞻搜索策略解决。多步推理基准实验结果表明，ReARTeR显著提升了RAG系统的推理能力，展现了其巨大潜力。

> Retrieval-Augmented Generation (RAG) systems for Large Language Models (LLMs) hold promise in knowledge-intensive tasks but face limitations in complex multi-step reasoning. While recent methods have integrated RAG with chain-of-thought reasoning or test-time search using Process Reward Models (PRMs), these approaches encounter challenges such as a lack of explanations, bias in PRM training data, early-step bias in PRM scores, and insufficient post-training optimization of reasoning potential. To address these issues, we propose Retrieval-Augmented Reasoning through Trustworthy Process Rewarding (ReARTeR), a framework that enhances RAG systems' reasoning capabilities through post-training and test-time scaling. At test time, ReARTeR introduces Trustworthy Process Rewarding via a Process Reward Model for accurate scalar scoring and a Process Explanation Model (PEM) for generating natural language explanations, enabling step refinement. During post-training, it utilizes Monte Carlo Tree Search guided by Trustworthy Process Rewarding to collect high-quality step-level preference data, optimized through Iterative Preference Optimization. ReARTeR addresses three core challenges: (1) misalignment between PRM and PEM, tackled through off-policy preference learning; (2) bias in PRM training data, mitigated by balanced annotation methods and stronger annotations for challenging examples; and (3) early-step bias in PRM, resolved through a temporal-difference-based look-ahead search strategy. Experimental results on multi-step reasoning benchmarks demonstrate significant improvements, underscoring ReARTeR's potential to advance the reasoning capabilities of RAG systems.

[Arxiv](https://arxiv.org/abs/2501.07861)