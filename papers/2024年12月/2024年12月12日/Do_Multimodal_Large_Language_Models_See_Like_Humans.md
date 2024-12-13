# 多模态大型语言模型是否能像人类那样去观察？

发布时间：2024年12月12日

`LLM应用` `多模态`

> Do Multimodal Large Language Models See Like Humans?

# 摘要

> 多模态大型语言模型（MLLMs）依靠大型语言模型的最新进展，在各类视觉任务中斩获出色成果。然而，一个关键问题尚未解决：MLLMs 对视觉信息的感知是否与人类相仿？当下的基准测试无法从这一角度评估 MLLMs。为应对此挑战，我们推出了 HVSBench，这是一个大规模的基准测试，旨在衡量 MLLMs 与人类视觉系统（HVS）在反映人类视觉的基础视觉任务上的契合度。HVSBench 精心筛选了超过 85K 的多模态样本，涵盖 HVS 中的 13 个类别和 5 个领域，包括突出性、数量感知、优先级排序、自由观看和搜索。大量实验证明，我们的基准测试能有效对 MLLMs 进行全面评估。具体而言，我们评估了 13 个 MLLMs，发现即便是最优模型也有很大提升空间，多数仅取得中等成绩。我们的实验表明，HVSBench 给前沿的 MLLMs 带来了新的重大挑战。我们坚信，HVSBench 将助力对与人类一致且可解释的 MLLMs 的研究，成为理解 MLLMs 如何感知和处理视觉信息的关键一步。

> Multimodal Large Language Models (MLLMs) have achieved impressive results on various vision tasks, leveraging recent advancements in large language models. However, a critical question remains unaddressed: do MLLMs perceive visual information similarly to humans? Current benchmarks lack the ability to evaluate MLLMs from this perspective. To address this challenge, we introduce HVSBench, a large-scale benchmark designed to assess the alignment between MLLMs and the human visual system (HVS) on fundamental vision tasks that mirror human vision. HVSBench curated over 85K multimodal samples, spanning 13 categories and 5 fields in HVS, including Prominence, Subitizing, Prioritizing, Free-Viewing, and Searching. Extensive experiments demonstrate the effectiveness of our benchmark in providing a comprehensive evaluation of MLLMs. Specifically, we evaluate 13 MLLMs, revealing that even the best models show significant room for improvement, with most achieving only moderate results. Our experiments reveal that HVSBench presents a new and significant challenge for cutting-edge MLLMs. We believe that HVSBench will facilitate research on human-aligned and explainable MLLMs, marking a key step in understanding how MLLMs perceive and process visual information.

[Arxiv](https://arxiv.org/abs/2412.09603)