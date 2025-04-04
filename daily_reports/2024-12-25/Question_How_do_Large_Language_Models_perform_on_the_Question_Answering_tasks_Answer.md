# 问题：大型语言模型在问答任务中的表现怎样？ 回答：
发布时间：2024年12月17日


> Question: How do Large Language Models perform on the Question Answering tasks? Answer:
>
> 大型语言模型（LLMs）在各类自然语言处理任务中展现出良好的成果，无需为这些任务专门进行训练，只需运用少样本或零样本提示技术即可。常见的自然语言处理任务之一是问答（QA）。在本研究中，我们针对较小的微调模型和开箱即用的遵循指令的 LLMs，在斯坦福问答数据集 2.0（SQuAD2）上展开了全面的性能对比，尤其是在采用单次推理提示技术的情况下。鉴于数据集包含无法回答的问题，以往的工作采用了双重推理的方法。我们提出了一种提示方式，旨在无需双重推理就能激发相同的能力，节省计算时间和资源。此外，我们通过比较它们在相似但不同的 QA 数据集上的表现来探究其泛化能力，两个模型均不进行微调，模拟现实世界中的使用场景，比如将上下文和提出的问题从维基百科换成新闻文章。
  我们的结果显示，在微调任务中，较小的微调模型胜过当前最先进的（SOTA）LLMs，但近期的 SOTA 模型能够在分布外测试中缩小这一差距，甚至在 5 个测试的 QA 数据集中的 3 个上超越微调模型。
>
> https://arxiv.org/abs/2412.12893

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.12893](https://arxiv.org/abs/2412.12893)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)