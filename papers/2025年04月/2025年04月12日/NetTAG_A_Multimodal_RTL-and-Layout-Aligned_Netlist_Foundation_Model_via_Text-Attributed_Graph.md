# NetTAG：基于文本属性图的多模态网表基础模型，实现RTL与布局对齐

发布时间：2025年04月12日

`LLM应用` `电子设计自动化` `电路设计`

> NetTAG: A Multimodal RTL-and-Layout-Aligned Netlist Foundation Model via Text-Attributed Graph

# 摘要

> 电路表示学习在电子设计自动化 (EDA) 中展现出巨大潜力，通过捕捉电路的结构和功能属性推动技术进步。现有的预训练解决方案依赖于复杂的函数监督图学习，例如真值表模拟，但仅能处理简单的与非门图 (AIGs)，难以完全编码其他复杂门的功能。虽然大型语言模型 (LLMs) 在功能理解方面表现出色，但它们缺乏对展平网表的结构感知能力。为推进网表表示学习，我们提出了NetTAG——一个融合门语义与图结构的网表基础模型，支持多种门类型，并适用于各种功能和物理任务。NetTAG超越了现有仅基于图的方法，将网表表示为文本属性图，其中 gates 由符号逻辑表达式和物理特性作为文本属性注释。其多模态架构结合了基于 LLM 的文本编码器用于门语义理解，以及图 transformer 用于全局结构分析。通过门和图的自监督目标预训练，并与 RTL 和布局阶段对齐，NetTAG能够捕捉全面的电路内在属性。实验结果表明，NetTAG在四个功能和物理任务上始终超越现有方法，并超越了现有的 AIG 编码器，证明了其广泛的适用性。

> Circuit representation learning has shown promise in advancing Electronic Design Automation (EDA) by capturing structural and functional circuit properties for various tasks. Existing pre-trained solutions rely on graph learning with complex functional supervision, such as truth table simulation. However, they only handle simple and-inverter graphs (AIGs), struggling to fully encode other complex gate functionalities. While large language models (LLMs) excel at functional understanding, they lack the structural awareness for flattened netlists. To advance netlist representation learning, we present NetTAG, a netlist foundation model that fuses gate semantics with graph structure, handling diverse gate types and supporting a variety of functional and physical tasks. Moving beyond existing graph-only methods, NetTAG formulates netlists as text-attributed graphs, with gates annotated by symbolic logic expressions and physical characteristics as text attributes. Its multimodal architecture combines an LLM-based text encoder for gate semantics and a graph transformer for global structure. Pre-trained with gate and graph self-supervised objectives and aligned with RTL and layout stages, NetTAG captures comprehensive circuit intrinsics. Experimental results show that NetTAG consistently outperforms each task-specific method on four largely different functional and physical tasks and surpasses state-of-the-art AIG encoders, demonstrating its versatility.

[Arxiv](https://arxiv.org/abs/2504.09260)