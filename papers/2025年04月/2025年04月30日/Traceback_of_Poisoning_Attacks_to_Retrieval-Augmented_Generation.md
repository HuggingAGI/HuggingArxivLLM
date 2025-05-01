# 检索增强生成中的投毒攻击溯源

发布时间：2025年04月30日

`RAG` `RAG系统` `知识库安全`

> Traceback of Poisoning Attacks to Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）与检索增强生成（RAG）系统的结合通过整合外部知识源来提升准确性。然而，近期研究揭示了RAG系统易受中毒攻击的弱点，即攻击者向知识库中注入恶意文本，从而引发预期的有害响应。现有的防御措施主要集中在推理阶段的缓解，面对复杂的攻击手段显得力不从心。本文提出RAGForensics——首个专为RAG设计的追溯系统，旨在识别知识库中引发攻击的中毒文本。该系统采用迭代方法，首先从数据库中检索部分文本，随后借助特别设计的提示语，引导大型语言模型识别潜在的中毒文本。跨多数据集的实证评估证实了RAGForensics在抵御先进中毒攻击方面的有效性。这项研究开创了在RAG系统中追溯中毒文本的先河，为提升其安全性提供了实用且富有前景的防御机制。

> Large language models (LLMs) integrated with retrieval-augmented generation (RAG) systems improve accuracy by leveraging external knowledge sources. However, recent research has revealed RAG's susceptibility to poisoning attacks, where the attacker injects poisoned texts into the knowledge database, leading to attacker-desired responses. Existing defenses, which predominantly focus on inference-time mitigation, have proven insufficient against sophisticated attacks. In this paper, we introduce RAGForensics, the first traceback system for RAG, designed to identify poisoned texts within the knowledge database that are responsible for the attacks. RAGForensics operates iteratively, first retrieving a subset of texts from the database and then utilizing a specially crafted prompt to guide an LLM in detecting potential poisoning texts. Empirical evaluations across multiple datasets demonstrate the effectiveness of RAGForensics against state-of-the-art poisoning attacks. This work pioneers the traceback of poisoned texts in RAG systems, providing a practical and promising defense mechanism to enhance their security.

[Arxiv](https://arxiv.org/abs/2504.21668)