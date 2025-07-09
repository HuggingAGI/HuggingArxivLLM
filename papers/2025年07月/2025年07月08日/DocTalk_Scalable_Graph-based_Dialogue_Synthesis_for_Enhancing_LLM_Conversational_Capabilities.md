# DocTalk：基于大规模图结构的对话合成技术，助力提升大型语言模型（LLM）的对话能力

发布时间：2025年07月08日

`LLM应用

理由：这篇论文讨论了如何通过合成对话数据来提升大型语言模型在多轮对话任务中的表现，属于应用层面的研究。` `对话系统`

> DocTalk: Scalable Graph-based Dialogue Synthesis for Enhancing LLM Conversational Capabilities

# 摘要

> 大型语言模型（LLMs）在多轮对话任务中被广泛应用，但其预训练数据主要由连续文本组成，这可能造成能力需求与训练范式之间的不匹配。我们提出了一种新方法，通过从现有文本语料库中合成对话数据来解决这一问题。我们设计了一种流水线，能够将多个相关文档聚类转换为扩展的多轮、多主题信息检索对话。通过将该流水线应用于维基百科文章，我们创建了DocTalk——一个多轮预训练对话语料库，包含超过73万次长对话。我们假设，在预训练过程中接触此类合成对话结构可以提升LLMs的基本多轮对话能力，如上下文记忆和理解。实证研究表明，在预训练过程中引入DocTalk可使上下文记忆和理解能力提升高达40%，同时不影响基础性能。DocTalk已在https://huggingface.co/datasets/AmazonScience/DocTalk上线。

> Large Language Models (LLMs) are increasingly employed in multi-turn conversational tasks, yet their pre-training data predominantly consists of continuous prose, creating a potential mismatch between required capabilities and training paradigms. We introduce a novel approach to address this discrepancy by synthesizing conversational data from existing text corpora. We present a pipeline that transforms a cluster of multiple related documents into an extended multi-turn, multi-topic information-seeking dialogue. Applying our pipeline to Wikipedia articles, we curate DocTalk, a multi-turn pre-training dialogue corpus consisting of over 730k long conversations. We hypothesize that exposure to such synthesized conversational structures during pre-training can enhance the fundamental multi-turn capabilities of LLMs, such as context memory and understanding. Empirically, we show that incorporating DocTalk during pre-training results in up to 40% gain in context memory and understanding, without compromising base performance. DocTalk is available at https://huggingface.co/datasets/AmazonScience/DocTalk.

[Arxiv](https://arxiv.org/abs/2507.05750)