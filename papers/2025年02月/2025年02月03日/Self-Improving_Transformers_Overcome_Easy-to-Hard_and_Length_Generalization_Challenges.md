# 自我改进的Transformer成功应对了从易到难和长度泛化的双重挑战

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLM）在应对长度泛化和解决超出训练分布的复杂问题时的局限性，并提出了一种自我改进的方法。该方法通过迭代生成并学习自己的解决方案，逐步攻克更难的挑战，同时保持标准的Transformer架构。论文还展示了在算术、字符串操作和迷宫求解等任务中的实验结果，表明自我改进方法能够显著提升模型的分布外性能。这些内容主要涉及LLM的理论改进和性能提升，因此归类为LLM理论。` `人工智能` `机器学习`

> Self-Improving Transformers Overcome Easy-to-Hard and Length Generalization Challenges

# 摘要

> 大型语言模型在应对长度泛化和解决超出训练分布的复杂问题时常常力不从心。我们提出了一种自我改进方法，模型通过迭代生成并学习自己的解决方案，逐步攻克更难的挑战，同时保持标准的Transformer架构。在算术、字符串操作和迷宫求解等任务中，自我改进让模型能够解决远超初始训练分布的问题——例如，从10位数加法轻松泛化到100位数加法，且未见性能饱和。我们发现，在某些情况下，筛选正确的自我生成示例能带来分布外性能的指数级提升。此外，从预训练模型出发，显著加速了多个任务的自我改进进程。我们的研究展示了如何通过受控的从弱到强课程，在不改变位置嵌入或模型架构的情况下，系统教会模型逻辑外推。

> Large language models often struggle with length generalization and solving complex problem instances beyond their training distribution. We present a self-improvement approach where models iteratively generate and learn from their own solutions, progressively tackling harder problems while maintaining a standard transformer architecture. Across diverse tasks including arithmetic, string manipulation, and maze solving, self-improving enables models to solve problems far beyond their initial training distribution-for instance, generalizing from 10-digit to 100-digit addition without apparent saturation. We observe that in some cases filtering for correct self-generated examples leads to exponential improvements in out-of-distribution performance across training rounds. Additionally, starting from pretrained models significantly accelerates this self-improvement process for several tasks. Our results demonstrate how controlled weak-to-strong curricula can systematically teach a model logical extrapolation without any changes to the positional embeddings, or the model architecture.

[Arxiv](https://arxiv.org/abs/2502.01612)