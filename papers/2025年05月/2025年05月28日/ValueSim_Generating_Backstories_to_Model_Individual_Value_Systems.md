# ValueSim：通过生成背景故事建模个人价值体系

发布时间：2025年05月28日

`LLM应用` `人工智能伦理` `个性化模拟`

> ValueSim: Generating Backstories to Model Individual Value Systems

# 摘要

> 随着大型语言模型（LLMs）能力愈发接近人类水平，如何使其与人类价值观对齐变得至关重要。当前，提示学习和强化学习等先进方法被用于提升LLMs与人类价值观的对齐程度。然而，尽管这些方法在解决伦理问题和提升有用性方面取得了一定成效，但它们大多忽视了对个性化人类价值体系的模拟。为弥补这一研究空白，我们提出了ValueSim框架，通过生成反映个人经历和人口统计信息的背景故事来模拟个体价值观。ValueSim能够将结构化的个体数据转化为叙事性背景故事，并采用受认知-情感人格系统启发的多模块架构，基于这些叙述模拟个体价值观。在基于世界价值观调查构建的自建基准测试中，ValueSim的top-1准确率相比检索增强生成方法提升了10%以上。进一步分析表明，随着用户交互历史的增加，模型性能得到显著提升，这表明ValueSim能够随着时间推移不断完善其人格模拟能力。

> As Large Language Models (LLMs) continue to exhibit increasingly human-like capabilities, aligning them with human values has become critically important. Contemporary advanced techniques, such as prompt learning and reinforcement learning, are being deployed to better align LLMs with human values. However, while these approaches address broad ethical considerations and helpfulness, they rarely focus on simulating individualized human value systems. To address this gap, we present ValueSim, a framework that simulates individual values through the generation of personal backstories reflecting past experiences and demographic information. ValueSim converts structured individual data into narrative backstories and employs a multi-module architecture inspired by the Cognitive-Affective Personality System to simulate individual values based on these narratives. Testing ValueSim on a self-constructed benchmark derived from the World Values Survey demonstrates an improvement in top-1 accuracy by over 10% compared to retrieval-augmented generation methods. Further analysis reveals that performance enhances as additional user interaction history becomes available, indicating the model's ability to refine its persona simulation capabilities over time.

[Arxiv](https://arxiv.org/abs/2505.23827)