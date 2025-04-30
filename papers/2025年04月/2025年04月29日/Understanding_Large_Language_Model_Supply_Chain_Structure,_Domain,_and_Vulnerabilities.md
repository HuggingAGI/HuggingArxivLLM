# 解析大型语言模型供应链：结构、领域与漏洞

发布时间：2025年04月29日

`LLM理论` `软件供应链` `开源软件`

> Understanding Large Language Model Supply Chain: Structure, Domain, and Vulnerabilities

# 摘要

> 大型语言模型（LLMs）彻底改变了人工智能领域，在自然语言理解和生成等技术上取得了突破性进展。然而，随着LLMs的快速发展，其背后的供应链——大型语言模型供应链（LLMSC）——在安全性和可靠性方面面临严峻挑战。LLMSC是一个复杂的开源组件网络，对LLM的开发和部署至关重要。尽管其重要性不言而喻，但目前对其结构特征、领域构成和安全漏洞的研究仍然有限。

为填补这一研究空白，我们开展了首个针对LLMSC的实证研究，分析了来自PyPI和NPM的开源包数据集，覆盖14个功能领域。通过构建包含15,725个节点、10,402条边和180个独特漏洞的有向依赖图，我们深入探究了LLMSC的结构特征，并揭示了安全风险在依赖网络中的传播机制。

研究发现，LLMSC呈现出“局部密集、全局稀疏”的独特拓扑结构。具体而言，79.7%的依赖树包含少于5个节点，而少数大型依赖树却占据了整个生态系统的主导地位，占比高达77.66%。此外，图中以高连接度的枢纽节点为特征，排名前5的节点平均每个拥有1,282个依赖项。

在安全方面，关键漏洞的影响范围随依赖层级的增加而显著扩大。具体而言，漏洞在依赖树的第二层平均影响142.1个节点，并在第三层达到峰值，影响237.8个节点。特别值得注意的是，像transformers这样的关键枢纽节点成为级联风险的集中点，直接或间接影响超过1,300个下游包。

这些发现不仅为LLMSC的结构和安全动态提供了重要的定量见解，还凸显了制定针对性缓解策略以增强整个生态系统弹性的迫切需求。


> Large Language Models (LLMs) have revolutionized artificial intelligence (AI), driving breakthroughs in natural language understanding, text generation, and autonomous systems. However, the rapid growth of LLMs presents significant challenges in the security and reliability of the Large Language Model Supply Chain (LLMSC), a complex network of open-source components, libraries, and tools essential for LLM development and deployment. Despite its critical importance, the LLMSC remains underexplored, particularly regarding its structural characteristics, domain composition, and security vulnerabilities. To address this gap, we conduct the first empirical study of the LLMSC, analyzing a curated dataset of open-source packages from PyPI and NPM across 14 functional domains. We construct a directed dependency graph comprising 15,725 nodes, 10,402 edges, and 180 unique vulnerabilities to investigate the structural characteristics of the LLMSC and analyze how security risks propagate through its dependency network. Our findings reveal that the LLMSC exhibits a ``locally dense, globally sparse'' topology, with 79.7% of dependency trees containing fewer than 5 nodes, while a few large trees dominate the ecosystem, accounting for 77.66% of all nodes. The graph is characterized by high-degree hubs, with the top 5 most connected nodes averaging 1,282 dependents each. Security analysis shows that critical vulnerabilities propagate to an average of 142.1 nodes at the second layer of dependency trees and peak at 237.8 affected nodes at the third layer. Notably, cascading risks are concentrated in critical hub nodes such as transformers, which directly or indirectly affect over 1,300 downstream packages. These findings provide quantitative insights into the structural and security dynamics of the LLMSC and emphasize the need for targeted mitigation strategies to enhance ecosystem resilience.

[Arxiv](https://arxiv.org/abs/2504.20763)