# 案例推理提升大型语言模型在药物相互作用预测中的能力

发布时间：2025年05月28日

`LLM应用` `知识图谱`

> Case-Based Reasoning Enhances the Predictive Power of LLMs in Drug-Drug Interaction

# 摘要

> 药物相互作用（DDI）预测对治疗安全至关重要。尽管大型语言模型（LLMs）在药物相关任务中展现出潜力，但其在药物相互作用预测方面的效果仍具挑战性。受临床实践中基于案例推理（CBR）的成熟方法启发，我们提出了一种名为CBR-DDI的新颖框架，该框架通过从历史案例中提炼药理学原则，提升LLM在药物相互作用任务中的推理能力。CBR-DDI利用大型语言模型提取药理学见解，并借助图神经网络（GNNs）建模药物关联，构建知识库。通过混合检索机制和双层知识增强提示，LLMs能够有效检索并重用相关案例。此外，我们还引入了代表性的抽样策略，用于动态优化案例。大量实验表明，CBR-DDI实现了最先进的性能，与流行的LLMs和CBR基线相比，准确率显著提高了28.7%，同时保持了高度的可解释性和灵活性。

> Drug-drug interaction (DDI) prediction is critical for treatment safety. While large language models (LLMs) show promise in pharmaceutical tasks, their effectiveness in DDI prediction remains challenging. Inspired by the well-established clinical practice where physicians routinely reference similar historical cases to guide their decisions through case-based reasoning (CBR), we propose CBR-DDI, a novel framework that distills pharmacological principles from historical cases to improve LLM reasoning for DDI tasks. CBR-DDI constructs a knowledge repository by leveraging LLMs to extract pharmacological insights and graph neural networks (GNNs) to model drug associations. A hybrid retrieval mechanism and dual-layer knowledge-enhanced prompting allow LLMs to effectively retrieve and reuse relevant cases. We further introduce a representative sampling strategy for dynamic case refinement. Extensive experiments demonstrate that CBR-DDI achieves state-of-the-art performance, with a significant 28.7% accuracy improvement over both popular LLMs and CBR baseline, while maintaining high interpretability and flexibility.

[Arxiv](https://arxiv.org/abs/2505.23034)