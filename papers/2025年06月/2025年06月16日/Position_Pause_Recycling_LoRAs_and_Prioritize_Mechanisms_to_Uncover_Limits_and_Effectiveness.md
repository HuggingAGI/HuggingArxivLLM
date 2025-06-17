# # 职位
暂停循环利用低秩适应（LoRAs），优先研究机制以揭示其极限与有效性。

发布时间：2025年06月16日

`LLM理论` `模型优化`

> Position: Pause Recycling LoRAs and Prioritize Mechanisms to Uncover Limits and Effectiveness

# 摘要

> 在数据受限（由监管或领域特定约束引起）的情况下，合并或路由低秩适配器（LoRAs）已成为增强大型语言模型的热门方案。本文主张，研究界应将重心从开发新算法转向理解LoRAs复用的有效场景。通过理论分析和合成的两跳推理及数学问题任务，我们探讨了LoRAs复用是否实现真正的组合泛化，还是仅体现浅层模式匹配。评估参数平均和动态适配器选择两种方法后发现，LoRAs复用常无法在不相交微调数据集间有效整合知识，尤其当预训练中相关知识代表性不足时。结合对LoRA有限表达能力的理论分析，我们的实证结果揭示了其在未见任务中复用的先决条件和限制，并对其作为数据无关方法的可行性提出质疑。我们建议暂停探索回收LoRAs的新方法，强调制定严格机制以指导未来基于适配器的模型合并研究和实践系统设计的必要性。


> Merging or routing low-rank adapters (LoRAs) has emerged as a popular solution for enhancing large language models, particularly when data access is restricted by regulatory or domain-specific constraints. This position paper argues that the research community should shift its focus from developing new merging or routing algorithms to understanding the conditions under which reusing LoRAs is truly effective. Through theoretical analysis and synthetic two-hop reasoning and math word-problem tasks, we examine whether reusing LoRAs enables genuine compositional generalization or merely reflects shallow pattern matching. Evaluating two data-agnostic methods--parameter averaging and dynamic adapter selection--we found that reusing LoRAs often fails to logically integrate knowledge across disjoint fine-tuning datasets, especially when such knowledge is underrepresented during pretraining. Our empirical results, supported by theoretical insights into LoRA's limited expressiveness, highlight the preconditions and constraints of reusing them for unseen tasks and cast doubt on its feasibility as a truly data-free approach. We advocate for pausing the pursuit of novel methods for recycling LoRAs and emphasize the need for rigorous mechanisms to guide future academic research in adapter-based model merging and practical system designs for practitioners.

[Arxiv](https://arxiv.org/abs/2506.13479)