# 面向全面药物禁忌症的检索增强型大型语言模型系统

发布时间：2025年08月08日

`RAG`

> Retrieval Augmented Large Language Model System for Comprehensive Drug Contraindications

# 摘要

> 大型语言模型（LLMs）在多个领域展现了其强大的多功能性，但在医疗领域，特别是在需要高度准确性的药物禁忌症领域，其应用仍面临挑战。本研究通过引入检索增强生成（RAG）管道，显著提升了LLMs在处理禁忌症方面的效果。基于OpenAI的GPT-4o-mini模型，并结合text-embedding-3-small模型进行嵌入，我们利用Langchain构建了一个混合检索系统，并通过重新排序优化检索结果。该系统整合了公共数据库中的药物利用审查（DUR）数据，重点关注特定年龄组、怀孕及合并用药相关的禁忌症信息。数据集包含三个类别共计300对问答，基线模型的准确率在0.49到0.57之间。引入RAG管道后，模型在年龄组、怀孕及合并用药相关禁忌症上的准确率分别提升至0.94、0.87和0.89。研究结果表明，通过RAG框架增强LLMs，能够显著提升药物禁忌信息的准确性和可靠性，从而有效降低处方和用药决策中的不确定性。

> The versatility of large language models (LLMs) has been explored across various sectors, but their application in healthcare poses challenges, particularly in the domain of pharmaceutical contraindications where accurate and reliable information is required. This study enhances the capability of LLMs to address contraindications effectively by implementing a Retrieval Augmented Generation (RAG) pipeline. Utilizing OpenAI's GPT-4o-mini as the base model, and the text-embedding-3-small model for embeddings, our approach integrates Langchain to orchestrate a hybrid retrieval system with re-ranking. This system leverages Drug Utilization Review (DUR) data from public databases, focusing on contraindications for specific age groups, pregnancy, and concomitant drug use. The dataset includes 300 question-answer pairs across three categories, with baseline model accuracy ranging from 0.49 to 0.57. Post-integration of the RAG pipeline, we observed a significant improvement in model accuracy, achieving rates of 0.94, 0.87, and 0.89 for contraindications related to age groups, pregnancy, and concomitant drug use, respectively. The results indicate that augmenting LLMs with a RAG framework can substantially reduce uncertainty in prescription and drug intake decisions by providing more precise and reliable drug contraindication information.

[Arxiv](https://arxiv.org/abs/2508.06145)