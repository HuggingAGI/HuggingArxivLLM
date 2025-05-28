# 借助多样化外部知识增强大型语言模型从自然语言到信号时态逻辑的转换能力

发布时间：2025年05月26日

`LLM应用

论文摘要：时序逻辑 (TL)，特别是信号时序逻辑 (STL)，因其能够实现精确的形式化规范而在自动驾驶和机器人等网络物理系统中广泛应用。自动将自然语言 (NL) 转换为 STL 是一种克服手动转换耗时且易出错问题的高效方法。然而，由于缺乏合适的数据集，这一自动转换过程目前面临诸多挑战，尚未得到充分探索。本文提出了一种名为 STL-DivEn 的 NL-STL 数据集，包含 16,000 个多样化模式样本。我们首先手动创建了一个小规模的 NL-STL 对种子集，随后通过聚类识别出具有代表性的示例，并利用这些示例指导大型语言模型 (LLMs) 生成更多 NL-STL 对。最后，通过严格的基于规则的过滤器和人工验证确保数据集的多样性和准确性。此外，我们引入了基于外部知识的生成-然后-优化流程，提出了 Knowledge-Guided STL Transformation (KGST) 框架，用于将自然语言转换为 STL。统计分析表明，STL-DivEn 数据集比现有的 NL-STL 数据集更具多样性。基于指标和人工评估的结果均显示，我们的 KGST 方法在 STL-DivEn 和 DeepSTL 数据集上的转换准确性优于基线模型。` `自动驾驶` `机器人`

> Enhancing Transformation from Natural Language to Signal Temporal Logic Using LLMs with Diverse External Knowledge

# 摘要

> 时序逻辑 (TL)，特别是信号时序逻辑 (STL)，因其能够实现精确的形式化规范而在自动驾驶和机器人等网络物理系统中广泛应用。自动将自然语言 (NL) 转换为 STL 是一种克服手动转换耗时且易出错问题的高效方法。然而，由于缺乏合适的数据集，这一自动转换过程目前面临诸多挑战，尚未得到充分探索。本文提出了一种名为 STL-DivEn 的 NL-STL 数据集，包含 16,000 个多样化模式样本。我们首先手动创建了一个小规模的 NL-STL 对种子集，随后通过聚类识别出具有代表性的示例，并利用这些示例指导大型语言模型 (LLMs) 生成更多 NL-STL 对。最后，通过严格的基于规则的过滤器和人工验证确保数据集的多样性和准确性。此外，我们引入了基于外部知识的生成-然后-优化流程，提出了 Knowledge-Guided STL Transformation (KGST) 框架，用于将自然语言转换为 STL。统计分析表明，STL-DivEn 数据集比现有的 NL-STL 数据集更具多样性。基于指标和人工评估的结果均显示，我们的 KGST 方法在 STL-DivEn 和 DeepSTL 数据集上的转换准确性优于基线模型。

> Temporal Logic (TL), especially Signal Temporal Logic (STL), enables precise formal specification, making it widely used in cyber-physical systems such as autonomous driving and robotics. Automatically transforming NL into STL is an attractive approach to overcome the limitations of manual transformation, which is time-consuming and error-prone. However, due to the lack of datasets, automatic transformation currently faces significant challenges and has not been fully explored. In this paper, we propose an NL-STL dataset named STL-Diversity-Enhanced (STL-DivEn), which comprises 16,000 samples enriched with diverse patterns. To develop the dataset, we first manually create a small-scale seed set of NL-STL pairs. Next, representative examples are identified through clustering and used to guide large language models (LLMs) in generating additional NL-STL pairs. Finally, diversity and accuracy are ensured through rigorous rule-based filters and human validation. Furthermore, we introduce the Knowledge-Guided STL Transformation (KGST) framework, a novel approach for transforming natural language into STL, involving a generate-then-refine process based on external knowledge. Statistical analysis shows that the STL-DivEn dataset exhibits more diversity than the existing NL-STL dataset. Moreover, both metric-based and human evaluations indicate that our KGST approach outperforms baseline models in transformation accuracy on STL-DivEn and DeepSTL datasets.

[Arxiv](https://arxiv.org/abs/2505.20658)