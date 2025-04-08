# LEO-MINI：一个高效多模态大型语言模型，采用条件标记缩减与多模态专家混合

发布时间：2025年04月06日

`LLM应用` `计算机视觉` `人工智能`

> LEO-MINI: An Efficient Multimodal Large Language Model using Conditional Token Reduction and Mixture of Multi-Modal Experts

# 摘要

> 多模态大语言模型（MLLMs）中视觉标记的冗余性显著降低了计算效率。近期的采样器和摘要器等方法虽然减少了视觉标记数量，但牺牲了视觉推理能力。我们提出了一种新型MLLM——LEO-MINI，它在大幅减少视觉标记的同时提升了视觉推理能力。在效率方面，LEO-MINI采用了CoTR模块，通过视觉标记、文本标记和紧凑可学习查询的相似性，将大量视觉标记整合到更小的集合中。在效果方面，LEO-MINI通过MMoE模块在计算开销最小的情况下提升了模型能力。MMoE采用了一组LoRA专家和新路由机制，根据输入文本和视觉标记进行切换，而不是仅使用输入隐藏状态。MMoE还包含一个通用LoRA专家，用于学习LLM推理的通用知识。为了提取更丰富的视觉特征，MMoE采用了在多样化领域数据上训练的视觉专家。我们在各种基准视觉-语言任务上将LEO-MINI与现有高效MLLMs进行了对比评估，展示了其改进的效率和性能。

> Redundancy of visual tokens in multi-modal large language models (MLLMs) significantly reduces their computational efficiency. Recent approaches, such as resamplers and summarizers, have sought to reduce the number of visual tokens, but at the cost of visual reasoning ability. To address this, we propose LEO-MINI, a novel MLLM that significantly reduces the number of visual tokens and simultaneously boosts visual reasoning capabilities. For efficiency, LEO-MINI incorporates CoTR, a novel token reduction module to consolidate a large number of visual tokens into a smaller set of tokens, using the similarity between visual tokens, text tokens, and a compact learnable query. For effectiveness, to scale up the model's ability with minimal computational overhead, LEO-MINI employs MMoE, a novel mixture of multi-modal experts module. MMOE employs a set of LoRA experts with a novel router to switch between them based on the input text and visual tokens instead of only using the input hidden state. MMoE also includes a general LoRA expert that is always activated to learn general knowledge for LLM reasoning. For extracting richer visual features, MMOE employs a set of vision experts trained on diverse domain-specific data. To demonstrate LEO-MINI's improved efficiency and performance, we evaluate it against existing efficient MLLMs on various benchmark vision-language tasks.

[Arxiv](https://arxiv.org/abs/2504.04653)