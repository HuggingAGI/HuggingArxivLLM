# 简单性原则的可扩展性：基于单一Transformer模型的视觉语言学习实证分析

发布时间：2025年04月14日

`LLM应用

理由：这篇论文主要讨论了SAIL模型的设计和应用，特别是其在多模态处理和视觉任务中的应用。虽然涉及模型架构和机制，但其核心在于模型的应用效果和性能评估，因此属于LLM应用类别。` `多模态模型` `计算机视觉`

> The Scalability of Simplicity: Empirical Analysis of Vision-Language Learning with a Single Transformer

# 摘要

> 本文提出了一种名为SAIL的单变换器统一多模态大型语言模型（MLLM），它在同一架构中实现了原始像素编码与语言解码的整合。与依赖预训练视觉变换器（ViT）的现有模块化MLLM不同，SAIL摒弃了单独的视觉编码器，采用了更为简约的设计理念。通过混合注意力机制和多模态位置编码，SAIL能够更好地适应视觉和文本数据的独特属性。我们对SAIL的扩展性、跨模态信息流动模式以及视觉表达能力进行了系统性评估，并与模块化MLLM进行了对比。通过扩大训练数据规模和模型参数量，SAIL达到了与模块化MLLM相当的性能水平。值得注意的是，取消预训练ViT组件不仅提升了SAIL的扩展能力，还带来了独特的跨模态信息流动模式。此外，SAIL在视觉任务，如语义分割方面表现优异，其效果可与ViT-22B相媲美。SAIL的代码和模型已开源，可在https://github.com/bytedance/SAIL获取。

> This paper introduces SAIL, a single transformer unified multimodal large language model (MLLM) that integrates raw pixel encoding and language decoding within a singular architecture. Unlike existing modular MLLMs, which rely on a pre-trained vision transformer (ViT), SAIL eliminates the need for a separate vision encoder, presenting a more minimalist architecture design. Instead of introducing novel architectural components, SAIL adapts mix-attention mechanisms and multimodal positional encodings to better align with the distinct characteristics of visual and textual modalities. We systematically compare SAIL's properties-including scalability, cross-modal information flow patterns, and visual representation capabilities-with those of modular MLLMs. By scaling both training data and model size, SAIL achieves performance comparable to modular MLLMs. Notably, the removal of pretrained ViT components enhances SAIL's scalability and results in significantly different cross-modal information flow patterns. Moreover, SAIL demonstrates strong visual representation capabilities, achieving results on par with ViT-22B in vision tasks such as semantic segmentation. Code and models are available at https://github.com/bytedance/SAIL.

[Arxiv](https://arxiv.org/abs/2504.10462)