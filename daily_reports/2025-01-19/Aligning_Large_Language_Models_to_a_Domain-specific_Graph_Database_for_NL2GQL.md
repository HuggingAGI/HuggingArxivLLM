# 将大型语言模型与领域专用图数据库对齐，实现NL2GQL
发布时间：2024年09月05日

`代码编写`
> Aligning Large Language Models to a Domain-specific Graph Database for NL2GQL
>
> # 摘要
图数据库（Graph DB）在金融、社交网络和医学等多个领域应用广泛。然而，将自然语言（NL）转换为图查询语言（GQL），即NL2GQL，由于其复杂性和专业性，带来了巨大挑战。尽管一些方法尝试利用大型语言模型（LLMs）解决类似任务（如text2SQL），但在特定领域的NL2GQL任务中，缺乏领域特定的NL-GQL数据对，使得LLMs与图数据库的对齐变得复杂。为此，我们提出了一套明确的流程：首先，利用ChatGPT生成NL-GQL数据对，并通过图数据库进行自我指导；随后，使用生成的数据微调LLMs，确保其与图数据库的对齐。此外，我们发现相关模式在高效生成准确GQL中的重要性，因此引入了一种提取相关模式作为输入上下文的方法。我们使用从金融和医学领域的图数据库中构建的两个数据集（FinGQL和MediGQL）进行评估。实验结果显示，我们的方法显著优于基线方法，在FinGQL和MediGQL上分别提升了5.90和6.36个绝对点的EM，以及6.00和7.09个绝对点的EX。
>
> https://arxiv.org/abs/2402.16567

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2402.16567](https://arxiv.org/abs/2402.16567)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)