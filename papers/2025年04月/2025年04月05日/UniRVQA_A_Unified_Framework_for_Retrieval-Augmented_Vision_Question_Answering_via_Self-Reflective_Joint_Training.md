# UniRVQA：基于自我反思联合训练的统一检索增强视觉问答框架

发布时间：2025年04月05日

`其他` `视觉问答` `知识图谱`

> UniRVQA: A Unified Framework for Retrieval-Augmented Vision Question Answering via Self-Reflective Joint Training

# 摘要

> 知识图谱视觉问答系统（KB-VQA）能够处理需要结合外部知识的复杂视觉问答任务。现有方法通常采用分离式框架处理检索与生成，这种设计可能导致性能瓶颈。多模态信息整合是另一个关键挑战。通用多模态预训练模型在细粒度知识检索方面表现有限，而专用模型虽有效但计算成本高昂。为此，我们提出了一种统一增强的视觉问答框架（UniRVQA）。该框架通过统一设计实现跨任务知识共享，扩展多模态表示学习能力。我们引入反思式回答机制，帮助模型优化知识边界，并将晚期交互整合到联合训练中，提升细粒度理解能力。实验表明，UniRVQA在问答准确率上显著提升4.7%，并使基础模型的VQA性能平均提升7.5%，展现出强大的竞争力。

> Knowledge-based Vision Question Answering (KB-VQA) systems address complex visual-grounded questions requiring external knowledge, such as web-sourced encyclopedia articles. Existing methods often use sequential and separate frameworks for the retriever and the generator with limited parametric knowledge sharing. However, since both retrieval and generation tasks require accurate understanding of contextual and external information, such separation can potentially lead to suboptimal system performance. Another key challenge is the integration of multimodal information. General-purpose multimodal pre-trained models, while adept at multimodal representation learning, struggle with fine-grained retrieval required for knowledge-intensive visual questions. Recent specialized pre-trained models mitigate the issue, but are computationally expensive. To bridge the gap, we propose a Unified Retrieval-Augmented VQA framework (UniRVQA). UniRVQA adapts general multimodal pre-trained models for fine-grained knowledge-intensive tasks within a unified framework, enabling cross-task parametric knowledge sharing and the extension of existing multimodal representation learning capability. We further introduce a reflective-answering mechanism that allows the model to explicitly evaluate and refine its knowledge boundary. Additionally, we integrate late interaction into the retrieval-augmented generation joint training process to enhance fine-grained understanding of queries and documents. Our approach achieves competitive performance against state-of-the-art models, delivering a significant 4.7% improvement in answering accuracy, and brings an average 7.5% boost in base MLLMs' VQA performance.

[Arxiv](https://arxiv.org/abs/2504.04065)