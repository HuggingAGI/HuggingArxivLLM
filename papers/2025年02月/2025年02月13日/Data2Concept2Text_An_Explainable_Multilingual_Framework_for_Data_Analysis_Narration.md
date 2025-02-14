# 数据到概念到文本：一个可解释的多语言数据分析叙述框架

发布时间：2025年02月13日

`其他` `知识表示与自动推理`

> Data2Concept2Text: An Explainable Multilingual Framework for Data Analysis Narration

# 摘要

> 本文提出了一套完整的可解释系统，能够解读数据集，抽象潜在特征，并以自然语言描述。该系统分为两个关键阶段：(i) 从数据中提取新兴属性并转化为抽象概念；(ii) 将概念转为自然语言。尽管大型语言模型（LLMs）在自然语言生成方面表现出色，但其统计性质和复杂机制仍使其被视为黑箱，缺乏可信度。开发一个可解释的数据解释管道将有助于其在医疗信息处理等安全关键环境中的应用，并使非专家和视障人士能够访问叙述性信息。为此，我们认为知识表示和自动推理研究领域可能提供有效替代方案。在扩展之前针对第一阶段（i）的研究基础上，我们专注于第二阶段——Concept2Text。由于其可解释性，数据翻译可通过基于逻辑的规则轻松建模，再次强调了声明式编程在实现 AI 可解释性方面的作用。本文探讨了一种基于 Prolog/CLP 的重写系统，用于解释以类和关系表示的概念以及源自通用本体的常识，生成自然语言文本。其主要特点包括层次树重写、模块化多语言生成、支持语义、语法和词汇层面的等效变体，以及一个透明的基于规则的系统。我们概述了该系统的架构，并通过一些能够根据输入概念生成众多多样且等效重写的示例，展示了其灵活性。

> This paper presents a complete explainable system that interprets a set of data, abstracts the underlying features and describes them in a natural language of choice. The system relies on two crucial stages: (i) identifying emerging properties from data and transforming them into abstract concepts, and (ii) converting these concepts into natural language. Despite the impressive natural language generation capabilities demonstrated by Large Language Models, their statistical nature and the intricacy of their internal mechanism still force us to employ these techniques as black boxes, forgoing trustworthiness. Developing an explainable pipeline for data interpretation would allow facilitating its use in safety-critical environments like processing medical information and allowing non-experts and visually impaired people to access narrated information. To this end, we believe that the fields of knowledge representation and automated reasoning research could present a valid alternative. Expanding on prior research that tackled the first stage (i), we focus on the second stage, named Concept2Text. Being explainable, data translation is easily modeled through logic-based rules, once again emphasizing the role of declarative programming in achieving AI explainability. This paper explores a Prolog/CLP-based rewriting system to interpret concepts-articulated in terms of classes and relations, plus common knowledge-derived from a generic ontology, generating natural language text. Its main features include hierarchical tree rewritings, modular multilingual generation, support for equivalent variants across semantic, grammar, and lexical levels, and a transparent rule-based system. We outline the architecture and demonstrate its flexibility through some examples capable of generating numerous diverse and equivalent rewritings based on the input concept.

[Arxiv](https://arxiv.org/abs/2502.09218)