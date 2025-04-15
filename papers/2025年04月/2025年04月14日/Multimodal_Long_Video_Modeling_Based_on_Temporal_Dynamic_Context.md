# 基于时间动态上下文的多模态长视频建模

发布时间：2025年04月14日

`LLM应用` `视频理解` `视听理解`

> Multimodal Long Video Modeling Based on Temporal Dynamic Context

# 摘要

> 大型语言模型（LLMs）的最新进展推动了视频理解领域的重要突破。然而，现有模型在处理长视频时仍面临两大挑战：LLMs的上下文长度限制以及视频内容的海量信息。尽管一些新方法专为长视频理解设计，但它们在令牌压缩过程中常丢失关键信息，且难以有效处理音频等额外模态。为此，我们提出了一种基于帧间时序关系的动态长视频编码方法——时序动态上下文（TDC）。具体而言，首先根据帧间相似性将视频分割为语义一致的场景，随后通过视觉-音频编码器将每帧转化为令牌。其次，我们设计了一种创新的时序上下文压缩器，用于减少每个片段的令牌数量。具体实现上，采用基于查询的Transformer将视频、音频及指令文本令牌聚合为有限的时序上下文令牌。最后，将静态帧令牌与时序上下文令牌输入LLM以完成视频理解。此外，针对超长视频，我们提出了一种无需训练的链式推理策略，通过逐步提取多个视频片段的答案来实现推理。这些中间答案不仅作为推理过程的一部分，还能为最终答案提供支持。我们在多个通用视频理解和视听理解基准测试中进行了广泛实验，结果表明本方法表现出色。代码和模型已在GitHub上开源，地址为https://github.com/Hoar012/TDC-Video。


> Recent advances in Large Language Models (LLMs) have led to significant breakthroughs in video understanding. However, existing models still struggle with long video processing due to the context length constraint of LLMs and the vast amount of information within the video. Although some recent methods are designed for long video understanding, they often lose crucial information during token compression and struggle with additional modality like audio. In this work, we propose a dynamic long video encoding method utilizing the temporal relationship between frames, named Temporal Dynamic Context (TDC). Firstly, we segment the video into semantically consistent scenes based on inter-frame similarities, then encode each frame into tokens using visual-audio encoders. Secondly, we propose a novel temporal context compressor to reduce the number of tokens within each segment. Specifically, we employ a query-based Transformer to aggregate video, audio, and instruction text tokens into a limited set of temporal context tokens. Finally, we feed the static frame tokens and the temporal context tokens into the LLM for video understanding. Furthermore, to handle extremely long videos, we propose a training-free chain-of-thought strategy that progressively extracts answers from multiple video segments. These intermediate answers serve as part of the reasoning process and contribute to the final answer. We conduct extensive experiments on general video understanding and audio-video understanding benchmarks, where our method demonstrates strong performance. The code and models are available at https://github.com/Hoar012/TDC-Video.

[Arxiv](https://arxiv.org/abs/2504.10443)