# # NLI4DB：面向数据库的自然语言界面系统性综述

发布时间：2025年03月04日

`LLM应用

摘要中讨论了自然语言数据库接口（NLIDB）系统，并特别提到使用大语言模型（LLM）进行Text2SQL任务，这属于LLM的具体应用。因此，这篇论文应归类为LLM应用。` `数据库`

> NLI4DB: A Systematic Review of Natural Language Interfaces for Databases

# 摘要

> 随着生活各领域对数据库查询需求的持续增长，研究者们对自然语言数据库接口（NLIDB）投入了大量关注。本文全面综述了近期提出的各类NLIDB系统。首先，我们介绍了自然语言处理技术、可执行数据库语言以及自然语言与可执行语言之间的中间表示形式，随后概述了从自然语言到可执行数据库语言的翻译过程。该过程分为三个阶段：（i）自然语言预处理，（ii）自然语言理解，（iii）自然语言翻译。预处理阶段采用传统方法和数据驱动方法。传统方法依赖预定义规则和语法规则，涉及正则表达式、依存句法分析和命名实体识别等技术。数据驱动方法则依赖大规模数据和机器学习模型，采用词嵌入和模式连接等技术。自然语言理解方法分为三类：基于规则、基于机器学习和混合方法。随后，我们描述了在关系型和时空型数据库上构建可执行语言的一般流程。接着，介绍了将自然语言转化为可执行语言的常见基准测试和评估指标，并探讨了生成新基准的方法。最后，我们总结了NLIDB系统的分类、发展与增强，讨论了与NLIDB相关的深度语言理解与数据库交互技术，包括（i）使用大语言模型（LLM）进行Text2SQL任务，（ii）从SQL生成自然语言解释，（iii）将语音查询转换为SQL。

> As the demand for querying databases in all areas of life continues to grow, researchers have devoted significant attention to the natural language interface for databases (NLIDB). This paper presents a comprehensive survey of recently proposed NLIDBs. We begin with a brief introduction to natural language processing techniques, executable database languages and the intermediate representation between natural language and executable language, and then provide an overview of the translation process from natural language to executable database language. The translation process is divided into three stages: (i) natural language preprocessing, (ii) natural language understanding, and (iii) natural language translation. Traditional and data-driven methods are utilized in the preprocessing stage. Traditional approaches rely on predefined rules and grammars, and involve techniques such as regular expressions, dependency parsing and named entity recognition. Data-driven approaches depend on large-scale data and machine learning models, using techniques including word embedding and pattern linking. Natural language understanding methods are classified into three categories: (i) rule-based, (ii) machine learning-based, and (iii) hybrid. We then describe a general construction process for executable languages over relational and spatio-temporal databases. Subsequently, common benchmarks and evaluation metrics for transforming natural language into executable language are presented, and methods for generating new benchmarks are explored. Finally, we summarize the classification, development, and enhancement of NLIDB systems, and discuss deep language understanding and database interaction techniques related to NLIDB, including (i) using LLM for Text2SQL tasks, (ii) generating natural language interpretations from SQL, and (iii) transforming speech queries into SQL.

[Arxiv](https://arxiv.org/abs/2503.02435)