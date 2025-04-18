# CodeGRAF：为增强检索的跨语言代码生成提取复合语法图。
发布时间：2024年05月02日

`RAG`
> CodeGRAG: Extracting Composed Syntax Graphs for Retrieval Augmented Cross-Lingual Code Generation
>
> 运用大型语言模型来生成代码，在软件开发领域呈现出革命性的前景。尽管这些通用的大型语言模型已经展现出了一定的智能，但在代码生成的特定领域，它们的表现仍有提升空间，这主要是由于自然语言与编程语言之间的语法差异和词汇不匹配。编程语言的逻辑性和复杂性也增加了正确生成代码的难度。目前，为了寻找更优的解决方案，通常需要对大型语言模型进行多次提示，这不仅成本高昂。本文提出了一种名为“语法图检索增强的代码生成”（CodeGRAG）的新方法，旨在提升大型语言模型在单轮代码生成任务中的表现。CodeGRAG 能够提取并概括代码块的控制流和数据流，弥合编程语言与自然语言之间的鸿沟。这种方法提炼出的外部结构知识不仅模拟了代码块的内在流程，还能帮助大型语言模型更深入地理解代码的语法结构，并在不同编程语言之间架起沟通的桥梁。CodeGRAG 显著增强了大型语言模型的代码生成能力，甚至在跨语言代码生成方面也展现出了性能提升，比如能够将 Python 代码转换成 C++。
>
> https://arxiv.org/abs/2405.02355

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.02355/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.02355/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.02355/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.02355/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.02355](https://arxiv.org/abs/2405.02355)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886