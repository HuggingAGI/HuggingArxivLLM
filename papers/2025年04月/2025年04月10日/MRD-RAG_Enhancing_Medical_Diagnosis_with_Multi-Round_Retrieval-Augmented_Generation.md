# MRD-RAG：多轮检索增强生成助力医学诊断提升

发布时间：2025年04月10日

`RAG`

> MRD-RAG: Enhancing Medical Diagnosis with Multi-Round Retrieval-Augmented Generation

# 摘要

> 近年来，医疗大语言模型（LLMs）的快速部署已成为重要趋势，而检索增强生成（RAG）凭借其快速部署和隐私保护的优势脱颖而出。然而，现有医疗RAG框架仍存在局限性：单轮设计难以应对多轮诊断，多轮框架又缺乏医生般的精准问询能力。为此，我们提出了一种模仿医生诊断流程的多轮诊断RAG（MRD-RAG）框架。该框架能深入分析潜在疾病间的关联，实现精准的多轮诊断。我们在两个现代医疗数据集和两个传统中医数据集上进行了实验，并通过GPT和人类医生对不同方法进行评估。结果表明，MRD-RAG显著提升了LLMs的诊断性能，展现了其在医疗诊断中的巨大潜力。项目代码和数据可访问https://github.com/YixiangCh/MRD-RAG/tree/master获取。

> In recent years, accurately and quickly deploying medical large language models (LLMs) has become a significant trend. Among these, retrieval-augmented generation (RAG) has garnered significant attention due to its features of rapid deployment and privacy protection. However, existing medical RAG frameworks still have shortcomings. Most existing medical RAG frameworks are designed for single-round question answering tasks and are not suitable for multi-round diagnostic dialogue. On the other hand, existing medical multi-round RAG frameworks do not consider the interconnections between potential diseases to inquire precisely like a doctor. To address these issues, we propose a Multi-Round Diagnostic RAG (MRD-RAG) framework that mimics the doctor's diagnostic process. This RAG framework can analyze diagnosis information of potential diseases and accurately conduct multi-round diagnosis like a doctor. To evaluate the effectiveness of our proposed frameworks, we conduct experiments on two modern medical datasets and two traditional Chinese medicine datasets, with evaluations by GPT and human doctors on different methods. The results indicate that our RAG framework can significantly enhance the diagnostic performance of LLMs, highlighting the potential of our approach in medical diagnosis. The code and data can be found in our project website https://github.com/YixiangCh/MRD-RAG/tree/master.

[Arxiv](https://arxiv.org/abs/2504.07724)