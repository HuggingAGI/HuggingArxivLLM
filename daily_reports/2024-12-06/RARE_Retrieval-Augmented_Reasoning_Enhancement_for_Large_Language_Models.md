# RARE：大型语言模型的检索增强推理强化
发布时间：2024年12月05日

`RAG`
> RARE: Retrieval-Augmented Reasoning Enhancement for Large Language Models
>
> 此项工作推出了 RARE（检索增强推理增强），这是对相互推理框架（rStar）的一种多用途拓展，旨在提升大型语言模型（LLMs）在诸如常识和医学推理等复杂、知识密集型任务中的推理精准度和事实完整性。RARE 在蒙特卡罗树搜索（MCTS）框架中融入了两项创新举措：A6 基于初始问题陈述生成搜索查询，通过这些查询进行信息检索，并借助检索到的数据增强推理从而得出最终答案；A7 专门针对生成的子问题进行信息检索，并利用相关的上下文信息重新回答这些子问题。另外，还提出了一种检索增强事实性评分器来替换原有的鉴别器，优先考虑符合高事实性标准的推理路径。使用 LLaMA 3.1 的实验结果显示，RARE 让开源 LLMs 能够与 GPT-4 和 GPT-4o 等顶尖开源模型具备相当的性能。本研究确立了 RARE 是在逻辑连贯性和事实完整性至关重要的领域中优化 LLMs 的可扩展解决方案。
>
> https://arxiv.org/abs/2412.02830

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.02830](https://arxiv.org/abs/2412.02830)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)