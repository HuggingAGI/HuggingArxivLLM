# # 提升医院风险预测：知识增强型多模态电子健康记录建模
利用知识增强型多模态电子健康记录建模，助力医院风险预测的提升。

发布时间：2025年08月03日

`LLM应用

理由：这篇论文探讨了如何在医疗领域中应用大型语言模型（LLM），通过整合多模态数据和知识检索来提高临床预测的准确性。它展示了LLM在实际应用中的有效性，属于LLM应用的范畴。`

> Improving Hospital Risk Prediction with Knowledge-Augmented Multimodal EHR Modeling

# 摘要

> 精准预测临床结果对早期干预、高效资源配置和提升患者护理至关重要。电子健康记录（EHRs）包含多模态数据，包括结构化数据和非结构化的临床笔记，这些笔记提供了丰富且具体情境的信息。我们提出了一种统一的框架，通过两阶段架构无缝整合这些数据，支持多种临床任务。第一阶段利用微调的大型语言模型（LLM）从临床笔记中提取关键信息，并结合基于图的外部知识检索增强理解。第二阶段结合非结构化表示和结构化特征生成最终预测。我们在30天再入院率和住院死亡率预测中验证了其有效性，分别达到了AUC评分0.84和0.92，超越现有基线和临床实践。这是首个将LLM与基于图的知识检索方法结合，并通过整合结构化数据提升临床预测能力的医疗预测框架。

> Accurate prediction of clinical outcomes using Electronic Health Records (EHRs) is critical for early intervention, efficient resource allocation, and improved patient care. EHRs contain multimodal data, including both structured data and unstructured clinical notes that provide rich, context-specific information. In this work, we introduce a unified framework that seamlessly integrates these diverse modalities, leveraging all relevant available information through a two-stage architecture for clinical risk prediction. In the first stage, a fine-tuned Large Language Model (LLM) extracts crucial, task-relevant information from clinical notes, which is enhanced by graph-based retrieval of external domain knowledge from sources such as a medical corpus like PubMed, grounding the LLM's understanding. The second stage combines both unstructured representations and features derived from the structured data to generate the final predictions. This approach supports a wide range of clinical tasks. Here, we demonstrate its effectiveness on 30-day readmission and in-hospital mortality prediction. Experimental results show that our framework achieves strong performance, with AUC scores of $0.84$ and $0.92$, respectively, despite these tasks involving severely imbalanced datasets, with positive rates ranging from approximately $4\%$ to $13\%$. Moreover, it outperforms all existing baselines and clinical practices, including established risk scoring systems. To the best of our knowledge, this is one of the first frameworks for healthcare prediction which enhances the power of an LLM-based graph-guided knowledge retrieval method by combining it with structured data for improved clinical outcome prediction.

[Arxiv](https://arxiv.org/abs/2508.01970)