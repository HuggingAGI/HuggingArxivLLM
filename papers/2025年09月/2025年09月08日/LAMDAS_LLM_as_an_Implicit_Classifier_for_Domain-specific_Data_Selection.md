# LAMDAS：LLM作为领域特定数据选择的隐式分类器

发布时间：2025年09月08日

`LLM应用` `基础理论`

> LAMDAS: LLM as an Implicit Classifier for Domain-specific Data Selection

# 摘要

> 要让大型语言模型（LLMs）适配特定领域，常常会遇到一个关键瓶颈：高质量人工标注数据的稀缺。虽然海量未经筛选的数据唾手可得，但盲目用于微调反而可能引入噪声、降低性能。因此，数据的策略性筛选至关重要，亟需一套既精准又高效的方案。现有方法可分为基于相似性和直接优化两类，但均难以兼顾这些要求。本文提出了LAMDAS（LLM As an iMplicit classifier for domain-specific DAta Selection）——一种新颖方法，它将预训练LLM自身用作隐式分类器，从而省去了显式特征工程和计算密集型优化步骤。LAMDAS将数据选择重构为一类分类问题，旨在识别出“归属于”小型参考数据集所定义目标领域的候选数据。大量实验证实，LAMDAS仅用少量数据就超越了全量数据训练的性能，且在多种场景下均优于九个最先进（SOTA）基线模型。此外，与所有评估基线相比，LAMDAS在性能提升与计算效率间取得了最理想的平衡。

> Adapting large language models (LLMs) to specific domains often faces a critical bottleneck: the scarcity of high-quality, human-curated data. While large volumes of unchecked data are readily available, indiscriminately using them for fine-tuning risks introducing noise and degrading performance. Strategic data selection is thus crucial, requiring a method that is both accurate and efficient. Existing approaches, categorized as similarity-based and direct optimization methods, struggle to simultaneously achieve these goals. In this paper, we introduce LAMDAS (LLM As an iMplicit classifier for domain-specific DAta Selection), a novel approach that leverages the pre-trained LLM itself as an implicit classifier, thereby bypassing explicit feature engineering and computationally intensive optimization process. LAMDAS reframes data selection as a one-class classification problem, identifying candidate data that "belongs" to the target domain defined by a small reference dataset. Extensive experimental results demonstrate that LAMDAS not only exceeds the performance of full-data training using a fraction of the data but also outperforms nine state-of-the-art (SOTA) baselines under various scenarios. Furthermore, LAMDAS achieves the most compelling balance between performance gains and computational efficiency compared to all evaluated baselines.

[Arxiv](https://arxiv.org/abs/2509.06524)