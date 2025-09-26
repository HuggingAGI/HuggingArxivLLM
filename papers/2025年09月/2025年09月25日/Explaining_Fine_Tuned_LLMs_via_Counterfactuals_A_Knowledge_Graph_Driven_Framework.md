# 通过反事实解释微调LLMs：知识图谱驱动的框架

发布时间：2025年09月25日

`LLM理论` `医疗健康`

> Explaining Fine Tuned LLMs via Counterfactuals A Knowledge Graph Driven Framework

# 摘要

> 低秩适应（LoRA）的普及让大型语言模型（LLMs）能高效获取领域特定知识，但微调机制如何改变模型的结构推理与语义行为仍是亟待探索的难题。本研究提出一种新型框架，借助基于知识图谱的反事实来解析微调后的大语言模型。具体而言，我们构建了生物信息学工具领域的异质知识图谱BioToolKG，并设计出基于反事实的微调大语言模型解释器（CFFTLLMExplainer）。该解释器通过学习图节点与边的软掩码，生成可引发最大语义差异的最小结构扰动。我们的方法在联合优化结构稀疏性与语义差异的同时，还施加了熵正则化、边平滑性等保持可解释性的约束。将此框架应用于基于LLaMA微调的大语言模型后发现：反事实掩码不仅揭示了模型的结构依赖关系，还与LoRA引起的参数变化相吻合。这项工作为理解微调大语言模型的内部机制提供了新视角，并凸显了反事实图作为可解释人工智能潜在工具的价值。

> The widespread adoption of Low-Rank Adaptation (LoRA) has enabled large language models (LLMs) to acquire domain-specific knowledge with remarkable efficiency. However, understanding how such a fine-tuning mechanism alters a model's structural reasoning and semantic behavior remains an open challenge. This work introduces a novel framework that explains fine-tuned LLMs via counterfactuals grounded in knowledge graphs. Specifically, we construct BioToolKG, a domain-specific heterogeneous knowledge graph in bioinformatics tools and design a counterfactual-based fine-tuned LLMs explainer (CFFTLLMExplainer) that learns soft masks over graph nodes and edges to generate minimal structural perturbations that induce maximum semantic divergence. Our method jointly optimizes structural sparsity and semantic divergence while enforcing interpretability preserving constraints such as entropy regularization and edge smoothness. We apply this framework to a fine-tuned LLaMA-based LLM and reveal that counterfactual masking exposes the model's structural dependencies and aligns with LoRA-induced parameter shifts. This work provides new insights into the internal mechanisms of fine-tuned LLMs and highlights counterfactual graphs as a potential tool for interpretable AI.

[Arxiv](https://arxiv.org/abs/2509.21241)