# # 评估标准：探索CUBE数据集中的解释性评估新框架

发布时间：2025年03月31日

`LLM应用`

> Rubrik's Cube: Testing a New Rubric for Evaluating Explanations on the CUBE dataset

# 摘要

> 大型语言模型（LLMs）凭借其强大的性能和易用性，正在越来越多地被应用于解释生成任务。然而，尽管这些模型已被广泛采用，但它们生成的解释却经常出现可靠性问题，导致用户难以辨别好坏解释。为解决这一难题，我们提出了Rubrik的CUBE评估体系。这是一个以教育理念为启发的评估框架，包含26,000个解释样本。这些解释由人类和六款开源及闭源大型语言模型撰写，并根据CUBE框架进行质量标注。CUBE数据集专注于两个推理任务和两个语言任务，为全面验证我们的评估体系提供了丰富的多样性。通过Rubrik，我们发现解释质量受任务特性和感知难度的影响。进一步分析表明，低质量解释主要源于大模型生成解释缺乏简洁性，而非连贯性或词汇选择问题。完整的数据集、评估框架和代码将在论文接收后公开。

> The performance and usability of Large-Language Models (LLMs) are driving their use in explanation generation tasks. However, despite their widespread adoption, LLM explanations have been found to be unreliable, making it difficult for users to distinguish good from bad explanations. To address this issue, we present Rubrik's CUBE, an education-inspired rubric and a dataset of 26k explanations, written and later quality-annotated using the rubric by both humans and six open- and closed-source LLMs. The CUBE dataset focuses on two reasoning and two language tasks, providing the necessary diversity for us to effectively test our proposed rubric. Using Rubrik, we find that explanations are influenced by both task and perceived difficulty. Low quality stems primarily from a lack of conciseness in LLM-generated explanations, rather than cohesion and word choice. The full dataset, rubric, and code will be made available upon acceptance.

[Arxiv](https://arxiv.org/abs/2503.23899)