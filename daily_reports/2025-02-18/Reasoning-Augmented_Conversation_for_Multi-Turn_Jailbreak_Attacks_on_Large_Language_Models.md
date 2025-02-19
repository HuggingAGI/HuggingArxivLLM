# 推理增强对话：针对大型语言模型的多轮越狱攻击研究
发布时间：2025年02月17日

`模型安全`
> Reasoning-Augmented Conversation for Multi-Turn Jailbreak Attacks on Large Language Models
>
> 多轮越狱攻击通过与大型语言模型 (LLMs) 进行迭代对话，模拟真实的人类交互过程，揭示了关键的安全漏洞。然而，现有方法往往难以在语义连贯性和攻击有效性之间取得平衡，导致要么出现良性的语义漂移，要么无法有效规避检测。为了解决这一挑战，我们提出了 Reasoning-Augmented Conversation（RACE），这是一种新型的多轮越狱攻击框架，它将有害查询重新表述为良性的推理任务，并利用 LLMs 强大的推理能力来破坏安全对齐。具体而言，我们引入了一个攻击状态机框架，系统地建模问题转换和迭代推理，确保跨多轮的连贯查询生成。在此框架的基础上，我们设计了收益引导的探索模块、自我对弈模块以及拒绝反馈模块，以保持攻击语义、增强攻击效果并维持推理驱动的攻击进展。在多个 LLM 上进行的广泛实验表明，RACE 在复杂的对话场景中实现了最先进的攻击效果，攻击成功率 (ASR) 最高提升了 96%。值得注意的是，我们的方法在针对领先商业模型 OpenAI o1 和 DeepSeek R1 时，分别实现了 82% 和 92% 的攻击成功率，突显了其强大的效果。我们已将代码发布在 https://github.com/NY1024/RACE，以促进这一关键领域进一步的研究。
>
> https://arxiv.org/abs/2502.11054

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.11054](https://arxiv.org/abs/2502.11054)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)