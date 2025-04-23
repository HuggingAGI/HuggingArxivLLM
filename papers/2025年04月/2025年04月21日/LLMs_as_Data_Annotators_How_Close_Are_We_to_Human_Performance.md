# LLMs能否媲美人工标注？我们离人类水平还有多远

发布时间：2025年04月21日

`LLM应用` `命名实体识别`

> LLMs as Data Annotators: How Close Are We to Human Performance

# 摘要

> 在自然语言处理（NLP）领域，微调大型语言模型（LLMs）虽然有效，但离不开高质量的标注数据。然而，手动标注数据耗时耗力且成本高昂。为了解决这一难题，LLMs越来越多地被用于自动化标注过程，其中在上下文中学习（ICL）方法尤为常见，即通过在提示中提供与任务相关的示例来提升性能。然而，手动挑选上下文示例不仅效率低下，还可能影响模型表现。本文通过全面实验，对比了多种LLMs在命名实体识别（NER）任务中的表现，涵盖了不同嵌入模型，并在多个数据集上进行了测试。评估对象包括参数量约为70亿和700亿的模型，既有专有模型，也有非专有模型。此外，借助增强生成（RAG）的成功经验，本文提出了一种新方法，通过自动检索上下文示例来弥补ICL的不足，从而提升模型性能。研究结果表明，选择合适的LLM和嵌入模型至关重要，需权衡LLM规模与预期性能，并将研究重点转向更具挑战性的数据集。

> In NLP, fine-tuning LLMs is effective for various applications but requires high-quality annotated data. However, manual annotation of data is labor-intensive, time-consuming, and costly. Therefore, LLMs are increasingly used to automate the process, often employing in-context learning (ICL) in which some examples related to the task are given in the prompt for better performance. However, manually selecting context examples can lead to inefficiencies and suboptimal model performance. This paper presents comprehensive experiments comparing several LLMs, considering different embedding models, across various datasets for the Named Entity Recognition (NER) task. The evaluation encompasses models with approximately $7$B and $70$B parameters, including both proprietary and non-proprietary models. Furthermore, leveraging the success of Retrieval-Augmented Generation (RAG), it also considers a method that addresses the limitations of ICL by automatically retrieving contextual examples, thereby enhancing performance. The results highlight the importance of selecting the appropriate LLM and embedding model, understanding the trade-offs between LLM sizes and desired performance, and the necessity to direct research efforts towards more challenging datasets.

[Arxiv](https://arxiv.org/abs/2504.15022)