# GRAFT: 面向文档级机器翻译的基于图的流程感知智能体框架

发布时间：2025年07月04日

`LLM应用`

> GRAFT: A Graph-based Flow-aware Agentic Framework for Document-level Machine Translation

# 摘要

> 文档级机器翻译（DocMT）在捕捉 discourse级别现象时常常力不从心。现有方法依赖启发式规则将文档分割为 discourse单元，但这些分割结果往往与准确翻译所需的真正 discourse结构不符，导致翻译过程中难以保持文档的一致性。为了解决这一难题，我们提出了用于文档级翻译的图增强智能体框架（GRAFT），这是一种基于图的新型 DocMT 系统，借助大型语言模型（LLM）智能体实现文档翻译。我们的方法将分割、基于有向无环图（DAG）的依赖建模以及 discourse 意识的翻译整合到一个统一框架中。在八个翻译方向和六个不同领域进行的实验表明，GRAFT 的性能显著优于现有 DocMT 系统。具体而言，与强大的基线相比，GRAFT 在 IWSLT2017 的 TED 测试集上平均提升了 2.8 d BLEU，而在特定领域的英汉翻译中提升了 2.3 d BLEU。此外，我们的分析表明，GRAFT 在处理 discourse级别现象方面表现出色，能够生成连贯且上下文准确的翻译。

> Document level Machine Translation (DocMT) approaches often struggle with effectively capturing discourse level phenomena. Existing approaches rely on heuristic rules to segment documents into discourse units, which rarely align with the true discourse structure required for accurate translation. Otherwise, they fail to maintain consistency throughout the document during translation. To address these challenges, we propose Graph Augmented Agentic Framework for Document Level Translation (GRAFT), a novel graph based DocMT system that leverages Large Language Model (LLM) agents for document translation. Our approach integrates segmentation, directed acyclic graph (DAG) based dependency modelling, and discourse aware translation into a cohesive framework. Experiments conducted across eight translation directions and six diverse domains demonstrate that GRAFT achieves significant performance gains over state of the art DocMT systems. Specifically, GRAFT delivers an average improvement of 2.8 d BLEU on the TED test sets from IWSLT2017 over strong baselines and 2.3 d BLEU for domain specific translation from English to Chinese. Moreover, our analyses highlight the consistent ability of GRAFT to address discourse level phenomena, yielding coherent and contextually accurate translations.

[Arxiv](https://arxiv.org/abs/2507.03311)