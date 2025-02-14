# 多智能体辩论是答案，那问题又是什么？

发布时间：2025年02月12日

`Agent` `人工智能` `机器学习`

> If Multi-Agent Debate is the Answer, What is the Question?

# 摘要

> 多智能体辩论（MAD）作为一种有前景的方法，通过让多个智能体在推理过程中进行迭代讨论，已被证明能有效提升大型语言模型（LLMs）的事实准确性和推理质量。尽管MAD方法潜力巨大，但我们认为当前研究在评估实践方面存在重大缺陷，包括数据集重叠有限和基线不一致，这引发了对模型泛化能力的重大担忧。因此，本文通过四个基础模型，对五种具有代表性的MAD方法进行了系统性评估，涵盖九个基准测试。令人惊讶的是，即使在消耗额外推理时间计算资源的情况下，MAD方法也未能可靠地超越Chain-of-Thought和Self-Consistency等简单的单智能体基线。通过分析，我们发现模型异质性可以显著提升MAD框架的表现。为此，我们提出了Heter-MAD，使单一LLM智能体能够访问异质基础模型的输出，从而增强现有MAD框架的性能。最后，我们提出了推进MAD的潜在方向，旨在引发更广泛的讨论，并激发未来在这一领域的研究工作。

> Multi-agent debate (MAD) has emerged as a promising approach to enhance the factual accuracy and reasoning quality of large language models (LLMs) by engaging multiple agents in iterative discussions during inference. Despite its potential, we argue that current MAD research suffers from critical shortcomings in evaluation practices, including limited dataset overlap and inconsistent baselines, raising significant concerns about generalizability. Correspondingly, this paper presents a systematic evaluation of five representative MAD methods across nine benchmarks using four foundational models. Surprisingly, our findings reveal that MAD methods fail to reliably outperform simple single-agent baselines such as Chain-of-Thought and Self-Consistency, even when consuming additional inference-time computation. From our analysis, we found that model heterogeneity can significantly improve MAD frameworks. We propose Heter-MAD enabling a single LLM agent to access the output from heterogeneous foundation models, which boosts the performance of current MAD frameworks. Finally, we outline potential directions for advancing MAD, aiming to spark a broader conversation and inspire future work in this area.

[Arxiv](https://arxiv.org/abs/2502.08788)