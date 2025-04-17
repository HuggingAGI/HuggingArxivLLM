# PATFinger: 专门设计用于对抗未经授权的多模态数据集使用的基于提示适应的可迁移指纹识别技术

发布时间：2025年04月15日

`LLM应用

摘要中讨论了多模态数据集的使用判定问题，并提出了一种名为PATFinger的新型提示适应性可转移指纹方案。该方案结合了全局最优扰动（GOP）和自适应提示，用于捕捉数据集特定的分布特征。通过这种方法，数据集所有者可以有效监控数据集的使用情况，尤其是在跨模态检索架构中。研究结果表明，PATFinger在检测未经授权的数据集使用方面表现出显著优势。该研究属于大型语言模型的实际应用，因此归类为LLM应用。` `多模态` `数据安全`

> PATFinger: Prompt-Adapted Transferable Fingerprinting against Unauthorized Multimodal Dataset Usage

# 摘要

> 多模态数据集通过提供跨模态语义，为预训练大规模视觉-语言模型提供了重要支持。然而，目前关于数据集使用的判定工作主要集中在单模态数据集的所有权验证，且多采用侵入性方法和非侵入性技术，而跨模态方法的探索仍显不足。侵入性方法虽能适应多模态数据集，却会对模型准确性造成损害；而非侵入性方法依赖于标签驱动的决策边界，难以确保验证过程中的稳定行为。针对这些问题，我们提出了一种名为PATFinger的新型提示适应性可转移指纹方案，该方案从无训练角度出发，结合全局最优扰动（GOP）和自适应提示，精准捕捉数据集特定的分布特征。与传统方法不同，PATFinger利用数据集的内在属性作为指纹，而非强制模型学习触发器。通过从样本分布中推导出的GOP，PATFinger能够最大化不同模态间的嵌入漂移。随后，方案通过将自适应提示与GOP样本重新对齐，深入捕捉精心设计的代理模型上的跨模态交互。这使得数据集所有者能够通过观察检索查询过程中与PATFinger相关联的特定预测行为，有效监控数据集的使用情况。实验结果表明，与现有方法相比，PATFinger在检测未经授权的多模态数据集使用方面表现出显著优势，其有效性在多种跨模态检索架构中提升了30%。

> The multimodal datasets can be leveraged to pre-train large-scale vision-language models by providing cross-modal semantics. Current endeavors for determining the usage of datasets mainly focus on single-modal dataset ownership verification through intrusive methods and non-intrusive techniques, while cross-modal approaches remain under-explored. Intrusive methods can adapt to multimodal datasets but degrade model accuracy, while non-intrusive methods rely on label-driven decision boundaries that fail to guarantee stable behaviors for verification. To address these issues, we propose a novel prompt-adapted transferable fingerprinting scheme from a training-free perspective, called PATFinger, which incorporates the global optimal perturbation (GOP) and the adaptive prompts to capture dataset-specific distribution characteristics. Our scheme utilizes inherent dataset attributes as fingerprints instead of compelling the model to learn triggers. The GOP is derived from the sample distribution to maximize embedding drifts between different modalities. Subsequently, our PATFinger re-aligns the adaptive prompt with GOP samples to capture the cross-modal interactions on the carefully crafted surrogate model. This allows the dataset owner to check the usage of datasets by observing specific prediction behaviors linked to the PATFinger during retrieval queries. Extensive experiments demonstrate the effectiveness of our scheme against unauthorized multimodal dataset usage on various cross-modal retrieval architectures by 30% over state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2504.11509)