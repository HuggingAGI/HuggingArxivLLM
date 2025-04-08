# 实用的投毒攻击对抗检索增强生成

发布时间：2025年04月04日

`RAG`

> Practical Poisoning Attacks against Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）展现了令人瞩目的自然语言处理能力，但它们仍面临幻觉和知识过时等挑战。检索增强生成（RAG）作为一种前沿方法，有效缓解了这些问题。尽管RAG提升了LLM的输出质量，但它仍易受中毒攻击影响。近期研究表明，向知识库中注入毒化文本可导致RAG系统失效，但现有攻击大多假设攻击者能为每次查询插入足够多的毒化文本，以在检索中超过正确答案文本数量，这一假设往往不切实际。

为克服这一限制，我们提出了CorruptRAG，这是一种针对RAG系统的实用中毒攻击方法，攻击者仅需注入一条毒化文本，显著提升了攻击的可行性和隐蔽性。大量跨多数据集的实验表明，CorruptRAG相较于现有基线实现了更高的攻击成功率。

> Large language models (LLMs) have demonstrated impressive natural language processing abilities but face challenges such as hallucination and outdated knowledge. Retrieval-Augmented Generation (RAG) has emerged as a state-of-the-art approach to mitigate these issues. While RAG enhances LLM outputs, it remains vulnerable to poisoning attacks. Recent studies show that injecting poisoned text into the knowledge database can compromise RAG systems, but most existing attacks assume that the attacker can insert a sufficient number of poisoned texts per query to outnumber correct-answer texts in retrieval, an assumption that is often unrealistic. To address this limitation, we propose CorruptRAG, a practical poisoning attack against RAG systems in which the attacker injects only a single poisoned text, enhancing both feasibility and stealth. Extensive experiments across multiple datasets demonstrate that CorruptRAG achieves higher attack success rates compared to existing baselines.

[Arxiv](https://arxiv.org/abs/2504.03957)