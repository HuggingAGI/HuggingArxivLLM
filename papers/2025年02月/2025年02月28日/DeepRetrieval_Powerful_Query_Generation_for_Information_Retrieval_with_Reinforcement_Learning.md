# DeepRetrieval：基于强化学习的信息检索强大查询生成

发布时间：2025年02月28日

`LLM应用` `信息检索` `出版物`

> DeepRetrieval: Powerful Query Generation for Information Retrieval with Reinforcement Learning

# 摘要

> 信息检索系统是高效访问大规模文档集合的关键。近年来，研究者们开始利用大型语言模型（LLMs）通过查询增强来提升检索性能，但这些方法往往依赖于昂贵的监督学习或蒸馏技术，这些技术需要大量的计算资源和人工标注的数据。本文中，我们介绍了DeepRetrieval，这是一种基于强化学习的新颖方法，它通过试错直接训练LLMs进行查询增强，而无需监督数据。通过将检索召回率作为奖励信号，我们的系统学会了生成能够最大化文档检索性能的有效查询。初步实验结果表明，DeepRetrieval显著优于现有的最先进的方法，包括最近的LEADS系统，在出版物搜索和临床试验搜索任务中分别达到了60.82%和70.84%的召回率，同时使用了更小的模型（30亿参数 vs. 70亿参数）且无需监督数据。这些结果表明，我们的强化学习方法为信息检索提供了一种更高效且有效的范式，可能改变文档检索系统的格局。代码可在https://github.com/pat-jj/DeepRetrieval获取。

> Information retrieval systems are crucial for enabling effective access to large document collections. Recent approaches have leveraged Large Language Models (LLMs) to enhance retrieval performance through query augmentation, but often rely on expensive supervised learning or distillation techniques that require significant computational resources and hand-labeled data. In this paper, we introduce DeepRetrieval, a novel reinforcement learning-based approach that trains LLMs to perform query augmentation directly through trial and error, without requiring supervised data. By using the retrieval recall as a reward signal, our system learns to generate effective queries that maximize document retrieval performance. Our preliminary results demonstrate that DeepRetrieval significantly outperforms existing state-of-the-art methods, including the recent LEADS system, achieving 60.82\% recall on publication search and 70.84\% recall on trial search tasks while using a smaller model (3B vs. 7B parameters) and requiring no supervision data. These results suggest that our reinforcement learning approach offers a more efficient and effective paradigm for information retrieval, potentially changing the landscape of document retrieval systems. code is available at https://github.com/pat-jj/DeepRetrieval.

[Arxiv](https://arxiv.org/abs/2503.00223)