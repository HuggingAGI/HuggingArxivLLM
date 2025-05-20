# 华中师范大学在SemEval-2025任务3中的研究：通过结合大型语言模型的内部与外部知识实现多语言幻觉标注

发布时间：2025年05月17日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在检测跨语言问答系统中的幻觉的应用。虽然它涉及多个LLMs的使用，但其核心是实际应用，特别是跨语言幻觉检测的系统构建和评估，因此属于LLM应用类别。` `问答系统`

> CCNU at SemEval-2025 Task 3: Leveraging Internal and External Knowledge of Large Language Models for Multilingual Hallucination Annotation

# 摘要

> 我们介绍了华中师范大学（CCNU）团队开发的用于Mu-SHROOM共享任务的系统，该系统专注于检测跨14种语言的问答系统中的幻觉。我们的方法利用了多个具有不同专业领域的大型语言模型（LLMs），并行标注幻觉，模拟 crowdsourcing 标注过程。每个基于LLM的标注器在标注过程中整合了与输入相关的内部和外部知识。借助开源的LLM DeepSeek-V3，我们的系统在印地语数据中取得了最高排名（#1），并在其他七种语言中获得了前五名的位置。本文还讨论了我们在开发过程中探索的不成功方法，并分享了参与此共享任务所获得的关键见解。

> We present the system developed by the Central China Normal University (CCNU) team for the Mu-SHROOM shared task, which focuses on identifying hallucinations in question-answering systems across 14 different languages. Our approach leverages multiple Large Language Models (LLMs) with distinct areas of expertise, employing them in parallel to annotate hallucinations, effectively simulating a crowdsourcing annotation process. Furthermore, each LLM-based annotator integrates both internal and external knowledge related to the input during the annotation process. Using the open-source LLM DeepSeek-V3, our system achieves the top ranking (\#1) for Hindi data and secures a Top-5 position in seven other languages. In this paper, we also discuss unsuccessful approaches explored during our development process and share key insights gained from participating in this shared task.

[Arxiv](https://arxiv.org/abs/2505.11965)