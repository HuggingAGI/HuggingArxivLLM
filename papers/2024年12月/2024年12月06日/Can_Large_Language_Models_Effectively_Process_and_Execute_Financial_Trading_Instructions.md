# 大型语言模型能否有效处理并执行金融交易指令？

发布时间：2024年12月06日

`LLM应用` `交易系统`

> Can Large Language Models Effectively Process and Execute Financial Trading Instructions?

# 摘要

> 大型语言模型（LLMs）的发展为金融业带来了变革机遇，尤其在金融交易领域。然而，如何将LLMs与交易系统相融合成了难题。为应对此问题，我们提出了一个智能交易订单识别管道，能在交易执行中把交易订单转化为标准格式。该系统提升了人类交易员与交易平台的交互能力，还解决了交易执行中错误信息获取的问题。另外，我们构建了一个包含500条数据的交易订单数据集，用以模拟真实交易场景。并且，我们设计了若干指标，通过在我们的数据集中对五个前沿的LLMs进行实验，对数据集的可靠性以及大模型在金融领域的生成能力进行全面评估。结果显示，尽管LLMs展现出高生成率（87.50%至98.33%）和出色的跟进率，但在准确性（5%至10%）和完整性方面遭遇重大挑战，缺失率颇高（14.29%至67.29%）。此外，LLMs倾向于过度询问，这表明大型模型往往会收集更多信息，给信息安全带来一定挑战。

> The development of Large Language Models (LLMs) has created transformative opportunities for the financial industry, especially in the area of financial trading. However, how to integrate LLMs with trading systems has become a challenge. To address this problem, we propose an intelligent trade order recognition pipeline that enables the conversion of trade orders into a standard format in trade execution. The system improves the ability of human traders to interact with trading platforms while addressing the problem of misinformation acquisition in trade execution. In addition, we have created a trade order dataset of 500 pieces of data to simulate real-world trading scenarios. Moreover, we designed several metrics to provide a comprehensive assessment of dataset reliability and the generative power of big models in finance by experimenting with five state-of-the-art LLMs on our dataset. The results indicate that while LLMs demonstrate high generation rates (87.50% to 98.33%) and perfect follow-up rates, they face significant challenges in accuracy (5% to 10%) and completeness, with high missing rates (14.29% to 67.29%). In addition, LLMs tend to over-interrogate, suggesting that large models tend to collect more information, carrying certain challenges for information security.

[Arxiv](https://arxiv.org/abs/2412.04856)