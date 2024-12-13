# 评估在 K-12 教育问答中存在知识差异时检索增强生成系统的稳健性

发布时间：2024年12月12日

`RAG` `问答系统`

> Assessing the Robustness of Retrieval-Augmented Generation Systems in K-12 Educational Question Answering with Knowledge Discrepancies

# 摘要

> 检索增强生成（RAG）系统在 K-12 教育领域作为问答系统展现出了非凡潜力，该领域的知识通常在权威教科书的有限范围内被查询。然而，教科书和大型语言模型（LLMs）中的参数知识存在差异，这可能会降低 RAG 系统的有效性。为系统探究这种知识差异下 RAG 系统的稳健性，我们推出了 EduKDQA 这一问答数据集，它通过在答案和源文档中进行假设的知识更新来模拟实际应用中的知识差异。EduKDQA 涵盖五个学科，包含 3005 个问题，从上下文利用和知识整合的角度来看，属于全面的问题类型。我们针对检索和问答性能开展了大量实验。我们发现，多数 RAG 系统在知识存在差异的问答中性能大幅下滑，而需要整合上下文知识和参数知识的问题给 LLMs 带来了挑战。

> Retrieval-Augmented Generation (RAG) systems have demonstrated remarkable potential as question answering systems in the K-12 Education domain, where knowledge is typically queried within the restricted scope of authoritative textbooks. However, the discrepancy between textbooks and the parametric knowledge in Large Language Models (LLMs) could undermine the effectiveness of RAG systems. To systematically investigate the robustness of RAG systems under such knowledge discrepancies, we present EduKDQA, a question answering dataset that simulates knowledge discrepancies in real applications by applying hypothetical knowledge updates in answers and source documents. EduKDQA includes 3,005 questions covering five subjects, under a comprehensive question typology from the perspective of context utilization and knowledge integration. We conducted extensive experiments on retrieval and question answering performance. We find that most RAG systems suffer from a substantial performance drop in question answering with knowledge discrepancies, while questions that require integration of contextual knowledge and parametric knowledge pose a challenge to LLMs.

[Arxiv](https://arxiv.org/abs/2412.08985)