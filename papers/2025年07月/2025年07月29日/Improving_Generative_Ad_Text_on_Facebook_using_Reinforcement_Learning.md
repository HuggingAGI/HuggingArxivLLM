# 利用强化学习优化 Facebook 的生成式广告文案

发布时间：2025年07月29日

`LLM应用` `数字营销`

> Improving Generative Ad Text on Facebook using Reinforcement Learning

# 摘要

> 生成式AI，尤其是大型语言模型（LLMs），正在蓄势待发，推动一场重大的经济变革。LLMs通过在海量文本数据上预训练学习通用语言模式，但要使其适应具体实际任务，后训练阶段至关重要。强化学习（RL）是领先的后训练技术，但其经济影响仍未得到充分探索和量化。我们通过 Facebook 上首次部署强化学习训练的 LLM 用于生成广告来探讨这一问题。我们的模型“AdLlama”集成到 Meta 的文本生成功能中，为广告商提供一个 AI 工具，帮助他们创建人类编写广告文案的新变体。为了训练此模型，我们引入了基于性能反馈的强化学习（RLPF），这是一种后训练方法，利用历史广告表现数据作为奖励信号。在 Facebook 上覆盖近 35,000 名广告商和 640,000 个广告变体的为期 10 周的大型 A/B 测试中，我们发现与基于精选广告训练的监督模仿模型相比，AdLlama 将点击率提高了 6.7%（p=0.0296）。这代表了 Facebook 广告商投资回报的重大提升。我们还发现使用 AdLlama 的广告商生成了更多广告变体，表明他们对模型输出的更高满意度。据我们所知，这是迄今为止在生态效度环境中使用生成式 AI 的最大规模研究，为强化学习后训练的实际影响提供了重要的量化数据点。此外，结果表明，RLPF 是一种有前景且可推广的指标驱动后训练方法，弥合了功能强大的语言模型与实际成果之间的差距。

> Generative artificial intelligence (AI), in particular large language models (LLMs), is poised to drive transformative economic change. LLMs are pre-trained on vast text data to learn general language patterns, but a subsequent post-training phase is critical to align them for specific real-world tasks. Reinforcement learning (RL) is the leading post-training technique, yet its economic impact remains largely underexplored and unquantified. We examine this question through the lens of the first deployment of an RL-trained LLM for generative advertising on Facebook. Integrated into Meta's Text Generation feature, our model, "AdLlama," powers an AI tool that helps advertisers create new variations of human-written ad text. To train this model, we introduce reinforcement learning with performance feedback (RLPF), a post-training method that uses historical ad performance data as a reward signal. In a large-scale 10-week A/B test on Facebook spanning nearly 35,000 advertisers and 640,000 ad variations, we find that AdLlama improves click-through rates by 6.7% (p=0.0296) compared to a supervised imitation model trained on curated ads. This represents a substantial improvement in advertiser return on investment on Facebook. We also find that advertisers who used AdLlama generated more ad variations, indicating higher satisfaction with the model's outputs. To our knowledge, this is the largest study to date on the use of generative AI in an ecologically valid setting, offering an important data point quantifying the tangible impact of RL post-training. Furthermore, the results show that RLPF is a promising and generalizable approach for metric-driven post-training that bridges the gap between highly capable language models and tangible outcomes.

[Arxiv](https://arxiv.org/abs/2507.21983)