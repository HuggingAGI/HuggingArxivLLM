# 金融风洞：检索增强的市场模拟器

发布时间：2025年03月22日

`RAG` `市场模拟`

> Financial Wind Tunnel: A Retrieval-Augmented Market Simulator

# 摘要

> 市场模拟器致力于生成高质量的合成金融数据，这些数据能够精准模仿现实市场的动态变化，这对模型开发和性能评估至关重要。尽管模拟技术不断进步，现有框架通常只能在特定任务中表现出色，而市场波动却在规模和来源上各不相同。为了解决这一难题，我们推出了金融风洞（FWT），一个检索增强型市场模拟器，旨在为模型测试生成可控、合理且灵活的市场动态。FWT在不同数据频率下展现出全面而系统的生成能力。通过检索方法提取横截面信息作为增强条件，我们的基于扩散的模拟器能够将宏观与微观市场模式无缝融合。此外，FWT框架支持广泛的模拟控制，包括通过“如果-那么”提示进行因果生成，或合成前所未有的跨市场趋势。我们还开发了一个自动优化器，利用FWT模拟场景的压力测试，帮助下游定量模型在控制风险的同时提升收益。实验结果表明，我们的方法不仅实现了通用且可靠的市场模拟，还显著提升了下游模型在复杂多变市场环境中的性能和适应性。我们的代码和数据样本可在https://anonymous.4open.science/r/fwt_-E852获取。

> Market simulator tries to create high-quality synthetic financial data that mimics real-world market dynamics, which is crucial for model development and robust assessment. Despite continuous advancements in simulation methodologies, market fluctuations vary in terms of scale and sources, but existing frameworks often excel in only specific tasks. To address this challenge, we propose Financial Wind Tunnel (FWT), a retrieval-augmented market simulator designed to generate controllable, reasonable, and adaptable market dynamics for model testing. FWT offers a more comprehensive and systematic generative capability across different data frequencies. By leveraging a retrieval method to discover cross-sectional information as the augmented condition, our diffusion-based simulator seamlessly integrates both macro- and micro-level market patterns. Furthermore, our framework allows the simulation to be controlled with wide applicability, including causal generation through "what-if" prompts or unprecedented cross-market trend synthesis. Additionally, we develop an automated optimizer for downstream quantitative models, using stress testing of simulated scenarios via FWT to enhance returns while controlling risks. Experimental results demonstrate that our approach enables the generalizable and reliable market simulation, significantly improve the performance and adaptability of downstream models, particularly in highly complex and volatile market conditions. Our code and data sample is available at https://anonymous.4open.science/r/fwt_-E852

[Arxiv](https://arxiv.org/abs/2503.17909)