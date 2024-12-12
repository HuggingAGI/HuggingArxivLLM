# 利用大型语言模型，将金融数据与新闻文章相结合来预测股票价格走势
发布时间：2024年11月02日

`智能金融`
> Combining Financial Data and News Articles for Stock Price Movement Prediction Using Large Language Models
>
> 预测金融市场和股票价格的变动，得分析公司业绩、历史价格走势、行业特定事件，还有像社交媒体和新闻报道这类人为因素的影响。我们认为财务报告（像损益表、资产负债表、现金流量表）、历史价格数据和近期新闻文章能共同体现上述因素。我们把表格形式的财务数据跟文本新闻文章结合起来，运用预训练的大型语言模型（LLMs）去预测市场动态。LLMs 的最新研究显示，它们能完成表格和文本分类任务，所以成了我们给多模态数据分类的主要模型。我们使用检索增强技术，检索并把与公司有关的新闻文章的相关部分附加到财务指标上，在零、二和四样本的设定下提示 LLMs。我们的数据集涵盖了从不同来源收集的新闻文章、历史股票价格以及 20 家在股票市场不同行业交易量最高的公司的财务报告数据。我们为基于 LLM 的分类器采用了近期发布的语言模型，包括 GPT-3 和 4 以及 LLaMA-2 和 3 模型。我们推出了一个基于 LLM 的分类器，能够利用表格（结构化）和文本（非结构化）数据的组合执行分类任务。通过使用这个模型，我们预测了数据集中给定股票的价格走势，在 3 个月和 6 个月期间的加权 F1 分数分别是 58.5％和 59.1％，马修斯相关系数都是 0.175。
>
> https://arxiv.org/abs/2411.01368

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.01368](https://arxiv.org/abs/2411.01368)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)