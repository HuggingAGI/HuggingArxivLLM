# TeRA：基于向量的随机张量网络——大型语言模型高阶适应

发布时间：2025年09月03日

`LLM理论` `基础理论`

> TeRA: Vector-based Random Tensor Network for High-Rank Adaptation of Large Language Models

# 摘要

> 参数高效微调（PEFT）方法（如低秩适应LoRA）大幅减少了微调大型语言模型（LLMs）时所需的可训练参数。LoRA风格适配器的后续发展形成两个主要方向：一是通过高秩适配器提升模型表达能力，二是进一步精简参数（如基于向量的方法）。然而，这些方法存在固有权衡——要实现高秩权重更新的表达能力，往往需牺牲基于向量技术的极致参数效率。为此，我们提出基于向量的随机	extbf{张}(Te)量网络高	extbf{秩}(R)	extbf{适}(A)应（TeRA），这是一种新型PEFT方法，既能实现高秩权重更新，又保留了基于向量PEFT适配器的参数效率。其核心在于将张量化权重更新矩阵参数化为类Tucker张量网络（TN）：大型随机初始化因子被冻结并跨层共享，仅训练由对角因子矩阵条目构成的小型层特定缩放向量。这种设计有效解耦了权重更新矩阵的秩与可训练参数数量。大量实验表明，TeRA性能媲美甚至超越高秩适配器，而所需可训练参数与基于向量的方法相当。理论分析与消融研究进一步验证了该方法的有效性。

> Parameter-Efficient Fine-Tuning (PEFT) methods, such as Low-Rank Adaptation (LoRA), have significantly reduced the number of trainable parameters needed in fine-tuning large language models (LLMs). Subsequent developments of LoRA-style adapters have diverged into two main directions: (1) enhancing model expressivity with high-rank adapters, and (2) pushing for further parameter reduction, as exemplified by vector-based methods. However, these approaches present a trade-off, as achieving the expressivity of high-rank weight updates typically comes at the cost of sacrificing the extreme parameter efficiency offered by vector-based techniques. To address this issue, we propose a vector-based random underline{\textbf{Te}}nsor network for high-underline{\textbf{R}}ank underline{\textbf{A}}daptation (TeRA), a novel PEFT method that achieves high-rank weight updates while retaining the parameter efficiency of vector-based PEFT adapters. This is achieved by parameterizing the tensorized weight update matrix as a Tucker-like tensor network (TN), in which large randomly initialized factors are frozen and shared across layers, while only small layer-specific scaling vectors, formed by entries in diagonal factor matrices, are trained. This design effectively decouples the rank of the weight update matrix from the number of trainable parameters. Comprehensive experiments demonstrate that TeRA matches or even outperforms high-rank adapters, while requiring a trainable parameter count similar to vector-based methods. Theoretical analysis and ablation studies further validate the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2509.03234)