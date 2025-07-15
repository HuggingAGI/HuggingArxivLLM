# RAG安全防护：探索检索增强生成中的知识投毒攻击

发布时间：2025年07月09日

`RAG` `知识图谱` `数据安全`

> RAG Safety: Exploring Knowledge Poisoning Attacks to Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过引入外部数据有效缓解大型语言模型（LLMs）的幻觉和知识过时问题。凭借在整合多源数据和支撑可靠推理方面的优势，知识图谱（KGs）在RAG系统中得到广泛应用，催生了基于KG的RAG（KG-RAG）方法。尽管RAG系统已广泛应用于多种场景，但近期研究表明其对数据投毒攻击存在脆弱性：恶意信息若注入外部知识源，可能导致系统生成错误或有害响应。然而，现有研究仅关注非结构化文本数据源的RAG系统，而对KG-RAG的安全风险却鲜有探索，尽管KG因其结构化和可编辑特性而具独特脆弱性。本文首次系统性研究KG-RAG方法在数据投毒攻击下的安全问题。为此，我们提出了一种与实际应用相符的实用且隐蔽攻击设置。我们的攻击策略首先识别出对抗性目标答案，然后通过在KG中插入扰动三元组构建误导性推理链，从而增加KG-RAG方法在生成过程中检索和依赖这些扰动的可能性。在两个基准数据集和四种近期KG-RAG方法上的大量实验表明，即使仅施加极小KG扰动，我们的攻击策略也能显著降低KG-RAG性能。此外，我们还进行了深入分析，以理解KG-RAG系统内部阶段的安全威胁，并探讨LLMs在对抗性知识面前的鲁棒性。

> Retrieval-Augmented Generation (RAG) enhances large language models (LLMs) by retrieving external data to mitigate hallucinations and outdated knowledge issues. Benefiting from the strong ability in facilitating diverse data sources and supporting faithful reasoning, knowledge graphs (KGs) have been increasingly adopted in RAG systems, giving rise to KG-based RAG (KG-RAG) methods. Though RAG systems are widely applied in various applications, recent studies have also revealed its vulnerabilities to data poisoning attacks, where malicious information injected into external knowledge sources can mislead the system into producing incorrect or harmful responses. However, these studies focus exclusively on RAG systems using unstructured textual data sources, leaving the security risks of KG-RAG largely unexplored, despite the fact that KGs present unique vulnerabilities due to their structured and editable nature. In this work, we conduct the first systematic investigation of the security issue of KG-RAG methods through data poisoning attacks. To this end, we introduce a practical, stealthy attack setting that aligns with real-world implementation. We propose an attack strategy that first identifies adversarial target answers and then inserts perturbation triples to complete misleading inference chains in the KG, increasing the likelihood that KG-RAG methods retrieve and rely on these perturbations during generation. Through extensive experiments on two benchmarks and four recent KG-RAG methods, our attack strategy demonstrates strong effectiveness in degrading KG-RAG performance, even with minimal KG perturbations. In-depth analyses are also conducted to understand the safety threats within the internal stages of KG-RAG systems and to explore the robustness of LLMs against adversarial knowledge.

[Arxiv](https://arxiv.org/abs/2507.08862)