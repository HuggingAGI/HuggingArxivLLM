# 借助自适应多方面检索增强，利用大型语言模型实现知识图谱问答

发布时间：2024年12月24日

`LLM应用` `知识图谱` `逻辑推理`

> Harnessing Large Language Models for Knowledge Graph Question Answering via Adaptive Multi-Aspect Retrieval-Augmentation

# 摘要

> 大型语言模型（LLMs）能力出众，然而在应对复杂知识推理任务时，会有幻觉和知识过时的情况，致使输出的内容与事实不符。此前的研究尝试从大规模知识图谱（KGs）中检索事实知识，以辅助LLMs进行逻辑推理和答案预测来解决此问题。但这类方法往往会引入噪声和无关数据，在涉及多个知识方面的广泛上下文时尤其如此。如此一来，LLM的注意力可能会从问题和相关信息上跑偏。在我们的研究中，我们推出了一个基于知识图谱的自适应多方面检索增强（Amar）框架。此方法检索包含实体、关系和子图的知识，并把每段检索到的文本转化为提示嵌入。Amar框架有两个关键子组件：1）一个自对齐模块，用于对齐实体、关系和子图之间的共性，以增强检索到的文本，从而降低噪声干扰；2）一个相关性门控模块，通过软门来获取问题与多方面检索数据之间的相关性得分，以确定哪些信息可用来增强LLMs的输出，甚至将某些信息完全过滤掉。我们的方法在WebQSP和CWQ这两个常见数据集上表现出色，准确率比最佳竞争对手提高了1.9％，在逻辑形式生成方面比直接将检索到的文本作为上下文提示的方法提高了6.6％。这些成果证明了Amar在提升LLMs推理能力方面的有效性。

> Large Language Models (LLMs) demonstrate remarkable capabilities, yet struggle with hallucination and outdated knowledge when tasked with complex knowledge reasoning, resulting in factually incorrect outputs. Previous studies have attempted to mitigate it by retrieving factual knowledge from large-scale knowledge graphs (KGs) to assist LLMs in logical reasoning and prediction of answers. However, this kind of approach often introduces noise and irrelevant data, especially in situations with extensive context from multiple knowledge aspects. In this way, LLM attention can be potentially mislead from question and relevant information. In our study, we introduce an Adaptive Multi-Aspect Retrieval-augmented over KGs (Amar) framework. This method retrieves knowledge including entities, relations, and subgraphs, and converts each piece of retrieved text into prompt embeddings. The Amar framework comprises two key sub-components: 1) a self-alignment module that aligns commonalities among entities, relations, and subgraphs to enhance retrieved text, thereby reducing noise interference; 2) a relevance gating module that employs a soft gate to learn the relevance score between question and multi-aspect retrieved data, to determine which information should be used to enhance LLMs' output, or even filtered altogether. Our method has achieved state-of-the-art performance on two common datasets, WebQSP and CWQ, showing a 1.9\% improvement in accuracy over its best competitor and a 6.6\% improvement in logical form generation over a method that directly uses retrieved text as context prompts. These results demonstrate the effectiveness of Amar in improving the reasoning of LLMs.

[Arxiv](https://arxiv.org/abs/2412.18537)