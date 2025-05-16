# CL-RAG：通过课程学习架起检索增强生成的桥梁

发布时间：2025年05月15日

`RAG` `问答系统`

> CL-RAG: Bridging the Gap in Retrieval-Augmented Generation with Curriculum Learning

# 摘要

> 检索增强生成（RAG）是一种提升大型语言模型（LLMs）能力的有效方法。现有方法主要通过直接利用检索到的前k个文档来优化RAG系统中的检索器或生成器。然而，不同用户查询下文档的有效性差异显著，有些提供有价值的知识，而另一些则完全缺乏关键信息，这阻碍了检索器和生成器在训练中的适应性。受人类认知学习启发，课程学习通过从简单到困难的样本逐步训练模型，从而提升其泛化能力。我们将这一有效范式整合到RAG系统的训练中。本文提出了一种基于课程学习的多阶段RAG系统训练框架，名为CL-RAG。我们首先分别通过样本演化构建了适用于检索器和生成器的多难度级别训练数据。然后，基于课程学习方法分阶段训练模型，从而更有效地优化RAG系统的整体性能和泛化能力。我们的CL-RAG框架在四个开放领域问答数据集上表现一致有效，相较于多种先进方法，性能提升了2%到4%。

> Retrieval-Augmented Generation (RAG) is an effective method to enhance the capabilities of large language models (LLMs). Existing methods focus on optimizing the retriever or generator in the RAG system by directly utilizing the top-k retrieved documents. However, the documents effectiveness are various significantly across user queries, i.e. some documents provide valuable knowledge while others totally lack critical information. It hinders the retriever and generator's adaptation during training. Inspired by human cognitive learning, curriculum learning trains models using samples progressing from easy to difficult, thus enhancing their generalization ability, and we integrate this effective paradigm to the training of the RAG system. In this paper, we propose a multi-stage Curriculum Learning based RAG system training framework, named CL-RAG. We first construct training data with multiple difficulty levels for the retriever and generator separately through sample evolution. Then, we train the model in stages based on the curriculum learning approach, thereby optimizing the overall performance and generalization of the RAG system more effectively. Our CL-RAG framework demonstrates consistent effectiveness across four open-domain QA datasets, achieving performance gains of 2% to 4% over multiple advanced methods.

[Arxiv](https://arxiv.org/abs/2505.10493)