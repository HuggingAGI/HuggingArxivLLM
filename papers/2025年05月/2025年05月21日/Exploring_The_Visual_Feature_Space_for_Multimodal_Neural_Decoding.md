# 多模态神经解码中的视觉特征空间探索

发布时间：2025年05月21日

`LLM应用

摘要分析：该论文探讨了多模态大型语言模型在脑信号解码中的应用，属于将LLM技术应用于神经科学的具体案例，因此归类为LLM应用。` `神经科学` `人工智能`

> Exploring The Visual Feature Space for Multimodal Neural Decoding

# 摘要

> 脑信号的复杂交织推动了利用多模态AI实现可解释性描述的研究，通过将脑信号与视觉和文本数据对齐。然而，现有研究大多局限于粗略的解释，缺乏关键细节，如物体描述、位置、属性及其关系，导致视觉解码时重建结果不够精确且存在歧义。为此，我们分析了多模态大型语言模型（MLLMs）中预训练视觉组件的视觉特征空间选择，并提出了一种零样本多模态脑解码方法，通过与这些模型交互实现跨多粒度层次的解码。% 为评估模型从脑信号中解码精细细节的能力，我们提出了多粒度脑细节理解基准（MG-BrainDub），包含详细描述和显著问答两个任务，其指标突出了关键视觉元素。我们的方法显著提升了神经解码的精度，为更精准的神经解码应用提供了支持。代码将在https://github.com/weihaox/VINDEX上开放。

> The intrication of brain signals drives research that leverages multimodal AI to align brain modalities with visual and textual data for explainable descriptions. However, most existing studies are limited to coarse interpretations, lacking essential details on object descriptions, locations, attributes, and their relationships. This leads to imprecise and ambiguous reconstructions when using such cues for visual decoding. To address this, we analyze different choices of vision feature spaces from pre-trained visual components within Multimodal Large Language Models (MLLMs) and introduce a zero-shot multimodal brain decoding method that interacts with these models to decode across multiple levels of granularities. % To assess a model's ability to decode fine details from brain signals, we propose the Multi-Granularity Brain Detail Understanding Benchmark (MG-BrainDub). This benchmark includes two key tasks: detailed descriptions and salient question-answering, with metrics highlighting key visual elements like objects, attributes, and relationships. Our approach enhances neural decoding precision and supports more accurate neuro-decoding applications. Code will be available at https://github.com/weihaox/VINDEX.

[Arxiv](https://arxiv.org/abs/2505.15755)