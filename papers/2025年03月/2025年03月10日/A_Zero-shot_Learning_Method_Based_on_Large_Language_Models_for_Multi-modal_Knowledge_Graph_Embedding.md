# 一种基于大型语言模型的多模态知识图谱嵌入零样本学习方法

发布时间：2025年03月10日

`LLM应用

理由：这篇论文提出了一种基于大型语言模型（LLMs）的零样本学习框架，用于解决多模态知识图谱中未见类别的语义信息转移问题。它展示了LLMs在零样本学习任务中的应用，属于LLM应用的范畴。` `机器学习` `知识图谱`

> A Zero-shot Learning Method Based on Large Language Models for Multi-modal Knowledge Graph Embedding

# 摘要

> 零样本学习（ZL）在自然语言处理、图像分类和跨语言迁移等涉及未见类别的任务中至关重要。然而，现有应用在处理涉及未见类别的新关系或实体时往往表现不佳，这严重限制了其在开放领域场景中的扩展性和实用性。针对多模态知识图谱（MMKG）嵌入表示学习中未见类别语义信息转移的挑战，本文提出了一种基于大型语言模型（LLMs）的零样本学习框架ZSLLM。我们利用未见类别的文本模态信息作为提示，充分挖掘LLMs的推理能力，实现未见类别跨模态语义信息的高效转移。通过模型学习，MMKG中未见类别的嵌入表示得到显著提升。在多个真实数据集上的广泛实验表明，我们的方法在性能上优于现有最优方法。

> Zero-shot learning (ZL) is crucial for tasks involving unseen categories, such as natural language processing, image classification, and cross-lingual transfer. Current applications often fail to accurately infer and handle new relations or entities involving unseen categories, severely limiting their scalability and practicality in open-domain scenarios. ZL learning faces the challenge of effectively transferring semantic information of unseen categories in multi-modal knowledge graph (MMKG) embedding representation learning. In this paper, we propose ZSLLM, a framework for zero-shot embedding learning of MMKGs using large language models (LLMs). We leverage textual modality information of unseen categories as prompts to fully utilize the reasoning capabilities of LLMs, enabling semantic information transfer across different modalities for unseen categories. Through model-based learning, the embedding representation of unseen categories in MMKG is enhanced. Extensive experiments conducted on multiple real-world datasets demonstrate the superiority of our approach compared to state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2503.07202)