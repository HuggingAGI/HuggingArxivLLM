# ReMatch技术利用LLMs的力量，实现了检索增强型模式匹配，让数据结构间的对应关系更加精准高效。

发布时间：2024年03月03日

`LLM应用`

> ReMatch: Retrieval Enhanced Schema Matching with LLMs

# 摘要

> 在数据整合领域，模式匹配是一项至关重要的任务，它旨在协调源数据库与目标数据库的模式以建立二者元素间的联系。然而，这项任务难度颇高，主要受到文本和语义多样性及模式规模差异的影响。尽管已有大量研究尝试运用机器学习解决这一问题，但这些方法普遍存在准确率低、依赖人工模式映射训练模型或因隐私保护而无法获取源数据库模式数据等问题。本文提出一种创新方法——ReMatch，借助于检索增强型大规模语言模型（LLMs）实现模式匹配，无需预先设定映射关系、进行模型训练，也不需直接访问源数据库数据。具体而言，ReMatch 首先将目标模式的表格与源模式的属性转化为结构化段落文档。然后，针对每个源属性文档，按照语义关联性检索出 $J$ 个代表目标模式表格的文档。接着，为每个源表格构建提示信息，其中包括其所有属性及其描述，以及先前从顶级检索结果中挑选出的 $J$ 张目标表格的所有属性。在此基础上，我们利用 LLMs 和提示信息执行匹配任务，从而为每个源属性生成包含 $K$ 个可能匹配项的排序列表。实验证明，在处理大型真实世界模式时，ReMatch 能显著提升匹配效能，超越其他机器学习方法。摆脱了对训练数据的依赖，ReMatch 成为实际应用场景的理想选择。

> Schema matching is a crucial task in data integration, involving the alignment of a source database schema with a target schema to establish correspondence between their elements. This task is challenging due to textual and semantic heterogeneity, as well as differences in schema sizes. Although machine-learning-based solutions have been explored in numerous studies, they often suffer from low accuracy, require manual mapping of the schemas for model training, or need access to source schema data which might be unavailable due to privacy concerns. In this paper we present a novel method, named ReMatch, for matching schemas using retrieval-enhanced Large Language Models (LLMs). Our method avoids the need for predefined mapping, any model training, or access to data in the source database. In the ReMatch method the tables of the target schema and the attributes of the source schema are first represented as structured passage-based documents. For each source attribute document, we retrieve $J$ documents, representing target schema tables, according to their semantic relevance. Subsequently, we create a prompt for every source table, comprising all its attributes and their descriptions, alongside all attributes from the set of top $J$ target tables retrieved previously. We employ LLMs using this prompt for the matching task, yielding a ranked list of $K$ potential matches for each source attribute. Our experimental results on large real-world schemas demonstrate that ReMatch significantly improves matching capabilities and outperforms other machine learning approaches. By eliminating the requirement for training data, ReMatch becomes a viable solution for real-world scenarios.

[Arxiv](https://arxiv.org/abs/2403.01567)