# LLM法庭机制：多模型协作增强证据生成，助力文本属性图异常检测

发布时间：2025年08月01日

`LLM应用` `数据安全` `网络安全`

> Court of LLMs: Evidence-Augmented Generation via Multi-LLM Collaboration for Text-Attributed Graph Anomaly Detection

# 摘要

> 文本属性图（TAGs）中复杂拓扑结构与丰富文本信息的结合，为图异常检测（GAD）带来了全新视角。然而，现有GAD方法主要聚焦于设计复杂的图域优化目标，忽视了文本模态的互补价值。由于常用浅层嵌入技术（如词袋模型或跳字模型）编码文本特征，可能导致遗漏与异常相关的语义上下文。为释放文本模态的潜力，大型语言模型（LLMs）凭借强大的语义理解和推理能力成为理想选择。然而，其在TAG异常检测中的应用尚处于探索阶段，且受限于输入长度，难以有效编码图中固有的高阶结构信息。

为实现TAG的高质量异常检测，我们提出了CoLL，一个结合LLMs和图神经网络（GNNs）的创新框架，旨在充分发挥两者的互补优势。CoLL通过多LLM协作进行增强型证据生成，精准捕获与异常相关的上下文，并为检测到的异常提供清晰易懂的解释。同时，CoLL集成了配备门控机制的GNN，可自适应地融合文本特征与证据，同时完整保留图中的高阶拓扑信息。实验结果表明，CoLL表现出显著优势，平均AP提升了13.37%。这项研究为将LLMs应用于推动GAD的发展开辟了新途径。

> The natural combination of intricate topological structures and rich textual information in text-attributed graphs (TAGs) opens up a novel perspective for graph anomaly detection (GAD). However, existing GAD methods primarily focus on designing complex optimization objectives within the graph domain, overlooking the complementary value of the textual modality, whose features are often encoded by shallow embedding techniques, such as bag-of-words or skip-gram, so that semantic context related to anomalies may be missed. To unleash the enormous potential of textual modality, large language models (LLMs) have emerged as promising alternatives due to their strong semantic understanding and reasoning capabilities. Nevertheless, their application to TAG anomaly detection remains nascent, and they struggle to encode high-order structural information inherent in graphs due to input length constraints. For high-quality anomaly detection in TAGs, we propose CoLL, a novel framework that combines LLMs and graph neural networks (GNNs) to leverage their complementary strengths. CoLL employs multi-LLM collaboration for evidence-augmented generation to capture anomaly-relevant contexts while delivering human-readable rationales for detected anomalies. Moreover, CoLL integrates a GNN equipped with a gating mechanism to adaptively fuse textual features with evidence while preserving high-order topological information. Extensive experiments demonstrate the superiority of CoLL, achieving an average improvement of 13.37% in AP. This study opens a new avenue for incorporating LLMs in advancing GAD.

[Arxiv](https://arxiv.org/abs/2508.00507)