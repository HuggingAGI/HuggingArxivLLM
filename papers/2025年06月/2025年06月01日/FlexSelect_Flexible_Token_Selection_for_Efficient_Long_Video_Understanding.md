# # 摘要  
FlexSelect：灵活的标记选择，用于高效长视频理解

发布时间：2025年06月01日

`LLM应用` `视频处理` `视频理解`

> FlexSelect: Flexible Token Selection for Efficient Long Video Understanding

# 摘要

> 长视频理解对VideoLLM提出了巨大挑战，主要源于其极高的计算与内存需求。本文提出了一种名为FlexSelect的灵活高效token选择策略，用于处理长视频。FlexSelect借助参考变换器层的跨模态注意力模式，精准识别并保留语义价值最高的内容。该策略包含两大核心组件：(1) 无需训练的token排名管道，通过忠实的跨模态注意力权重评估每个视频token的重要性；(2) 基于排名监督的轻量级选择器，经过训练能够精准复制排名并高效过滤冗余token。这一通用方法可无缝融入LLaVA-Video、InternVL和Qwen-VL等各类VideoLLM架构，作为即插即用模块扩展其时间上下文长度。实验证明，FlexSelect在VideoMME、MLVU、LongVB和LVBench等多个长视频基准测试中表现优异。此外，FlexSelect实现了显著的速度提升（例如，在LLaVA-Video-7B模型上提升9倍），充分展现了其在高效长视频理解中的巨大潜力。项目详情请访问：https://yunzhuzhang0918.github.io/flex_select

> Long-form video understanding poses a significant challenge for video large language models (VideoLLMs) due to prohibitively high computational and memory demands. In this paper, we propose FlexSelect, a flexible and efficient token selection strategy for processing long videos. FlexSelect identifies and retains the most semantically relevant content by leveraging cross-modal attention patterns from a reference transformer layer. It comprises two key components: (1) a training-free token ranking pipeline that leverages faithful cross-modal attention weights to estimate each video token's importance, and (2) a rank-supervised lightweight selector that is trained to replicate these rankings and filter redundant tokens. This generic approach can be seamlessly integrated into various VideoLLM architectures, such as LLaVA-Video, InternVL and Qwen-VL, serving as a plug-and-play module to extend their temporal context length. Empirically, FlexSelect delivers strong gains across multiple long-video benchmarks including VideoMME, MLVU, LongVB, and LVBench. Moreover, it achieves significant speed-ups (for example, up to 9 times on a LLaVA-Video-7B model), highlighting FlexSelect's promise for efficient long-form video understanding. Project page available at: https://yunzhuzhang0918.github.io/flex_select

[Arxiv](https://arxiv.org/abs/2506.00993)