# # NOCL：面向节点的概念化 LLM，无需消息传递即可处理图任务

发布时间：2025年05月28日

`LLM应用` `社交网络` `推荐系统`

> NOCL: Node-Oriented Conceptualization LLM for Graph Tasks without Message Passing

# 摘要

> 图结构在社交网络、生物和推荐系统等跨领域的复杂交互建模中至关重要。传统的图神经网络，尤其是消息传递神经网络（MPNNs），严重依赖监督学习，这限制了它们的泛化能力和在标签稀缺场景中的应用。最近的自监督方法仍然需要标签微调，这在零样本场景中限制了它们的有效性。同时，大型语言模型（LLMs）在自然语言任务中表现出色，但将其应用于图结构时面临重大挑战，包括保持推理能力、管理来自丰富节点属性的大量令牌长度，以及仅限于文本属性图（TAGs）和单级任务。为了解决这些限制，我们提出了基于节点导向的概念化大型语言模型（NOCL），这是一个利用两种核心技术的新颖框架：1）节点描述，将异质节点属性转换为结构化的自然语言，将LLM的应用范围从TAGs扩展到非TAGs；2）节点概念，利用预训练的语言模型将节点描述编码为紧凑的语义嵌入，与直接使用节点描述相比，将令牌长度显著减少高达93.9%。此外，我们的NOCL采用图表示描述符，将不同层次的图任务统一到一个共享的语言查询格式中，为图基础模型开辟了新的方向。实验结果验证了NOCL在监督学习方面相对于传统MPNNs和混合LLM-MPNN方法的竞争性能，并在零样本设置中展示了更优的泛化能力。

> Graphs are essential for modeling complex interactions across domains such as social networks, biology, and recommendation systems. Traditional Graph Neural Networks, particularly Message Passing Neural Networks (MPNNs), rely heavily on supervised learning, limiting their generalization and applicability in label-scarce scenarios. Recent self-supervised approaches still require labeled fine-tuning, limiting their effectiveness in zero-shot scenarios. Meanwhile, Large Language Models (LLMs) excel in natural language tasks but face significant challenges when applied to graphs, including preserving reasoning abilities, managing extensive token lengths from rich node attributes, and being limited to textual-attributed graphs (TAGs) and a single level task. To overcome these limitations, we propose the Node-Oriented Conceptualization LLM (NOCL), a novel framework that leverages two core techniques: 1) node description, which converts heterogeneous node attributes into structured natural language, extending LLM from TAGs to non-TAGs; 2) node concept, which encodes node descriptions into compact semantic embeddings using pretrained language models, significantly reducing token lengths by up to 93.9% compared to directly using node descriptions. Additionally, our NOCL employs graph representation descriptors to unify graph tasks at various levels into a shared, language-based query format, paving a new direction for Graph Foundation Models. Experimental results validate NOCL's competitive supervised performance relative to traditional MPNNs and hybrid LLM-MPNN methods and demonstrate superior generalization in zero-shot settings.

[Arxiv](https://arxiv.org/abs/2506.10014)