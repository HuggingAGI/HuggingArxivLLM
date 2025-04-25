# Token打乱：探索高分辨率图像生成的新路径

发布时间：2025年04月24日

`LLM应用

摘要中的论文专注于优化多模态大型语言模型（MLLMs）在图像生成中的应用，提出了一种新的方法Token-Shuffle，以提高生成分辨率和效率。这属于LLM的应用层面改进。` `计算机视觉` `生成式AI`

> Token-Shuffle: Towards High-Resolution Image Generation with Autoregressive Models

# 摘要

> 自回归 (AR) 模型长期在语言生成领域占据主导地位，但在图像合成领域的应用却常被认为不如扩散模型 (Diffusion-based models) 竞争力强。AR 模型的主要限制在于需要大量图像令牌，这不仅限制了训练和推理效率，也影响了图像分辨率。为解决这一问题，我们提出了 Token-Shuffle，这是一种新颖且简单的 Transformer 中减少图像令牌数量的方法。

我们的核心发现是多模态大型语言模型 (MLLMs) 中视觉词汇表的维度冗余，其中视觉编码器生成的低维视觉码直接映射到高维语言词汇表。基于此，我们提出了两个关键操作：Token-Shuffle 和 Token-Unshuffle。Token-Shuffle 通过沿通道维度合并空间上邻近的令牌来减少输入令牌数量；Token-Unshuffle 则在 Transformer 块推理后解码令牌，以恢复空间排列输出。

通过与文本提示联合训练，我们的方法无需额外的预训练文本编码器，使 MLLMs 能够以统一的下一个令牌预测方式支持极高分辨率的图像生成，同时保持高效的训练和推理。我们首次将 AR 文本到图像生成的分辨率提升至 2048x2048，生成效果令人满意。在 GenAI-benchmark 中，我们的 2.7B 模型在困难提示下获得 0.77 的总体评分，分别领先 AR 模型 LlamaGen 0.18 和扩散模型 LDM 0.15。详尽的大规模人工评估也证明了我们在文本对齐、视觉缺陷和视觉外观方面的出色图像生成能力。

我们希望 Token-Shuffle 能够成为 MLLMs 中高效高分辨率图像生成的基础设计。


> Autoregressive (AR) models, long dominant in language generation, are increasingly applied to image synthesis but are often considered less competitive than Diffusion-based models. A primary limitation is the substantial number of image tokens required for AR models, which constrains both training and inference efficiency, as well as image resolution. To address this, we present Token-Shuffle, a novel yet simple method that reduces the number of image tokens in Transformer. Our key insight is the dimensional redundancy of visual vocabularies in Multimodal Large Language Models (MLLMs), where low-dimensional visual codes from visual encoder are directly mapped to high-dimensional language vocabularies. Leveraging this, we consider two key operations: token-shuffle, which merges spatially local tokens along channel dimension to decrease the input token number, and token-unshuffle, which untangles the inferred tokens after Transformer blocks to restore the spatial arrangement for output. Jointly training with textual prompts, our strategy requires no additional pretrained text-encoder and enables MLLMs to support extremely high-resolution image synthesis in a unified next-token prediction way while maintaining efficient training and inference. For the first time, we push the boundary of AR text-to-image generation to a resolution of 2048x2048 with gratifying generation performance. In GenAI-benchmark, our 2.7B model achieves 0.77 overall score on hard prompts, outperforming AR models LlamaGen by 0.18 and diffusion models LDM by 0.15. Exhaustive large-scale human evaluations also demonstrate our prominent image generation ability in terms of text-alignment, visual flaw, and visual appearance. We hope that Token-Shuffle can serve as a foundational design for efficient high-resolution image generation within MLLMs.

[Arxiv](https://arxiv.org/abs/2504.17789)