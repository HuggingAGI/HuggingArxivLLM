# GraphRAG 遭遇质疑

发布时间：2025年01月23日

`RAG

理由：这篇论文主要讨论了GraphRAG，一种基于多尺度知识图谱的检索增强生成（RAG）方法。论文探讨了GraphRAG在安全性方面的脆弱性，并提出了一种新的攻击方式GRAGPoison。由于论文的核心内容围绕RAG技术的改进和安全性问题，因此将其分类为RAG。` `信息安全` `知识图谱`

> GraphRAG under Fire

# 摘要

> # 摘要
GraphRAG 通过将外部知识构建为多尺度知识图谱，推动了检索增强生成（RAG）的发展，使语言模型能够在推理中同时整合广泛的上下文和细粒度的细节。尽管 GraphRAG 在多个领域表现出色，但其安全性影响仍未被充分研究。为填补这一空白，本研究探讨了 GraphRAG 对投毒攻击的脆弱性，揭示了一个有趣的安全悖论：与传统的 RAG 相比，GraphRAG 基于图的索引和检索增强了对简单投毒攻击的抵抗力，但同时也引入了新的攻击面。我们提出了 GRAGPoison，这是一种利用知识图谱中共享关系的新型攻击方式，能够同时破坏多个查询。GRAGPoison 采用三种关键策略：i) 关系注入以引入虚假知识，ii) 关系增强以放大投毒影响，iii) 叙事生成以将恶意内容嵌入连贯文本。跨数据集和模型的实证评估表明，GRAGPoison 在有效性（成功率高达 98%）和可扩展性（使用少于 68% 的投毒文本）上显著优于现有攻击。我们还探讨了潜在的防御措施及其局限性，为未来研究指明了方向。

> GraphRAG advances retrieval-augmented generation (RAG) by structuring external knowledge as multi-scale knowledge graphs, enabling language models to integrate both broad context and granular details in their reasoning. While GraphRAG has demonstrated success across domains, its security implications remain largely unexplored. To bridge this gap, this work examines GraphRAG's vulnerability to poisoning attacks, uncovering an intriguing security paradox: compared to conventional RAG, GraphRAG's graph-based indexing and retrieval enhance resilience against simple poisoning attacks; meanwhile, the same features also create new attack surfaces. We present GRAGPoison, a novel attack that exploits shared relations in the knowledge graph to craft poisoning text capable of compromising multiple queries simultaneously. GRAGPoison employs three key strategies: i) relation injection to introduce false knowledge, ii) relation enhancement to amplify poisoning influence, and iii) narrative generation to embed malicious content within coherent text. Empirical evaluation across diverse datasets and models shows that GRAGPoison substantially outperforms existing attacks in terms of effectiveness (up to 98% success rate) and scalability (using less than 68% poisoning text). We also explore potential defensive measures and their limitations, identifying promising directions for future research.

[Arxiv](https://arxiv.org/abs/2501.14050)