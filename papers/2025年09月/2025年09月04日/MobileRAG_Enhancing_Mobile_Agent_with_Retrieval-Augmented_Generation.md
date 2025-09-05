# MobileRAG：检索增强生成赋能移动智能体

发布时间：2025年09月04日

`RAG` `基础理论`

> MobileRAG: Enhancing Mobile Agent with Retrieval-Augmented Generation

# 摘要

> 智能手机已成为人们日常生活中不可或缺的一部分，几乎渗透到现代社会的各个角落。随着大型语言模型（LLMs）的持续发展，众多基于LLM的移动智能体应运而生。这些智能体能够精准解析多样化的用户查询，并自动协助用户完成复杂或重复性操作。然而，当前智能体存在三大痛点：1）严重依赖LLM的理解能力，可能导致任务中因误操作或步骤遗漏而出错；2）缺乏与外部环境的交互，当应用无法满足用户查询时往往会终止任务；3）缺乏记忆能力，每次指令都需重新构建界面，且无法从过往错误中学习和纠正。为缓解上述问题，我们提出了MobileRAG——一个基于检索增强生成（RAG）技术的移动智能体增强框架，包含InterRAG、LocalRAG和MemRAG三个模块。该框架借助RAG技术，能更快更精准地识别用户查询，完成复杂及长序列的移动任务。此外，为更全面评估MobileRAG的性能，我们还推出了MobileRAG-Eval基准——它更具挑战性，包含大量需外部知识辅助的复杂真实世界移动任务。在MobileRAG-Eval上的大量实验结果显示，MobileRAG能轻松应对真实世界的移动任务，相比现有最先进方法，在操作步骤更少的情况下性能提升了10.3%。相关代码已公开：https://github.com/liuxiaojieOutOfWorld/MobileRAG_arxiv

> Smartphones have become indispensable in people's daily lives, permeating nearly every aspect of modern society. With the continuous advancement of large language models (LLMs), numerous LLM-based mobile agents have emerged. These agents are capable of accurately parsing diverse user queries and automatically assisting users in completing complex or repetitive operations. However, current agents 1) heavily rely on the comprehension ability of LLMs, which can lead to errors caused by misoperations or omitted steps during tasks, 2) lack interaction with the external environment, often terminating tasks when an app cannot fulfill user queries, and 3) lack memory capabilities, requiring each instruction to reconstruct the interface and being unable to learn from and correct previous mistakes. To alleviate the above issues, we propose MobileRAG, a mobile agents framework enhanced by Retrieval-Augmented Generation (RAG), which includes InterRAG, LocalRAG, and MemRAG. It leverages RAG to more quickly and accurately identify user queries and accomplish complex and long-sequence mobile tasks. Additionally, to more comprehensively assess the performance of MobileRAG, we introduce MobileRAG-Eval, a more challenging benchmark characterized by numerous complex, real-world mobile tasks that require external knowledge assistance. Extensive experimental results on MobileRAG-Eval demonstrate that MobileRAG can easily handle real-world mobile tasks, achieving 10.3\% improvement over state-of-the-art methods with fewer operational steps. Our code is publicly available at: https://github.com/liuxiaojieOutOfWorld/MobileRAG_arxiv

[Arxiv](https://arxiv.org/abs/2509.03891)