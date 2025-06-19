# 跨领域视角再探强化学习在LLM推理中的应用

发布时间：2025年06月17日

`LLM应用` `跨领域推理`

> Revisiting Reinforcement Learning for LLM Reasoning from A Cross-Domain Perspective

# 摘要

> 强化学习 (RL) 为提升大型语言模型 (LLM) 的推理能力提供了有前景的解决方案。然而，现有的研究大多局限于数学和代码领域，这限制了我们对 RL 在更广泛推理任务中应用的理解。一个关键挑战在于缺乏可靠且可扩展的 RL 奖励信号，尤其是在多样化的推理领域中。

我们推出了 Guru，一个包含 92,000 个可验证示例的精选 RL 推理语料库，涵盖了数学、代码、科学、逻辑、模拟和表格六个推理领域。每个领域都通过特定的奖励设计、去重和筛选构建，确保了 RL 训练的可靠性和有效性。

基于 Guru，我们系统地重新审视了 LLM 推理中 RL 的现有发现，发现不同领域间存在显著差异。例如，尽管先前研究认为 RL 主要激发预训练模型中的已有知识，但我们的研究揭示了一个更细致的模式：在预训练过程中频繁出现的领域（如数学、代码和科学）能够轻松受益于跨领域 RL 训练，而预训练过程中接触有限的领域（如逻辑、模拟和表格）则需要在领域内进行训练才能实现有意义的性能提升。这表明 RL 可能有助于真正的技能获取。

最后，我们推出了 Guru-7B 和 Guru-32B 两个模型，它们在使用公开数据进行 RL 训练的开源模型中实现了最先进的性能，在六个推理领域的 17 项任务评估中分别超过了最佳基线模型 7.9% 和 6.7%。我们还展示了我们的模型如何有效提升其基础模型的 Pass@k 性能，尤其是在那些在预训练数据中不太可能出现的复杂任务上。

我们发布了数据、模型、训练和评估代码，以促进通用推理能力的提升，详情请访问：https://github.com/LLM360/Reasoning360

> Reinforcement learning (RL) has emerged as a promising approach to improve large language model (LLM) reasoning, yet most open efforts focus narrowly on math and code, limiting our understanding of its broader applicability to general reasoning. A key challenge lies in the lack of reliable, scalable RL reward signals across diverse reasoning domains. We introduce Guru, a curated RL reasoning corpus of 92K verifiable examples spanning six reasoning domains--Math, Code, Science, Logic, Simulation, and Tabular--each built through domain-specific reward design, deduplication, and filtering to ensure reliability and effectiveness for RL training. Based on Guru, we systematically revisit established findings in RL for LLM reasoning and observe significant variation across domains. For example, while prior work suggests that RL primarily elicits existing knowledge from pretrained models, our results reveal a more nuanced pattern: domains frequently seen during pretraining (Math, Code, Science) easily benefit from cross-domain RL training, while domains with limited pretraining exposure (Logic, Simulation, and Tabular) require in-domain training to achieve meaningful performance gains, suggesting that RL is likely to facilitate genuine skill acquisition. Finally, we present Guru-7B and Guru-32B, two models that achieve state-of-the-art performance among open models RL-trained with publicly available data, outperforming best baselines by 7.9% and 6.7% on our 17-task evaluation suite across six reasoning domains. We also show that our models effectively improve the Pass@k performance of their base models, particularly on complex tasks less likely to appear in pretraining data. We release data, models, training and evaluation code to facilitate general-purpose reasoning at: https://github.com/LLM360/Reasoning360

[Arxiv](https://arxiv.org/abs/2506.14965)