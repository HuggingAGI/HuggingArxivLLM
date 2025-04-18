# ConExion: 结合大型语言模型的概念提取

发布时间：2025年04月17日

`LLM应用` `知识图谱`

> ConExion: Concept Extraction with Large Language Models

# 摘要

> 本文提出了一种基于预训练大型语言模型 (LLMs) 从文档中提取概念的新方法。与传统方法仅提取文档中重要信息的关键短语不同，我们的方法更进一步，致力于提取与特定领域相关的所有当前概念。通过在两个广泛使用的基准数据集上的全面评估，我们证明了与现有最优技术相比，我们的方法显著提升了F1分数。此外，我们还探索了在这些模型中使用提示进行无监督概念提取的潜力。提取的概念不仅能够支持本体论覆盖范围的评估，还能促进本体论学习，充分展现了大型语言模型在概念提取任务中的强大能力。我们的源代码和数据集已公开发布在 https://github.com/ISE-FIZKarlsruhe/concept_extraction，欢迎访问查看。

> In this paper, an approach for concept extraction from documents using pre-trained large language models (LLMs) is presented. Compared with conventional methods that extract keyphrases summarizing the important information discussed in a document, our approach tackles a more challenging task of extracting all present concepts related to the specific domain, not just the important ones. Through comprehensive evaluations of two widely used benchmark datasets, we demonstrate that our method improves the F1 score compared to state-of-the-art techniques. Additionally, we explore the potential of using prompts within these models for unsupervised concept extraction. The extracted concepts are intended to support domain coverage evaluation of ontologies and facilitate ontology learning, highlighting the effectiveness of LLMs in concept extraction tasks. Our source code and datasets are publicly available at https://github.com/ISE-FIZKarlsruhe/concept_extraction.

[Arxiv](https://arxiv.org/abs/2504.12915)