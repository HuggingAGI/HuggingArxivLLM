# 融合知识图谱与LLMs，提升零-shot视觉问答能力

发布时间：2025年01月22日

`LLM应用

**理由**：这篇论文主要探讨了如何结合知识图谱和大型语言模型（LLMs）来提升零样本视觉问答（ZS-VQA）的效果。虽然涉及知识图谱，但其核心是利用LLMs的强大理解能力来解读图像内容，并结合知识图谱进行信息扩展和连接。因此，这篇论文主要属于LLM应用领域。` `计算机视觉` `问答系统`

> Combining Knowledge Graph and LLMs for Enhanced Zero-shot Visual Question Answering

# 摘要

> 零样本视觉问答（ZS-VQA）是一个新兴的关键研究领域，旨在无需训练样本的情况下回答视觉问题。现有研究分别利用知识图谱或大型语言模型（LLMs）作为外部信息源，以帮助VQA模型理解图像和问题。然而，LLMs在准确解释问题含义方面存在困难，而知识图谱虽具有丰富的实体关系，却难以有效连接图像内容。本文提出了一种新颖的设计，结合知识图谱和LLMs进行零样本视觉问答。我们利用LLMs的强大理解能力，通过战略性问题搜索机制准确解读图像内容，同时使用知识图谱扩展和连接用户查询与图像内容，以提升视觉问答效果。进一步采用优化算法确定不同信息源损失函数的最优权重，以获得全局最优的候选答案集。在两个基准数据集上的实验结果表明，我们的模型达到了最先进的（SOTA）性能。源代码和基准数据将公开发布。

> Zero-shot visual question answering (ZS-VQA), an emerged critical research area, intends to answer visual questions without providing training samples. Existing research in ZS-VQA has proposed to leverage knowledge graphs or large language models (LLMs), respectively, as external information sources to help VQA model comprehend images and questions. However, LLMs often struggle in accurately interpreting specific question meanings. Meanwhile, although knowledge graph has rich entity relationships, it is challenging to effectively connect entities to individual image content for visual question answers. In this paper, we propose a novel design to combine knowledge graph and LLMs for zero-shot visual question answer. Our approach uses LLMs' powerful understanding capabilities to accurately interpret image content through a strategic question search mechanism. Meanwhile, the knowledge graph is used to expand and connect users' queries to the image content for better visual question answering. An optimization algorithm is further used to determine the optimal weights for the loss functions derived from different information sources, towards a globally optimal set of candidate answers. Experimental results on two benchmark datasets demonstrate that our model achieves state-of-the-art (SOTA) performance. Both source code and benchmark data will be released for public access.

[Arxiv](https://arxiv.org/abs/2501.12697)