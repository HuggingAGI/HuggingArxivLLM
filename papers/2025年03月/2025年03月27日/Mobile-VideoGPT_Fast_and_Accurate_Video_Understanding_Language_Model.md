# 移动视频GPT：快速准确的视频理解模型

发布时间：2025年03月27日

`LLM应用

理由：这篇论文探讨了视频理解模型在实际应用中的效率问题，并提出了一种高效的多模态框架Mobile-VideoGPT。论文的重点在于模型的应用和优化，特别是在视频理解任务中的实际应用，因此归类到LLM应用。` `视频分析` `移动计算`

> Mobile-VideoGPT: Fast and Accurate Video Understanding Language Model

# 摘要

> 视频理解模型在实际应用中常常因为高计算需求、大量参数和缓慢推理速度而效率低下。为了解决这些问题，我们提出了Mobile-VideoGPT，一个高效的多模态框架，能够在不到十亿参数的情况下运行。与传统视频大型多模态模型（LMMs）不同，Mobile-VideoGPT采用轻量级双视觉编码器、高效投影器和小型语言模型（SLM），实现了实时吞吐量。为了进一步提升效率，我们引入了基于注意力的关键帧评分机制，配合高效的令牌投影器，能够剪枝冗余视觉令牌并保留关键上下文线索。我们在六个 established 的视频理解基准测试（如MVBench、EgoSchema、NextQA和PercepTest）上评估了我们的模型。实验结果表明，Mobile-VideoGPT-0.5B能够以每秒46个令牌的速度生成内容，同时在参数量减少40%且吞吐量提升超过2倍的情况下，平均超越现有0.5B参数的最先进模型6个百分点。我们的代码和模型已公开发布，访问地址为：https://github.com/Amshaker/Mobile-VideoGPT。


> Video understanding models often struggle with high computational requirements, extensive parameter counts, and slow inference speed, making them inefficient for practical use. To tackle these challenges, we propose Mobile-VideoGPT, an efficient multimodal framework designed to operate with fewer than a billion parameters. Unlike traditional video large multimodal models (LMMs), Mobile-VideoGPT consists of lightweight dual visual encoders, efficient projectors, and a small language model (SLM), enabling real-time throughput. To further improve efficiency, we present an Attention-Based Frame Scoring mechanism to select the key-frames, along with an efficient token projector that prunes redundant visual tokens and preserves essential contextual cues. We evaluate our model across well-established six video understanding benchmarks (e.g., MVBench, EgoSchema, NextQA, and PercepTest). Our results show that Mobile-VideoGPT-0.5B can generate up to 46 tokens per second while outperforming existing state-of-the-art 0.5B-parameter models by 6 points on average with 40% fewer parameters and more than 2x higher throughput. Our code and models are publicly available at: https://github.com/Amshaker/Mobile-VideoGPT.

[Arxiv](https://arxiv.org/abs/2503.21782)