# 范数增长与稳定性挑战在局部化顺序知识编辑中的

发布时间：2025年02月26日

`LLM理论` `人工智能`

> Norm Growth and Stability Challenges in Localized Sequential Knowledge Editing

# 摘要

> 本研究聚焦于大型语言模型（LLMs）的局部更新，特别是在知识编辑任务中的表现。知识编辑旨在在不改变模型整体能力的前提下，整合或修改特定事实。我们发现，无论是持续预训练、全微调还是基于LORA的微调，更新后的矩阵的Frobenius范数都会增加，这对局部知识编辑尤为不利，因为仅有一部分矩阵被更新。我们揭示了一种普遍现象：无论采用微调、基于超网络的方法还是定位与编辑方法，更新后的矩阵范数都会随着更新次数的增加而持续增长。这种增长会破坏模型的平衡，尤其是在仅更新部分矩阵的情况下，可能导致模型不稳定和下游性能下降。通过深入分析中间激活向量，我们发现内部激活的范数减少，且这些激活所占据的子空间发生了变化，这表明与未编辑的模型相比，这些激活向量现在占据了表示空间中完全不同的区域。本文揭示了持续和局部序列知识编辑的技术挑战及其对模型稳定性和实用性的影响。

> This study investigates the impact of localized updates to large language models (LLMs), specifically in the context of knowledge editing - a task aimed at incorporating or modifying specific facts without altering broader model capabilities. We first show that across different post-training interventions like continuous pre-training, full fine-tuning and LORA-based fine-tuning, the Frobenius norm of the updated matrices always increases. This increasing norm is especially detrimental for localized knowledge editing, where only a subset of matrices are updated in a model . We reveal a consistent phenomenon across various editing techniques, including fine-tuning, hypernetwork-based approaches, and locate-and-edit methods: the norm of the updated matrix invariably increases with successive updates. Such growth disrupts model balance, particularly when isolated matrices are updated while the rest of the model remains static, leading to potential instability and degradation of downstream performance. Upon deeper investigations of the intermediate activation vectors, we find that the norm of internal activations decreases and is accompanied by shifts in the subspaces occupied by these activations, which shows that these activation vectors now occupy completely different regions in the representation space compared to the unedited model. With our paper, we highlight the technical challenges with continuous and localized sequential knowledge editing and their implications for maintaining model stability and utility.

[Arxiv](https://arxiv.org/abs/2502.19416)