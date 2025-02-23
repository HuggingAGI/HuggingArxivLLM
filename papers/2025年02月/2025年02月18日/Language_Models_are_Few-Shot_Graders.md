# 语言模型摇身一变，成为 Few-Shot 评分专家！

发布时间：2025年02月18日

`LLM应用` `教育评分系统`

> Language Models are Few-Shot Graders

# 摘要

> 为学生作业提供评价是有效学习的关键环节，自动化这一流程可以显著减轻人工评分者的负担。借助大型语言模型（LLMs）的进步，自动简答题评分（ASAG）系统为评估开放性学生回答并提供即时反馈提供了一个有前景的解决方案。本文介绍了一个基于最新LLMs的ASAG流水线。我们的新LLM-based ASAG流水线在相同数据集上优于现有的定制模型。我们还比较了三个OpenAI模型的评分表现：GPT-4、GPT-4o和o1-preview。结果显示，GPT-4o在准确性和成本效益之间达到了最佳平衡，而o1-preview尽管准确性更高，但因错误方差较大，实用性较低。我们研究了在提示中加入教师评分示例的效果，采用不加示例、随机选择和基于检索增强生成（RAG）的选择策略。发现表明，提供评分示例提高了评分准确性，其中基于RAG的选择策略表现更优。此外，整合评分标准通过提供结构化的评估标准进一步提升了准确性。

> Providing evaluations to student work is a critical component of effective student learning, and automating its process can significantly reduce the workload on human graders. Automatic Short Answer Grading (ASAG) systems, enabled by advancements in Large Language Models (LLMs), offer a promising solution for assessing and providing instant feedback for open-ended student responses. In this paper, we present an ASAG pipeline leveraging state-of-the-art LLMs. Our new LLM-based ASAG pipeline achieves better performances than existing custom-built models on the same datasets. We also compare the grading performance of three OpenAI models: GPT-4, GPT-4o, and o1-preview. Our results demonstrate that GPT-4o achieves the best balance between accuracy and cost-effectiveness. On the other hand, o1-preview, despite higher accuracy, exhibits a larger variance in error that makes it less practical for classroom use. We investigate the effects of incorporating instructor-graded examples into prompts using no examples, random selection, and Retrieval-Augmented Generation (RAG)-based selection strategies. Our findings indicate that providing graded examples enhances grading accuracy, with RAG-based selection outperforming random selection. Additionally, integrating grading rubrics improves accuracy by offering a structured standard for evaluation.

[Arxiv](https://arxiv.org/abs/2502.13337)