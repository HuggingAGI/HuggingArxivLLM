# MRAG：一个用于时间敏感型问答的模块化检索框架
发布时间：2024年12月19日

`RAG`
> MRAG: A Modular Retrieval Framework for Time-Sensitive Question Answering
>
> 理解时间关系并回答时间敏感问题，对于由大型语言模型（LLMs）驱动的问答系统而言，极为关键但也充满挑战。现有的办法，要么用新事实更新LLMs的参数知识，这既耗费资源又常不现实，要么把LLMs与外部知识检索（即检索增强生成）相融合。然而，现成的检索器常常难以找出需要深度时间推理的相关文档。为了系统探究时间敏感型问答，我们引入了TempRAGEval基准，它通过融入时间扰动和黄金证据标签来重新利用现有数据集。不出所料，所有现有的检索方法在处理这些时间推理密集型问题时都颇为吃力。我们进一步提出了模块化检索（MRAG），这是一个无需训练的框架，涵盖三个模块：（1）问题处理，将问题拆解为主要内容和时间约束；（2）检索与总结，检索证据并依据主要内容利用LLMs进行总结；（3）语义-时间混合排序，基于语义和时间相关性为每个证据总结打分。在TempRAGEval上，MRAG在检索性能方面显著优于基线检索器，进而使最终答案的准确性得到进一步提升。
>
> https://arxiv.org/abs/2412.15540

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.15540](https://arxiv.org/abs/2412.15540)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)