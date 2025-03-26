# Video-XL-Pro：极长视频理解的重构式令牌压缩方案

发布时间：2025年03月24日

`LLM应用` `视频处理` `视频分析`

> Video-XL-Pro: Reconstructive Token Compression for Extremely Long Video Understanding

# 摘要

> 尽管采用了高级的token压缩技术，现有的多模态大语言模型（MLLMs）在理解长达数小时的视频方面仍然存在困难。针对这一问题，我们提出了Video-XL-Pro，这是一种基于Reconstructive Compression of Tokens（ReCoT）的高效方法。ReCoT是一个可学习模块，通过自监督学习生成全面且紧凑的视频tokens，并引入了两个关键组件：(i) 动态Token合成器（DTS）：通过学习token间的内在关系，从静态图像tokens生成伪视频tokens，用于遮蔽视频建模。(ii) 语义引导遮蔽（SGM）：自适应地遮蔽冗余的视觉tokens，以促进更有效的重构学习。为了提升MLLMs微调的训练效率，我们设计了一种针对视频的特定数据集剪枝策略，并开发了一个简单却有效的Query-aware Selector，使模型能够精确定位与查询相关的视频tokens。Video-XL-Pro仅使用30亿个参数，在多个长视频理解基准测试中超越了大多数基于更大数据集训练的70亿参数模型。此外，它还能在单个A100 GPU上处理超过8000帧的视频，同时保持高质量的性能表现。

> Despite advanced token compression techniques, existing multimodal large language models (MLLMs) still struggle with hour-long video understanding. In this work, we propose Video-XL-Pro, an efficient method for extremely long video understanding, built upon Reconstructive Compression of Tokens (ReCoT), a learnable module that leverages self-supervised learning to generate comprehensive and compact video tokens. ReCoT introduces two key components: (i) Dynamic Token Synthesizer (DTS): DTS generates pseudo-video tokens from static image tokens by learning intra-token relationships, which are then used in masked video modeling. (ii) Semantic-Guided Masking (SGM): SGM adaptively masks redundant visual tokens to facilitate more effective reconstructive learning. To improve training efficiency in MLLMs fine-tuning, we introduce a video-specific dataset pruning strategy and design a simple yet Query-aware Selector that enables the model to precisely locate query-relevant video tokens. With only 3B parameters, Video-XL-Pro outperforms most 7B models trained on larger datasets across multiple long video understanding benchmarks. Moreover, it can process over 8K frames on a single A100 GPU while maintaining high-quality performance.

[Arxiv](https://arxiv.org/abs/2503.18478)