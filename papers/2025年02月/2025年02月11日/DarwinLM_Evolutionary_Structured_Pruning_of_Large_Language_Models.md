# 达尔文LM：大语言模型的进化式结构化剪枝

发布时间：2025年02月11日

`LLM应用` `模型优化`

> DarwinLM: Evolutionary Structured Pruning of Large Language Models

# 摘要

> 大型语言模型 (LLMs) 在自然语言处理任务中表现优异，但其高昂的计算成本限制了实际应用，尤其在实时场景中。结构化剪枝通过压缩模型并直接提升端到端性能，提供了一种高效解决方案，且与硬件环境无关。然而，模型各组件对剪枝的敏感度不同，因此需要\emph{非均匀}压缩策略。剪枝方法不仅要找到高效的子结构，还需兼顾压缩后的训练效果。为此，我们提出\sysname，一种\emph{训练感知}的结构化剪枝方法。该方法基于进化搜索，在每一代生成多个子代模型并通过变异操作，筛选出最优模型。为评估压缩后训练效果，我们在子代种群中引入轻量级多步骤训练，逐步增加标记数量，并在每阶段淘汰表现不佳的模型。我们在Llama-2-7B、Llama-3.1-8B和Qwen-2.5-14B-Instruct上的实验表明，\sysname实现了结构化剪枝的最先进性能。例如，\sysname超越了ShearedLlama，同时在压缩后训练中所需的训练数据量减少了【数学公式】倍。

> Large Language Models (LLMs) have achieved significant success across various NLP tasks. However, their massive computational costs limit their widespread use, particularly in real-time applications. Structured pruning offers an effective solution by compressing models and directly providing end-to-end speed improvements, regardless of the hardware environment. Meanwhile, different components of the model exhibit varying sensitivities towards pruning, calling for \emph{non-uniform} model compression. However, a pruning method should not only identify a capable substructure, but also account for post-compression training. To this end, we propose \sysname, a method for \emph{training-aware} structured pruning. \sysname builds upon an evolutionary search process, generating multiple offspring models in each generation through mutation, and selecting the fittest for survival. To assess the effect of post-training, we incorporate a lightweight, multistep training process within the offspring population, progressively increasing the number of tokens and eliminating poorly performing models in each selection stage. We validate our method through extensive experiments on Llama-2-7B, Llama-3.1-8B and Qwen-2.5-14B-Instruct, achieving state-of-the-art performance for structured pruning. For instance, \sysname surpasses ShearedLlama while requiring $5\times$ less training data during post-compression training.

[Arxiv](https://arxiv.org/abs/2502.07780)