# 评测毒化攻击对检索增强生成的影响

发布时间：2025年05月24日

`RAG` `问答系统` `对话系统`

> Benchmarking Poisoning Attacks against Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过在推理过程中整合外部知识，已被证明能有效缓解大型语言模型的幻觉问题。然而，这种整合也引入了新的安全漏洞，尤其是对中毒攻击的易感性。尽管先前的研究探讨了多种中毒策略，但对RAG系统实际威胁的全面评估仍不完善。为填补这一空白，我们提出首个全面评估中毒攻击对RAG影响的基准框架。我们的基准涵盖5个标准问答（QA）数据集及其10个扩展变体，同时包含13种中毒攻击方法和7种防御机制，全面覆盖现有技术。通过该基准，我们对所有攻击和防御方法进行了跨数据集的全面评估。研究发现，现有攻击在标准QA数据集上表现良好，但在扩展版本中效果显著下降。此外，我们的结果表明，多种先进的RAG架构，如序列式、分支式、条件式和循环式RAG，以及多轮对话式、多模态RAG系统和基于RAG的LLM代理系统，仍易受中毒攻击。值得注意的是，当前防御技术未能提供 robust 保护，凸显了开发更 resilient 和通用防御策略的迫切需求。

> Retrieval-Augmented Generation (RAG) has proven effective in mitigating hallucinations in large language models by incorporating external knowledge during inference. However, this integration introduces new security vulnerabilities, particularly to poisoning attacks. Although prior work has explored various poisoning strategies, a thorough assessment of their practical threat to RAG systems remains missing. To address this gap, we propose the first comprehensive benchmark framework for evaluating poisoning attacks on RAG. Our benchmark covers 5 standard question answering (QA) datasets and 10 expanded variants, along with 13 poisoning attack methods and 7 defense mechanisms, representing a broad spectrum of existing techniques. Using this benchmark, we conduct a comprehensive evaluation of all included attacks and defenses across the full dataset spectrum. Our findings show that while existing attacks perform well on standard QA datasets, their effectiveness drops significantly on the expanded versions. Moreover, our results demonstrate that various advanced RAG architectures, such as sequential, branching, conditional, and loop RAG, as well as multi-turn conversational RAG, multimodal RAG systems, and RAG-based LLM agent systems, remain susceptible to poisoning attacks. Notably, current defense techniques fail to provide robust protection, underscoring the pressing need for more resilient and generalizable defense strategies.

[Arxiv](https://arxiv.org/abs/2505.18543)