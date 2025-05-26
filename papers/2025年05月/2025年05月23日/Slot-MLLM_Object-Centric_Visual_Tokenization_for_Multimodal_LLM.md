# Slot-MLLM：以对象为中心的视觉分词，助力多模态大语言模型

发布时间：2025年05月23日

`LLM应用` `多模态模型` `计算机视觉`

> Slot-MLLM: Object-Centric Visual Tokenization for Multimodal LLM

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）近期已成为实现人工通用智能的关键方法。特别是在视觉语言领域，MLLMs不仅能够生成文本，还能从多模态输入中生成视觉输出。这一突破需要高效的图像标记，以便LLMs在输入和输出过程中都能有效处理。然而，现有MLLMs的图像标记方法通常仅捕捉全局抽象概念或均匀分割的图像块，这限制了MLLMs在理解和生成细节视觉内容（特别是在对象级别）方面的有效性。为了解决这一问题，我们提出了一种基于Slot Attention的对象中心视觉标记器，专门用于MLLMs。具体而言，基于Q-Former编码器、扩散解码器和残差向量量化，我们的离散化Slot标记能够编码局部视觉细节，同时保持高级语义，并与文本数据对齐，无缝融入LLMs的统一下一步预测框架。实验结果表明，Slot-MLLM在涉及局部细节理解和生成的各类视觉语言任务中，相较于使用先前视觉标记器的基线模型，性能有了显著提升。值得注意的是，这是首次在野外自然图像上展示MLLMs使用基于对象中心的Slot Attention的可行性。


> Recently, multimodal large language models (MLLMs) have emerged as a key approach in achieving artificial general intelligence. In particular, vision-language MLLMs have been developed to generate not only text but also visual outputs from multimodal inputs. This advancement requires efficient image tokens that LLMs can process effectively both in input and output. However, existing image tokenization methods for MLLMs typically capture only global abstract concepts or uniformly segmented image patches, restricting MLLMs' capability to effectively understand or generate detailed visual content, particularly at the object level. To address this limitation, we propose an object-centric visual tokenizer based on Slot Attention specifically for MLLMs. In particular, based on the Q-Former encoder, diffusion decoder, and residual vector quantization, our proposed discretized slot tokens can encode local visual details while maintaining high-level semantics, and also align with textual data to be integrated seamlessly within a unified next-token prediction framework of LLMs. The resulting Slot-MLLM demonstrates significant performance improvements over baselines with previous visual tokenizers across various vision-language tasks that entail local detailed comprehension and generation. Notably, this work is the first demonstration of the feasibility of object-centric slot attention performed with MLLMs and in-the-wild natural images.

[Arxiv](https://arxiv.org/abs/2505.17726)