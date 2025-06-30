# LLaVA-Scissor：面向视频大语言模型的语义连通组件标记压缩

发布时间：2025年06月26日

`LLM应用` `视频处理` `多模态`

> LLaVA-Scissor: Token Compression with Semantic Connected Components for Video LLMs

# 摘要

> 本文提出了一种专为视频多模态大型语言模型设计的无训练token压缩策略——LLaVA-Scissor。与以往基于注意力分数压缩token但常导致语义覆盖不全和token冗余的方法不同，我们创新性地引入了语义连通组件（SCC）方法，通过将token分配到不同的语义区域，确保全面的语义覆盖。最终，我们提出了一种两步的时空token压缩策略，在空间和时间域中均利用SCC进行优化。该策略通过用一组不重叠的语义token高效表示整个视频，实现了有效的token压缩。我们在多样化的视频理解基准测试中对LLaVA-Scissor的token压缩能力进行了全面评估，包括视频问答、长视频理解和综合性多选题基准测试。实验结果表明，LLaVA-Scissor在各种视频理解基准测试中表现优异，尤其是在低token保留率下展现出显著优势。项目页面：https://github.com/HumanMLLM/LLaVA-Scissor。

> In this paper, we present LLaVA-Scissor, a training-free token compression strategy designed for video multimodal large language models. Previous methods mostly attempt to compress tokens based on attention scores, but fail to effectively capture all semantic regions and often lead to token redundancy. Differently, we propose to leverage the Semantic Connected Components (SCC) approach that assigns tokens to distinct semantic regions within the token set, ensuring comprehensive semantic coverage. The outcome is a two-step spatio-temporal token compression strategy that utilizes SCC in both spatial and temporal domains. This strategy can effectively compress tokens by representing the entire video with a set of non-overlapping semantic tokens. We conduct extensive evaluations of the token compression capabilities of LLaVA-Scissor across diverse video understanding benchmarks, including video question answering, long video understanding, and comprehensive multi-choices benchmarks. Experimental results show that the proposed LLaVA-Scissor outperforms other token compression methods, achieving superior performance in various video understanding benchmarks, particularly at low token retention ratios. Project page: https://github.com/HumanMLLM/LLaVA-Scissor.

[Arxiv](https://arxiv.org/abs/2506.21862)