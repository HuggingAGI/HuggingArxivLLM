# 超越检索：融合跨编码器与GPT重排器的LLM在生物医学问答中的应用探索

发布时间：2025年07月07日

`RAG` `生物医学` `问答系统`

> Beyond Retrieval: Ensembling Cross-Encoders and GPT Rerankers with LLMs for Biomedical QA

# 摘要

> 基于信息检索的生物医学语义问答系统在跟踪海量、快速演变且不断增长的生物医学文献方面发挥着关键作用。它能帮助研究人员、医疗专业人士乃至普通用户获取基于证据的相关知识。BioASQ 2025 Task13b挑战赛是该领域的重要基准测试，为技术发展提供了竞争平台。本文介绍了我们在此次挑战中的方法和成果：我们构建了一个基于检索增强生成（RAG）的系统，通过检索PubMed文档和片段来生成生物医学问题的答案。在检索任务中，我们通过生成生物医学文章的密集嵌入进行初始检索，并结合微调交叉编码器与大型语言模型（LLMs）进行重排序，以识别最相关的文档。我们的解决方案在检索任务中实现了MAP@10为0.1581，排名榜单第10位。在答案生成方面，我们采用了指令微调大型语言模型的少样本提示方法。系统在是/否问题上达到了0.95的宏F1分数（排名第12），在事实性问题上达到了0.64的平均倒数排名（MRR）（排名第1），在列表问题上达到了0.63的平均F1分数（排名第5），在理想答案上达到了0.29的ROUGE-SU4 F1分数（排名第11）。

> Biomedical semantic question answering rooted in information retrieval can play a crucial role in keeping up to date with vast, rapidly evolving and ever-growing biomedical literature. A robust system can help researchers, healthcare professionals and even layman users access relevant knowledge grounded in evidence. The BioASQ 2025 Task13b Challenge serves as an important benchmark, offering a competitive platform for advancement of this space. This paper presents the methodologies and results from our participation in this challenge where we built a Retrieval-Augmented Generation (RAG) system that can answer biomedical questions by retrieving relevant PubMed documents and snippets to generate answers. For the retrieval task, we generated dense embeddings from biomedical articles for initial retrieval, and applied an ensemble of finetuned cross-encoders and large language models (LLMs) for re-ranking to identify top relevant documents. Our solution achieved an MAP@10 of 0.1581, placing 10th on the leaderboard for the retrieval task. For answer generation, we employed few-shot prompting of instruction-tuned LLMs. Our system achieved macro-F1 score of 0.95 for yes/no questions (rank 12), Mean Reciprocal Rank (MRR) of 0.64 for factoid questions (rank 1), mean-F1 score of 0.63 for list questions (rank 5), and ROUGE-SU4 F1 score of 0.29 for ideal answers (rank 11).

[Arxiv](https://arxiv.org/abs/2507.05577)