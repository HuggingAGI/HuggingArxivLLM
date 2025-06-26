# 通过引导向量理解思维语言模型中的推理机制

发布时间：2025年06月23日

`LLM理论` `人工智能`

> Understanding Reasoning in Thinking Language Models via Steering Vectors

# 摘要

> 大型语言模型（LLMs）的最新进展催生了思考型语言模型，这些模型在生成响应前会构建内部推理链。尽管这些模型在性能上有所提升，但对其推理过程的控制仍然具有挑战性。本研究提出了一种针对思考型LLMs的引导方法，通过分析和操控DeepSeek-R1-Distill模型中的特定推理行为来实现。通过对涵盖10个不同类别的500个任务进行系统性实验，我们识别出思考型模型展现的多种推理行为，包括表达不确定性、生成假设验证示例以及在推理链中回溯。我们证明，这些行为受到模型激活空间中线性方向的中介影响，并可通过引导向量进行控制。通过提取和应用这些向量，我们提供了一种调节模型推理过程特定方面的方法，例如其回溯倾向或表达不确定性的倾向。我们的方法为以可控和可解释的方式引导思考型模型的推理过程提供了实用工具。我们使用三个DeepSeek-R1-Distill模型验证了我们的引导方法，展示了在不同模型架构中的一致控制效果。

> Recent advances in large language models (LLMs) have led to the development of thinking language models that generate extensive internal reasoning chains before producing responses. While these models achieve improved performance, controlling their reasoning processes remains challenging. This work presents a steering approach for thinking LLMs by analyzing and manipulating specific reasoning behaviors in DeepSeek-R1-Distill models. Through a systematic experiment on 500 tasks across 10 diverse categories, we identify several reasoning behaviors exhibited by thinking models, including expressing uncertainty, generating examples for hypothesis validation, and backtracking in reasoning chains. We demonstrate that these behaviors are mediated by linear directions in the model's activation space and can be controlled using steering vectors. By extracting and applying these vectors, we provide a method to modulate specific aspects of the model's reasoning process, such as its tendency to backtrack or express uncertainty. Our approach offers practical tools for steering reasoning processes in thinking models in a controlled and interpretable manner. We validate our steering method using three DeepSeek-R1-Distill models, demonstrating consistent control across different model architectures.

[Arxiv](https://arxiv.org/abs/2506.18167)