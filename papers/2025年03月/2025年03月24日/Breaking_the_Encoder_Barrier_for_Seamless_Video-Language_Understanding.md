# # 突破编码器限制，实现无缝视频语言理解

发布时间：2025年03月24日

`LLM应用` `多模态交互`

> Breaking the Encoder Barrier for Seamless Video-Language Understanding

# 摘要

> 大多数视频-大型语言模型（Video-LLMs）采用编码器-解码器架构，通过视觉编码器提取帧级特征供语言模型处理。然而，这种架构存在计算成本高昂、分辨率偏差明显以及难以捕捉细腻多模态交互的局限。为突破这些限制，我们提出ELVA——一款无需编码器的Video-LLM，能够直接建模细致入微的视频-语言交互。ELVA通过令牌合并构建自底向上的层级表示，并引入视频指导监督器实现直接的时空表示学习。此外，其混合分辨率机制巧妙整合高低分辨率帧作为输入，在性能与效率之间实现最佳平衡。仅使用7M公开可用的视频-文本对，ELVA不仅达到与基于编码器的Video-LLMs相当的性能，还将计算量减少95%，推理延迟降低92%，为实时视频理解提供了一个高效且可扩展的解决方案。


> Most Video-Large Language Models (Video-LLMs) adopt an encoder-decoder framework, where a vision encoder extracts frame-wise features for processing by a language model. However, this approach incurs high computational costs, introduces resolution biases, and struggles to capture fine-grained multimodal interactions. To overcome these limitations, we propose ELVA, an encoder-free Video-LLM that directly models nuanced video-language interactions without relying on a vision encoder. ELVA employs token merging to construct a bottom-up hierarchical representation and incorporates a video guidance supervisor for direct spatiotemporal representation learning. Additionally, a hybrid-resolution mechanism strategically integrates high- and low-resolution frames as inputs to achieve an optimal balance between performance and efficiency. With only 7M publicly available video-text pairs, ELVA achieves performance on par with encoder-based Video-LLMs while reducing FLOPs by up to 95\% and inference latency by 92\%, offering a scalable and efficient solution for real-time video understanding.

[Arxiv](https://arxiv.org/abs/2503.18422)