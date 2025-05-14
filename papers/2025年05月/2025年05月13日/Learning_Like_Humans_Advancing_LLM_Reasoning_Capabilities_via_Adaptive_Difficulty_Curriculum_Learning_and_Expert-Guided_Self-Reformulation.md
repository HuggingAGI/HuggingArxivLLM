# 像人类一样学习：利用自适应难度课程学习和专家引导的自我重组提升LLM推理能力

发布时间：2025年05月13日

`LLM理论` `数学教育`

> Learning Like Humans: Advancing LLM Reasoning Capabilities via Adaptive Difficulty Curriculum Learning and Expert-Guided Self-Reformulation

# 摘要

> 尽管在数学推理等领域取得了令人瞩目的进展，大型语言模型在持续解决复杂问题方面仍面临重大挑战。我们从关键的人类学习策略中汲取灵感，提出两种全新策略，旨在提升大型语言模型解决复杂问题的能力。首先，自适应难度课程学习（ADCL）是一种新型课程学习策略，它通过定期重新评估即将到来的数据批次的难度，以应对难度偏移现象（即模型在训练过程中对问题难度的感知动态变化），从而保持与模型不断发展的能力相匹配。其次，专家引导自我重新表述（EGSR）是一种新型强化学习策略，它通过引导模型在自己的概念框架内重新表述专家解决方案，而非依赖直接模仿，从而弥合了模仿学习与纯探索之间的差距，促进更深层次的理解和知识内化。基于Qwen2.5-7B模型，在具有挑战性的数学推理基准测试中进行了广泛实验，结果表明，这些受人类启发的策略协同作用显著提升了模型性能。值得注意的是，将这些策略结合使用，在AIME24基准上，性能比标准零样本强化学习基线提升了10%；在AIME25上，提升了16.6%。

> Despite impressive progress in areas like mathematical reasoning, large language models still face significant challenges in consistently solving complex problems. Drawing inspiration from key human learning strategies, we propose two novel strategies to enhance the capability of large language models to solve these complex problems. First, Adaptive Difficulty Curriculum Learning (ADCL) is a novel curriculum learning strategy that tackles the Difficulty Shift phenomenon (i.e., a model's perception of problem difficulty dynamically changes during training) by periodically re-estimating difficulty within upcoming data batches to maintain alignment with the model's evolving capabilities. Second, Expert-Guided Self-Reformulation (EGSR) is a novel reinforcement learning strategy that bridges the gap between imitation learning and pure exploration by guiding models to reformulate expert solutions within their own conceptual framework, rather than relying on direct imitation, fostering deeper understanding and knowledge assimilation. Extensive experiments on challenging mathematical reasoning benchmarks, using Qwen2.5-7B as the base model, demonstrate that these human-inspired strategies synergistically and significantly enhance performance. Notably, their combined application improves performance over the standard Zero-RL baseline by 10% on the AIME24 benchmark and 16.6% on AIME25.

[Arxiv](https://arxiv.org/abs/2505.08364)