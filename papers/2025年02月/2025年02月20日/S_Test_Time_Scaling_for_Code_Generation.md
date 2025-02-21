# S*: 测试时间缩放的代码生成方法

发布时间：2025年02月20日

`LLM应用

理由：这篇论文主要探讨了如何通过提出一个新的框架S*来提升大型语言模型在代码生成领域的推理时间和性能。它具体应用在代码生成这一领域，并且展示了该框架在多个模型上的实际效果，因此属于LLM应用。` `代码生成` `软件开发`

> S*: Test Time Scaling for Code Generation

# 摘要

> 提升大型语言模型（LLMs）的推理时间计算在各领域都展现出潜力，尽管数学领域已有大量研究，但代码生成领域仍鲜有探索。本文中，我们提出了S*——首个混合推理时间缩放框架，该框架显著提升了生成代码的覆盖率和选择准确性。S* 在现有并行缩放范式的基础上，引入了串行缩放以突破性能边界。它还采用了一种新型选择机制，自适应生成区分输入用于成对比较，并结合执行基础信息，稳健地识别正确解决方案。我们在12个大型语言模型和大型推理模型上进行了评估，结果显示：(1) S* 在不同模型家族和规模上均能显著提升性能，使3B模型超越GPT-4o-mini；(2) S* 使非推理模型超越推理模型——配备S*的GPT-4o-mini在LiveCodeBench上的表现优于o1-preview 3.7%；(3) S* 进一步提升了最先进推理模型的性能——配备S*的DeepSeek-R1-Distill-Qwen-32B在LiveCodeBench上达到85.7%，接近o1 (high)的88.5%。代码将在https://github.com/NovaSky-AI/SkyThought上提供。

> Increasing test-time compute for LLMs shows promise across domains but remains underexplored in code generation, despite extensive study in math. In this paper, we propose S*, the first hybrid test-time scaling framework that substantially improves the coverage and selection accuracy of generated code. S* extends the existing parallel scaling paradigm with sequential scaling to push performance boundaries. It further leverages a novel selection mechanism that adaptively generates distinguishing inputs for pairwise comparison, combined with execution-grounded information to robustly identify correct solutions. We evaluate across 12 Large Language Models and Large Reasoning Model and show: (1) S* consistently improves performance across model families and sizes, enabling a 3B model to outperform GPT-4o-mini; (2) S* enables non-reasoning models to surpass reasoning models - GPT-4o-mini with S* outperforms o1-preview by 3.7% on LiveCodeBench; (3) S* further boosts state-of-the-art reasoning models - DeepSeek-R1-Distill-Qwen-32B with S* achieves 85.7% on LiveCodeBench, approaching o1 (high) at 88.5%. Code will be available under https://github.com/NovaSky-AI/SkyThought.

[Arxiv](https://arxiv.org/abs/2502.14382)