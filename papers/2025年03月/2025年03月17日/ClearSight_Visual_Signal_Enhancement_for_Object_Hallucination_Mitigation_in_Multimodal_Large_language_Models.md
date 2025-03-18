# ClearSight：通过视觉信号增强缓解多模态大型语言模型中的物体幻觉

发布时间：2025年03月17日

`LLM应用` `人工智能` `计算机视觉`

> ClearSight: Visual Signal Enhancement for Object Hallucination Mitigation in Multimodal Large language Models

# 摘要

> 对比解码策略被广泛用于缓解多模态大语言模型中的对象幻觉问题。通过减少对语言先验的过度依赖，这些策略确保生成内容紧密基于视觉输入，从而产生上下文准确的输出。由于对比解码无需额外训练或外部工具，因此在计算效率和通用性方面表现出色，极具吸引力。然而，这些方法存在两个主要局限：(1) 简单地抑制语言先验可能损害生成内容的连贯性和准确性；(2) 处理对比输入会增加计算负担，显著降低推理速度。针对这些挑战，我们提出了一种即插即用的技术——视觉放大融合（VAF），通过增强模型中间层对视觉信号的关注，其中模态融合主要发生。这种方法能够更有效地捕捉视觉特征，减少模型对语言模态的偏见。实验结果表明，VAF显著降低了各种多模态大语言模型中的幻觉现象，同时保持了推理速度，且生成输出的连贯性和准确性得到了保障。

> Contrastive decoding strategies are widely used to mitigate object hallucinations in multimodal large language models (MLLMs). By reducing over-reliance on language priors, these strategies ensure that generated content remains closely grounded in visual inputs, producing contextually accurate outputs. Since contrastive decoding requires no additional training or external tools, it offers both computational efficiency and versatility, making it highly attractive. However, these methods present two main limitations: (1) bluntly suppressing language priors can compromise coherence and accuracy of generated content, and (2) processing contrastive inputs adds computational load, significantly slowing inference speed. To address these challenges, we propose Visual Amplification Fusion (VAF), a plug-and-play technique that enhances attention to visual signals within the model's middle layers, where modality fusion predominantly occurs. This approach enables more effective capture of visual features, reducing the model's bias toward language modality. Experimental results demonstrate that VAF significantly reduces hallucinations across various MLLMs without affecting inference speed, while maintaining coherence and accuracy in generated outputs.

[Arxiv](https://arxiv.org/abs/2503.13107)