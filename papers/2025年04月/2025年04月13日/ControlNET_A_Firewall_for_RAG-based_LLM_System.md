# ControlNET：面向RAG基大型语言模型系统的防火墙

发布时间：2025年04月13日

`RAG`

> ControlNET: A Firewall for RAG-based LLM System

# 摘要

> 检索增强生成（RAG）显著提升了大型语言模型（LLMs）的事实准确性与领域适应性，使其在医疗、金融及企业应用等敏感领域得到广泛应用。RAG通过整合外部知识缓解模型的幻觉问题，但同时也带来了隐私风险与安全风险，尤其是数据泄露与数据投毒风险。尽管近期研究探讨了提示注入与投毒攻击，但针对通过控制输入输出查询流来缓解此类威胁的综合性研究仍存在显著空白。

本文提出了一种AI防火墙——ControlNET，旨在保护基于RAG的LLM系统免受这些漏洞影响。ControlNET通过利用激活偏移现象检测对抗性查询，并通过语义发散减轻其影响以控制查询流。我们使用先进的开源LLMs（Llama3、Vicuna、Mistral）在Msmarco、HotpotQA、FinQA和MedicalSys四个不同基准数据集上进行了全面实验。

实验结果表明，ControlNET在检测和缓解安全威胁的同时保持系统无害性，实现了超过0.909的AUROC。总体而言，ControlNET提供了一种有效、健壮、无害的防御机制，标志着基于RAG的LLM系统安全部署的重要进展。

> Retrieval-Augmented Generation (RAG) has significantly enhanced the factual accuracy and domain adaptability of Large Language Models (LLMs). This advancement has enabled their widespread deployment across sensitive domains such as healthcare, finance, and enterprise applications. RAG mitigates hallucinations by integrating external knowledge, yet introduces privacy risk and security risk, notably data breaching risk and data poisoning risk. While recent studies have explored prompt injection and poisoning attacks, there remains a significant gap in comprehensive research on controlling inbound and outbound query flows to mitigate these threats. In this paper, we propose an AI firewall, ControlNET, designed to safeguard RAG-based LLM systems from these vulnerabilities. ControlNET controls query flows by leveraging activation shift phenomena to detect adversarial queries and mitigate their impact through semantic divergence. We conduct comprehensive experiments on four different benchmark datasets including Msmarco, HotpotQA, FinQA, and MedicalSys using state-of-the-art open source LLMs (Llama3, Vicuna, and Mistral). Our results demonstrate that ControlNET achieves over 0.909 AUROC in detecting and mitigating security threats while preserving system harmlessness. Overall, ControlNET offers an effective, robust, harmless defense mechanism, marking a significant advancement toward the secure deployment of RAG-based LLM systems.

[Arxiv](https://arxiv.org/abs/2504.09593)