# FLAME：灵活的LLM辅助内容审核引擎
发布时间：2025年02月13日

`模型安全`
> FLAME: Flexible LLM-Assisted Moderation Engine
>
> 大型语言模型（LLMs）的快速发展带来了用户与模型交互内容审核的重大挑战。尽管LLMs展现了卓越的能力，但它们仍易受对抗攻击，尤其是能够绕过内容安全措施的“越狱攻击”（jailbreaking）。当前主要依赖输入提示词过滤的内容审核系统已显不足，如最佳N选1（BoN）越狱攻击对主流LLMs的成功率高达80%以上。

本文提出了一种新的方法：灵活的LLM辅助审核引擎（FLAME），将审核重点从输入过滤转向输出审核。与分析用户查询的传统熔断方法不同，FLAME通过对模型响应进行评估，具有以下关键优势：（1）训练和推理阶段的计算效率提升，（2）增强对BoN越狱攻击的抵抗能力，（3）通过可定制的主题过滤实现安全标准的灵活定义与更新。

实验表明，FLAME显著优于现有审核系统。例如，FLAME使GPT-4o-mini和DeepSeek-v3的攻击成功率降低了约9倍，同时保持了较低的计算开销。我们对多种LLMs进行了全面评估，并分析了该引擎在对抗先进越狱攻击时的效率。这项工作为开发更 robust 和灵活的内容审核系统提供了重要贡献。
>
> https://arxiv.org/abs/2502.09175

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.09175](https://arxiv.org/abs/2502.09175)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)