# 对大型时间序列模型进行金融微调
发布时间：2024年12月13日

`智能金融`
> Financial Fine-tuning a Large Time Series Model
>
> 大型模型在自然语言处理、图像生成，尤其是近期的时间序列预测领域，展现出了前所未有的强大能力。这不禁让我们思考：若把市场价格视作时间序列，大型模型能否用于预测市场？本文中，我们通过评估最新的时间序列基础模型 TimesFM 在价格预测上的表现来回答此问题。我们发现，鉴于价格数据的不规则特性，直接运用 TimesFM 效果不佳，于是提议针对价格预测任务，在金融数据上对 TimeFM 进行微调。具体做法是，在涵盖 1 亿个时间点、包含从小时到日等不同粒度的金融工具的价格数据上，对最新的时间序列基础模型 TimesFM 进行持续预训练。微调后的模型在价格预测的准确性上高于基准模型。我们在各类金融市场中对模型进行了模拟交易，结果显示，在回报、夏普比率、最大回撤和交易成本等方面，它都优于各种基准。
>
> https://arxiv.org/abs/2412.09880

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.09880](https://arxiv.org/abs/2412.09880)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)