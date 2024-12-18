# RA-SGG：基于多原型学习的检索增强型场景图生成框架

发布时间：2024年12月17日

`其他` `计算机视觉` `图像识别`

> RA-SGG: Retrieval-Augmented Scene Graph Generation Framework via Multi-Prototype Learning

# 摘要

> 场景图生成（SGG）研究面临两大基本难题：谓词的长尾分布以及谓词间的语义模糊性。这使得 SGG 模型倾向于头部谓词，偏爱占主导的通用谓词，而忽视了细粒度谓词。在本文中，我们将 SGG 视为带有部分标注的多标签分类问题来应对这些挑战，其中细粒度谓词的相关标签缺失。在此新框架下，我们提出了检索增强场景图生成（RA-SGG），它能识别可能需要多标签的潜在实例，并通过从已建立的存储库中检索相关样本，用与原始标签语义相近的多标签丰富单标签。基于增强关系（即发现的多标签），我们采用多原型学习来训练 SGG 模型。多项综合实验表明，RA-SGG 在 VG 上比最先进的基线高出 3.6%，在 GQA 上高出 5.9%，尤其在 F@K 方面，这表明 RA-SGG 有效缓解了由谓词的长尾分布和语义歧义导致的预测偏差问题。

> Scene Graph Generation (SGG) research has suffered from two fundamental challenges: the long-tailed predicate distribution and semantic ambiguity between predicates. These challenges lead to a bias towards head predicates in SGG models, favoring dominant general predicates while overlooking fine-grained predicates. In this paper, we address the challenges of SGG by framing it as multi-label classification problem with partial annotation, where relevant labels of fine-grained predicates are missing. Under the new frame, we propose Retrieval-Augmented Scene Graph Generation (RA-SGG), which identifies potential instances to be multi-labeled and enriches the single-label with multi-labels that are semantically similar to the original label by retrieving relevant samples from our established memory bank. Based on augmented relations (i.e., discovered multi-labels), we apply multi-prototype learning to train our SGG model. Several comprehensive experiments have demonstrated that RA-SGG outperforms state-of-the-art baselines by up to 3.6% on VG and 5.9% on GQA, particularly in terms of F@K, showing that RA-SGG effectively alleviates the issue of biased prediction caused by the long-tailed distribution and semantic ambiguity of predicates.

[Arxiv](https://arxiv.org/abs/2412.12788)