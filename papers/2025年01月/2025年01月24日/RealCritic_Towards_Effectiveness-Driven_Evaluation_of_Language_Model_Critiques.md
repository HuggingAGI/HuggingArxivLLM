# RealCritic: 迈向语言模型评论的有效性驱动评估

发布时间：2025年01月24日

`LLM理论

理由：这篇论文主要关注的是大型语言模型（LLMs）的批评能力及其评估方法，提出了一个新的基准来评估LLMs的批评能力，并探讨了不同模型在批评场景中的表现差异。这些内容涉及到LLMs的理论研究和性能评估，因此应归类为LLM理论。` `模型评估`

> RealCritic: Towards Effectiveness-Driven Evaluation of Language Model Critiques

# 摘要

> 批评对提升大型语言模型（LLMs）的性能至关重要，它通过识别缺陷并提出改进建议，既促进了自我改进，也为他人提供了建设性反馈。然而，由于任务的开放性，评估LLMs的批评能力是一个重大挑战。我们引入了一个新的基准，旨在评估LLMs的批评能力。与现有的开环基准不同，我们的方法采用闭环方法，评估从批评中生成的修正的质量。此外，该基准还包含了自我批评、交叉批评和迭代批评等特性，这些特性对于区分高级推理模型与经典模型的能力至关重要。我们使用八个具有挑战性的推理任务来实现这一基准。我们有几个有趣的发现：首先，尽管在直接链式思维生成中表现出相当的性能，经典LLMs在所有批评场景中显著落后于基于高级推理的模型o1-mini；其次，在自我批评和迭代批评设置中，经典LLMs甚至可能相对于其基线能力表现不佳。我们希望这个基准能成为指导未来进展的宝贵资源。代码和数据可在url{https://github.com/tangzhy/RealCritic}获取。

> Critiques are important for enhancing the performance of Large Language Models (LLMs), enabling both self-improvement and constructive feedback for others by identifying flaws and suggesting improvements. However, evaluating the critique capabilities of LLMs presents a significant challenge due to the open-ended nature of the task. In this work, we introduce a new benchmark designed to assess the critique capabilities of LLMs. Unlike existing benchmarks, which typically function in an open-loop fashion, our approach employs a closed-loop methodology that evaluates the quality of corrections generated from critiques. Moreover, the benchmark incorporates features such as self-critique, cross-critique, and iterative critique, which are crucial for distinguishing the abilities of advanced reasoning models from more classical ones. We implement this benchmark using eight challenging reasoning tasks. We have several interesting findings. First, despite demonstrating comparable performance in direct chain-of-thought generation, classical LLMs significantly lag behind the advanced reasoning-based model o1-mini across all critique scenarios. Second, in self-critique and iterative critique settings, classical LLMs may even underperform relative to their baseline capabilities. We hope that this benchmark will serve as a valuable resource to guide future advancements. The code and data are available at url{https://github.com/tangzhy/RealCritic}.

[Arxiv](https://arxiv.org/abs/2501.14492)