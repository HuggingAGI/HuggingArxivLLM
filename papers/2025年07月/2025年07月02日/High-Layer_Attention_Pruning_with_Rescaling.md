# 基于重新缩放的高层注意力剪枝方法

发布时间：2025年07月02日

`LLM理论` `模型压缩`

> High-Layer Attention Pruning with Rescaling

# 摘要

> 剪枝是压缩大型语言模型（LLMs）的高效方法，能显著降低推理延迟。但传统无训练的结构化剪枝方法常采用不加区分的启发式指标，直接移除各层的部分注意力头，未考虑其在网络中的位置。本研究提出一种全新的剪枝算法，专注于战略性地剪除模型高层中的注意力头。鉴于剪除注意力头会影响令牌表示的幅度，我们引入自适应重缩放参数，用于剪枝后校准表示规模，以抵消此影响。我们在包括 LLaMA3.1-8B、Mistral-7B-v0.3、Qwen2-7B 和 Gemma2-9B 在内的多种 LLM 上进行了全面实验，评估涵盖 27 个数据集的生成和判别任务。结果表明，我们的方法显著优于现有结构化剪枝方法，尤其在生成任务中表现远超现有基线。

> Pruning is a highly effective approach for compressing large language models (LLMs), significantly reducing inference latency. However, conventional training-free structured pruning methods often employ a heuristic metric that indiscriminately removes some attention heads across all pruning layers, without considering their positions within the network architecture. In this work, we propose a novel pruning algorithm that strategically prunes attention heads in the model's higher layers. Since the removal of attention heads can alter the magnitude of token representations, we introduce an adaptive rescaling parameter that calibrates the representation scale post-pruning to counteract this effect. We conduct comprehensive experiments on a wide range of LLMs, including LLaMA3.1-8B, Mistral-7B-v0.3, Qwen2-7B, and Gemma2-9B. Our evaluation includes both generation and discriminative tasks across 27 datasets. The results consistently demonstrate that our method outperforms existing structured pruning methods. This improvement is particularly notable in generation tasks, where our approach significantly outperforms existing baselines.

[Arxiv](https://arxiv.org/abs/2507.01900)