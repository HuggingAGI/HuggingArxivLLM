# 基于树的RAG-智能体推荐系统：医疗测试数据案例分析

发布时间：2025年01月05日

`RAG

理由：这篇论文描述了一个名为 HiRMed 的系统，它利用 RAG（Retrieval-Augmented Generation）技术来实现智能医学测试推荐。RAG 是一种结合了检索和生成的技术，通常用于增强语言模型的能力。论文中提到的系统通过在每个树节点上进行医学推理，利用 RAG 技术来分析和理解症状与疾病的关系，并动态调整推荐策略。因此，这篇论文的核心技术是 RAG，应归类为 RAG。` `推荐系统`

> Tree-based RAG-Agent Recommendation System: A Case Study in Medical Test Data

# 摘要

> 我们推出了 HiRMed（分层 RAG 增强的医学测试推荐系统），这是一种创新的树状结构推荐系统，利用 RAG 技术实现智能医学测试推荐。与传统基于向量相似度的方法不同，HiRMed 通过专门的 RAG 过程在每个树节点上进行医学推理。系统从根节点（初始症状）出发，逐步分析潜在疾病及其诊断需求。每一层的 RAG 增强节点不仅进行简单匹配，还通过分析检索到的医学知识，理解症状与疾病的关系，并确定最佳诊断路径。系统根据医学推理结果动态调整推荐策略，综合考虑紧急程度和诊断不确定性等因素。实验表明，与传统检索方法相比，HiRMed 在覆盖率、准确性和漏诊率上表现更优。这一成果通过在传统树状检索结构中引入医学推理能力，推动了医学测试推荐领域的重大进步。

> We present HiRMed (Hierarchical RAG-enhanced Medical Test Recommendation), a novel tree-structured recommendation system that leverages Retrieval-Augmented Generation (RAG) for intelligent medical test recommendations. Unlike traditional vector similarity-based approaches, our system performs medical reasoning at each tree node through a specialized RAG process. Starting from the root node with initial symptoms, the system conducts step-wise medical analysis to identify potential underlying conditions and their corresponding diagnostic requirements. At each level, instead of simple matching, our RAG-enhanced nodes analyze retrieved medical knowledge to understand symptom-disease relationships and determine the most appropriate diagnostic path. The system dynamically adjusts its recommendation strategy based on medical reasoning results, considering factors such as urgency levels and diagnostic uncertainty. Experimental results demonstrate that our approach achieves superior performance in terms of coverage rate, accuracy, and miss rate compared to conventional retrieval-based methods. This work represents a significant advance in medical test recommendation by introducing medical reasoning capabilities into the traditional tree-based retrieval structure.

[Arxiv](https://arxiv.org/abs/2501.02727)