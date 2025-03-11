# 基于人类认知启发的 RAG 结合知识图谱，用于复杂问题解决

发布时间：2025年03月09日

`RAG` `知识图谱` `问答系统`

> Human Cognition Inspired RAG with Knowledge Graph for Complex Problem Solving

# 摘要

> 大型语言模型（LLMs）在多个领域展现了变革性的潜力，但它们在知识整合和复杂问题推理方面仍面临重大挑战，常常导致幻觉和不可靠的输出。检索增强生成（RAG）作为一种通过整合外部知识来提升LLMs准确性的有前景的解决方案应运而生。然而，传统RAG系统在处理复杂关系信息和多步骤推理方面存在困难，限制了其在高级问题解决任务中的有效性。为了解决这些限制，我们提出了CogGRAG，一个受认知启发的图基RAG框架，旨在提升LLMs在知识图谱问答（KGQA）中的性能。受人类认知过程的启发，我们将复杂问题分解并进行自我验证，我们的框架采用了一个三阶段的方法：分解、检索和自我验证推理。通过整合这些组件，CogGRAG提升了LLMs在复杂问题解决中的准确性。我们在四个基准数据集上进行了系统性实验，结果显示CogGRAG优于基线模型。

> Large language models (LLMs) have demonstrated transformative potential across various domains, yet they face significant challenges in knowledge integration and complex problem reasoning, often leading to hallucinations and unreliable outputs. Retrieval-Augmented Generation (RAG) has emerged as a promising solution to enhance LLMs accuracy by incorporating external knowledge. However, traditional RAG systems struggle with processing complex relational information and multi-step reasoning, limiting their effectiveness in advanced problem-solving tasks. To address these limitations, we propose CogGRAG, a cognition inspired graph-based RAG framework, designed to improve LLMs performance in Knowledge Graph Question Answering (KGQA). Inspired by the human cognitive process of decomposing complex problems and performing self-verification, our framework introduces a three-stage methodology: decomposition, retrieval, and reasoning with self-verification. By integrating these components, CogGRAG enhances the accuracy of LLMs in complex problem solving. We conduct systematic experiments with three LLM backbones on four benchmark datasets, where CogGRAG outperforms the baselines.

[Arxiv](https://arxiv.org/abs/2503.06567)