# 优图-GraphRAG：面向图检索增强复杂推理的垂直统一智能体

发布时间：2025年08月27日

`RAG` `基础理论`

> Youtu-GraphRAG: Vertically Unified Agents for Graph Retrieval-Augmented Complex Reasoning

# 摘要

> 图检索增强生成（GraphRAG）通过将碎片化知识梳理为显式结构化的图，大幅提升了大型语言模型的复杂推理能力。然而，以往研究多孤立优化图构建或图检索环节，性能不尽如人意，尤其在领域迁移场景下表现更差。为此，本文提出垂直统一的智能体范式Youtu-GraphRAG，将整个框架深度整合为有机整体。具体实现包括：（i）引入种子图模式，通过限定目标实体类型、关系及属性类型约束自动抽取智能体，并支持对未知领域的持续扩展以提升可扩展性；（ii）为从模式中提炼更高阶知识，创新提出双感知社区检测方法，融合结构拓扑与子图语义实现知识的全面组织，自然生成层次化知识树，支持基于社区摘要的自上而下过滤与自下而上推理；（iii）设计智能体检索器，通过解读同一图模式将复杂查询拆解为可并行处理的子查询，并通过迭代反思实现更深度的推理；（iv）针对预训练LLM的知识泄露问题，构建定制匿名数据集并设计“匿名还原”新任务，以精准评估GraphRAG框架的真实性能。在六个高难度基准数据集上的实验验证了Youtu-GraphRAG的强鲁棒性：与现有最优方法相比，token成本降低高达90.71%，准确率提升16.62%，显著优化了帕累托前沿。结果表明，该方法具备优异的适应性，仅需微调模式即可实现跨领域的无缝迁移。

> Graph retrieval-augmented generation (GraphRAG) has effectively enhanced large language models in complex reasoning by organizing fragmented knowledge into explicitly structured graphs. Prior efforts have been made to improve either graph construction or graph retrieval in isolation, yielding suboptimal performance, especially when domain shifts occur. In this paper, we propose a vertically unified agentic paradigm, Youtu-GraphRAG, to jointly connect the entire framework as an intricate integration. Specifically, (i) a seed graph schema is introduced to bound the automatic extraction agent with targeted entity types, relations and attribute types, also continuously expanded for scalability over unseen domains; (ii) To obtain higher-level knowledge upon the schema, we develop novel dually-perceived community detection, fusing structural topology with subgraph semantics for comprehensive knowledge organization. This naturally yields a hierarchical knowledge tree that supports both top-down filtering and bottom-up reasoning with community summaries; (iii) An agentic retriever is designed to interpret the same graph schema to transform complex queries into tractable and parallel sub-queries. It iteratively performs reflection for more advanced reasoning; (iv) To alleviate the knowledge leaking problem in pre-trained LLM, we propose a tailored anonymous dataset and a novel 'Anonymity Reversion' task that deeply measures the real performance of the GraphRAG frameworks. Extensive experiments across six challenging benchmarks demonstrate the robustness of Youtu-GraphRAG, remarkably moving the Pareto frontier with up to 90.71% saving of token costs and 16.62% higher accuracy over state-of-the-art baselines. The results indicate our adaptability, allowing seamless domain transfer with minimal intervention on schema.

[Arxiv](https://arxiv.org/abs/2508.19855)