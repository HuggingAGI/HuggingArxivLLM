# LexRAG: 针对多轮法律咨询对话中的检索增强生成进行基准测试

发布时间：2025年02月27日

`RAG` `问答系统`

> LexRAG: Benchmarking Retrieval-Augmented Generation in Multi-Turn Legal Consultation Conversation

# 摘要

> 检索增强生成（RAG）在提升大型语言模型（LLMs）性能方面已被证明在多个领域非常有效。然而，目前尚无专门针对法律领域 RAG 有效性评估的基准测试，这限制了该领域的发展。为填补这一空白，我们提出了 LexRAG，这是首个用于评估多轮法律咨询中 RAG 系统的基准测试。

LexRAG 包含 1,013 个多轮对话样本和 17,228 篇候选法律文章。每个样本均由法律专家标注，并包含五轮逐步深入的提问。LexRAG 包含两个关键任务：（1）对话知识检索，要求基于多轮上下文准确检索相关法律文章；（2）响应生成，专注于生成符合法律规范的回答。

为了确保可靠的可重复性，我们开发了 LexiT，一个专注于法律领域的 RAG 工具包，提供针对法律场景的 RAG 系统组件的全面实现。此外，我们引入了一个基于 LLM 的评估流水线，以实现详细且有效的评估。通过对各种 LLM 和检索方法的实验分析，我们揭示了现有 RAG 系统在处理法律咨询对话时的关键局限性。

LexRAG 为 RAG 系统在法律领域的实际应用确立了新的基准，其代码和数据可在 https://github.com/CSHaitao/LexRAG 获取。

> Retrieval-augmented generation (RAG) has proven highly effective in improving large language models (LLMs) across various domains. However, there is no benchmark specifically designed to assess the effectiveness of RAG in the legal domain, which restricts progress in this area. To fill this gap, we propose LexRAG, the first benchmark to evaluate RAG systems for multi-turn legal consultations. LexRAG consists of 1,013 multi-turn dialogue samples and 17,228 candidate legal articles. Each sample is annotated by legal experts and consists of five rounds of progressive questioning. LexRAG includes two key tasks: (1) Conversational knowledge retrieval, requiring accurate retrieval of relevant legal articles based on multi-turn context. (2) Response generation, focusing on producing legally sound answers. To ensure reliable reproducibility, we develop LexiT, a legal RAG toolkit that provides a comprehensive implementation of RAG system components tailored for the legal domain. Additionally, we introduce an LLM-as-a-judge evaluation pipeline to enable detailed and effective assessment. Through experimental analysis of various LLMs and retrieval methods, we reveal the key limitations of existing RAG systems in handling legal consultation conversations. LexRAG establishes a new benchmark for the practical application of RAG systems in the legal domain, with its code and data available at https://github.com/CSHaitao/LexRAG.

[Arxiv](https://arxiv.org/abs/2502.20640)