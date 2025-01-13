# 跨模态检索中的深度可逆一致性学习

发布时间：2025年01月09日

`其他

理由：这篇论文主要讨论的是跨模态检索（CMR）和表示学习，提出了一种名为深度可逆一致性学习（DRCL）的新方法。虽然涉及多模态样本和表示学习，但并没有直接涉及Agent、RAG、LLM应用或LLM理论。因此，将其分类为“其他”更为合适。` `跨模态检索` `机器学习`

> Deep Reversible Consistency Learning for Cross-modal Retrieval

# 摘要

> # 摘要
跨模态检索（CMR）通常通过学习共同表示来直接衡量多模态样本间的相似性。现有方法大多假设多模态样本成对出现，并采用联合训练学习共同表示，限制了CMR的灵活性。尽管部分方法通过独立训练策略提升了CMR的灵活性，但它们依赖随机初始化的正交矩阵指导表示学习，假设类间样本彼此独立，限制了样本表示与真实标签间的语义对齐潜力。为此，我们提出了一种名为深度可逆一致性学习（DRCL）的新方法。DRCL包含两个核心模块：选择性先验学习（SPL）和可逆语义一致性学习（RSC）。具体而言，SPL首先在每个模态上学习变换权重矩阵，并根据质量评分选择最佳先验，避免盲目选择低质量模态的先验。随后，RSC通过模态不变表示重铸机制（MRR），利用先验的广义逆矩阵从样本语义标签中重铸潜在的模态不变表示。由于标签不含模态特定信息，我们利用重铸特征指导表示学习，最大程度保持语义一致性。此外，RSC引入特征增强机制（FA），鼓励模型在更广泛的数据分布上学习，提升多样性。最后，我们在五个常用数据集上进行了广泛实验，并与15个先进基线对比，验证了DRCL的有效性和优越性。

> Cross-modal retrieval (CMR) typically involves learning common representations to directly measure similarities between multimodal samples. Most existing CMR methods commonly assume multimodal samples in pairs and employ joint training to learn common representations, limiting the flexibility of CMR. Although some methods adopt independent training strategies for each modality to improve flexibility in CMR, they utilize the randomly initialized orthogonal matrices to guide representation learning, which is suboptimal since they assume inter-class samples are independent of each other, limiting the potential of semantic alignments between sample representations and ground-truth labels. To address these issues, we propose a novel method termed Deep Reversible Consistency Learning (DRCL) for cross-modal retrieval. DRCL includes two core modules, \ie Selective Prior Learning (SPL) and Reversible Semantic Consistency learning (RSC). More specifically, SPL first learns a transformation weight matrix on each modality and selects the best one based on the quality score as the Prior, which greatly avoids blind selection of priors learned from low-quality modalities. Then, RSC employs a Modality-invariant Representation Recasting mechanism (MRR) to recast the potential modality-invariant representations from sample semantic labels by the generalized inverse matrix of the prior. Since labels are devoid of modal-specific information, we utilize the recast features to guide the representation learning, thus maintaining semantic consistency to the fullest extent possible. In addition, a feature augmentation mechanism (FA) is introduced in RSC to encourage the model to learn over a wider data distribution for diversity. Finally, extensive experiments conducted on five widely used datasets and comparisons with 15 state-of-the-art baselines demonstrate the effectiveness and superiority of our DRCL.

[Arxiv](https://arxiv.org/abs/2501.05686)