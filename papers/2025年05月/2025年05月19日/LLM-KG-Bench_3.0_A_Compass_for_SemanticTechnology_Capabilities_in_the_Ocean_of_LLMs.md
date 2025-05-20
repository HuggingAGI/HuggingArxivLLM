# LLM-KG-Bench 3.0: 指引语义技术能力在大型语言模型海洋中航行的评估基准

发布时间：2025年05月19日

`LLM应用` `知识图谱` `语义网`

> LLM-KG-Bench 3.0: A Compass for SemanticTechnology Capabilities in the Ocean of LLMs

# 摘要

> 当前大语言模型（LLMs）不仅能协助编写程序代码，还能处理多种任务，但它们是否也能在知识图谱（KGs）领域大展身手？在语义网与知识图谱工程（KGE）领域，哪种LLM表现最为出色？是否无需手动检查大量答案即可确定这一点？这些问题的答案，正是3.0版本的LLM-KG-Bench框架所要揭晓的。该框架包含一组可扩展的任务，用于自动化评估LLM的回答，并覆盖了语义技术相关工作的多个方面。本文将详细介绍3.0版本的LLM-KG-Bench框架，并展示通过该框架和多个先进LLM生成的提示、答案及评估数据集。自框架初版发布以来，已进行了多项重大改进，包括提供更大灵活性以处理评估任务的更新任务API、优化的任务设计以及通过vllm库对多种开源模型的扩展支持等。借助30多个当代开源和专有LLM，我们生成了一个全面的数据集，能够创建展示模型在处理RDF和SPARQL方面能力的示例卡片，并比较它们在Turtle和JSON-LD RDF序列化任务上的表现。

> Current Large Language Models (LLMs) can assist developing program code beside many other things, but can they support working with Knowledge Graphs (KGs) as well? Which LLM is offering the best capabilities in the field of Semantic Web and Knowledge Graph Engineering (KGE)? Is this possible to determine without checking many answers manually? The LLM-KG-Bench framework in Version 3.0 is designed to answer these questions. It consists of an extensible set of tasks for automated evaluation of LLM answers and covers different aspects of working with semantic technologies. In this paper the LLM-KG-Bench framework is presented in Version 3 along with a dataset of prompts, answers and evaluations generated with it and several state-of-the-art LLMs. Significant enhancements have been made to the framework since its initial release, including an updated task API that offers greater flexibility in handling evaluation tasks, revised tasks, and extended support for various open models through the vllm library, among other improvements. A comprehensive dataset has been generated using more than 30 contemporary open and proprietary LLMs, enabling the creation of exemplary model cards that demonstrate the models' capabilities in working with RDF and SPARQL, as well as comparing their performance on Turtle and JSON-LD RDF serialization tasks.

[Arxiv](https://arxiv.org/abs/2505.13098)