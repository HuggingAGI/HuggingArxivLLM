# THINK-Bench：评测大型推理模型的思考效率与思维链质量

发布时间：2025年05月28日

`LLM理论` `模型效率` `评估工具`

> THINK-Bench: Evaluating Thinking Efficiency and Chain-of-Thought Quality of Large Reasoning Models

# 摘要

> 大推理模型（LRMs）在复杂任务中表现优异，通常超越传统大型语言模型（LLMs）。然而，过度思考这一问题严重制约了其计算效率。具体而言，模型在简单任务中生成大量冗余token，对准确结果贡献有限，导致计算资源的极大浪费。为系统研究这一现象，我们推出了Think-Bench，一个专为评估LRMs推理效率设计的基准工具。我们还提出了全新的效率指标，并对多种LRMs进行了多维度的全面评估，涵盖推理过程、结果质量及链式思维（CoT）特性。研究发现，多数LRMs在处理简单问题时会生成不必要的冗长推理链，存在过度思考现象。尽管许多LRMs具备高质量的CoT能力，但效率问题仍待解决。我们期待Think-Bench能为LRMs研究提供坚实基础，推动相关领域发展。

> Large reasoning models (LRMs) have achieved impressive performance in complex tasks, often outperforming conventional large language models (LLMs). However, the prevalent issue of overthinking severely limits their computational efficiency. Overthinking occurs when models generate excessive and redundant tokens that contribute little to accurate outcomes, especially in simple tasks, resulting in a significant waste of computational resources. To systematically investigate this issue, we introduce Think-Bench, a benchmark designed to evaluate the reasoning efficiency of LRMs. We also propose novel efficiency metrics and conduct a comprehensive evaluation of various LRMs across multiple dimensions, including the reasoning process, outcome quality, and chain-of-thought (CoT) characteristics. Our analysis reveals that most LRMs exhibit overthinking in handling easy questions, generating unnecessarily lengthy reasoning chains. While many LRMs demonstrate high CoT quality, several suffer from low efficiency. We hope that Think-Bench can serve as a robust foundation for advancing research into LRMs.

[Arxiv](https://arxiv.org/abs/2505.22113)