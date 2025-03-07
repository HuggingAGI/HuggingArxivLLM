# 小模型制胜：知识蒸馏 vs 自训练，降低问答机器人的幻觉风险
发布时间：2025年02月26日


> Winning Big with Small Models: Knowledge Distillation vs. Self-Training for Reducing Hallucination in QA Agents
>
> 在客服支持领域，大型语言模型（LLMs）的部署面临幻觉（生成错误信息）和专有模型高昂成本的双重限制。为应对这些挑战，我们提出了一种检索增强型问答（QA）pipeline，并深入探讨了人工输入与自动化之间的平衡之道。基于一个关于三星智能电视用户手册的问题数据集，我们发现：LLMs生成的合成数据在减少微调模型幻觉方面显著优于传统的众包数据。此外，我们还对自训练（在模型自身输出上进行微调）和知识蒸馏（在更强模型的输出上进行微调，如GPT-4o）进行了对比研究，发现自训练在幻觉减少方面能达到与知识蒸馏相媲美的效果。我们推测，这一令人意外的发现可能源于知识蒸馏场景中暴露偏差问题的加剧，并通过事后分析进一步验证了这一推测。同时，我们还通过引入情境化「我不知道」的响应机制，显著提升了系统对无法回答问题和检索失败场景的鲁棒性。这些研究发现表明：借助开源模型，结合合成数据和自训练方法，我们完全能够构建出既可扩展又具成本效益的问答系统，从而大幅减少对专有工具或昂贵人工标注的依赖。
>
> https://arxiv.org/abs/2502.19545

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.19545](https://arxiv.org/abs/2502.19545)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)