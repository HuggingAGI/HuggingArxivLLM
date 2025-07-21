# SPARQL 查询生成：LLMs 中训练数据记忆化与知识注入的影响评估

发布时间：2025年07月18日

`LLM应用` `问答系统` `知识图谱`

> SPARQL Query Generation with LLMs: Measuring the Impact of Training Data Memorization and Knowledge Injection

# 摘要

> 如今，拥有自然语言用户界面的软件的重要性不容小觑。特别是在问答系统中，根据从同一问题检索到的信息生成一个SPARQL查询（通常称为查询构建）是基于知识图谱的问答系统（KGQA）的核心任务。随着大型语言模型（LLMs）的兴起，它们被视为一种非常适合提高问答功能质量的方法，因为仍有很大的改进空间，旨在提高质量和可信度。然而，LLMs是在网络数据上进行训练的，研究人员无法控制基准或知识图谱是否已经包含在训练数据中。本文提出了一种新方法，通过在不同条件下从自然语言问题生成SPARQL查询来评估LLMs的质量：（1）零样本SPARQL生成，（2）带有知识注入，以及（3）带有“匿名化”知识注入。这使我们首次能够估计训练数据对LLMs提升的问答质量的影响。最终，这将有助于确定一种方法的可移植性，或者良好的结果是否可能主要因为基准已经包含在训练数据中（参见LLM记忆）。所开发的方法具有可移植性、鲁棒性，并支持任何知识图谱；因此，它可以轻松应用于任何KGQA或LLM，从而能够产生对实际LLM能力的一致见解。

> Nowadays, the importance of software with natural-language user interfaces cannot be underestimated. In particular, in Question Answering (QA) systems, generating a SPARQL query for a given natural-language question (often named Query Building) from the information retrieved from the same question is the central task of QA systems working over Knowledge Graphs (KGQA). Due to the rise of Large Language Models (LLMs), they are considered a well-suited method to increase the quality of the question-answering functionality, as there is still a lot of room for improvement, aiming for enhanced quality and trustworthiness. However, LLMs are trained on web data, where researchers have no control over whether the benchmark or the knowledge graph was already included in the training data. In this paper, we introduce a novel method that evaluates the quality of LLMs by generating a SPARQL query from a natural-language question under various conditions: (1) zero-shot SPARQL generation, (2) with knowledge injection, and (3) with "anonymized" knowledge injection. This enables us, for the first time, to estimate the influence of the training data on the QA quality improved by LLMs. Ultimately, this will help to identify how portable a method is or whether good results might mostly be achieved because a benchmark was already included in the training data (cf. LLM memorization). The developed method is portable, robust, and supports any knowledge graph; therefore, it could be easily applied to any KGQA or LLM, s.t., generating consistent insights into the actual LLM capabilities is possible.

[Arxiv](https://arxiv.org/abs/2507.13859)