# Virgo: 复现 o1 类 MLLM 的初步探索

发布时间：2025年01月03日

`LLM应用

理由：这篇论文主要讨论了如何通过微调多模态大型语言模型（MLLMs）来构建多模态慢思考系统，并展示了文本推理数据在激发MLLMs慢思考能力方面的有效性。这属于将大型语言模型应用于特定任务（即多模态推理）的研究，因此归类为“LLM应用”。` `人工智能` `多模态学习`

> Virgo: A Preliminary Exploration on Reproducing o1-like MLLM

# 摘要

> 最近，基于大型语言模型（LLMs）的慢思考推理系统因其在推理过程中扩展思考时间的能力而备受瞩目。同时，将这一能力应用于多模态大型语言模型（MLLMs）的兴趣也日益浓厚。由于MLLMs需要处理跨模态的复杂数据语义，实现多模态慢思考系统显然更具挑战性。
为此，本文提出了一种简洁的方法：通过对一个强大的MLLM进行少量文本长形式思考数据的微调，成功构建了多模态慢思考系统Virgo（视觉推理与长思考）。我们发现，这些以自然语言表达的长形式推理过程能够有效迁移到MLLMs中。有趣的是，文本推理数据在激发MLLMs的慢思考能力方面甚至优于视觉推理数据。尽管研究尚处于初期，但结果表明，慢思考能力与语言模型组件密切相关，且这种能力可以跨模态或领域迁移。这一发现为开发更强大的慢思考推理系统提供了指导。相关资源已发布在https://github.com/RUCAIBox/Virgo。

> Recently, slow-thinking reasoning systems, built upon large language models (LLMs), have garnered widespread attention by scaling the thinking time during inference. There is also growing interest in adapting this capability to multimodal large language models (MLLMs). Given that MLLMs handle more complex data semantics across different modalities, it is intuitively more challenging to implement multimodal slow-thinking systems.
  To address this issue, in this paper, we explore a straightforward approach by fine-tuning a capable MLLM with a small amount of textual long-form thought data, resulting in a multimodal slow-thinking system, Virgo (Visual reasoning with long thought). We find that these long-form reasoning processes, expressed in natural language, can be effectively transferred to MLLMs. Moreover, it seems that such textual reasoning data can be even more effective than visual reasoning data in eliciting the slow-thinking capacities of MLLMs. While this work is preliminary, it demonstrates that slow-thinking capacities are fundamentally associated with the language model component, which can be transferred across modalities or domains. This finding can be leveraged to guide the development of more powerful slow-thinking reasoning systems. We release our resources at https://github.com/RUCAIBox/Virgo.

[Arxiv](https://arxiv.org/abs/2501.01904)