# WebEvolver：利用协同进化的世界模型提升网络代理的自我改进能力
发布时间：2025年04月22日


> WebEvolver: Enhancing Web Agent Self-Improvement with Coevolving World Model
>
> 智能体自我改进通过基于自身策略自主采样的轨迹训练其大型语言模型（LLM）主干，展现出巨大潜力。然而，近期在Web环境中的进展面临一个关键限制：智能体在自主学习周期中会达到性能停滞点，阻碍进一步提升。我们认为，这是由于对Web环境探索不足以及大型语言模型中预训练Web知识的利用不够充分所致。为了改善自我改进的效果，我们提出了一种引入协同演化的世界模型大型语言模型的新型框架。该世界模型基于Web环境中的当前观察和动作预测下一步的观察结果。通过利用大型语言模型对丰富网络内容的预训练知识，世界模型承担双重角色：(1) 作为虚拟Web服务器，生成自我指令的训练数据，持续优化智能体的策略；(2) 在推理过程中作为想象引擎，实现向前模拟，指导智能体大型语言模型的动作选择。在真实Web环境（Mind2Web-Live、WebVoyager 和 GAIA-web）中的实验表明，与现有自我演化的智能体相比，我们的方法性能提升了10%，证明了该方法的有效性和通用性，且无需从更强大的闭源模型中进行蒸馏。我们的研究表明，将世界模型集成到自主智能体框架中是实现持续适应性的必要条件。
>
> https://arxiv.org/abs/2504.21024

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.21024](https://arxiv.org/abs/2504.21024)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)