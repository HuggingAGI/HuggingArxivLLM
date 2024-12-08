# CausalStock：用于新闻驱动的股票走势预测的深度端到端因果发现
发布时间：2024年11月10日

`智能金融`
> CausalStock: Deep End-to-end Causal Discovery for News-driven Stock Movement Prediction
>
> 在新闻驱动的多股票走势预测任务中，现有工作中存在两个未得到很好解决的问题。一方面，在利用其他股票的价格信息实现准确的股票走势预测时，“关系发现”是关键部分。鉴于股票关系通常是单向的，例如“供应商 - 消费者”关系，因果关系更适合捕捉股票之间的影响。另一方面，新闻数据中存在大量噪声，导致难以提取有效信息。考虑到这两个问题，我们提出了一个名为 CausalStock 的新型框架用于新闻驱动的多股票走势预测，它发现了股票之间的时间因果关系。我们设计了一个依赖滞后的时间因果发现机制来对时间因果图分布进行建模。然后采用功能因果模型来封装发现的因果关系并预测股票走势。此外，我们利用大型语言模型（LLM）出色的文本评估能力，提出了一种去噪新闻编码器，从大量新闻数据中提取有用信息。实验结果表明，CausalStock 在从美国、中国、日本和英国市场收集的六个真实世界数据集中，对于新闻驱动的多股票走势预测和多股票走势预测任务，都优于强大的基线。此外，得益于因果关系，CausalStock 可以提供具有良好可解释性的清晰预测机制。
>
> https://arxiv.org/abs/2411.06391

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.06391](https://arxiv.org/abs/2411.06391)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)