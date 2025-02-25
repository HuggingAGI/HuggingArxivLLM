# 探索自回归预测下一个词：In-Context Learning 源于泛化能力
发布时间：2025年02月24日


> Towards Auto-Regressive Next-Token Prediction: In-Context Learning Emerges from Generalization
>
> 大型语言模型（LLMs）展现出了显著超越传统方法的上下文学习（ICL）能力。然而，现有对ICL的理论分析主要存在两大局限：(a) 有限的独立同分布(i.i.d.)假设。大多数研究聚焦于监督函数学习任务，其中提示语的构造基于独立同分布的输入-标签对。这种i.i.d.假设与真实语言学习场景中的提示语标记相互依赖性存在显著差异。(b) 缺乏涌现机制解释。大部分文献从隐式优化角度解答了ICL在做什么，但对于ICL如何涌现以及预训练阶段对ICL的影响却鲜有阐释。在本文中，为扩展(a)的局限，我们采用更贴近语言模型实际训练的自回归下个词预测（AR-NTP）范式。具体而言，在AR-NTP框架下，我们强调提示语标记间的依赖关系，即基于前序序列预测后续每个标记。针对(b)的局限，我们系统地构建了预训练与ICL的理论框架，突出了序列和主题的分层结构，同时引入了双层期望机制。最终，我们为预训练LLMs推导出数据依赖、主题依赖和优化依赖的PAC-Bayesian泛化界限，研究发现ICL的涌现源于序列和主题的泛化能力。我们的理论通过数值线性动力系统、合成GINC和真实语言数据集的实验得到了验证。
>
> https://arxiv.org/abs/2502.17024

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.17024](https://arxiv.org/abs/2502.17024)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)