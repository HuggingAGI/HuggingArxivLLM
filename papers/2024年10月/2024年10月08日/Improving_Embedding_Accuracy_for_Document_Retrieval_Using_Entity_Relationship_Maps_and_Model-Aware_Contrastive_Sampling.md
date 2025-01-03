# 提升文档检索嵌入精度：基于实体关系图与模型感知对比采样

发布时间：2024年10月08日

`RAG

理由：这篇论文介绍了一个专门为文档检索增强生成（RAG）任务设计的模型APEX-Embedding-7B，并详细描述了其训练技术和性能提升。RAG任务的核心是通过检索增强生成，结合检索和生成模型来提高文本生成的质量和准确性。因此，这篇论文明显属于RAG分类。` `信息检索`

> Improving Embedding Accuracy for Document Retrieval Using Entity Relationship Maps and Model-Aware Contrastive Sampling

# 摘要

> 本文介绍了APEX-Embedding-7B（高级认知提取处理），一个70亿参数的仅解码器文本特征提取模型，专为文档检索增强生成（RAG）任务设计。我们采用两种训练技术显著提升了事实聚焦能力：（1）使用结构化实体关系图进行预收敛中断微调，引导模型关注事实而非语义风格，从而增强纯文本性能；（2）模型感知对比采样，基于基础模型能力生成平衡的硬负样本和软负样本整理图。这一组合方法大幅提升了纯文本查询/文档对的检索性能，rank@1准确率达到90.86%（比次优模型提高6.26%），并将训练数据输入上下文大小平均减少37.71%。我们的模型在长上下文文档检索任务的文本特征提取领域树立了新的标杆。

> In this paper we present APEX-Embedding-7B (Advanced Processing for Epistemic eXtraction), a 7-billion parameter decoder-only text Feature Extraction Model, specifically designed for Document Retrieval-Augmented Generation (RAG) tasks. Our approach employs two training techniques that yield an emergent improvement in factual focus: (1) Pre-convergence interrupted fine-tuning using Structured Entity Relationship Maps as training data input: designed to shift the model's attention and create a bias towards factual content rather than semantic style - this enhances plain text performance despite not being directly trained for it; and (2) Model-Aware Contrastive Sampling, creating a balanced and evenly distributed collation map of hard and soft negatives directly informed by the base model's competency. This combined methodology yields significant improvements, enhancing plain text query/document pair retrieval to achieve an absolute rank@1 accuracy of 90.86% (an increase of 6.26% compared to the next leading model) in our evaluation, and reducing training data input context size by an average of 37.71% compared to plain text for both queries and document texts. Based on our evaluations, our model establishes a new state-of-the-art standard in text feature extraction for longer context document retrieval tasks.

[Arxiv](https://arxiv.org/abs/2410.18105)