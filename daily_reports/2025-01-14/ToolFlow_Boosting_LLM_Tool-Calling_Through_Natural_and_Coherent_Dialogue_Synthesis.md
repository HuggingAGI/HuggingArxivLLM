# ToolFlow: 利用自然流畅的对话合成增强LLM工具调用
发布时间：2024年10月24日

`Agent应用`
> ToolFlow: Boosting LLM Tool-Calling Through Natural and Coherent Dialogue Synthesis
>
> # 摘要
监督微调（SFT）是提升大型语言模型（LLMs）工具调用能力的常用方法，通常依赖于合成数据。当前的数据合成流程包括工具采样、需求制定和调用语句生成。然而，随机采样的工具缺乏关联性，难以组合，导致数据多样性不足。此外，现有方法忽视了对话轮次间的连贯性，使得合成数据与现实场景脱节。为此，我们提出了基于图的采样策略，以获取更相关的工具组合，并设计了计划生成策略，用于指导连贯对话的合成。我们将这两种策略结合，通过多代理交互式合成对话数据，构建了工具调用数据合成管道 ToolFlow。数据质量评估显示，ToolFlow 合成的对话在自然性和连贯性上均有显著提升。最后，我们利用 ToolFlow 生成的 8,000 条合成对话对 LLaMA-3.1-8B 进行 SFT，结果显示该模型在工具调用性能上可与 GPT-4 媲美甚至超越，同时保持了强大的通用能力。
>
> https://arxiv.org/abs/2410.18447

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.18447](https://arxiv.org/abs/2410.18447)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)