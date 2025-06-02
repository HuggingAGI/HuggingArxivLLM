# 在层次化视觉理解方面，视觉大语言模型的表现不尽如人意，而大语言模型本身成为了性能瓶颈。

发布时间：2025年05月30日

`LLM应用` `视觉问答` `计算机视觉`

> Vision LLMs Are Bad at Hierarchical Visual Understanding, and LLMs Are the Bottleneck

# 摘要

> 本文发现，当前先进的大型语言模型（LLMs）普遍缺乏对视觉世界的层次化认知，甚至对已确立的生物分类体系也知之甚少。这一局限性使得LLMs成为视觉LLMs实现层次化视觉理解的瓶颈——例如，它们可以识别海葵鱼，但却无法理解脊椎动物这一更广泛的类别。我们的研究基于约一百万个四选一视觉问答（VQA）任务，这些任务整合了六个分类体系和四个图像数据集。有趣的是，当使用这些VQA任务对视觉LLM进行微调时，我们发现LLMs的瓶颈效应依然显著：VQA任务的改进更多体现在提升LLM的层次化一致性上，而非直接增强视觉LLM的能力。我们推测，只有当LLMs掌握了相应的分类知识时，视觉LLMs才能真正实现对视觉概念的完整层次化理解。

> This paper reveals that many state-of-the-art large language models (LLMs) lack hierarchical knowledge about our visual world, unaware of even well-established biology taxonomies. This shortcoming makes LLMs a bottleneck for vision LLMs' hierarchical visual understanding (e.g., recognizing Anemone Fish but not Vertebrate). We arrive at these findings using about one million four-choice visual question answering (VQA) tasks constructed from six taxonomies and four image datasets. Interestingly, finetuning a vision LLM using our VQA tasks reaffirms LLMs' bottleneck effect to some extent because the VQA tasks improve the LLM's hierarchical consistency more than the vision LLM's. We conjecture that one cannot make vision LLMs understand visual concepts fully hierarchical until LLMs possess corresponding taxonomy knowledge.

[Arxiv](https://arxiv.org/abs/2505.24840)