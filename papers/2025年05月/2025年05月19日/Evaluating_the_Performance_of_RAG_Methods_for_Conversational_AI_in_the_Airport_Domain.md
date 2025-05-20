# 评测RAG方法在机场领域对话式AI中的性能表现

发布时间：2025年05月19日

`RAG` `对话系统`

> Evaluating the Performance of RAG Methods for Conversational AI in the Airport Domain

# 摘要

> 年旅客吞吐量排名前20的机场每天处理数千架次航班，是充满活力的环境，它们的目标是提升自动化水平。为此，我们开发了一个对话式AI系统，帮助机场工作人员与航班信息系统沟通。该系统不仅能够回答标准机场问题，还能解析专业术语、行业行话、缩略语，并解决涉及推理的动态问题。在本研究中，我们构建了三种检索增强生成（RAG）方法，包括传统RAG、SQL RAG和基于知识图谱的Graph RAG。实验结果显示，传统RAG结合BM25 + GPT-4达到了84.84%的准确率，但偶尔会产生不实信息，这对机场安全构成风险。相比之下，SQL RAG和Graph RAG的准确率分别为80.85%和91.49%，且生成不实信息的情况显著减少。此外，Graph RAG在处理推理类问题时表现尤为出色。基于实验结果，我们推荐SQL RAG和Graph RAG更适合机场环境，因其生成不实信息的风险较低，并且能够有效处理动态问题。

> Airports from the top 20 in terms of annual passengers are highly dynamic environments with thousands of flights daily, and they aim to increase the degree of automation. To contribute to this, we implemented a Conversational AI system that enables staff in an airport to communicate with flight information systems. This system not only answers standard airport queries but also resolves airport terminology, jargon, abbreviations, and dynamic questions involving reasoning. In this paper, we built three different Retrieval-Augmented Generation (RAG) methods, including traditional RAG, SQL RAG, and Knowledge Graph-based RAG (Graph RAG). Experiments showed that traditional RAG achieved 84.84% accuracy using BM25 + GPT-4 but occasionally produced hallucinations, which is risky to airport safety. In contrast, SQL RAG and Graph RAG achieved 80.85% and 91.49% accuracy respectively, with significantly fewer hallucinations. Moreover, Graph RAG was especially effective for questions that involved reasoning. Based on our observations, we thus recommend SQL RAG and Graph RAG are better for airport environments, due to fewer hallucinations and the ability to handle dynamic questions.

[Arxiv](https://arxiv.org/abs/2505.13006)