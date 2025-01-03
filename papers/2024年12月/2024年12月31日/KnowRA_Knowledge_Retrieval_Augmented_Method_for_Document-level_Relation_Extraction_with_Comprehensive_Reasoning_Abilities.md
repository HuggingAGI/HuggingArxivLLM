# KnowRA: 知识检索增强的文档级关系抽取方法，具备全面推理能力

发布时间：2024年12月31日

`RAG

理由：该论文提出了一种知识检索增强方法（KnowRA），通过检索外部知识库来增强文档级关系抽取（Doc-RE）的能力。这种方法涉及到检索增强生成（Retrieval-Augmented Generation, RAG）的核心思想，即通过检索外部知识来增强模型的推理能力。因此，该论文应归类为RAG。` `知识图谱`

> KnowRA: Knowledge Retrieval Augmented Method for Document-level Relation Extraction with Comprehensive Reasoning Abilities

# 摘要

> 文档级关系抽取（Doc-RE）旨在从多句中提取实体间关系。与句子级关系抽取相比，Doc-RE需要更全面的推理能力，涉及实体、上下文和外部知识的复杂跨句交互。然而，现有方法多聚焦于单一推理能力，缺乏利用外部知识进行长文档综合推理的能力。为此，我们提出了KnowRA，一种知识检索增强方法，通过综合推理自主决定是否引入外部知识辅助Doc-RE。首先，我们构建文档图进行语义编码，并集成共指消解模型以增强共指推理能力。接着，通过检索外部知识库将文档图扩展为文档知识图，并引入轴注意力机制，分别提升常识推理和逻辑推理能力。最后，我们在常识推理和共指推理模块中引入知识过滤方法，剔除无关知识。在两个数据集上的大量实验表明，我们的方法优于现有基线方法。代码已开源：https://anonymous.4open.science/r/KnowRA。

> Document-level relation extraction (Doc-RE) aims to extract relations between entities across multiple sentences. Therefore, Doc-RE requires more comprehensive reasoning abilities like humans, involving complex cross-sentence interactions between entities, contexts, and external general knowledge, compared to the sentence-level RE. However, most existing Doc-RE methods focus on optimizing single reasoning ability, but lack the ability to utilize external knowledge for comprehensive reasoning on long documents. To solve these problems, a knowledge retrieval augmented method, named KnowRA, was proposed with comprehensive reasoning to autonomously determine whether to accept external knowledge to assist DocRE. Firstly, we constructed a document graph for semantic encoding and integrated the co-reference resolution model into KnowRA to augment the co-reference reasoning ability. Then, we further expanded the document graph into a document knowledge graph by retrieving the external knowledge base and introduced the axis attention mechanism into KnowRA to improve its common-sense and logical reasoning abilities, respectively. Finally, a knowledge filtering method was presented in the common-sense and co-reference reasoning module to filter out irrelevant knowledge. Extensive experiments conducted on two datasets verified the effectiveness of our method compared to the state-of-the-art baselines. Our code is available at https://anonymous.4open.science/r/KnowRA.

[Arxiv](https://arxiv.org/abs/2501.00571)