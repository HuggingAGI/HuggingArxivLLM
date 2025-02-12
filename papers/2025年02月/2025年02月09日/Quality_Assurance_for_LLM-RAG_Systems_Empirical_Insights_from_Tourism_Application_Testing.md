# LLM-RAG系统的质量保障研究：从旅游应用测试中获得的实证见解

发布时间：2025年02月09日

`RAG` `推荐系统`

> Quality Assurance for LLM-RAG Systems: Empirical Insights from Tourism Application Testing

# 摘要

> 本文提出了一种全面的框架，用于测试和评估增强有检索增强生成（RAG）功能的大型语言模型（LLM）系统在旅游应用中的质量特性。通过系统性地对三种不同LLM变体在多个参数配置下进行实证评估，我们展示了我们的测试方法在评估功能正确性和非功能性属性方面的有效性。我们的框架实现了17个不同的指标，涵盖了通过LLM评委进行的句法分析、语义评估和行为评估。该研究揭示了不同架构选择和参数配置对系统性能的影响，特别强调了温度和top-p参数对响应质量的影响。测试是在Värmland地区的旅游推荐系统上进行的，采用了标准和RAG增强的配置。结果显示，较新的LLM版本在性能指标上显示出适度的改进，尽管这些差异在响应长度和复杂性上更为明显，而不是在语义质量上。这项研究为在LLM-RAG系统中实施稳健的测试实践提供了实用见解，为在生产环境中部署这些架构的组织提供了宝贵的指导。

> This paper presents a comprehensive framework for testing and evaluating quality characteristics of Large Language Model (LLM) systems enhanced with Retrieval-Augmented Generation (RAG) in tourism applications. Through systematic empirical evaluation of three different LLM variants across multiple parameter configurations, we demonstrate the effectiveness of our testing methodology in assessing both functional correctness and extra-functional properties. Our framework implements 17 distinct metrics that encompass syntactic analysis, semantic evaluation, and behavioral evaluation through LLM judges. The study reveals significant information about how different architectural choices and parameter configurations affect system performance, particularly highlighting the impact of temperature and top-p parameters on response quality. The tests were carried out on a tourism recommendation system for the Värmland region, utilizing standard and RAG-enhanced configurations. The results indicate that the newer LLM versions show modest improvements in performance metrics, though the differences are more pronounced in response length and complexity rather than in semantic quality. The research contributes practical insights for implementing robust testing practices in LLM-RAG systems, providing valuable guidance to organizations deploying these architectures in production environments.

[Arxiv](https://arxiv.org/abs/2502.05782)