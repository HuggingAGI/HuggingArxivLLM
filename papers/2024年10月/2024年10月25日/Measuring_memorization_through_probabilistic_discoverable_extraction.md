# 借助概率可发现提取来衡量记忆。

发布时间：2024年10月25日

`LLM理论` `语言模型` `数据安全`

> Measuring memorization through probabilistic discoverable extraction

# 摘要

> 大型语言模型（LLMs）易记住训练数据，这因可能提取敏感信息而令人担忧。当下测量 LLMs 记忆率的主要方法——可发现提取（Carlini 等人，2022），依赖于单序列贪婪采样，或许低估了真实的记忆程度。本文引入了可发现提取的概率松弛法，它能在一组生成的样本中量化提取目标序列的概率，同时考虑了各种采样方案和多次尝试。此方法鉴于 LLMs 和用户交互模式的概率特性，解决了通过可发现提取报告记忆率的局限。我们的实验表明，这种概率度量能揭示出比通过可发现提取所得更高的记忆率情况。我们还进一步探究了不同采样方案对可提取性的影响，为 LLM 记忆及其相关风险提供了更全面、更切实的评估。我们的贡献涵盖了新的概率记忆定义、其有效性的实证依据，以及对不同模型、规模、采样方案和训练数据重复的全面评估。

> Large language models (LLMs) are susceptible to memorizing training data, raising concerns due to the potential extraction of sensitive information. Current methods to measure memorization rates of LLMs, primarily discoverable extraction (Carlini et al., 2022), rely on single-sequence greedy sampling, potentially underestimating the true extent of memorization. This paper introduces a probabilistic relaxation of discoverable extraction that quantifies the probability of extracting a target sequence within a set of generated samples, considering various sampling schemes and multiple attempts. This approach addresses the limitations of reporting memorization rates through discoverable extraction by accounting for the probabilistic nature of LLMs and user interaction patterns. Our experiments demonstrate that this probabilistic measure can reveal cases of higher memorization rates compared to rates found through discoverable extraction. We further investigate the impact of different sampling schemes on extractability, providing a more comprehensive and realistic assessment of LLM memorization and its associated risks. Our contributions include a new probabilistic memorization definition, empirical evidence of its effectiveness, and a thorough evaluation across different models, sizes, sampling schemes, and training data repetitions.

[Arxiv](https://arxiv.org/abs/2410.19482)