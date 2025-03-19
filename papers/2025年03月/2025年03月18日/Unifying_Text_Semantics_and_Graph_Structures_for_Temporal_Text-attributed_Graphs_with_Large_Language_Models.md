# # 统一文本语义与图结构：面向时间文本属性图的大型语言模型方法

发布时间：2025年03月18日

`LLM应用` `数据科学` `信息处理`

> Unifying Text Semantics and Graph Structures for Temporal Text-attributed Graphs with Large Language Models

# 摘要

> 时间图神经网络 (TGNNs) 在时间图建模中表现优异。然而，现实世界的时间图往往伴随丰富的文本信息，形成了时间文本属性图 (TTAGs)。这种动态文本语义与动态图结构的结合显著增加了建模难度。现有 TGNNs 采用静态文本嵌入方法，并过度依赖侧重结构信息的编码机制，忽视了文本语义的时间演化特性及其与图结构之间的协同强化关系。为解决这些问题，我们提出了 	extbf{Cross}，一个能够无缝扩展现有 TGNNs 的新框架，专为 TTAG 建模设计。其核心思想是借助先进的大型语言模型 (LLMs) 捕捉文本中的动态语义，并生成融合语义与结构的高阶表达。具体而言，我们在 {Cross} 框架中设计了时间语义提取器，使 LLM 能够深入理解节点文本邻域上下文的动态演变，从而更好地捕捉语义动态。随后，我们引入语义-结构协同编码器，与提取器协同工作，通过综合语义和结构信息生成更具洞察力的表示，同时促进两者之间的相互强化。在四个公共数据集和一个实际工业数据集上的大量实验结果充分证明了 {Cross} 的显著优势和强大的鲁棒性。

> Temporal graph neural networks (TGNNs) have shown remarkable performance in temporal graph modeling. However, real-world temporal graphs often possess rich textual information, giving rise to temporal text-attributed graphs (TTAGs). Such combination of dynamic text semantics and evolving graph structures introduces heightened complexity. Existing TGNNs embed texts statically and rely heavily on encoding mechanisms that biasedly prioritize structural information, overlooking the temporal evolution of text semantics and the essential interplay between semantics and structures for synergistic reinforcement. To tackle these issues, we present \textbf{Cross}, a novel framework that seamlessly extends existing TGNNs for TTAG modeling. The key idea is to employ the advanced large language models (LLMs) to extract the dynamic semantics in text space and then generate expressive representations unifying both semantics and structures. Specifically, we propose a Temporal Semantics Extractor in the {Cross} framework, which empowers the LLM to offer the temporal semantic understanding of node's evolving contexts of textual neighborhoods, facilitating semantic dynamics. Subsequently, we introduce the Semantic-structural Co-encoder, which collaborates with the above Extractor for synthesizing illuminating representations by jointly considering both semantic and structural information while encouraging their mutual reinforcement. Extensive experimental results on four public datasets and one practical industrial dataset demonstrate {Cross}'s significant effectiveness and robustness.

[Arxiv](https://arxiv.org/abs/2503.14411)