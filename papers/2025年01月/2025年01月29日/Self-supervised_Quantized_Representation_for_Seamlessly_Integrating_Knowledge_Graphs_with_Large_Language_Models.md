# 自监督量化表示：知识图谱与大型语言模型的无缝集成

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要讨论了如何将知识图谱（KG）的结构信息与大型语言模型（LLMs）进行整合，并提出了一种两阶段框架来实现这一目标。论文的核心在于通过学习和应用实体的量化代码，使得KG与LLMs能够高效整合，并在KG链接预测和三元组分类任务中表现出色。这属于LLM在实际应用中的优化和改进，因此归类为LLM应用。` `知识图谱`

> Self-supervised Quantized Representation for Seamlessly Integrating Knowledge Graphs with Large Language Models

# 摘要

> 知识图谱（KG）与自然语言之间的天然差距使得如何将KG的结构信息与大型语言模型（LLMs）无缝整合成为一个关键问题。为此，我们提出了一个两阶段框架，通过学习和应用实体的量化代码，实现KG与LLMs的高效整合。首先，我们提出了一种自监督量化表示（SSQR）方法，将KG的结构和语义知识压缩为离散代码（token），使其与语言格式对齐。接着，我们设计了KG指令跟随数据，将这些代码作为特征直接输入LLMs，从而实现无缝整合。实验表明，SSQR生成的代码更具区分性，优于现有无监督量化方法。此外，微调后的LLaMA2和LLaMA3.1在KG链接预测和三元组分类任务中表现优异，每个实体仅需16个token，远少于传统提示方法的数千个token。

> Due to the presence of the natural gap between Knowledge Graph (KG) structures and the natural language, the effective integration of holistic structural information of KGs with Large Language Models (LLMs) has emerged as a significant question. To this end, we propose a two-stage framework to learn and apply quantized codes for each entity, aiming for the seamless integration of KGs with LLMs. Firstly, a self-supervised quantized representation (SSQR) method is proposed to compress both KG structural and semantic knowledge into discrete codes (\ie, tokens) that align the format of language sentences. We further design KG instruction-following data by viewing these learned codes as features to directly input to LLMs, thereby achieving seamless integration. The experiment results demonstrate that SSQR outperforms existing unsupervised quantized methods, producing more distinguishable codes. Further, the fine-tuned LLaMA2 and LLaMA3.1 also have superior performance on KG link prediction and triple classification tasks, utilizing only 16 tokens per entity instead of thousands in conventional prompting methods.

[Arxiv](https://arxiv.org/abs/2501.18119)