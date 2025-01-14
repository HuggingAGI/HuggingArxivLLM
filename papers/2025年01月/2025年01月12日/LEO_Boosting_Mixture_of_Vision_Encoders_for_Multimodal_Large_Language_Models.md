# LEO: 增强多模态大语言模型的视觉编码器混合能力

发布时间：2025年01月12日

`LLM应用

**理由**：该论文主要讨论了多模态大型语言模型（MLLMs）在视觉理解方面的应用，特别是通过引入多种视觉专家和设计新的视觉令牌融合策略来提升模型性能。论文的核心在于如何将视觉信息与语言模型结合，并应用于具体的视觉语言任务和自动驾驶领域。因此，该论文属于**LLM应用**类别。` `自动驾驶` `视觉理解`

> LEO: Boosting Mixture of Vision Encoders for Multimodal Large Language Models

# 摘要

> # 摘要
增强的视觉理解是多模态大型语言模型（MLLMs）的核心。近期，混合MLLMs通过引入多种视觉专家，解决了单一视觉编码器和视觉令牌过长的问题。尽管这些MLLMs取得了显著进展，但在有效整合多样化视觉编码器方面仍存在研究空白。本研究探索了混合MLLMs的视觉令牌融合策略，并设计了LEO——一种采用双分支视觉编码器框架的新型MLLM。LEO通过后适应融合策略和自适应分块技术，依次交错来自两个视觉编码器的视觉令牌。在13个视觉语言基准上的广泛测试表明，LEO在大多数任务上超越了当前最先进的开源MLLMs和混合MLLMs。此外，LEO无需调整模型架构或训练方法，即可适应自动驾驶这一专业领域，并取得了与现有基线相当的竞争力。代码和模型将公开提供。

> Enhanced visual understanding serves as a cornerstone for multimodal large language models (MLLMs). Recent hybrid MLLMs incorporate a mixture of vision experts to address the limitations of using a single vision encoder and excessively long visual tokens. Despite the progress of these MLLMs, a research gap remains in effectively integrating diverse vision encoders. This work explores fusion strategies of visual tokens for hybrid MLLMs, leading to the design of LEO, a novel MLLM with a dual-branch vision encoder framework that incorporates a post-adaptation fusion strategy and adaptive tiling: for each segmented tile of the input images, LEO sequentially interleaves the visual tokens from its two vision encoders. Extensive evaluation across 13 vision-language benchmarks reveals that LEO outperforms state-of-the-art open-source MLLMs and hybrid MLLMs on the majority of tasks. Furthermore, we show that LEO can be adapted to the specialized domain of autonomous driving without altering the model architecture or training recipe, achieving competitive performance compared to existing baselines. The code and model will be publicly available.

[Arxiv](https://arxiv.org/abs/2501.06986)