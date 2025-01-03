# 提升答案归因，助力大型语言模型生成忠实文本

发布时间：2024年10月22日

`RAG

理由：该论文主要关注的是如何将大型语言模型（LLMs）生成的答案与支持这些答案的来源进行关联，即答案归因。这涉及到检索增强生成（Retrieval-Augmented Generation, RAG）的核心思想，即通过检索外部信息来增强LLM生成的内容。论文中提到的“答案分割”和“证据检索”都是RAG技术的关键组成部分。因此，这篇论文应被分类为RAG。` `问答系统`

> Enhancing Answer Attribution for Faithful Text Generation with Large Language Models

# 摘要

> 近年来，大型语言模型（LLMs）的普及改变了用户与AI对话系统的互动方式。提升LLM生成答案的可信度，关键在于将回答中的主张追溯到支持它们的来源，这一过程称为答案归因。尽管已有研究开始探索LLMs中的答案归因任务，但仍面临挑战。本文首先通过案例研究评估了现有答案归因方法的有效性，重点关注答案分割和证据检索。基于发现的不足，我们提出了新方法，旨在生成更独立且情境化的主张，以优化检索和归因效果。实验表明，新方法显著提升了答案归因组件的性能。最后，我们探讨了该任务的未来研究方向。

> The increasing popularity of Large Language Models (LLMs) in recent years has changed the way users interact with and pose questions to AI-based conversational systems. An essential aspect for increasing the trustworthiness of generated LLM answers is the ability to trace the individual claims from responses back to relevant sources that support them, the process known as answer attribution. While recent work has started exploring the task of answer attribution in LLMs, some challenges still remain. In this work, we first perform a case study analyzing the effectiveness of existing answer attribution methods, with a focus on subtasks of answer segmentation and evidence retrieval. Based on the observed shortcomings, we propose new methods for producing more independent and contextualized claims for better retrieval and attribution. The new methods are evaluated and shown to improve the performance of answer attribution components. We end with a discussion and outline of future directions for the task.

[Arxiv](https://arxiv.org/abs/2410.17112)