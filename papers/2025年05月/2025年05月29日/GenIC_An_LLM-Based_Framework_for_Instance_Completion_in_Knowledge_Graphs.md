# GenIC：基于大型语言模型的知识图谱实例补全框架

发布时间：2025年05月29日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）来解决知识图谱补全问题，特别是通过端到端的生成式框架GenIC来实现实例补全。论文的具体内容涉及如何利用LLM从实体描述中提取事实并识别知识图谱模式，这表明它是在应用层面上探讨LLM的能力，而不是研究LLM本身的理论或机制。因此，这篇论文应归类为LLM应用。` `知识图谱`

> GenIC: An LLM-Based Framework for Instance Completion in Knowledge Graphs

# 摘要

> 知识图谱补全旨在通过添加代表事实的新三元组，填补知识库中的空白。该任务的复杂性取决于三元组中已有多少部分是已知的。实例补全涉及在仅给定头实体的情况下预测关系和尾实体（h, ?, ?）。值得注意的是，现代知识库通常包含实体描述和类型，这些可以为推理缺失的事实提供有价值的上下文。通过利用这些文本描述以及大型语言模型从它们中提取事实并识别知识图谱模式的能力，我们提出了一种基于LLM的端到端实例补全方法。具体来说，我们引入了GenIC：一种两步的生成式实例补全框架。第一步专注于属性预测，将其视为一个多标签分类任务。第二步是链接预测，将其视为一个生成式的序列到序列任务。在三个数据集上的实验结果表明，我们的方法优于现有的基线。我们的代码可在https://github.com/amal-gader/genic获取。

> Knowledge graph completion aims to address the gaps of knowledge bases by adding new triples that represent facts. The complexity of this task depends on how many parts of a triple are already known. Instance completion involves predicting the relation-tail pair when only the head is given (h, ?, ?). Notably, modern knowledge bases often contain entity descriptions and types, which can provide valuable context for inferring missing facts. By leveraging these textual descriptions and the ability of large language models to extract facts from them and recognize patterns within the knowledge graph schema, we propose an LLM-powered, end-to-end instance completion approach. Specifically, we introduce GenIC: a two-step Generative Instance Completion framework. The first step focuses on property prediction, treated as a multi-label classification task. The second step is link prediction, framed as a generative sequence-to-sequence task. Experimental results on three datasets show that our method outperforms existing baselines. Our code is available at https://github.com/amal-gader/genic.

[Arxiv](https://arxiv.org/abs/2505.24036)