# # 链式思维压缩中的激活引导

发布时间：2025年07月07日

`LLM应用

摘要讨论了大型语言模型（LLMs）在推理过程中的优化，提出了一种名为激活引导压缩（ASC）的方法，用于缩短推理轨迹，提升效率。该方法属于应用层面的改进，因此归类为LLM应用。` `人工智能`

> Activation Steering for Chain-of-Thought Compression

# 摘要

> 大型语言模型 (LLMs) 在包含中间步骤（即“思维链” CoTs）时，在复杂推理方面表现出色。然而，这些推理过程往往过于冗长，即使是简单的问题也是如此，导致上下文浪费、延迟增加和能耗上升。我们发现，冗长的以英语为主的 CoTs 和简洁的以数学为中心的 CoTs 在模型的残差流激活空间中占据不同的区域。通过提取和注入一个“转向向量”在这些模式之间切换，我们可以可靠地将生成引导至更简洁的推理方式，从而在不重新训练的情况下有效压缩 CoTs。我们将这种方法形式化为激活引导压缩 (ASC)，这是一种通过直接修改隐藏表示来缩短推理轨迹的推理时技术。此外，我们从一个闭式 KL 散度有界约束出发，对 ASC 对输出分布的影响进行了理论分析，以调节转向强度。仅使用 100 个冗长和简洁的配对示例，ASC 在 MATH500 和 GSM8K 数据集上实现了高达 67.43% 的 CoT 长度减少，同时在 7B、8B 和 32B 参数模型上保持准确性。作为一种无需训练的方法，ASC 引入的运行时开销可以忽略不计，并且在 MATH500 上，对于一个 8B 模型，端到端推理的总时间平均加快了 2.73 倍。这使得 ASC 成为一种实用且高效的工具，适用于需要低延迟或成本敏感的推理能力 LLM 部署场景。代码可在以下位置获取：https://github.com/ArminAzizi98/ASC

> Large language models (LLMs) excel at complex reasoning when they include intermediate steps, known as "chains of thought" (CoTs). However, these rationales are often overly verbose, even for simple problems, leading to wasted context, increased latency, and higher energy consumption. We observe that verbose, English-heavy CoTs and concise, math-centric CoTs occupy distinct regions in the model's residual-stream activation space. By extracting and injecting a "steering vector" to transition between these modes, we can reliably shift generation toward more concise reasoning, effectively compressing CoTs without retraining. We formalize this approach as Activation-Steered Compression (ASC), an inference-time technique that shortens reasoning traces by directly modifying hidden representations. In addition, we provide a theoretical analysis of the impact of ASC on the output distribution, derived from a closed-form KL-divergence-bounded constraint to regulate steering strength. Using only 100 paired verbose and concise examples, ASC achieves up to 67.43% reduction in CoT length on MATH500 and GSM8K datasets, while maintaining accuracy across 7B, 8B, and 32B parameter models. As a training-free method, ASC introduces negligible runtime overhead and, on MATH500, delivers an average 2.73x speedup in end-to-end reasoning wall-clock time on an 8B model. This makes ASC a practical and efficient tool for streamlining the deployment of reasoning-capable LLMs in latency- or cost-sensitive settings. The code is available at: https://github.com/ArminAzizi98/ASC

[Arxiv](https://arxiv.org/abs/2507.04742)