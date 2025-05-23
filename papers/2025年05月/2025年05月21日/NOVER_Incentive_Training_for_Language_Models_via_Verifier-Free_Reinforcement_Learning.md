# NOVER: 基于无验证器强化学习的语言模型激励训练方法

发布时间：2025年05月21日

`LLM理论` `人工智能`

> NOVER: Incentive Training for Language Models via Verifier-Free Reinforcement Learning

# 摘要

> 近期，以DeepSeek R1-Zero为代表的进展凸显了激励训练的独特优势。这种强化学习方法通过仅关注语言模型输出的最终答案部分来计算奖励，从而有效推动了中间推理步骤的生成。然而，这类方法的核心依赖于外部验证器，这在数学和编码等领域造成了应用限制，因为这些领域中验证器的获取相对容易。尽管奖励模型可以承担验证器的角色，但它们的训练需要高质量的标注数据，且成本高昂。为此，我们提出了NOVER（无验证器强化学习），这是一个仅需标准监督微调数据的通用强化学习框架，无需依赖外部验证器。NOVER使激励训练能够广泛应用于各类文本到文本任务，并在从大型推理模型（如DeepSeek R1 671B）蒸馏出的同规模模型上实现了7.7%的性能提升。此外，NOVER的灵活性为大型语言模型的优化开辟了新的可能性，例如逆向激励训练。

> Recent advances such as DeepSeek R1-Zero highlight the effectiveness of incentive training, a reinforcement learning paradigm that computes rewards solely based on the final answer part of a language model's output, thereby encouraging the generation of intermediate reasoning steps. However, these methods fundamentally rely on external verifiers, which limits their applicability to domains like mathematics and coding where such verifiers are readily available. Although reward models can serve as verifiers, they require high-quality annotated data and are costly to train. In this work, we propose NOVER, NO-VERifier Reinforcement Learning, a general reinforcement learning framework that requires only standard supervised fine-tuning data with no need for an external verifier. NOVER enables incentive training across a wide range of text-to-text tasks and outperforms the model of the same size distilled from large reasoning models such as DeepSeek R1 671B by 7.7 percent. Moreover, the flexibility of NOVER enables new possibilities for optimizing large language models, such as inverse incentive training.

[Arxiv](https://arxiv.org/abs/2505.16022)