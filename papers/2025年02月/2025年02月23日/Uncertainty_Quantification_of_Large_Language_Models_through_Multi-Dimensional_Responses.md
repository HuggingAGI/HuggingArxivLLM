# 基于多维度的响应，我们对大型语言模型的不确定性进行了量化分析。

发布时间：2025年02月23日

`LLM应用`

> Uncertainty Quantification of Large Language Models through Multi-Dimensional Responses

# 摘要

> 大型语言模型（LLMs）凭借其庞大的训练数据集和强大的transformer架构，在多个任务中表现出了卓越的能力。然而，LLMs响应的可靠性仍是一个待解决的问题。特别是在医疗、金融和决策等关键领域，LLMs的不确定性量化（UQ）显得尤为重要。现有的UQ方法主要关注语义相似性，却忽视了响应中蕴含的深层知识维度。我们提出了一种多维UQ框架，整合了语义和知识感知相似性分析。通过生成多个响应，并借助辅助LLMs提取隐性知识，我们构建了独立的相似性矩阵，并通过张量分解获得全面的不确定性表示。这种方法从语义和知识维度分离了重叠信息，捕捉到了语义变化和事实一致性，从而实现了更精确的UQ。我们的实证评估表明，与现有技术相比，我们的方法在识别不确定响应方面更具优势，为提升LLMs在高风险应用中的可靠性提供了一个更强大的框架。

> Large Language Models (LLMs) have demonstrated remarkable capabilities across various tasks due to large training datasets and powerful transformer architecture. However, the reliability of responses from LLMs remains a question. Uncertainty quantification (UQ) of LLMs is crucial for ensuring their reliability, especially in areas such as healthcare, finance, and decision-making. Existing UQ methods primarily focus on semantic similarity, overlooking the deeper knowledge dimensions embedded in responses. We introduce a multi-dimensional UQ framework that integrates semantic and knowledge-aware similarity analysis. By generating multiple responses and leveraging auxiliary LLMs to extract implicit knowledge, we construct separate similarity matrices and apply tensor decomposition to derive a comprehensive uncertainty representation. This approach disentangles overlapping information from both semantic and knowledge dimensions, capturing both semantic variations and factual consistency, leading to more accurate UQ. Our empirical evaluations demonstrate that our method outperforms existing techniques in identifying uncertain responses, offering a more robust framework for enhancing LLM reliability in high-stakes applications.

[Arxiv](https://arxiv.org/abs/2502.16820)