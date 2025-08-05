# 别想得太复杂：高效 R1 风格大规模推理模型研究综述

发布时间：2025年08月04日

`LLM理论` `推理模型`

> Don't Overthink It: A Survey of Efficient R1-style Large Reasoning Models

# 摘要

> 大型推理模型（LRMs）因其在处理复杂任务中的卓越表现，逐渐成为研究热点。其中，DeepSeek R1凭借出色的性能和开源性质，吸引了广泛关注，推动了R1风格LRMs的研究。与传统大型语言模型（LLMs）不同，这些模型通过引入强化学习中的长链式思考和自我反思机制，增强了逻辑推理和决策能力。然而，随着这些模型的广泛应用，过度思考的问题逐渐显现。具体来说，这些模型在生成答案时，常常构建过于冗长的推理链条，包含冗余或重复的步骤，导致推理效率降低，并可能影响最终答案的准确性。为此，提出了多种高效推理方法，旨在在不降低模型性能和推理能力的前提下，缩短推理路径的长度。通过系统性地回顾高效推理方法领域的最新研究成果，我们将现有工作主要分为两个方向：基于单模型优化和基于模型协作。第一类是单模型高效推理，专注于提升单个模型的推理效率；第二类是模型协作高效推理，探索通过多模型协作优化推理路径。此外，我们还维护了一个公开的GitHub仓库，跟踪高效推理方法的最新进展。

> Recently, Large Reasoning Models (LRMs) have gradually become a research hotspot due to their outstanding performance in handling complex tasks. Among them, DeepSeek R1 has garnered significant attention for its exceptional performance and open-source nature, driving advancements in the research of R1-style LRMs. Unlike traditional Large Language Models (LLMs), these models enhance logical deduction and decision-making capabilities during reasoning by incorporating mechanisms such as long chain-of-thought and self-reflection through reinforcement learning. However, with the widespread application of these models, the problem of overthinking has gradually emerged. Specifically, when generating answers, these models often construct excessively long reasoning chains with redundant or repetitive steps, which leads to reduced reasoning efficiency and may affect the accuracy of the final answer. To this end, various efficient reasoning methods have been proposed, aiming to reduce the length of reasoning paths without compromising model performance and reasoning capability. By reviewing the current research advancements in the field of efficient reasoning methods systematically, we categorize existing works into two main directions based on the lens of single-model optimization versus model collaboration: (1) Efficient Reasoning with Single Model, which focuses on improving the reasoning efficiency of individual models; and (2) Efficient Reasoning with Model Collaboration, which explores optimizing reasoning paths through collaboration among multiple models. Besides, we maintain a public GitHub repository that tracks the latest progress in efficient reasoning methods.

[Arxiv](https://arxiv.org/abs/2508.02120)