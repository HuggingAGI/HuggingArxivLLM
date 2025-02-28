# 多代理验证：利用多个验证器扩展测试计算能力

发布时间：2025年02月27日

`LLM应用

理由：这篇论文探讨了如何通过扩展验证器数量和使用多智能体验证（MAV）来提升大型语言模型（LLMs）在测试时的性能。它介绍了具体的方法如多维度验证器（AVs）和BoN-MAV算法，并展示了这些方法在实际应用中的有效性。因此，它属于LLM应用类别。` `模型优化` `模型增强`

> Multi-Agent Verification: Scaling Test-Time Compute with Multiple Verifiers

# 摘要

> 通过在测试时利用更多计算资源，大型语言模型（LLMs）可以在无额外训练的情况下实现性能提升。我们提出了一种新的测试时计算扩展维度——扩展验证器数量，并引入多智能体验证（MAV）这一结合多个验证器以提升性能的测试时计算范式。我们建议使用现成的LLMs，即多维度验证器（AVs），作为MAV系统中验证器的便捷选择。AVs无需额外训练且易于组合。我们进一步提出了BoN-MAV，一种结合最佳n采样与多个验证器的简单多智能体验证算法。实验表明，BoN-MAV的扩展模式优于自我一致性验证和奖励模型验证，并且展示了两种能力：弱到强泛化，即结合弱验证器可提升甚至更强大的LLMs；以及自我改进，即使用相同的基模型进行生成和验证。我们的研究证实，扩展验证器数量是提升语言模型测试时性能的一个极具潜力的新维度。

> By utilizing more computational resources at test-time, large language models (LLMs) can improve without additional training. One common strategy uses verifiers to evaluate candidate outputs. In this work, we propose a novel scaling dimension for test-time compute: scaling the number of verifiers. We introduce Multi-Agent Verification (MAV) as a test-time compute paradigm that combines multiple verifiers to improve performance. We propose using Aspect Verifiers (AVs), off-the-shelf LLMs prompted to verify different aspects of outputs, as one possible choice for the verifiers in a MAV system. AVs are a convenient building block for MAV since they can be easily combined without additional training. Moreover, we introduce BoN-MAV, a simple multi-agent verification algorithm that combines best-of-n sampling with multiple verifiers. BoN-MAV demonstrates stronger scaling patterns than self-consistency and reward model verification, and we demonstrate both weak-to-strong generalization, where combining weak verifiers improves even stronger LLMs, and self-improvement, where the same base model is used to both generate and verify outputs. Our results establish scaling the number of verifiers as a promising new dimension for improving language model performance at test-time.

[Arxiv](https://arxiv.org/abs/2502.20379)