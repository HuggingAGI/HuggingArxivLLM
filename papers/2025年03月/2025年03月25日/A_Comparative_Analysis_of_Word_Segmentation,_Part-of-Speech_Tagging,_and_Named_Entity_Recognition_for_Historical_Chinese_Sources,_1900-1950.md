# 历史中文文本（1900-1950）的分词、词性标注与命名实体识别对比研究

发布时间：2025年03月25日

`LLM应用` `历史文本处理`

> A Comparative Analysis of Word Segmentation, Part-of-Speech Tagging, and Named Entity Recognition for Historical Chinese Sources, 1900-1950

# 摘要

> 本文对比了大型语言模型（LLMs）与传统自然语言处理（NLP）工具在处理1900年至1950年中文文本中的分词、词性标注（POS）和命名实体识别（NER）任务。由于历史中文文本的表意文字特性、缺乏自然分词边界以及语言的重大变迁，这些文档给文本分析带来了独特挑战。基于上海图书馆共和期刊语料库的样本文本，我们对Jieba、spaCy等传统工具与GPT-4o、Claude 3.5和GLM系列等LLMs进行了对比测试。实验结果显示，尽管LLMs的计算成本显著高于传统方法，但在所有评估指标上均表现更优，体现了准确性和效率之间的权衡。此外，LLMs在处理特定类型文本（如诗歌）和时间跨度（即1920年前后文本）上的表现尤为突出，证明其上下文学习能力能够通过减少对领域特定训练数据的依赖，为历史文本的NLP研究开辟新路径。

> This paper compares large language models (LLMs) and traditional natural language processing (NLP) tools for performing word segmentation, part-of-speech (POS) tagging, and named entity recognition (NER) on Chinese texts from 1900 to 1950. Historical Chinese documents pose challenges for text analysis due to their logographic script, the absence of natural word boundaries, and significant linguistic changes. Using a sample dataset from the Shanghai Library Republican Journal corpus, traditional tools such as Jieba and spaCy are compared to LLMs, including GPT-4o, Claude 3.5, and the GLM series. The results show that LLMs outperform traditional methods in all metrics, albeit at considerably higher computational costs, highlighting a trade-off between accuracy and efficiency. Additionally, LLMs better handle genre-specific challenges such as poetry and temporal variations (i.e., pre-1920 versus post-1920 texts), demonstrating that their contextual learning capabilities can advance NLP approaches to historical texts by reducing the need for domain-specific training data.

[Arxiv](https://arxiv.org/abs/2503.19844)