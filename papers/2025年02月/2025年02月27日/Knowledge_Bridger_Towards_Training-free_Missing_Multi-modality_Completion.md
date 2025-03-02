# 知识桥接器：探索无需训练的多模态缺失内容补全

发布时间：2025年02月27日

`LLM应用` `知识图谱`

> Knowledge Bridger: Towards Training-free Missing Multi-modality Completion

# 摘要

> 传统方法在缺失模态补全问题上依赖于复杂的融合技术和大量完整数据的预训练，但这些方法在处理域外（OOD）场景时往往表现欠佳。本研究提出一个新挑战：能否开发出一种资源高效且具备强大 OOD 泛化能力的缺失模态补全模型？为此，我们推出了一种基于大语言多模态模型（LMMs）的无训练框架。我们的解决方案“Knowledge Bridger”采用模态无关的方法，巧妙结合了缺失模态的生成与排序。通过定义领域特定的先验知识，该方法能从现有模态中自动提取结构化信息，构建知识图谱。这些图谱借助 LMM 实现了生成和排序模块的无缝连接，从而生成高质量的缺失模态补全结果。实验结果表明，无论是在一般领域还是医学领域，我们的方法在 OOD 泛化方面均优于现有方案。此外，与直接使用 LMMs 进行生成和排序的方法相比，我们的知识驱动技术表现更优，这些洞察可能为其他领域的应用提供宝贵参考。

> Previous successful approaches to missing modality completion rely on carefully designed fusion techniques and extensive pre-training on complete data, which can limit their generalizability in out-of-domain (OOD) scenarios. In this study, we pose a new challenge: can we develop a missing modality completion model that is both resource-efficient and robust to OOD generalization? To address this, we present a training-free framework for missing modality completion that leverages large multimodal models (LMMs). Our approach, termed the "Knowledge Bridger", is modality-agnostic and integrates generation and ranking of missing modalities. By defining domain-specific priors, our method automatically extracts structured information from available modalities to construct knowledge graphs. These extracted graphs connect the missing modality generation and ranking modules through the LMM, resulting in high-quality imputations of missing modalities. Experimental results across both general and medical domains show that our approach consistently outperforms competing methods, including in OOD generalization. Additionally, our knowledge-driven generation and ranking techniques demonstrate superiority over variants that directly employ LMMs for generation and ranking, offering insights that may be valuable for applications in other domains.

[Arxiv](https://arxiv.org/abs/2502.19834)