# # 提升 LLM 驱动的 EDA 助手：RAFT 的应用
RAFT 助力提升 LLM 驱动的 EDA 助手性能。

发布时间：2025年06月06日

`RAG` `电子设计自动化`

> Improving LLM-Powered EDA Assistants with RAFT

# 摘要

> 电子设计工程师在设计验证和技术开发等任务中常常面临高效获取所需信息的难题。尽管大型语言模型（LLMs）作为对话代理可以提升生产力，但开源LLMs缺乏电子设计自动化（EDA）领域的专业知识。在检索增强生成（RAG）框架下，LLMs依赖外部上下文，但仍然可能生成不准确的回答。检索增强微调（RAFT）能够提升LLMs的性能，但在EDA领域获取标注的问题/答案（Q/A）数据颇具挑战。为解决这一问题，我们提出利用合成Q/A数据结合RAFT来增强LLMs。实验结果表明，结合合成数据的RAFT显著提升了LLMs在基于RAG的EDA任务中的表现。此外，我们还探讨了将真实用户问题作为检索增强小样本（RAFS）示例用于合成数据生成的影响。同时，我们实现了安全访问控制，确保敏感信息仅限于授权人员访问。最后，我们评估了在合成数据微调过程中数据泄露和意外记忆的风险，提供了实用的见解。


> Electronic design engineers often struggle to efficiently access relevant information for tasks like design verification and technology development. While large language models (LLMs) can enhance productivity as conversational agents, pre-trained open-source LLMs lack domain-specific knowledge for Electronic Design Automation (EDA). In a Retrieval-Augmented Generation (RAG) context, LLMs rely on external context but may still produce inaccurate responses. Retrieval-Augmented Fine-Tuning (RAFT) improves LLM performance, but acquiring labeled question/answer (Q/A) data in EDA is difficult. To address this, we propose using synthetic Q/A datasets to enhance LLMs with RAFT. Our results show that RAFT with synthetic data significantly boosts LLM performance for RAG-based EDA tasks. We also investigate the impact of using real user questions as Retrieval-Augmented Few-Shot (RAFS) examples for synthetic data generation. Additionally, we implement secure access control to ensure sensitive information is only accessible to authorized personnel. Finally, we assess the risk of data leakage and unintended memorization during fine-tuning with synthetic data, providing practical insights.

[Arxiv](https://arxiv.org/abs/2506.06500)