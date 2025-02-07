# 通过对抗性领域对齐的医学多模态模型窃取攻击

发布时间：2025年02月04日

`LLM应用

理由：这篇论文主要讨论了医学多模态大型语言模型（MLLMs）在医疗系统中的应用，特别是放射学报告生成模型的使用。论文还提出了一种针对医学MLLMs的窃取攻击方法（ADA-STEAL），这属于对LLM在实际应用中的安全性和保护措施的研究。因此，这篇论文应归类为LLM应用。` `放射学`

> Medical Multimodal Model Stealing Attacks via Adversarial Domain Alignment

# 摘要

> # 摘要
医学多模态大型语言模型（MLLMs）正逐渐成为医疗系统的关键组成部分，助力医务人员进行决策和结果分析。放射学报告生成模型能够解读医学影像，从而减轻放射科医生的工作负担。由于医学数据稀缺且受隐私法规保护，医学MLLMs被视为宝贵的知识产权。然而，这些资产可能面临模型窃取的风险，攻击者试图通过黑盒访问复制其功能。目前，医学领域的模型窃取主要针对分类任务，但现有攻击对MLLMs无效。本文提出了一种名为对抗性领域对齐（ADA-STEAL）的攻击方法，这是首个针对医学MLLMs的窃取攻击。ADA-STEAL利用公开且广泛可用的自然图像，而非医学图像。我们证明，通过对抗性噪声进行数据增强足以弥合自然图像与受害者MLLM的领域特定分布之间的差距。在IU X-RAY和MIMIC-CXR放射学数据集上的实验表明，对抗性领域对齐使攻击者能够在无需访问医学数据的情况下窃取医学MLLM。

> Medical multimodal large language models (MLLMs) are becoming an instrumental part of healthcare systems, assisting medical personnel with decision making and results analysis. Models for radiology report generation are able to interpret medical imagery, thus reducing the workload of radiologists. As medical data is scarce and protected by privacy regulations, medical MLLMs represent valuable intellectual property. However, these assets are potentially vulnerable to model stealing, where attackers aim to replicate their functionality via black-box access. So far, model stealing for the medical domain has focused on classification; however, existing attacks are not effective against MLLMs. In this paper, we introduce Adversarial Domain Alignment (ADA-STEAL), the first stealing attack against medical MLLMs. ADA-STEAL relies on natural images, which are public and widely available, as opposed to their medical counterparts. We show that data augmentation with adversarial noise is sufficient to overcome the data distribution gap between natural images and the domain-specific distribution of the victim MLLM. Experiments on the IU X-RAY and MIMIC-CXR radiology datasets demonstrate that Adversarial Domain Alignment enables attackers to steal the medical MLLM without any access to medical data.

[Arxiv](https://arxiv.org/abs/2502.02438)