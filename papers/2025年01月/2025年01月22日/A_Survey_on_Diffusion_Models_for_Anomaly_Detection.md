# 扩散模型在异常检测中的应用综述

发布时间：2025年01月22日

`其他

理由：这篇论文主要讨论的是扩散模型（DMs）在异常检测（AD）任务中的应用，特别是DMAD（用于异常检测的扩散模型）。虽然提到了与大型语言模型（LLM）的集成，但这并不是论文的核心内容。论文的重点在于扩散模型的应用和技术细节，因此更适合归类为“其他”，而不是与LLM直接相关的类别（如LLM应用、LLM理论、Agent或RAG）。` `网络安全` `异常检测`

> A Survey on Diffusion Models for Anomaly Detection

# 摘要

> # 摘要
扩散模型（DMs）作为一类强大的生成式AI模型，在网络安全、欺诈检测、医疗保健和制造等领域的异常检测（AD）任务中展现出巨大潜力。DMAD（用于异常检测的扩散模型）为识别复杂高维数据中的偏差提供了创新解决方案。本文系统回顾了DMAD研究的最新进展，探讨了其能力。我们首先介绍了AD和DMs的基本概念，随后深入分析了DDPMs、DDIMs和Score SDEs等经典DM架构。现有DMAD方法被分类为基于重建、基于密度和混合方法，并详细考察了其方法创新。我们还探讨了图像、时间序列、视频和多模态数据分析等多样化任务。此外，本文讨论了计算效率、模型可解释性、鲁棒性增强、边缘-云协作及与大型语言模型集成等关键挑战和新兴研究方向。DMAD研究论文和资源可在https://github.com/fdjingliu/DMAD获取。

> Diffusion models (DMs) have emerged as a powerful class of generative AI models, showing remarkable potential in anomaly detection (AD) tasks across various domains, such as cybersecurity, fraud detection, healthcare, and manufacturing. The intersection of these two fields, termed diffusion models for anomaly detection (DMAD), offers promising solutions for identifying deviations in increasingly complex and high-dimensional data. In this survey, we review recent advances in DMAD research. We begin by presenting the fundamental concepts of AD and DMs, followed by a comprehensive analysis of classic DM architectures including DDPMs, DDIMs, and Score SDEs. We further categorize existing DMAD methods into reconstruction-based, density-based, and hybrid approaches, providing detailed examinations of their methodological innovations. We also explore the diverse tasks across different data modalities, encompassing image, time series, video, and multimodal data analysis. Furthermore, we discuss critical challenges and emerging research directions, including computational efficiency, model interpretability, robustness enhancement, edge-cloud collaboration, and integration with large language models. The collection of DMAD research papers and resources is available at https://github.com/fdjingliu/DMAD.

[Arxiv](https://arxiv.org/abs/2501.11430)