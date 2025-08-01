# 基于文本到SQL的任务导向对话本体构建

发布时间：2025年07月31日

`LLM应用

理由：论文提出了一种基于LLM的任务导向对话本体构建方法，展示了LLM在构建结构化数据库中的应用，属于LLM的应用领域。` `任务导向对话`

> Text-to-SQL Task-oriented Dialogue Ontology Construction

# 摘要

> 大型语言模型（LLMs）作为通用知识来源被广泛应用，但其依赖的参数化知识限制了模型的可解释性和可信度。在任务导向对话（TOD）系统中，为确保可解释性和可控性，系统采用外部显式本体结构化数据库，但构建此类本体需依赖手动标注或监督式训练。我们提出了一种基于Text-to-SQL的任务导向对话本体构建方法——TeQoDO。该方法无需监督，LLM通过结合其内置的SQL编程能力和提示中的对话理论，自主从零构建TOD本体。研究显示，TeQoDO在下游对话状态跟踪任务中的表现优于迁移学习方法，且所构建的本体具有竞争力。消融研究表明，对话理论在构建过程中起到了关键作用。此外，TeQoDO能够扩展以支持构建更大规模的本体，我们在维基百科和ArXiv数据集上进行了相关研究。我们认为，这是迈向更广泛应用本体以提升LLM可解释性的重要一步。

> Large language models (LLMs) are widely used as general-purpose knowledge sources, but they rely on parametric knowledge, limiting explainability and trustworthiness. In task-oriented dialogue (TOD) systems, this separation is explicit, using an external database structured by an explicit ontology to ensure explainability and controllability. However, building such ontologies requires manual labels or supervised training. We introduce TeQoDO: a Text-to-SQL task-oriented Dialogue Ontology construction method. Here, an LLM autonomously builds a TOD ontology from scratch without supervision using its inherent SQL programming capabilities combined with dialogue theory provided in the prompt. We show that TeQoDO outperforms transfer learning approaches, and its constructed ontology is competitive on a downstream dialogue state tracking task. Ablation studies demonstrate the key role of dialogue theory. TeQoDO also scales to allow construction of much larger ontologies, which we investigate on a Wikipedia and ArXiv dataset. We view this as a step towards broader application of ontologies to increase LLM explainability.

[Arxiv](https://arxiv.org/abs/2507.23358)