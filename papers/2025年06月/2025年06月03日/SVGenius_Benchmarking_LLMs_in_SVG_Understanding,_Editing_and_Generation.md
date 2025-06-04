# SVGenius：评测LLMs在SVG理解、编辑与生成能力的基准测试

发布时间：2025年06月03日

`LLM应用` `矢量图形` `自动化设计`

> SVGenius: Benchmarking LLMs in SVG Understanding, Editing and Generation

# 摘要

> 大型语言模型（LLMs）和多模态LLMs在SVG处理方面展现出巨大潜力，但现有基准测试存在三大不足：现实场景覆盖有限、缺乏复杂度分层、评估范式分散。为此，我们推出了SVGenius，一个全面的基准测试框架，包含理解、编辑和生成三个递进维度，总计2,377个查询。该框架基于24个真实应用场景的数据构建，通过8个任务类别和18个指标对模型性能进行系统性评估。我们对22种主流模型进行了全面测试，涵盖不同规模、架构、训练范式和访问级别。研究发现，专有模型的表现显著优于开源模型，但所有模型在处理复杂任务时均出现性能下降，这表明现有方法存在根本性局限。然而，增强推理能力的训练方式比单纯扩大模型规模更能有效突破这些限制，尽管风格迁移仍是所有模型面临的最大挑战。SVGenius作为首个系统化的SVG处理评估框架，为开发更强大的矢量图形模型和推动自动化图形设计应用提供了重要参考。附录和补充材料（包括所有数据和代码）可在https://zju-real.github.io/SVGenius获取。

> Large Language Models (LLMs) and Multimodal LLMs have shown promising capabilities for SVG processing, yet existing benchmarks suffer from limited real-world coverage, lack of complexity stratification, and fragmented evaluation paradigms. We introduce SVGenius, a comprehensive benchmark comprising 2,377 queries across three progressive dimensions: understanding, editing, and generation. Built on real-world data from 24 application domains with systematic complexity stratification, SVGenius evaluates models through 8 task categories and 18 metrics. We assess 22 mainstream models spanning different scales, architectures, training paradigms, and accessibility levels. Our analysis reveals that while proprietary models significantly outperform open-source counterparts, all models exhibit systematic performance degradation with increasing complexity, indicating fundamental limitations in current approaches; however, reasoning-enhanced training proves more effective than pure scaling for overcoming these limitations, though style transfer remains the most challenging capability across all model types. SVGenius establishes the first systematic evaluation framework for SVG processing, providing crucial insights for developing more capable vector graphics models and advancing automated graphic design applications. Appendix and supplementary materials (including all data and code) are available at https://zju-real.github.io/SVGenius.

[Arxiv](https://arxiv.org/abs/2506.03139)