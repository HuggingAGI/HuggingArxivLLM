# 推理模型中的动态早期退出机制
发布时间：2025年04月22日


> Dynamic Early Exit in Reasoning Models
>
> 近期，大型推理语言模型（LRLMs）的进步依赖于测试时扩展，将长推理链生成扩展到解决复杂任务。然而，长推理链中的过度思考不仅降低了问题解决的效率，还可能因推理步骤过于冗长或重复而导致准确率下降。我们提出了一种简单而有效的方法，使大语言模型能够在生成过程中通过早期退出实现推理链的自我截断。与依赖固定启发式方法不同，我们的方法会在潜在的推理过渡点（例如，“Wait”标记）监控模型行为，并在模型对某个候选答案表现出高度信心时，动态终止后续推理链的生成。该方法无需额外训练，可无缝集成到现有的o1-like推理大语言模型中。在MATH-500、AMC 2023、GPQA Diamond和AIME 2024等多个推理基准测试中的实验表明，该方法在深度求索系列推理大语言模型上表现一致有效，平均将推理链长度缩短31%至43%，同时将准确率提升1.7%至5.7%。
>
> https://arxiv.org/abs/2504.15895

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.15895](https://arxiv.org/abs/2504.15895)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)