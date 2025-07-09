# 水库聊天：基于LLM与知识图谱的交互式文档增强系统（面向ReservoirPy）

发布时间：2025年07月04日

`RAG

理由：这篇论文主要探讨了检索增强生成（RAG）技术在提升大型语言模型（LLMs）能力方面的应用，特别是在代码开发和水库计算领域。通过整合外部知识和使用知识图谱，该方法旨在减少模型的幻觉现象并提高事实准确性。虽然论文提到了LLM的应用，但其核心方法和贡献集中在RAG技术上，因此归类为RAG。` `水库计算` `代码开发`

> ReservoirChat: Interactive Documentation Enhanced with LLM and Knowledge Graph for ReservoirPy

# 摘要

> 我们推出了一款工具，旨在提升大型语言模型（LLMs）在基于ReservoirPy库的代码开发支持以及水库计算领域复杂问题解答方面的能力。通过检索增强生成（RAG）和知识图谱整合外部知识，我们的方法致力于减少模型的幻觉现象，提升生成回答的事实准确性。该系统提供类似ChatGPT的交互体验，专为ReservoirPy设计，让用户能够编写、调试和理解Python代码，同时获取专业的领域见解。在我们的评估中，尽管像ChatGPT-4o和NotebookLM这样的专有模型在一般知识问题上表现略胜一筹，但我们的模型在编程任务上表现更优，并显著超越了其基础模型Codestral-22B。

> We introduce a tool designed to improve the capabilities of Large Language Models (LLMs) in assisting with code development using the ReservoirPy library, as well as in answering complex questions in the field of Reservoir Computing. By incorporating external knowledge through Retrieval-Augmented Generation (RAG) and knowledge graphs, our approach aims to reduce hallucinations and increase the factual accuracy of generated responses. The system provides an interactive experience similar to ChatGPT, tailored specifically for ReservoirPy, enabling users to write, debug, and understand Python code while accessing reliable domain-specific insights. In our evaluation, while proprietary models such as ChatGPT-4o and NotebookLM performed slightly better on general knowledge questions, our model outperformed them on coding tasks and showed a significant improvement over its base model, Codestral-22B.

[Arxiv](https://arxiv.org/abs/2507.05279)