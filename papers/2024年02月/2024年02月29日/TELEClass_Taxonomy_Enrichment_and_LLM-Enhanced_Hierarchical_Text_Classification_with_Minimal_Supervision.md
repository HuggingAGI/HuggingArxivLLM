# TELEClass 是一种创新方法，通过最小程度的监督实现对分类法的丰富和完善，并利用大型语言模型（LLM）提升层次文本分类的效果。

发布时间：2024年02月29日

`LLM应用`

> TELEClass: Taxonomy Enrichment and LLM-Enhanced Hierarchical Text Classification with Minimal Supervision

# 摘要

> 本文研究了以最小监督实现分层文本分类，仅依靠每个节点的类名指导模型学习。以往方法大多依赖于大量人工标注数据，不仅昂贵且耗时。然而，尽管大型语言模型（LLM）在零样本提示下处理多种任务表现出色，却难以应对庞大且结构化的分层标签场景。此外，现有弱监督方法仅利用分类法骨架，忽视了文本语料中蕴含的丰富类别指示特征。为此，我们提出TELEClass——一种基于分类法丰富与LLM增强的弱监督分层文本分类方案，它能自动化地从语料库挖掘类别指示主题词以充实标签分类法，并借助LLM对分层标签空间量身定制数据标注与生成过程。实验证明，TELEClass在两个公开数据集上的性能优于既有弱监督方法及基于LLM的零样本提示方法。

> Hierarchical text classification aims to categorize each document into a set of classes in a label taxonomy. Most earlier works focus on fully or semi-supervised methods that require a large amount of human annotated data which is costly and time-consuming to acquire. To alleviate human efforts, in this paper, we work on hierarchical text classification with the minimal amount of supervision: using the sole class name of each node as the only supervision. Recently, large language models (LLM) show competitive performance on various tasks through zero-shot prompting, but this method performs poorly in the hierarchical setting, because it is ineffective to include the large and structured label space in a prompt. On the other hand, previous weakly-supervised hierarchical text classification methods only utilize the raw taxonomy skeleton and ignore the rich information hidden in the text corpus that can serve as additional class-indicative features. To tackle the above challenges, we propose TELEClass, Taxonomy Enrichment and LLM-Enhanced weakly-supervised hierarchical text classification, which (1) automatically enriches the label taxonomy with class-indicative topical terms mined from the corpus to facilitate classifier training and (2) utilizes LLMs for both data annotation and creation tailored for the hierarchical label space. Experiments show that TELEClass can outperform previous weakly-supervised hierarchical text classification methods and LLM-based zero-shot prompting methods on two public datasets.

[Arxiv](https://arxiv.org/abs/2403.00165)