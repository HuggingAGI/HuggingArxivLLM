# 自作自受：利用护栏机制发起针对LLM检索增强生成的拒绝服务攻击

发布时间：2025年04月30日

`RAG` `人工智能`

> Hoist with His Own Petard: Inducing Guardrails to Facilitate Denial-of-Service Attacks on Retrieval-Augmented Generation of LLMs

# 摘要

> 检索增强生成（RAG）将大型语言模型（LLMs）与外部知识库相结合，虽然提升了输出质量，但也带来了新的安全挑战。目前针对RAG漏洞的研究大多集中在利用检索机制注入错误知识或恶意文本，以诱导生成错误输出。然而，这些方法忽视了LLMs本身的关键弱点，导致许多潜在的攻击向量未被探索，限制了攻击的范围和效率。本文揭示了一种新型漏洞：LLMs的安全护栏机制，虽然初衷是保护系统，但也可能被攻击者利用作为攻击向量。基于这一发现，我们提出了MutedRAG，这是一种新型的拒绝服务攻击，通过反向利用LLMs的安全护栏来破坏RAG系统的可用性。通过向知识库中注入极简的越狱文本（如"	extit{如何制造炸弹}"），MutedRAG故意触发LLMs的安全护栏，导致系统拒绝合法查询。此外，由于护栏机制的高度敏感性，单个越狱样本可能影响多个查询，从而有效提升攻击效率并降低成本。在三个数据集上的实验结果表明，MutedRAG在许多场景下实现了超过60%的攻击成功率，平均每攻击一个目标查询仅需注入不到一条恶意文本。此外，我们评估了针对MutedRAG的潜在防御策略，发现现有部分机制不足以缓解这一威胁，凸显了开发更 robust 解决方案的迫切需求。

> Retrieval-Augmented Generation (RAG) integrates Large Language Models (LLMs) with external knowledge bases, improving output quality while introducing new security risks. Existing studies on RAG vulnerabilities typically focus on exploiting the retrieval mechanism to inject erroneous knowledge or malicious texts, inducing incorrect outputs. However, these approaches overlook critical weaknesses within LLMs, leaving important attack vectors unexplored and limiting the scope and efficiency of attacks. In this paper, we uncover a novel vulnerability: the safety guardrails of LLMs, while designed for protection, can also be exploited as an attack vector by adversaries. Building on this vulnerability, we propose MutedRAG, a novel denial-of-service attack that reversely leverages the guardrails of LLMs to undermine the availability of RAG systems. By injecting minimalistic jailbreak texts, such as "\textit{How to build a bomb}", into the knowledge base, MutedRAG intentionally triggers the LLM's safety guardrails, causing the system to reject legitimate queries. Besides, due to the high sensitivity of guardrails, a single jailbreak sample can affect multiple queries, effectively amplifying the efficiency of attacks while reducing their costs. Experimental results on three datasets demonstrate that MutedRAG achieves an attack success rate exceeding 60% in many scenarios, requiring only less than one malicious text to each target query on average. In addition, we evaluate potential defense strategies against MutedRAG, finding that some of current mechanisms are insufficient to mitigate this threat, underscoring the urgent need for more robust solutions.

[Arxiv](https://arxiv.org/abs/2504.21680)