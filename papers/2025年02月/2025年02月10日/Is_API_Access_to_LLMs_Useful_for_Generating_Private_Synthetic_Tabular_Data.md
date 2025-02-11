# # API能否助力大型语言模型生成私有合成表格数据？

发布时间：2025年02月10日

`LLM应用

摘要中提到，论文探讨了如何利用大型语言模型（LLMs）生成满足差分隐私的合成数据，并提出了一种仅需API访问基础模型的方法。这属于LLM的应用层面，因为研究的重点是将LLMs应用于数据生成任务，并优化其性能。虽然涉及算法改进，但核心是应用。因此，归类为LLM应用。` `数据隐私`

> Is API Access to LLMs Useful for Generating Private Synthetic Tabular Data?

# 摘要

> 差分隐私（DP）合成数据是分析私有数据的得力工具。大型语言模型（LLMs）的突破性进展激发了多种提升差分隐私合成数据生成的算法技术。其中一类方法采用差分隐私微调技术优化基础模型权重，但最先进的模型权重往往不对外开放。本研究提出两种仅需API访问基础模型的差分隐私合成表格数据算法。我们对专为图像和文本数据设计的Private Evolution算法（Lin et al., 2023; Xie et al., 2024）进行了适应性调整，成功将其扩展至表格数据领域。在扩展Private Evolution的过程中，我们引入了一种基于查询负载的距离度量方法，这一创新可能具有独立的研究价值。我们提出了一组仅需单次API调用LLMs的算法，而非反复查询模型。研究发现，与无需API访问的现有基线相比，强大的LLMs API访问并不总是能显著提升差分隐私合成数据的质量。我们深入剖析了这一现象背后的原因，并提出了改进LLMs的建议，以期使其在这一应用场景中发挥更大的潜力。

> Differentially private (DP) synthetic data is a versatile tool for enabling the analysis of private data. Recent advancements in large language models (LLMs) have inspired a number of algorithm techniques for improving DP synthetic data generation. One family of approaches uses DP finetuning on the foundation model weights; however, the model weights for state-of-the-art models may not be public. In this work we propose two DP synthetic tabular data algorithms that only require API access to the foundation model. We adapt the Private Evolution algorithm (Lin et al., 2023; Xie et al., 2024) -- which was designed for image and text data -- to the tabular data domain. In our extension of Private Evolution, we define a query workload-based distance measure, which may be of independent interest. We propose a family of algorithms that use one-shot API access to LLMs, rather than adaptive queries to the LLM. Our findings reveal that API-access to powerful LLMs does not always improve the quality of DP synthetic data compared to established baselines that operate without such access. We provide insights into the underlying reasons and propose improvements to LLMs that could make them more effective for this application.

[Arxiv](https://arxiv.org/abs/2502.06555)