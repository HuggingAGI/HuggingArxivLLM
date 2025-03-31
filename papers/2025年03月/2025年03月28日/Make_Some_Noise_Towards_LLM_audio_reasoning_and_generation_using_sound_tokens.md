# LLM也能听声辨音！探索声音令牌在音频推理与生成中的应用

发布时间：2025年03月28日

`LLM应用

理由：这篇论文讨论了如何将语音处理与大型语言模型结合，提出了一种新的方法来实现语音理解和生成，属于大型语言模型的应用层面。` `语音处理` `多模态模型`

> Make Some Noise: Towards LLM audio reasoning and generation using sound tokens

# 摘要

> 语音理解和生成的整合在大型语言模型（LLMs）中仍具挑战性，主要源于语音的连续特性和高采样率。我们提出了一种创新方法，结合变分量化与条件流匹配，将语音压缩为0.23kpbs的超低码率离散令牌，实现与LLMs中文本令牌的无缝对接。通过低秩适配（LoRA）对预训练文本基LLM进行微调，我们评估了其在语音理解和生成等真正多模态能力方面的表现。我们的分词器在多个包含不同声学事件的数据集上优于传统VQ-VAE。尽管语音分词导致大量细节丢失，但基于离散令牌训练的多模态LLM在语音理解方面与现有最优方法相比表现优异，尽管语音生成效果尚待提升。我们的研究结果表明，更大规模、更多样化的数据集以及改进的评估指标是推动多模态LLM性能发展的关键。

> Integrating audio comprehension and generation into large language models (LLMs) remains challenging due to the continuous nature of audio and the resulting high sampling rates. Here, we introduce a novel approach that combines Variational Quantization with Conditional Flow Matching to convert audio into ultra-low bitrate discrete tokens of 0.23kpbs, allowing for seamless integration with text tokens in LLMs. We fine-tuned a pretrained text-based LLM using Low-Rank Adaptation (LoRA) to assess its effectiveness in achieving true multimodal capabilities, i.e., audio comprehension and generation. Our tokenizer outperforms a traditional VQ-VAE across various datasets with diverse acoustic events. Despite the substantial loss of fine-grained details through audio tokenization, our multimodal LLM trained with discrete tokens achieves competitive results in audio comprehension with state-of-the-art methods, though audio generation is poor. Our results highlight the need for larger, more diverse datasets and improved evaluation metrics to advance multimodal LLM performance.

[Arxiv](https://arxiv.org/abs/2503.22275)