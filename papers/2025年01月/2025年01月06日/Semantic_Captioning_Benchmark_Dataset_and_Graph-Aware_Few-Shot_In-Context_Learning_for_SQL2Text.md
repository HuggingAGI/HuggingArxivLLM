# 语义描述：SQL2Text的基准数据集与图感知少样本上下文学习

发布时间：2025年01月06日

`LLM应用

**理由**：该论文主要探讨了如何利用大型语言模型（LLMs）将SQL查询逆向转换为自然语言描述（SQL2Text），并提出了基于GPT-4o的迭代ICL提示方法。研究重点在于LLM在代码生成和解释任务中的应用，属于LLM在实际任务中的应用场景，因此分类为LLM应用。` `软件开发`

> Semantic Captioning: Benchmark Dataset and Graph-Aware Few-Shot In-Context Learning for SQL2Text

# 摘要

> 大型语言模型（LLMs）在多种NLP任务中表现卓越，尤其是将自然语言转换为正式代码的语义解析。然而，将代码逆向转换为自然语言的语义描述任务却鲜有研究。随着LLMs广泛应用于代码生成、安全分析和教育平台，这一任务的重要性日益凸显。本文聚焦于SQL查询的描述（SQL2Text），旨在解决在LLM生成代码可能带来安全风险的时代，理解和解释SQL查询的迫切需求。我们通过引入GPT-4o的迭代ICL提示，生成多个额外语句，重新利用Text2SQL数据集进行SQL2Text，从而增强数据集在逆向任务中的鲁棒性。我们基于不同样本选择方法进行实验，强调使用更小、计算效率更高的LLMs进行上下文学习（ICL）。研究结果显示，利用SQL的图属性进行ICL样本选择，在BLEU评分上显著优于随机选择，最高提升39%，且效果优于其他方法。数据集和代码已发布：url{https://github.com/aliwister/ast-icl}。

> Large Language Models (LLMs) have demonstrated remarkable performance in various NLP tasks, including semantic parsing, which trans lates natural language into formal code representations. However, the reverse process, translating code into natural language, termed semantic captioning, has received less attention. This task is becoming increasingly important as LLMs are integrated into platforms for code generation, security analysis, and educational purposes. In this paper, we focus on the captioning of SQL query (SQL2Text) to address the critical need for understanding and explaining SQL queries in an era where LLM-generated code poses potential security risks. We repurpose Text2SQL datasets for SQL2Text by introducing an iterative ICL prompt using GPT-4o to generate multiple additional utterances, which enhances the robustness of the datasets for the reverse task. We conduct our experiments using in-context learning (ICL) based on different sample selection methods, emphasizing smaller, more computationally efficient LLMs. Our findings demonstrate that leveraging the inherent graph properties of SQL for ICL sample selection significantly outperforms random selection by up to 39% on BLEU score and provides better results than alternative methods. Dataset and codes are published: \url{https://github.com/aliwister/ast-icl}.

[Arxiv](https://arxiv.org/abs/2501.03166)