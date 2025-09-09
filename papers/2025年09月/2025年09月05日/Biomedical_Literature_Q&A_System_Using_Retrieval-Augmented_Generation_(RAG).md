# 基于检索增强生成（RAG）的生物医学文献问答系统

发布时间：2025年09月05日

`RAG` `医疗健康`

> Biomedical Literature Q&A System Using Retrieval-Augmented Generation (RAG)

# 摘要

> 本研究构建了一个基于检索增强生成（RAG）架构的生物医学文献问答（Q&A）系统，致力于提升准确、循证医学信息的获取效率。针对传统健康搜索引擎的不足及公众获取生物医学研究的滞后性，该系统整合了PubMed论文、精选问答数据集和医学百科全书等多元来源，可检索相关信息并生成简洁且贴合语境的回答。检索流程采用基于MiniLM的语义嵌入与FAISS向量搜索技术，回答生成则由经微调的Mistral-7B-v0.3语言模型完成，该模型通过QLoRA优化实现了高效低资源训练。系统支持通用医学查询与特定领域任务，对乳腺癌文献的聚焦评估验证了领域对齐检索的价值。实证结果（以BERTScore F1值衡量）表明，与基线模型相比，其事实一致性和语义相关性均显著提升。研究结果凸显了RAG增强语言模型在弥合复杂生物医学文献与公众健康知识鸿沟方面的潜力，为未来多语言适配、隐私保护推理及个性化医疗AI系统的研发奠定了基础。

> This work presents a Biomedical Literature Question Answering (Q&A) system based on a Retrieval-Augmented Generation (RAG) architecture, designed to improve access to accurate, evidence-based medical information. Addressing the shortcomings of conventional health search engines and the lag in public access to biomedical research, the system integrates diverse sources, including PubMed articles, curated Q&A datasets, and medical encyclopedias ,to retrieve relevant information and generate concise, context-aware responses. The retrieval pipeline uses MiniLM-based semantic embeddings and FAISS vector search, while answer generation is performed by a fine-tuned Mistral-7B-v0.3 language model optimized using QLoRA for efficient, low-resource training. The system supports both general medical queries and domain-specific tasks, with a focused evaluation on breast cancer literature demonstrating the value of domain-aligned retrieval. Empirical results, measured using BERTScore (F1), show substantial improvements in factual consistency and semantic relevance compared to baseline models. The findings underscore the potential of RAG-enhanced language models to bridge the gap between complex biomedical literature and accessible public health knowledge, paving the way for future work on multilingual adaptation, privacy-preserving inference, and personalized medical AI systems.

[Arxiv](https://arxiv.org/abs/2509.05505)