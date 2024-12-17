# EventSum：一个针对中文多新闻文档的大规模、以事件为核心的摘要数据集

发布时间：2024年12月16日

`LLM应用` `事件处理`

> EventSum: A Large-Scale Event-Centric Summarization Dataset for Chinese Multi-News Documents

# 摘要

> 在现实生活中，诸如重大灾害、大型体育赛事这类动态事件，会随时间持续演变。获取这些事件的概览有助于人们迅速了解状况，并更有效地应对。然而这颇具挑战，因为事件关键信息往往分散于多个文档中，涉及复杂的事件知识理解与推理，这在过往工作中研究较少。于是，我们提出了以事件为中心的多文档摘要（ECS）任务，旨在依据多个相关新闻文档为给定事件生成简洁且全面的摘要。基于此，我们构建了 EventSum 数据集，它利用百度百科条目构建而成，并经过大量人工标注，以推动相关研究。这是首个大规模中文多文档摘要数据集，涵盖 5100 个事件和总计 57984 个新闻文档，平均每个事件有 11.4 个输入新闻文档和 13471 个字符。为保证数据质量并降低潜在的数据泄漏风险，我们采用多阶段标注方式对测试集进行人工标注。鉴于事件相关信息的复杂性，现有的指标难以全面评估生成摘要的质量。我们设计了特定指标，包括事件召回率、论点召回率、因果召回率和时间召回率以及相应的计算方法用于评估。我们在 EventSum 上开展了全面实验，以评估先进的长上下文大型语言模型（LLMs）在该任务中的表现。我们的实验结果表明：1）以事件为中心的多文档摘要任务对现有的长上下文 LLMs 而言仍具挑战性；2）我们设计的召回率指标对于评估摘要信息的全面性至关重要。

> In real life, many dynamic events, such as major disasters and large-scale sports events, evolve continuously over time. Obtaining an overview of these events can help people quickly understand the situation and respond more effectively. This is challenging because the key information of the event is often scattered across multiple documents, involving complex event knowledge understanding and reasoning, which is under-explored in previous work. Therefore, we proposed the Event-Centric Multi-Document Summarization (ECS) task, which aims to generate concise and comprehensive summaries of a given event based on multiple related news documents. Based on this, we constructed the EventSum dataset, which was constructed using Baidu Baike entries and underwent extensive human annotation, to facilitate relevant research. It is the first large scale Chinese multi-document summarization dataset, containing 5,100 events and a total of 57,984 news documents, with an average of 11.4 input news documents and 13,471 characters per event. To ensure data quality and mitigate potential data leakage, we adopted a multi-stage annotation approach for manually labeling the test set. Given the complexity of event-related information, existing metrics struggle to comprehensively assess the quality of generated summaries. We designed specific metrics including Event Recall, Argument Recall, Causal Recall, and Temporal Recall along with corresponding calculation methods for evaluation. We conducted comprehensive experiments on EventSum to evaluate the performance of advanced long-context Large Language Models (LLMs) on this task. Our experimental results indicate that: 1) The event-centric multi-document summarization task remains challenging for existing long-context LLMs; 2) The recall metrics we designed are crucial for evaluating the comprehensiveness of the summary information.

[Arxiv](https://arxiv.org/abs/2412.11814)