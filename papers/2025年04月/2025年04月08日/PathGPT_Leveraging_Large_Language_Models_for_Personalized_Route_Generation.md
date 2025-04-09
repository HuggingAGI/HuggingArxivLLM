# PathGPT：驾驭大型语言模型，实现个性化路线生成

发布时间：2025年04月08日

`LLM应用` `交通规划` `导航系统`

> PathGPT: Leveraging Large Language Models for Personalized Route Generation

# 摘要

> GPS设备的普及带来了大量历史轨迹数据的积累。基于这些数据，研究人员开发了全新的数据驱动方法来解决个性化路线推荐（PRR）问题。与传统的Dijkstra最短路径算法不同，这些新型算法能够识别和学习数据中的模式，生成更个性化的路线。然而，训练完成的模型仅能生成与训练模式相符的路线，难以适应新场景。受大型语言模型（LLMs）领域最新进展的启发，我们开发了一个统一模型，结合LLMs的自然语言理解和外部上下文信息，解决PRR问题并无缝适应新场景。实验表明，这一方法显著提升了LLMs在PRR问题上的性能。

> The proliferation of GPS enabled devices has led to the accumulation of a substantial corpus of historical trajectory data. By leveraging these data for training machine learning models,researchers have devised novel data-driven methodologies that address the personalized route recommendation (PRR) problem. In contrast to conventional algorithms such as Dijkstra shortest path algorithm,these novel algorithms possess the capacity to discern and learn patterns within the data,thereby facilitating the generation of more personalized paths. However,once these models have been trained,their application is constrained to the generation of routes that align with their training patterns. This limitation renders them less adaptable to novel scenarios and the deployment of multiple machine learning models might be necessary to address new possible scenarios,which can be costly as each model must be trained separately. Inspired by recent advances in the field of Large Language Models (LLMs),we leveraged their natural language understanding capabilities to develop a unified model to solve the PRR problem while being seamlessly adaptable to new scenarios without additional training. To accomplish this,we combined the extensive knowledge LLMs acquired during training with further access to external hand-crafted context information,similar to RAG (Retrieved Augmented Generation) systems,to enhance their ability to generate paths according to user-defined requirements. Extensive experiments on different datasets show a considerable uplift in LLM performance on the PRR problem.

[Arxiv](https://arxiv.org/abs/2504.05846)