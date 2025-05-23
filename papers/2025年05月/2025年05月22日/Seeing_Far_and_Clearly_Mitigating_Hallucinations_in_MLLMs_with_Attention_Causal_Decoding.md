# 看得远且清晰：通过注意力因果解码消除多语言大语言模型中的幻觉

发布时间：2025年05月22日

`LLM应用` `视觉问答` `计算机视觉`

> Seeing Far and Clearly: Mitigating Hallucinations in MLLMs with Attention Causal Decoding

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展显著提升了视觉问答的表现，但幻觉问题仍是其痛点。我们将其分为初始幻觉和滚雪球式幻觉两大类。通过因果推理启发，我们提出利用因果掩码优化多模态标记间的交互，以增强上下文推理。为此，我们开发了FarSight策略，通过优化因果掩码减少异常标记的干扰。我们设计了注意力寄存器结构和渐消掩码率的位置编码方法，使模型更关注有效上下文。实验表明，FarSight在图像和视频任务上显著降低了幻觉，证明了其有效性。

> Recent advancements in multimodal large language models (MLLMs) have significantly improved performance in visual question answering. However, they often suffer from hallucinations. In this work, hallucinations are categorized into two main types: initial hallucinations and snowball hallucinations. We argue that adequate contextual information can be extracted directly from the token interaction process. Inspired by causal inference in the decoding strategy, we propose to leverage causal masks to establish information propagation between multimodal tokens. The hypothesis is that insufficient interaction between those tokens may lead the model to rely on outlier tokens, overlooking dense and rich contextual cues. Therefore, we propose to intervene in the propagation process by tackling outlier tokens to enhance in-context inference. With this goal, we present FarSight, a versatile plug-and-play decoding strategy to reduce attention interference from outlier tokens merely by optimizing the causal mask. The heart of our method is effective token propagation. We design an attention register structure within the upper triangular matrix of the causal mask, dynamically allocating attention to capture attention diverted to outlier tokens. Moreover, a positional awareness encoding method with a diminishing masking rate is proposed, allowing the model to attend to further preceding tokens, especially for video sequence tasks. With extensive experiments, FarSight demonstrates significant hallucination-mitigating performance across different MLLMs on both image and video benchmarks, proving its effectiveness.

[Arxiv](https://arxiv.org/abs/2505.16652)