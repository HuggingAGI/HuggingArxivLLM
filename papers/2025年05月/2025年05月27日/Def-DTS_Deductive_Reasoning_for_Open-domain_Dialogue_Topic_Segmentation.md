# Def-DTS：基于演绎推理的开放领域对话主题分割

发布时间：2025年05月27日

`LLM应用` `对话处理`

> Def-DTS: Deductive Reasoning for Open-domain Dialogue Topic Segmentation

# 摘要

> 对话主题分割（DTS）旨在将对话划分为连贯的段落。尽管DTS在NLP下游任务中发挥着关键作用，但数据短缺、标注模糊和解决方案复杂度上升等问题长期困扰着这一领域。尽管大型语言模型（LLMs）和推理策略取得了进展，但这些成果尚未被广泛应用到DTS中。本文提出了Def-DTS：一种基于演绎推理的开放领域对话主题分割方法。该方法通过LLM支持的多步演绎推理提升DTS性能，并支持通过中间结果进行案例研究。我们的方法采用结构化提示技术，实现双向上下文总结、话语意图分类和演绎式主题转移检测。在意图分类过程中，我们提出了通用意图列表，用于领域无关的对话意图分类。实验结果表明，Def-DTS在各种对话场景下始终优于传统方法和最新技术，每个子任务均对性能提升有所贡献，尤其在减少类型2错误方面表现突出。我们还探讨了自动标注的可能性，强调了LLM推理技术在DTS中的重要性。

> Dialogue Topic Segmentation (DTS) aims to divide dialogues into coherent segments. DTS plays a crucial role in various NLP downstream tasks, but suffers from chronic problems: data shortage, labeling ambiguity, and incremental complexity of recently proposed solutions. On the other hand, Despite advances in Large Language Models (LLMs) and reasoning strategies, these have rarely been applied to DTS. This paper introduces Def-DTS: Deductive Reasoning for Open-domain Dialogue Topic Segmentation, which utilizes LLM-based multi-step deductive reasoning to enhance DTS performance and enable case study using intermediate result. Our method employs a structured prompting approach for bidirectional context summarization, utterance intent classification, and deductive topic shift detection. In the intent classification process, we propose the generalizable intent list for domain-agnostic dialogue intent classification. Experiments in various dialogue settings demonstrate that Def-DTS consistently outperforms traditional and state-of-the-art approaches, with each subtask contributing to improved performance, particularly in reducing type 2 error. We also explore the potential for autolabeling, emphasizing the importance of LLM reasoning techniques in DTS.

[Arxiv](https://arxiv.org/abs/2505.21033)