# 通过LLM代理实现零样本视觉编码器的嫁接

发布时间：2025年05月28日

`LLM应用

LLM应用`

> Zero-Shot Vision Encoder Grafting via LLM Surrogates

# 摘要

> 视觉语言模型 (VLMs) 通常将适中规模的视觉编码器与大型语言模型 (LLM)（如 Llama-70B）配对，这使得解码器成为训练过程中的主要计算负担。为了降低成本，我们提出了一种有前景的策略：先用小型语言模型训练视觉编码器，再将其迁移到大型模型中。我们通过直接继承大型目标 LLM 的浅层，构建了小型“代理模型”，这些代理模型与大型目标 LLM 共享相同的嵌入空间和表示语言。在代理模型上训练的视觉编码器可以被直接迁移到大型模型中，这一过程我们称之为零样本嫁接。当直接插入到完整的大型目标 LLM 中时，嫁接后的组合性能优于编码器-代理模型组合，并且在某些基准测试中，甚至可以与使用目标 LLM 的完整解码器训练相媲美。此外，我们的代理模型训练方法在使用 Llama-70B 作为解码器时，将整体 VLM 训练成本降低了约 45%。

> Vision language models (VLMs) typically pair a modestly sized vision encoder with a large language model (LLM), e.g., Llama-70B, making the decoder the primary computational burden during training. To reduce costs, a potential promising strategy is to first train the vision encoder using a small language model before transferring it to the large one. We construct small "surrogate models" that share the same embedding space and representation language as the large target LLM by directly inheriting its shallow layers. Vision encoders trained on the surrogate can then be directly transferred to the larger model, a process we call zero-shot grafting -- when plugged directly into the full-size target LLM, the grafted pair surpasses the encoder-surrogate pair and, on some benchmarks, even performs on par with full decoder training with the target LLM. Furthermore, our surrogate training approach reduces overall VLM training costs by ~45% when using Llama-70B as the decoder.

[Arxiv](https://arxiv.org/abs/2505.22664)