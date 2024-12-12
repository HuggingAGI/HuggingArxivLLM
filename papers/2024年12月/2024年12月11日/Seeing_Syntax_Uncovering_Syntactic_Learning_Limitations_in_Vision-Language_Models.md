# 《看到语法：揭示视觉语言模型中的句法学习局限性》

发布时间：2024年12月11日

`LLM理论` `多模态` `视觉语言模型`

> Seeing Syntax: Uncovering Syntactic Learning Limitations in Vision-Language Models

# 摘要

> 视觉语言模型（VLMs）是诸如图像字幕和文本到图像生成等多模态应用的基础模型。近期研究指出了 VLM 文本编码器存在的局限性，尤其是在组合性和语义理解等方面，不过这些局限性的根本原因尚不明确。在本研究中，我们旨在通过分析 VLM 文本编码器所编码的基本语言属性之一——句法信息来填补这一空白。我们进行了全面的分析，比较了具有不同目标函数、参数规模和训练数据规模的 VLM 与单模态语言模型（ULMs）在编码句法知识方面的能力。我们发现，ULM 文本编码器获取句法信息的能力比 VLM 中的更强。VLM 文本编码器所学到的句法信息主要由预训练目标决定，其作用比模型架构、模型规模或预训练数据量等其他因素更为关键。不同模型呈现出不同的层趋势，比如 CLIP 在各层的性能下降，而其他模型的中间层在编码句法知识方面较为丰富。

> Vision-language models (VLMs), serve as foundation models for multi-modal applications such as image captioning and text-to-image generation. Recent studies have highlighted limitations in VLM text encoders, particularly in areas like compositionality and semantic understanding, though the underlying reasons for these limitations remain unclear. In this work, we aim to address this gap by analyzing the syntactic information, one of the fundamental linguistic properties, encoded by the text encoders of VLMs. We perform a thorough analysis comparing VLMs with different objective functions, parameter size and training data size, and with uni-modal language models (ULMs) in their ability to encode syntactic knowledge. Our findings suggest that ULM text encoders acquire syntactic information more effectively than those in VLMs. The syntactic information learned by VLM text encoders is shaped primarily by the pre-training objective, which plays a more crucial role than other factors such as model architecture, model size, or the volume of pre-training data. Models exhibit different layer-wise trends where CLIP performance dropped across layers while for other models, middle layers are rich in encoding syntactic knowledge.

[Arxiv](https://arxiv.org/abs/2412.08111)