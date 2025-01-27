# 快速图思考：LLM在知识图谱上的广深快推理

发布时间：2025年01月24日

`RAG

理由：这篇论文主要讨论了图检索增强生成（GRAG）的改进方法，通过将知识图谱（KGs）等图信息融入大规模语言模型（LLMs）来减少幻觉现象。论文提出的FastToG方法通过社区检测和两阶段社区剪枝来提升检索效率，并将社区图结构转换为文本以便LLMs理解。这些内容与检索增强生成（RAG）密切相关，因此将其分类为RAG。` `知识图谱`

> Fast Think-on-Graph: Wider, Deeper and Faster Reasoning of Large Language Model on Knowledge Graph

# 摘要

> # 摘要
图检索增强生成（GRAG）通过将知识图谱（KGs）等图信息融入大规模语言模型（LLMs），进一步提升了RAG系统，以减少幻觉现象。然而，现有GRAG仍存在局限：1）简单范式难以应对复杂问题，因其从KGs中捕获的相关性狭窄且浅显；2）与KGs强耦合的方法在图密集时计算成本高且耗时。本文提出快速图思考（FastToG），一种创新范式，使LLMs能在KGs中“逐社区”思考。FastToG通过社区检测捕获更深层次相关性，并采用两阶段社区剪枝——粗剪枝和细剪枝——实现快速检索。此外，我们还开发了两种社区到文本的方法，将社区图结构转换为文本，便于LLMs理解。实验表明，FastToG在准确性、推理速度和可解释性上均优于现有方法。

> Graph Retrieval Augmented Generation (GRAG) is a novel paradigm that takes the naive RAG system a step further by integrating graph information, such as knowledge graph (KGs), into large-scale language models (LLMs) to mitigate hallucination. However, existing GRAG still encounter limitations: 1) simple paradigms usually fail with the complex problems due to the narrow and shallow correlations capture from KGs 2) methods of strong coupling with KGs tend to be high computation cost and time consuming if the graph is dense. In this paper, we propose the Fast Think-on-Graph (FastToG), an innovative paradigm for enabling LLMs to think ``community by community" within KGs. To do this, FastToG employs community detection for deeper correlation capture and two stages community pruning - coarse and fine pruning for faster retrieval. Furthermore, we also develop two Community-to-Text methods to convert the graph structure of communities into textual form for better understanding by LLMs. Experimental results demonstrate the effectiveness of FastToG, showcasing higher accuracy, faster reasoning, and better explainability compared to the previous works.

[Arxiv](https://arxiv.org/abs/2501.14300)