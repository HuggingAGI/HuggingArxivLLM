# 检索反馈记忆增强的大型模型检索生成方法

发布时间：2025年08月25日

`RAG` `基础理论`

> Retrieval Feedback Memory Enhancement Large Model Retrieval Generation Method

# 摘要

> 大型语言模型（LLMs）虽在各类任务中表现卓越，却存在固有局限：参数化知识受限且重训练成本高昂。检索增强生成（RAG）则通过检索模型内部参数缺失的外部存储知识，对生成过程进行增强。但RAG方法仍面临挑战：多轮查询中易出现信息丢失与冗余检索，且难以精确刻画复杂任务的知识缺口。为此，我们提出检索反馈与记忆检索增强生成（RFM-RAG）：通过构建动态证据池，将传统方法的无状态检索升级为有状态的持续知识管理。具体而言，该方法通过问题中的关系三元组与动态证据池的证据生成优化查询，精准描述模型知识缺口；检索关键外部知识以迭代更新证据池；并借助R反馈模型评估证据完整性，直至收敛。相较于传统RAG方法，我们的方法可持久存储检索段落，并从段落中高效提炼关键信息，构建清晰的新查询。在三个公开问答基准数据集上的实验显示，RFM-RAG性能超越现有方法，显著提升了系统整体准确率。

> Large Language Models (LLMs) have shown remarkable capabilities across diverse tasks, yet they face inherent limitations such as constrained parametric knowledge and high retraining costs. Retrieval-Augmented Generation (RAG) augments the generation process by retrieving externally stored knowledge absent from the models internal parameters. However, RAG methods face challenges such as information loss and redundant retrievals during multi-round queries, accompanying the difficulties in precisely characterizing knowledge gaps for complex tasks. To address these problems, we propose Retrieval Feedback and Memory Retrieval Augmented Generation(RFM-RAG), which transforms the stateless retrieval of previous methods into stateful continuous knowledge management by constructing a dynamic evidence pool. Specifically, our method generates refined queries describing the models knowledge gaps using relational triples from questions and evidence from the dynamic evidence pool; Retrieves critical external knowledge to iteratively update this evidence pool; Employs a R-Feedback Model to evaluate evidence completeness until convergence. Compared to traditional RAG methods, our approach enables persistent storage of retrieved passages and effectively distills key information from passages to construct clearly new queries. Experiments on three public QA benchmarks demonstrate that RFM-RAG outperforms previous methods and improves overall system accuracy.

[Arxiv](https://arxiv.org/abs/2508.17862)