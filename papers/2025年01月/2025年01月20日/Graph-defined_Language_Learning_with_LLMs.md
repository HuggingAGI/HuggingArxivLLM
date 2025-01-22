# 图定义语言学习与LLMs

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来建模图结构数据，特别是通过将图结构转换为图语言语料库，并在该语料库上预训练LLMs，以增强其在节点分类任务中的表现。虽然涉及到图结构数据的处理，但核心仍然是LLMs的应用，特别是在图结构数据上的应用。因此，这篇论文应归类为“LLM应用”。` `图结构建模` `节点分类`

> Graph-defined Language Learning with LLMs

# 摘要

> # 摘要
最近的研究利用大型语言模型（LLMs）来建模节点分类任务中的文本属性图结构。这些方法通过描述图结构让LLMs理解，或者通过图结构聚合LLMs生成的文本属性嵌入。然而，这些方法在使用LLMs建模图结构时面临两个主要限制：（i）在描述高阶图结构时，图描述变得冗长；（ii）仅凭文本属性无法包含足够的图结构信息。使用LLMs简洁且充分地建模图结构具有挑战性，因为LLMs缺乏直接建模图结构的内置机制，也难以处理高阶节点与目标节点之间复杂的长期依赖关系。
受到LLMs在一种语言上预训练后，只需少量额外训练即可在另一种语言上取得卓越表现的启发，我们提出了	extbf{G}raph-	extbf{D}efined 	extbf{L}anguage for 	extbf{L}arge 	extbf{L}anguage 	extbf{M}odel（GDL4LLM）。这一新颖框架使LLMs能够将其强大的语言理解能力转移到图结构数据上。GDL4LLM将图转换为图语言语料库，而不是图描述，并在此语料库上预训练LLMs，以充分理解图结构。在微调过程中，该语料库仅用少量标记简洁地描述了目标节点的结构信息。通过将图视为一种新语言，GDL4LLM使LLMs能够充分且简洁地建模图结构，用于节点分类任务。在三个真实世界数据集上的广泛实验表明，GDL4LLM通过高效地建模不同阶数的图结构，优于基于描述和文本属性嵌入的基线方法。

> Recent efforts leverage Large Language Models (LLMs) for modeling text-attributed graph structures in node classification tasks. These approaches describe graph structures for LLMs to understand or aggregate LLM-generated textual attribute embeddings through graph structure. However, these approaches face two main limitations in modeling graph structures with LLMs. (i) Graph descriptions become verbose in describing high-order graph structure. (ii) Textual attributes alone do not contain adequate graph structure information. It is challenging to model graph structure concisely and adequately with LLMs. LLMs lack built-in mechanisms to model graph structures directly. They also struggle with complex long-range dependencies between high-order nodes and target nodes.
  Inspired by the observation that LLMs pre-trained on one language can achieve exceptional performance on another with minimal additional training, we propose \textbf{G}raph-\textbf{D}efined \textbf{L}anguage for \textbf{L}arge \textbf{L}anguage \textbf{M}odel (GDL4LLM). This novel framework enables LLMs to transfer their powerful language understanding capabilities to graph-structured data. GDL4LLM translates graphs into a graph language corpus instead of graph descriptions and pre-trains LLMs on this corpus to adequately understand graph structures. During fine-tuning, this corpus describes the structural information of target nodes concisely with only a few tokens. By treating graphs as a new language, GDL4LLM enables LLMs to model graph structures adequately and concisely for node classification tasks. Extensive experiments on three real-world datasets demonstrate that GDL4LLM outperforms description-based and textual attribute embeddings-based baselines by efficiently modeling different orders of graph structure with LLMs.

[Arxiv](https://arxiv.org/abs/2501.11478)