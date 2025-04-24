# 语言模型中对称性与反对称性的捕捉：基于对称性感知的训练目标

发布时间：2025年04月22日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在关系推理方面的局限性，并提出了一种改进模型性能的方法。研究重点在于模型本身的改进和理解，属于LLM理论的范畴。` `知识图谱`

> Capturing Symmetry and Antisymmetry in Language Models through Symmetry-Aware Training Objectives

# 摘要

> 捕捉对称（如国家间的邻国关系）和反称（如parent_of）关系对众多应用至关重要。本文提出一个基于Wikidata的新型自然语言推理数据集，专为评估大型语言模型（LLMs）而设计。研究发现，LLMs在该基准测试中的表现与随机猜测不相上下，揭示了其在关系理解上的显著局限。为解决这一问题，我们采用对比学习结合k近邻方法对编码器进行重新训练。结果显示，重新训练后的编码器不仅在性能上媲美微调后的分类头，更在少样本学习效率和缓解灾难性遗忘方面展现出明显优势。

> Capturing symmetric (e.g., country borders another country) and antisymmetric (e.g., parent_of) relations is crucial for a variety of applications. This paper tackles this challenge by introducing a novel Wikidata-derived natural language inference dataset designed to evaluate large language models (LLMs). Our findings reveal that LLMs perform comparably to random chance on this benchmark, highlighting a gap in relational understanding. To address this, we explore encoder retraining via contrastive learning with k-nearest neighbors. The retrained encoder matches the performance of fine-tuned classification heads while offering additional benefits, including greater efficiency in few-shot learning and improved mitigation of catastrophic forgetting.

[Arxiv](https://arxiv.org/abs/2504.16312)