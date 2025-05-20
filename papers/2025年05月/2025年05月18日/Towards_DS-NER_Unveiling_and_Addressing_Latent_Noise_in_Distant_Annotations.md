# DS-NER：揭示并应对远程标注中的潜在噪声

发布时间：2025年05月18日

`LLM应用

理由：这篇论文探讨了大语言模型（LLM）在远程监督的命名实体识别（DS-NER）中的应用，特别是作为监督方法之一，讨论了其在数据标注和噪声处理中的应用效果。因此，它属于LLM应用类别。` `数据科学`

> Towards DS-NER: Unveiling and Addressing Latent Noise in Distant Annotations

# 摘要

> 远程监督的命名实体识别（DS-NER）作为一种廉价便捷的替代传统人工标注的方法，通过将文本与外部资源对齐实现了训练数据的自动化生成。尽管在噪声测量方法上付出了诸多努力，但很少有研究关注不同远程标注方法之间的潜在噪声分布。在本研究中，我们从两个方面探讨了DS-NER的有效性和鲁棒性：(1) 远程标注技术，涵盖传统基于规则的方法和创新的大语言模型监督方法；(2) 噪声评估，为此我们引入了一个全新的框架。该框架通过将挑战明确划分为未标注实体问题（UEP）和噪声实体问题（NEP），并为每个问题提供专门的解决方案，从而应对了这些挑战。我们的方法在源自三种不同数据源、涉及四种不同标注技术的八个真实远程监督数据集上取得了显著提升，证实了其优于当前最先进的方法。

> Distantly supervised named entity recognition (DS-NER) has emerged as a cheap and convenient alternative to traditional human annotation methods, enabling the automatic generation of training data by aligning text with external resources. Despite the many efforts in noise measurement methods, few works focus on the latent noise distribution between different distant annotation methods. In this work, we explore the effectiveness and robustness of DS-NER by two aspects: (1) distant annotation techniques, which encompasses both traditional rule-based methods and the innovative large language model supervision approach, and (2) noise assessment, for which we introduce a novel framework. This framework addresses the challenges by distinctly categorizing them into the unlabeled-entity problem (UEP) and the noisy-entity problem (NEP), subsequently providing specialized solutions for each. Our proposed method achieves significant improvements on eight real-world distant supervision datasets originating from three different data sources and involving four distinct annotation techniques, confirming its superiority over current state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2505.12454)