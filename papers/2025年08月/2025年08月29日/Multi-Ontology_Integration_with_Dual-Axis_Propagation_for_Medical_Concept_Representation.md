# 基于双轴传播的多本体整合：医学概念表示

发布时间：2025年08月29日

`LLM应用` `医疗健康`

> Multi-Ontology Integration with Dual-Axis Propagation for Medical Concept Representation

# 摘要

> 医学本体图谱借助结构化关系，将外部知识与电子健康记录中的医学编码建立映射。通过领域认可的关联（如父子关系），预测模型能整合相关概念的上下文信息，生成更丰富的医学概念表示。然而，现有研究多局限于单一本体系统，或孤立地处理多个本体系统（如疾病、药物、诊疗操作）的领域知识，未能将其整合为统一的学习框架。这导致概念表示学习常局限于本体内部关系，而忽略了跨本体的关联。

为此，本文提出LINKO——一种基于大型语言模型（LLM）的增强型集成本体学习框架。该框架通过在异构本体系统内部及系统间实现双轴知识传播，同步利用多个本体图谱，从而提升医学概念表示学习效果。具体而言，LINKO首先借助LLMs为本体概念嵌入提供图检索增强的初始化：通过精心设计包含概念描述的提示词，并结合本体上下文进一步优化。其次，该方法通过双轴知识传播联合学习多本体图谱中的医学概念：（1）本体内部跨层级的垂直传播；（2）各层级内并行的本体间水平传播。最后，通过两个公共数据集的大量实验验证，LINKO性能显著优于现有最优基线。作为可与现有电子健康记录预测模型兼容的插件式编码器，LINKO在数据稀缺及罕见病预测场景中进一步展现了更强的鲁棒性。

> Medical ontology graphs map external knowledge to medical codes in electronic health records via structured relationships. By leveraging domain-approved connections (e.g., parent-child), predictive models can generate richer medical concept representations by incorporating contextual information from related concepts. However, existing literature primarily focuses on incorporating domain knowledge from a single ontology system, or from multiple ontology systems (e.g., diseases, drugs, and procedures) in isolation, without integrating them into a unified learning structure. Consequently, concept representation learning often remains limited to intra-ontology relationships, overlooking cross-ontology connections. In this paper, we propose LINKO, a large language model (LLM)-augmented integrative ontology learning framework that leverages multiple ontology graphs simultaneously by enabling dual-axis knowledge propagation both within and across heterogeneous ontology systems to enhance medical concept representation learning. Specifically, LINKO first employs LLMs to provide a graph-retrieval-augmented initialization for ontology concept embedding, through an engineered prompt that includes concept descriptions, and is further augmented with ontology context. Second, our method jointly learns the medical concepts in diverse ontology graphs by performing knowledge propagation in two axes: (1) intra-ontology vertical propagation across hierarchical ontology levels and (2) inter-ontology horizontal propagation within every level in parallel. Last, through extensive experiments on two public datasets, we validate the superior performance of LINKO over state-of-the-art baselines. As a plug-in encoder compatible with existing EHR predictive models, LINKO further demonstrates enhanced robustness in scenarios involving limited data availability and rare disease prediction.

[Arxiv](https://arxiv.org/abs/2508.21320)