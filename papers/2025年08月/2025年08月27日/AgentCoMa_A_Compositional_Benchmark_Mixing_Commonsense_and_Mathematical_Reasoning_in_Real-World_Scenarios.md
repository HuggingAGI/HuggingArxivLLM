# AgentCoMa：融合常识与数学推理的现实场景组合式基准测试

发布时间：2025年08月27日

`Agent` `基础理论`

> AgentCoMa: A Compositional Benchmark Mixing Commonsense and Mathematical Reasoning in Real-World Scenarios

# 摘要

> 大型语言模型（LLMs）在涉及多步推理组合的复杂常识与数学问题上，已展现出高精度表现。然而，当前用于测试这些能力的组合基准往往只侧重常识推理或数学推理中的一种，而解决现实任务的LLM智能体却需要二者兼备。为此，本研究提出了智能体常识与数学基准（AgentCoMa）——每个组合任务均包含一个常识推理步骤和一个数学推理步骤。我们在61个不同规模、模型家族及训练策略的LLM上对该基准进行了测试。结果显示，LLM单独处理这两个步骤时表现尚可，但一旦结合，准确率便平均骤降约30%。这一差距远大于此前在同类推理多步骤组合基准中的观测结果。相比之下，非专家人类标注员在AgentCoMa中无论是处理组合问题还是单独步骤，准确率都同样出色。为深入探究这一差距，我们还开展了系列可解释性研究，包括分析神经元模式、注意力图及成员推理。本研究揭示了LLM在混合类型组合推理中的显著脆弱性，同时也为后续优化提供了测试基准。

> Large Language Models (LLMs) have achieved high accuracy on complex commonsense and mathematical problems that involve the composition of multiple reasoning steps. However, current compositional benchmarks testing these skills tend to focus on either commonsense or math reasoning, whereas LLM agents solving real-world tasks would require a combination of both. In this work, we introduce an Agentic Commonsense and Math benchmark (AgentCoMa), where each compositional task requires a commonsense reasoning step and a math reasoning step. We test it on 61 LLMs of different sizes, model families, and training strategies. We find that LLMs can usually solve both steps in isolation, yet their accuracy drops by ~30% on average when the two are combined. This is a substantially greater performance gap than the one we observe in prior compositional benchmarks that combine multiple steps of the same reasoning type. In contrast, non-expert human annotators can solve the compositional questions and the individual steps in AgentCoMa with similarly high accuracy. Furthermore, we conduct a series of interpretability studies to better understand the performance gap, examining neuron patterns, attention maps and membership inference. Our work underscores a substantial degree of model brittleness in the context of mixed-type compositional reasoning and offers a test bed for future improvement.

[Arxiv](https://arxiv.org/abs/2508.19988)