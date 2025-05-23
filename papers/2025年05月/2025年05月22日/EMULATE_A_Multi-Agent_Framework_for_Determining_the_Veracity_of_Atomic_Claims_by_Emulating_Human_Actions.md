# EMULATE：一个通过模拟人类行为评估原子声明真实性的多智能体框架

发布时间：2025年05月22日

`Agent` `信息检索` `人工智能`

> EMULATE: A Multi-Agent Framework for Determining the Veracity of Atomic Claims by Emulating Human Actions

# 摘要

> 判断原子声明的真实性是许多事实核查系统的关键环节。现有方法通常通过查询搜索引擎获取证据，再将这些证据与声明提供给大型语言模型进行分类，但这种流程与人类的实际操作有所不同。为了解决这一问题，近期研究提出了迭代式证据检索，允许在必要时多次收集证据。在此基础上，我们开发了名为EMULATE的新声明验证系统，通过多智能体框架模拟人类行为，每个智能体负责任务的一部分，如根据标准排序搜索结果或评估网页内容。在多个基准上的实验表明，EMULATE较以往方法有显著提升，证明了多智能体框架的有效性。

> Determining the veracity of atomic claims is an imperative component of many recently proposed fact-checking systems. Many approaches tackle this problem by first retrieving evidence by querying a search engine and then performing classification by providing the evidence set and atomic claim to a large language model, but this process deviates from what a human would do in order to perform the task. Recent work attempted to address this issue by proposing iterative evidence retrieval, allowing for evidence to be collected several times and only when necessary. Continuing along this line of research, we propose a novel claim verification system, called EMULATE, which is designed to better emulate human actions through the use of a multi-agent framework where each agent performs a small part of the larger task, such as ranking search results according to predefined criteria or evaluating webpage content. Extensive experiments on several benchmarks show clear improvements over prior work, demonstrating the efficacy of our new multi-agent framework.

[Arxiv](https://arxiv.org/abs/2505.16576)