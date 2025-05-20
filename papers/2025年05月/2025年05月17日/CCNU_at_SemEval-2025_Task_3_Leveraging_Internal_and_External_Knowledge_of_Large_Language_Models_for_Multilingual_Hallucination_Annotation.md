# 华中师范大学在SemEval-2025任务3中的研究工作：通过大型语言模型的内部与外部知识实现多语言幻觉标注

发布时间：2025年05月17日

`LLM应用

理由：这篇论文展示了Mu-SHROOM系统，该系统利用多个大型语言模型（LLMs）来检测跨语言问答系统中的幻觉。它专注于将LLMs应用于具体任务，属于LLM的应用层面。` `问答系统` `幻觉识别`

> CCNU at SemEval-2025 Task 3: Leveraging Internal and External Knowledge of Large Language Models for Multilingual Hallucination Annotation

# 摘要

> 我们展示了华中师范大学（CCNU）团队开发的 Mu-SHROOM 共享任务系统，该系统专注于识别跨 14 种不同语言的问答系统中的幻觉。我们的方法利用了多个具有不同专长领域的大型语言模型（LLMs），并行使用它们来标注幻觉，模拟了一个 crowdsourcing 注释流程。此外，每个基于 LLM 的注释器在注释过程中整合了与输入相关的内部和外部知识。利用开源的 LLM DeepSeek-V3，我们的系统在 Hindi 数据中获得了第一名，并在其他七种语言中获得了前五名。在这篇论文中，我们还讨论了我们在开发过程中探索的不成功的方法，并分享了参与此共享任务所获得的关键见解。

> We present the system developed by the Central China Normal University (CCNU) team for the Mu-SHROOM shared task, which focuses on identifying hallucinations in question-answering systems across 14 different languages. Our approach leverages multiple Large Language Models (LLMs) with distinct areas of expertise, employing them in parallel to annotate hallucinations, effectively simulating a crowdsourcing annotation process. Furthermore, each LLM-based annotator integrates both internal and external knowledge related to the input during the annotation process. Using the open-source LLM DeepSeek-V3, our system achieves the top ranking (\#1) for Hindi data and secures a Top-5 position in seven other languages. In this paper, we also discuss unsuccessful approaches explored during our development process and share key insights gained from participating in this shared task.

[Arxiv](https://arxiv.org/abs/2505.11965)