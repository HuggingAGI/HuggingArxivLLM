# 为何LLMs的有效上下文长度不尽如人意？

发布时间：2024年10月24日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在上下文窗口扩展方面的理论问题，特别是位置嵌入的改进方法（STRING）。论文提出了一个新的位置嵌入机制，并通过实验验证了其有效性。这些内容属于对LLM内部机制的理论研究和改进，因此应归类为LLM理论。` `人工智能`

> Why Does the Effective Context Length of LLMs Fall Short?

# 摘要

> 分布式训练和高效注意力机制的突破大幅扩展了大型语言模型（LLMs）的上下文窗口。然而，近期研究发现，开源LLMs的有效上下文长度往往不足，通常仅为训练长度的一半。我们将其归因于LLMs在预训练和后训练阶段形成的相对位置频率分布的左偏，这限制了其远距离信息收集能力。为此，我们提出了ShifTed Rotray位置嵌入（STRING）。STRING在推理时通过偏移训练良好的位置覆盖无效位置，从而在现有训练长度内提升性能。实验显示，无需额外训练，STRING显著提升了Llama3.1 70B和Qwen2 72B等最新大规模模型的性能，在RULER和InfiniteBench等长上下文基准上提升了超过10分，创下开源LLMs的新纪录。与商业模型相比，使用\method的Llama 3.1 70B甚至超越了GPT-4-128K，并明显优于Claude 2和Kimi-chat。

> Advancements in distributed training and efficient attention mechanisms have significantly expanded the context window sizes of large language models (LLMs). However, recent work reveals that the effective context lengths of open-source LLMs often fall short, typically not exceeding half of their training lengths. In this work, we attribute this limitation to the left-skewed frequency distribution of relative positions formed in LLMs pretraining and post-training stages, which impedes their ability to effectively gather distant information. To address this challenge, we introduce ShifTed Rotray position embeddING (STRING). STRING shifts well-trained positions to overwrite the original ineffective positions during inference, enhancing performance within their existing training lengths. Experimental results show that without additional training, STRING dramatically improves the performance of the latest large-scale models, such as Llama3.1 70B and Qwen2 72B, by over 10 points on popular long-context benchmarks RULER and InfiniteBench, establishing new state-of-the-art results for open-source LLMs. Compared to commercial models, Llama 3.1 70B with \method even achieves better performance than GPT-4-128K and clearly surpasses Claude 2 and Kimi-chat.

[Arxiv](https://arxiv.org/abs/2410.18745)