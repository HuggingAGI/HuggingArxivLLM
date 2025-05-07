# 迈向更有效的网络攻击技术识别：基于大型语言模型的网络威胁情报分析

发布时间：2025年05月05日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（如Llama2）在网络安全威胁情报提取中的应用，评估了其性能并提出改进方法。研究重点在于LLM的实际应用，而非理论或架构，因此归类为LLM应用。` `网络安全` `威胁情报`

> Towards Effective Identification of Attack Techniques in Cyber Threat Intelligence Reports using Large Language Models

# 摘要

> 本研究基于 MITRE ATT&CK 框架，评估了网络威胁情报 (CTI) 提取方法在识别网络威胁报告中攻击技术的性能。我们分析了四种配置，这些配置利用了包括威胁报告 ATT&CK 映射器 (TRAM) 和开源大型语言模型 (LLMs) 如 Llama2 在内的先进工具。研究发现，类别不平衡、过拟合和领域特定复杂性等重大挑战阻碍了技术提取的准确性。为了解决这些问题，我们提出了一种两步工作流程：首先由大型语言模型总结报告，然后通过重新训练的 SciBERT 模型处理经过重新平衡和 LLM 数据增强的数据集。这种方法显著提升了 F1 分数，其中多种攻击技术的 F1 分数超过了 0.90。我们的研究提高了基于网络的 CTI 系统效率，支持了互联数字环境中协作的网络安全运营，为未来整合人机协作平台的研究奠定了基础。

> This work evaluates the performance of Cyber Threat Intelligence (CTI) extraction methods in identifying attack techniques from threat reports available on the web using the MITRE ATT&CK framework. We analyse four configurations utilising state-of-the-art tools, including the Threat Report ATT&CK Mapper (TRAM) and open-source Large Language Models (LLMs) such as Llama2. Our findings reveal significant challenges, including class imbalance, overfitting, and domain-specific complexity, which impede accurate technique extraction. To mitigate these issues, we propose a novel two-step pipeline: first, an LLM summarises the reports, and second, a retrained SciBERT model processes a rebalanced dataset augmented with LLM-generated data. This approach achieves an improvement in F1-scores compared to baseline models, with several attack techniques surpassing an F1-score of 0.90. Our contributions enhance the efficiency of web-based CTI systems and support collaborative cybersecurity operations in an interconnected digital landscape, paving the way for future research on integrating human-AI collaboration platforms.

[Arxiv](https://arxiv.org/abs/2505.03147)