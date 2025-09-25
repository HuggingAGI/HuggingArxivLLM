# ShinkaEvolve：迈向开放式与样本高效的程序进化

发布时间：2025年09月17日

`Agent` `基础理论`

> ShinkaEvolve: Towards Open-Ended And Sample-Efficient Program Evolution

# 摘要

> 我们推出ShinkaEvolve：这是一个全新的开源框架，借助大型语言模型（LLMs）推动科学发现，不仅性能达到最先进水平，效率更是前所未有。近年来，随着LLMs推理时间计算的规模化发展，广义科学发现领域取得了重大突破。这些方法借助进化智能体框架，将LLMs用作变异算子来生成候选解决方案。然而，现有的代码进化方法存在严重局限：样本效率低下，往往需要数千个样本才能找到有效解决方案；且多为闭源，阻碍了其广泛应用与扩展。ShinkaEvolve针对这些局限提出了三项关键创新：一是平衡探索与利用的父代采样技术；二是用于高效搜索空间探索的代码新颖性拒绝采样；三是基于多臂老虎机的LLM集成选择策略。我们在多种任务上对ShinkaEvolve进行了评估，结果表明其在样本效率和解决方案质量上均有持续提升。ShinkaEvolve仅用150个样本就找到了全新的最先进圆填充解决方案；为AIME数学推理任务设计了高性能智能体框架；发现了ALE-Bench竞赛编程解决方案的改进方向；还挖掘出新颖的混合专家负载平衡损失函数，这些函数为优化策略领域带来了新的启发。研究结果显示，ShinkaEvolve不仅样本效率极高，还具备广泛的适用性。通过开源可访问性和成本效益，这项工作推动了跨各类计算问题的开放式发现民主化，让更多人能够参与其中。

> We introduce ShinkaEvolve: a new open-source framework leveraging large language models (LLMs) to advance scientific discovery with state-of-the-art performance and unprecedented efficiency. Recent advances in scaling inference time compute of LLMs have enabled significant progress in generalized scientific discovery. These approaches rely on evolutionary agentic harnesses that leverage LLMs as mutation operators to generate candidate solutions. However, current code evolution methods suffer from critical limitations: they are sample inefficient, requiring thousands of samples to identify effective solutions, and remain closed-source, hindering broad adoption and extension. ShinkaEvolve addresses these limitations, introducing three key innovations: a parent sampling technique balancing exploration and exploitation, code novelty rejection-sampling for efficient search space exploration, and a bandit-based LLM ensemble selection strategy. We evaluate ShinkaEvolve across diverse tasks, demonstrating consistent improvements in sample efficiency and solution quality. ShinkaEvolve discovers a new state-of-the-art circle packing solution using only 150 samples, designs high-performing agentic harnesses for AIME mathematical reasoning tasks, identifies improvements to ALE-Bench competitive programming solutions, and discovers novel mixture-of-expert load balancing loss functions that illuminate the space of optimization strategies. Our results demonstrate that ShinkaEvolve achieves broad applicability with exceptional sample efficiency. By providing open-source accessibility and cost-efficiency, this work democratizes open-ended discovery across diverse computational problems.

[Arxiv](https://arxiv.org/abs/2509.19349)