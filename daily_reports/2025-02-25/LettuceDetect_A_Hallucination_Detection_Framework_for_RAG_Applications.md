# LettuceDetect: 一款专为 RAG 应用设计的幻觉识别框架
发布时间：2025年02月24日

`RAG`
> LettuceDetect: A Hallucination Detection Framework for RAG Applications
>
> 尽管检索增强生成（RAG）系统引入了外部知识源，但幻觉答案的问题依然存在。我们提出了LettuceDetect框架，针对现有方法的两大关键问题：传统编码器方法的上下文窗口限制，以及基于LLM方法的计算低效。该框架凭借ModernBERT的长上下文处理能力（支持长达8k tokens），并基于RAGTruth基准数据集进行训练。与所有之前的基于编码器模型相比，我们的方法表现出更优性能，同时规模仅为最优模型的1/30。此外，在与大多数基于提示的方法对比中，LettuceDetect同样表现优异。LettuceDetect是一个基于token分类的模型，能够处理上下文-问题-答案三元组，从而在token级别识别无支持的声明。在RAGTruth语料库上的评估显示，示例级别检测的F1分数达到79.22%，较之前最优的基于编码器架构Luna提升了14.8%。此外，该系统在单个GPU上每秒可处理30至60个示例，使其更适用于实际RAG应用场景。
>
> https://arxiv.org/abs/2502.17125

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.17125](https://arxiv.org/abs/2502.17125)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)