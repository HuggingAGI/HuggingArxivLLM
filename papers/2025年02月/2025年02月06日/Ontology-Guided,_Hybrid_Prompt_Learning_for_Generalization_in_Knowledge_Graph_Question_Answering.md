# 基于本体引导的混合提示学习：提升知识图谱问答的泛化能力

发布时间：2025年02月06日

`LLM应用

理由：这篇论文提出了一种基于大型语言模型（LLM）的新型知识图谱问答（KGQA）方法，即OntoSCPrompt。该方法利用LLM进行语义解析和生成SPARQL查询结构，并通过混合提示学习策略将知识图谱本体融入学习过程。论文的核心在于如何利用LLM来改进KGQA系统的泛化能力和资源效率，这属于LLM在实际应用中的具体应用场景，因此应归类为LLM应用。` `知识图谱` `问答系统`

> Ontology-Guided, Hybrid Prompt Learning for Generalization in Knowledge Graph Question Answering

# 摘要

> # 摘要
现有的知识图谱问答（KGQA）方法大多针对特定知识图谱（如Wikidata、DBpedia或Freebase）设计。由于底层图模式、拓扑结构和断言的异质性，大多数KGQA系统难以迁移到未见过的知识图谱（KGs）上，除非进行资源密集型的训练。我们提出了OntoSCPrompt，一种基于大型语言模型（LLM）的新型KGQA方法，采用两阶段架构，将语义解析与KG依赖的交互分离。OntoSCPrompt首先生成SPARQL查询结构（包括SELECT、ASK、WHERE等关键字及占位符），然后用KG特定信息填充这些占位符。为了增强对底层KG的理解，我们提出了一种基于本体的混合提示学习策略，将KG本体融入混合提示（如离散和连续向量）的学习过程。此外，我们还设计了多种任务特定的解码策略，确保生成的SPARQL查询在两个阶段中的正确性和可执行性。实验结果表明，OntoSCPrompt在多个KGQA数据集（如CWQ、WebQSP和LC-QuAD 1.0）上的表现与SOTA方法相当，且无需重新训练，能够以资源高效的方式泛化到未见过的领域特定KGs（如DBLP-QuAD和CoyPu KG）。代码：\href{https://github.com/LongquanJiang/OntoSCPrompt}{https://github.com/LongquanJiang/OntoSCPrompt}

> Most existing Knowledge Graph Question Answering (KGQA) approaches are designed for a specific KG, such as Wikidata, DBpedia or Freebase. Due to the heterogeneity of the underlying graph schema, topology and assertions, most KGQA systems cannot be transferred to unseen Knowledge Graphs (KGs) without resource-intensive training data. We present OntoSCPrompt, a novel Large Language Model (LLM)-based KGQA approach with a two-stage architecture that separates semantic parsing from KG-dependent interactions. OntoSCPrompt first generates a SPARQL query structure (including SPARQL keywords such as SELECT, ASK, WHERE and placeholders for missing tokens) and then fills them with KG-specific information. To enhance the understanding of the underlying KG, we present an ontology-guided, hybrid prompt learning strategy that integrates KG ontology into the learning process of hybrid prompts (e.g., discrete and continuous vectors). We also present several task-specific decoding strategies to ensure the correctness and executability of generated SPARQL queries in both stages. Experimental results demonstrate that OntoSCPrompt performs as well as SOTA approaches without retraining on a number of KGQA datasets such as CWQ, WebQSP and LC-QuAD 1.0 in a resource-efficient manner and can generalize well to unseen domain-specific KGs like DBLP-QuAD and CoyPu KG Code: \href{https://github.com/LongquanJiang/OntoSCPrompt}{https://github.com/LongquanJiang/OntoSCPrompt}

[Arxiv](https://arxiv.org/abs/2502.03992)