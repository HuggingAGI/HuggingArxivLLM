# 个性化文本生成：基于对比激活引导
发布时间：2025年03月07日


> Personalized Text Generation with Contrastive Activation Steering
>
> 个性化文本生成的目标是从用户的过往文本中捕捉其独特的写作风格，并生成忠实反映这些风格特征的文本。目前，主要采用检索增强生成（RAG）和参数高效微调（PEFT）两大技术路线。尽管这些方法推动了领域的发展，但仍面临两大挑战：(1) 过往文本中内容语义与风格特征的混杂使得准确建模用户写作风格变得困难；(2) RAG的检索操作导致推理延迟，PEFT则需要为每个用户存储大量参数，限制了其扩展性。为解决这些问题，我们提出了StyleVector框架。该框架无需额外训练，通过在LLM的激活空间中将个性化写作风格解耦并表示为一个向量，实现了无需检索或存储参数的风格引导生成。实验结果表明，与PEFT方法相比，StyleVector在个性化生成质量上提升了8%，同时将存储需求降低了1700倍。
>
> https://arxiv.org/abs/2503.05213

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.05213](https://arxiv.org/abs/2503.05213)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)