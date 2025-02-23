# # 解锁电子健康记录中的多模态整合潜力：一种基于提示学习框架实现语言与时间序列融合的方法

发布时间：2025年02月19日

`LLM应用` `计算机视觉`

> Unlocking Multimodal Integration in EHRs: A Prompt Learning Framework for Language and Time Series Fusion

# 摘要

> 大型语言模型（LLMs）在视觉-语言任务中表现优异，但在医学领域的应用尚不广泛，特别是在整合结构化时间序列数据与非结构化临床记录方面。临床实践中，动态时间序列数据如实验室检测结果能捕捉关键时间模式，而临床记录则提供丰富的语义背景。然而，整合这些模态极具挑战性，因为连续信号与离散文本之间存在本质差异。为解决这一难题，我们提出了ProMedTS，这是一个创新的自监督多模态框架，通过提示引导学习统一这些异质数据类型。我们的方法利用轻量级异常检测生成异常描述，作为提示引导原始时间序列数据编码为信息嵌入。这些嵌入在共享潜在空间中与文本表示对齐，同时保留精细的时间细节和语义洞察。此外，我们的框架集成了定制的自监督目标，以增强跨模态与跨模态对齐。我们通过真实世界数据集在疾病诊断任务上评估ProMedTS，结果表明我们的方法始终优于现有最优方法。

> Large language models (LLMs) have shown remarkable performance in vision-language tasks, but their application in the medical field remains underexplored, particularly for integrating structured time series data with unstructured clinical notes. In clinical practice, dynamic time series data such as lab test results capture critical temporal patterns, while clinical notes provide rich semantic context. Merging these modalities is challenging due to the inherent differences between continuous signals and discrete text. To bridge this gap, we introduce ProMedTS, a novel self-supervised multimodal framework that employs prompt-guided learning to unify these heterogeneous data types. Our approach leverages lightweight anomaly detection to generate anomaly captions that serve as prompts, guiding the encoding of raw time series data into informative embeddings. These embeddings are aligned with textual representations in a shared latent space, preserving fine-grained temporal nuances alongside semantic insights. Furthermore, our framework incorporates tailored self-supervised objectives to enhance both intra- and inter-modal alignment. We evaluate ProMedTS on disease diagnosis tasks using real-world datasets, and the results demonstrate that our method consistently outperforms state-of-the-art approaches.

[Arxiv](https://arxiv.org/abs/2502.13509)