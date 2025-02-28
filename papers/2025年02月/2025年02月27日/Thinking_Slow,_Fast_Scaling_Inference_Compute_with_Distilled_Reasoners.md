# # 慢思与快想：蒸馏推理器助力推理计算的扩展

发布时间：2025年02月27日

`LLM理论`

> Thinking Slow, Fast: Scaling Inference Compute with Distilled Reasoners

# 摘要

> 近期研究表明，通过在测试阶段扩展计算资源，大型语言模型（LLMs）的性能可以得到显著提升。一种常见的策略是生成多个思维链（Chain-of-Thought, CoT）轨迹，并通过各种选择机制聚合它们的输出。这引发了一个根本性问题：在固定计算预算下，复杂度较低的模型能否凭借其优越的生成吞吐量，超越同规模的Transformer模型的表现？为了解答这一问题并克服缺乏强次二次推理器的现状，我们从预训练的Transformer模型中蒸馏出纯Mamba和混合Mamba模型。仅在80亿个令牌上进行训练，我们的蒸馏模型在数学推理数据集上展现出强劲的性能和扩展能力，同时在处理大批量和长序列时推理速度远超同类模型。尽管蒸馏导致零样本性能有所下降，但在固定时间预算下，纯Mamba和混合Mamba模型仍能超越其Transformer教师模型的覆盖范围和准确率，为推理计算的扩展开辟了全新方向。


> Recent advancements have demonstrated that the performance of large language models (LLMs) can be significantly enhanced by scaling computational resources at test time. A common strategy involves generating multiple Chain-of-Thought (CoT) trajectories and aggregating their outputs through various selection mechanisms. This raises a fundamental question: can models with lower complexity leverage their superior generation throughput to outperform similarly sized Transformers for a fixed computational budget? To address this question and overcome the lack of strong subquadratic reasoners, we distill pure and hybrid Mamba models from pretrained Transformers. Trained on only 8 billion tokens, our distilled models show strong performance and scaling on mathematical reasoning datasets while being much faster at inference for large batches and long sequences. Despite the zero-shot performance hit due to distillation, both pure and hybrid Mamba models can scale their coverage and accuracy performance past their Transformer teacher models under fixed time budgets, opening a new direction for scaling inference compute.

[Arxiv](https://arxiv.org/abs/2502.20339)