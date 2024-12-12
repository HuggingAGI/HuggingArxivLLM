# 适应非平稳环境：在知识图谱中运用多臂老虎机增强的检索增强生成
发布时间：2024年12月10日

`RAG`
> Adapting to Non-Stationary Environments: Multi-Armed Bandit Enhanced Retrieval-Augmented Generation on Knowledge Graphs
>
> 尽管大型语言模型在诸多自然语言处理任务中表现卓越，但其在大量世界知识的记忆方面仍存在显著局限。近期研究显示，借助检索增强生成（RAG）框架，并结合以结构化形式封装大量事实数据的知识图谱，能够显著增强大型语言模型的推理能力。然而，在实际场景中部署这类系统面临挑战：非平稳环境的持续演变可能致使性能降低，而用户满意度则需要在性能与响应能力之间精细平衡。为应对这些挑战，我们推出了一个多目标多臂老虎机强化的 RAG 框架，在实践中丰富且不断变化的检索情境下，由具备不同能力的多种检索方法予以支持。在此框架中，每种检索方法都被视作一个独特的“臂”。系统利用实时用户反馈来适应动态环境，依据输入查询以及每个臂的历史多目标性能来选择合适的检索方法。在两个基准 KGQA 数据集上开展的大量实验表明，我们的方法在非平稳环境下显著优于基线方法，同时在平稳环境中达到了顶尖性能。代码和数据可在 https://github.com/FUTUREEEEEE/Dynamic-RAG.git 获取。
>
> https://arxiv.org/abs/2412.07618

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.07618](https://arxiv.org/abs/2412.07618)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)