# RealFactBench：用于评估大型语言模型在现实世界事实核查任务中的基准

发布时间：2025年06月14日

`LLM应用

摘要中提到，大型语言模型在事实核查领域的应用，推出基准测试RealFactBench，评估模型在各种任务中的表现，属于LLM的应用研究。` `事实核查` `信息验证`

> RealFactBench: A Benchmark for Evaluating Large Language Models in Real-World Fact-Checking

# 摘要

> 大型语言模型（LLMs）凭借其推理、证据检索和解释生成能力，在事实核查领域展现出巨大潜力。然而，现有基准测试未能全面评估 LLMs 和多模态大型语言模型（MLLMs）在现实虚假信息场景中的表现。为此，我们推出了 RealFactBench，这是一个全面的基准测试，旨在评估 LLMs 和 MLLMs 在知识验证、谣言检测和事件验证等多种现实任务中的事实核查能力。RealFactBench 包含 6,000 个来自权威来源的高质量声明，涵盖多模态内容和多个领域。我们的评估框架引入了未知率（UnR）指标，能够更细致地评估模型在处理不确定性以及平衡过度保守与过度自信方面的表现。通过对 7 个代表性的 LLMs 和 4 个 MLLMs 的广泛实验，我们揭示了它们在现实世界事实核查中的局限性，并为未来研究提供了宝贵见解。RealFactBench 已在 https://github.com/kalendsyang/RealFactBench.git 上公开发布。

> Large Language Models (LLMs) hold significant potential for advancing fact-checking by leveraging their capabilities in reasoning, evidence retrieval, and explanation generation. However, existing benchmarks fail to comprehensively evaluate LLMs and Multimodal Large Language Models (MLLMs) in realistic misinformation scenarios. To bridge this gap, we introduce RealFactBench, a comprehensive benchmark designed to assess the fact-checking capabilities of LLMs and MLLMs across diverse real-world tasks, including Knowledge Validation, Rumor Detection, and Event Verification. RealFactBench consists of 6K high-quality claims drawn from authoritative sources, encompassing multimodal content and diverse domains. Our evaluation framework further introduces the Unknown Rate (UnR) metric, enabling a more nuanced assessment of models' ability to handle uncertainty and balance between over-conservatism and over-confidence. Extensive experiments on 7 representative LLMs and 4 MLLMs reveal their limitations in real-world fact-checking and offer valuable insights for further research. RealFactBench is publicly available at https://github.com/kalendsyang/RealFactBench.git.

[Arxiv](https://arxiv.org/abs/2506.12538)