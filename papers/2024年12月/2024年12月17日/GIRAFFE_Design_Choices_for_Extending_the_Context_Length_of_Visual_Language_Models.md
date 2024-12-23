# GIRAFFE：关于扩展视觉语言模型上下文长度的设计抉择

发布时间：2024年12月17日

`LLM应用` `视觉语言模型` `多模态处理`

> GIRAFFE: Design Choices for Extending the Context Length of Visual Language Models

# 摘要

> 视觉语言模型（VLMs）在处理多模态输入时表现出色，然而像视觉代理这类需处理多幅图像和高分辨率视频的应用，对远程建模能力有更高要求。而且，现有的开源 VLMs 在扩展上下文长度方面缺乏系统研究，商业模型提供的细节往往有限。为应对此问题，我们致力于构建有效方案，在保持其短上下文场景能力的同时提升长上下文性能。为此，我们通过广泛的实验设置，包括数据策划、上下文窗口扩展及利用等，做出最优设计选择：（1）分析数据源和长度分布，构建 ETVLM——一种平衡不同场景性能的数据方案；（2）考察现有位置扩展方法，指出其局限性并提出 M-RoPE++这一增强手段；还选择仅用混合源数据对骨干进行指令调整；（3）探讨如何更好地利用扩展的上下文窗口并提出混合分辨率训练。基于 Qwen-VL 系列模型，我们推出了长颈鹿，其有效扩展至 128K 长度。在 VideoMME 和 Viusal Haystacks 等众多长上下文 VLM 基准测试中，我们的长颈鹿在类似规模的开源长 VLMs 中达到了领先水平，与商业模型 GPT-4V 相比也颇具竞争力。我们会将代码、数据和模型开源。

> Visual Language Models (VLMs) demonstrate impressive capabilities in processing multimodal inputs, yet applications such as visual agents, which require handling multiple images and high-resolution videos, demand enhanced long-range modeling. Moreover, existing open-source VLMs lack systematic exploration into extending their context length, and commercial models often provide limited details. To tackle this, we aim to establish an effective solution that enhances long context performance of VLMs while preserving their capacities in short context scenarios. Towards this goal, we make the best design choice through extensive experiment settings from data curation to context window extending and utilizing: (1) we analyze data sources and length distributions to construct ETVLM - a data recipe to balance the performance across scenarios; (2) we examine existing position extending methods, identify their limitations and propose M-RoPE++ as an enhanced approach; we also choose to solely instruction-tune the backbone with mixed-source data; (3) we discuss how to better utilize extended context windows and propose hybrid-resolution training. Built on the Qwen-VL series model, we propose Giraffe, which is effectively extended to 128K lengths. Evaluated on extensive long context VLM benchmarks such as VideoMME and Viusal Haystacks, our Giraffe achieves state-of-the-art performance among similarly sized open-source long VLMs and is competitive with commercial model GPT-4V. We will open-source the code, data, and models.

[Arxiv](https://arxiv.org/abs/2412.12735)