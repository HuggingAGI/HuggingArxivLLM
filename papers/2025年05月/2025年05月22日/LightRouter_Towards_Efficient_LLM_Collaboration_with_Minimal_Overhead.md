# LightRouter：致力于高效LLM协作，实现超低开销

发布时间：2025年05月22日

`LLM应用` `人工智能`

> LightRouter: Towards Efficient LLM Collaboration with Minimal Overhead

# 摘要

> 大型语言模型的快速发展在众多自然语言处理任务中展现了非凡的能力。然而，现有大型语言模型在成本、性能和计算需求方面的显著差异，为用户选择最适合特定任务的模型带来了巨大挑战。本研究提出了 LightRouter，一个创新框架，旨在从更大的模型池中系统地选择和整合少量大型语言模型，以实现任务性能和成本效率的双重优化。LightRouter 采用自适应选择机制，识别只需少量引导令牌的模型，从而降低成本，并结合有效的集成策略来整合模型输出。在多个基准上的广泛实验表明，LightRouter 不仅匹配甚至超越了广泛使用的集成基线，准确率提升了 25%。与领先的高性能模型相比，LightRouter 在保持相当性能的同时，将推理成本降低了 27%。值得注意的是，LightRouter 无需了解单个模型的先验知识，仅依赖于廉价、轻量级的模型。这项研究不仅为高效选择大型语言模型提供了一种实用的方法，还为模型组合的最优策略提供了有价值的见解。

> The rapid advancement of large language models has unlocked remarkable capabilities across a diverse array of natural language processing tasks. However, the considerable differences among available LLMs-in terms of cost, performance, and computational demands-pose significant challenges for users aiming to identify the most suitable model for specific tasks. In this work, we present LightRouter, a novel framework designed to systematically select and integrate a small subset of LLMs from a larger pool, with the objective of jointly optimizing both task performance and cost efficiency. LightRouter leverages an adaptive selection mechanism to identify models that require only a minimal number of boot tokens, thereby reducing costs, and further employs an effective integration strategy to combine their outputs. Extensive experiments across multiple benchmarks demonstrate that LightRouter matches or outperforms widely-used ensemble baselines, achieving up to a 25% improvement in accuracy. Compared with leading high-performing models, LightRouter achieves comparable performance while reducing inference costs by up to 27%. Importantly, our framework operates without any prior knowledge of individual models and relies exclusively on inexpensive, lightweight models. This work introduces a practical approach for efficient LLM selection and provides valuable insights into optimal strategies for model combination.

[Arxiv](https://arxiv.org/abs/2505.16221)