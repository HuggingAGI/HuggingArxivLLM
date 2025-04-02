# Rec-R1：强化学习驱动生成式大模型与用户中心推荐系统融合
发布时间：2025年03月31日

`推荐系统`
> Rec-R1: Bridging Generative Large Language Models and User-Centric Recommendation Systems via Reinforcement Learning
>
> 我们提出了一种通用强化学习框架Rec-R1，它通过闭环优化将大型语言模型（LLMs）与推荐系统连接起来。与传统的提示方法和监督微调（SFT）不同，Rec-R1直接利用固定黑盒推荐模型的反馈来优化LLM的生成过程，无需依赖来自专有模型（如GPT-4o）的合成SFT数据，从而避免了数据蒸馏所需的巨大成本和努力。为了验证Rec-R1的有效性，我们选择两个具有代表性的任务进行评估：产品搜索和序列推荐。实验结果表明，Rec-R1不仅在性能上始终优于基于提示和SFT的方法，而且与强大的判别式基线相比也取得了显著提升，即使使用像BM25这样简单的检索器也是如此。此外，Rec-R1保留了LLM的通用能力，而传统的SFT方法通常会损害指令遵循和推理能力。这些发现表明，Rec-R1是一个有潜力的框架，可用于持续的任务特定适应，而不会出现灾难性遗忘。
>
> https://arxiv.org/abs/2503.24289

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.24289](https://arxiv.org/abs/2503.24289)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)