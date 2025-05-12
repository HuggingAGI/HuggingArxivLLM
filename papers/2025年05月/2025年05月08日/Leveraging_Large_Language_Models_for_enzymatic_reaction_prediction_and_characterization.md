# 基于大型语言模型的酶促反应预测与特性分析

发布时间：2025年05月08日

`LLM应用` `生物技术`

> Leveraging Large Language Models for enzymatic reaction prediction and characterization

# 摘要

> 预测酶促反应在生物催化、代谢工程和药物发现等领域具有重要作用，但目前仍是一个复杂且资源消耗巨大的任务。大型语言模型（LLMs）近期在多个科学领域展现了卓越的成功，例如通过其知识泛化能力、复杂结构推理能力以及运用上下文学习策略的能力。在本研究中，我们系统评估了LLMs，特别是Llama-3.1系列模型（8B和70B参数版本）在三个核心生化任务中的表现：酶委员会编号预测、正向合成与逆向合成。我们对比了单任务与多任务学习策略，采用通过LoRA适配器实现的参数高效微调方法。此外，我们还评估了不同数据集规模下的模型性能，以探索其在小数据环境中的适应能力。我们的研究结果表明，经过微调的LLMs能够捕捉生化知识，多任务学习通过共享酶学信息增强了正向与逆向合成的预测能力。同时，我们也发现了关键的局限性，例如在层级化的EC分类体系中的挑战，这为未来提升LLM驱动的生化建模指明了改进方向。

> Predicting enzymatic reactions is crucial for applications in biocatalysis, metabolic engineering, and drug discovery, yet it remains a complex and resource-intensive task. Large Language Models (LLMs) have recently demonstrated remarkable success in various scientific domains, e.g., through their ability to generalize knowledge, reason over complex structures, and leverage in-context learning strategies. In this study, we systematically evaluate the capability of LLMs, particularly the Llama-3.1 family (8B and 70B), across three core biochemical tasks: Enzyme Commission number prediction, forward synthesis, and retrosynthesis. We compare single-task and multitask learning strategies, employing parameter-efficient fine-tuning via LoRA adapters. Additionally, we assess performance across different data regimes to explore their adaptability in low-data settings. Our results demonstrate that fine-tuned LLMs capture biochemical knowledge, with multitask learning enhancing forward- and retrosynthesis predictions by leveraging shared enzymatic information. We also identify key limitations, for example challenges in hierarchical EC classification schemes, highlighting areas for further improvement in LLM-driven biochemical modeling.

[Arxiv](https://arxiv.org/abs/2505.05616)