# Ground-Compose-Reinforce：基于形式化语言的强化学习代理任务设定

发布时间：2025年07月14日

`Agent

理由：这篇论文主要关注构建situated agents，特别是如何将语言 grounding 到复杂的感知和行动中，使用神经符号框架来实现数据驱动的语言理解和行为生成。因此，它属于Agent类别。` `机器人技术` `人工智能`

> Ground-Compose-Reinforce: Tasking Reinforcement Learning Agents through Formal Language

# 摘要

> 在构建能够通过语言与人类互动的 situated agents 时，将语言 grounding 在复杂感知（如像素）和行动上是一个关键挑战。过去的研究通常通过手动设计语言 grounding 或者整理大量与环境元素相关的语言数据集来解决这一问题。我们提出了一种名为 Ground-Compose-Reinforce 的神经符号框架，旨在从数据中 grounding 正式语言，并通过这种语言直接对 RL 代理进行任务分配以激发行为。基于数据驱动的学习方法，我们的框架避免了手动设计奖励函数或符号检测器等特定领域的元素。通过组合式正式语言语义，我们的框架实现了数据高效的 grounding 和对任意语言组合的泛化。在基于图像的网格世界和 MuJoCo 机器人领域进行的实验表明，我们的方法能够在有限数据下可靠地将正式语言指令映射到行为，而端到端的数据驱动方法则无法做到这一点。

> Grounding language in complex perception (e.g. pixels) and action is a key challenge when building situated agents that can interact with humans via language. In past works, this is often solved via manual design of the language grounding or by curating massive datasets relating language to elements of the environment. We propose Ground-Compose-Reinforce, a neurosymbolic framework for grounding formal language from data, and eliciting behaviours by directly tasking RL agents through this language. By virtue of data-driven learning, our framework avoids the manual design of domain-specific elements like reward functions or symbol detectors. By virtue of compositional formal language semantics, our framework achieves data-efficient grounding and generalization to arbitrary language compositions. Experiments on an image-based gridworld and a MuJoCo robotics domain show that our approach reliably maps formal language instructions to behaviours with limited data while end-to-end, data-driven approaches fail.

[Arxiv](https://arxiv.org/abs/2507.10741)