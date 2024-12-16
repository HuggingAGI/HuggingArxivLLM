# B-VLLM：一种具备平衡时空标记的视觉大型语言模型

发布时间：2024年12月13日

`LLM应用` `视觉理解`

> B-VLLM: A Vision Large Language Model with Balanced Spatio-Temporal Tokens

# 摘要

> 最近，与视觉编码器集成的视觉大型语言模型（VLLMs）在视觉理解领域展现出出色表现。VLLMs 的关键在于把视觉内容编码成视觉标记序列，从而让 VLLMs 能够同时处理视觉和文本内容。然而，对于 VLLMs 而言，理解视频，特别是长视频依旧是个难题，因为在对视频编码时，视觉标记数量会迅速增多，可能超出 VLLMs 的上下文窗口，还会带来沉重的计算负担。为限制视觉标记数量，现有的 VLLMs 要么（1）将视频均匀下采样为固定帧数，要么（2）减少每一帧编码的视觉标记数量。我们认为，前者忽略了视频中丰富的时间线索，后者则忽视了每一帧中的空间细节。在本研究中，我们提出了平衡-VLLM（B-VLLM）：一种新颖的 VLLM 框架，旨在有效利用与任务相关的时空线索，同时将视觉标记数量控制在 VLLM 上下文窗口长度以内。我们方法的核心是设计了一个文本条件自适应帧选择模块，用于识别与视觉理解任务相关的帧。接着，利用时间帧标记合并技术对所选帧去重。所选帧的视觉标记通过空间标记采样模块和可选的空间标记合并策略进行处理，以实现对标记数量的精准控制。实验结果表明，B-VLLM 在平衡视频理解中的帧数和视觉标记数量方面效果显著，在各类视频理解基准测试中表现出众。我们的代码可在 https://github.com/zhuqiangLu/B-VLLM 获取。

> Recently, Vision Large Language Models (VLLMs) integrated with vision encoders have shown promising performance in vision understanding. The key of VLLMs is to encode visual content into sequences of visual tokens, enabling VLLMs to simultaneously process both visual and textual content. However, understanding videos, especially long videos, remain a challenge to VLLMs as the number of visual tokens grows rapidly when encoding videos, resulting in the risk of exceeding the context window of VLLMs and introducing heavy computation burden. To restrict the number of visual tokens, existing VLLMs either: (1) uniformly downsample videos into a fixed number of frames or (2) reducing the number of visual tokens encoded from each frame. We argue the former solution neglects the rich temporal cue in videos and the later overlooks the spatial details in each frame. In this work, we present Balanced-VLLM (B-VLLM): a novel VLLM framework that aims to effectively leverage task relevant spatio-temporal cues while restricting the number of visual tokens under the VLLM context window length. At the core of our method, we devise a text-conditioned adaptive frame selection module to identify frames relevant to the visual understanding task. The selected frames are then de-duplicated using a temporal frame token merging technique. The visual tokens of the selected frames are processed through a spatial token sampling module and an optional spatial token merging strategy to achieve precise control over the token count. Experimental results show that B-VLLM is effective in balancing the number of frames and visual tokens in video understanding, yielding superior performance on various video understanding benchmarks. Our code is available at https://github.com/zhuqiangLu/B-VLLM.

[Arxiv](https://arxiv.org/abs/2412.09919)