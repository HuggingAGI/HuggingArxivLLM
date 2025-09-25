# 面向文本与时间序列交错序列金融预测的模态专属专家多模态语言模型

发布时间：2025年09月23日

`LLM应用` `金融科技`

> Multimodal Language Models with Modality-Specific Experts for Financial Forecasting from Interleaved Sequences of Text and Time Series

# 摘要

> 文本与时间序列数据为金融市场提供了互补视角：新闻文章勾勒公司事件的叙事脉络，股票价格则映射市场对这些事件的反应。然而，尽管二者互补，有效融合这些交错模态以提升预测效果仍面临挑战。为此，我们提出一种统一神经架构，通过特定模态专家对这些交错序列建模，既能让模型学习独特的时间序列模式，又能实现跨模态联合推理，并保留预训练语言理解能力。为进一步提升多模态理解，我们引入带显著 token 加权机制的跨模态对齐框架，该机制通过聚焦信息最丰富的 token，学习跨模态表示的对齐。我们在大规模金融预测任务上验证了所提方法的有效性，在各类强单模态和多模态基线模型上均实现了最先进性能。我们还提出了一种可解释性方法，揭示了时间序列上下文的价值，并为跨模态对齐目标的设计提供了支持。最后，我们通过投资模拟验证，这些改进可转化为显著的经济收益。

> Text and time series data offer complementary views of financial markets: news articles provide narrative context about company events, while stock prices reflect how markets react to those events. However, despite their complementary nature, effectively integrating these interleaved modalities for improved forecasting remains challenging. In this work, we propose a unified neural architecture that models these interleaved sequences using modality-specific experts, allowing the model to learn unique time series patterns, while still enabling joint reasoning across modalities and preserving pretrained language understanding capabilities. To further improve multimodal understanding, we introduce a cross-modal alignment framework with a salient token weighting mechanism that learns to align representations across modalities with a focus on the most informative tokens. We demonstrate the effectiveness of our approach on a large-scale financial forecasting task, achieving state-of-the-art performance across a wide variety of strong unimodal and multimodal baselines. We develop an interpretability method that reveals insights into the value of time series-context and reinforces the design of our cross-modal alignment objective. Finally, we demonstrate that these improvements translate to meaningful economic gains in investment simulations.

[Arxiv](https://arxiv.org/abs/2509.19628)