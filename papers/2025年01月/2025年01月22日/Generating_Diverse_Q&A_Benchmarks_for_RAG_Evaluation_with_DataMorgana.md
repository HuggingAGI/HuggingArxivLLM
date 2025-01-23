# 利用 DataMorgana 生成多样化问答基准，助力 RAG 评估

发布时间：2025年01月22日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统的评估和基准测试工具DataMorgana的开发。论文的核心内容围绕如何生成多样化的合成问答对以更好地评估RAG系统，特别是在特定领域场景中的应用。因此，这篇论文应归类为RAG。` `信息检索` `问答系统`

> Generating Diverse Q&A Benchmarks for RAG Evaluation with DataMorgana

# 摘要

> # 评估检索增强生成（RAG）系统，尤其是在特定领域场景中，需要能够满足应用需求的基准测试。由于真实数据难以获取，通常采用基于LLM的方法生成合成数据。现有方案多为通用型：给定文档，生成问题以构建问答对。然而，尽管生成的问题可能单独来看不错，但它们往往缺乏多样性，难以全面覆盖真实用户与RAG系统的交互方式。我们推出DataMorgana，这是一款为RAG应用量身定制的高度可定制和多样化的合成问答基准测试工具。DataMorgana支持详细配置用户和问题类别，并控制其在基准测试中的分布。它采用轻量级的两阶段流程，确保高效快速迭代，同时生成反映预期流量的基准测试。我们通过一系列实验，定量和定性地证明DataMorgana在生成词汇、句法和语义多样化问题集方面优于现有工具和方法，适用于特定领域和通用知识语料库。DataMorgana将在2025年2月初宣布的SIGIR'2025 LiveRAG挑战赛中，作为首批测试者提供给研究社区中的选定团队。

> Evaluating Retrieval-Augmented Generation (RAG) systems, especially in domain-specific contexts, requires benchmarks that address the distinctive requirements of the applicative scenario. Since real data can be hard to obtain, a common strategy is to use LLM-based methods to generate synthetic data. Existing solutions are general purpose: given a document, they generate a question to build a Q&A pair. However, although the generated questions can be individually good, they are typically not diverse enough to reasonably cover the different ways real end-users can interact with the RAG system. We introduce here DataMorgana, a tool for generating highly customizable and diverse synthetic Q&A benchmarks tailored to RAG applications. DataMorgana enables detailed configurations of user and question categories and provides control over their distribution within the benchmark. It uses a lightweight two-stage process, ensuring efficiency and fast iterations, while generating benchmarks that reflect the expected traffic. We conduct a thorough line of experiments, showing quantitatively and qualitatively that DataMorgana surpasses existing tools and approaches in producing lexically, syntactically, and semantically diverse question sets across domain-specific and general-knowledge corpora. DataMorgana will be made available to selected teams in the research community, as first beta testers, in the context of the upcoming SIGIR'2025 LiveRAG challenge to be announced in early February 2025.

[Arxiv](https://arxiv.org/abs/2501.12789)