# 缩放搜索与学习：从强化学习视角重现 o1 的路线规划
发布时间：2024年12月18日


> Scaling of Search and Learning: A Roadmap to Reproduce o1 from Reinforcement Learning Perspective
>
> 摘要：OpenAI o1 在人工智能领域堪称重大里程碑，于众多需要强大推理能力的高难度任务中达到了专家级表现。此 http URL 宣称 o1 背后的核心技术为强化学习。近来的工作采用知识蒸馏等替代方式来效仿 o1 的推理风格，但其成效受限于教师模型的能力上限。故而，本文从强化学习的视角剖析了实现 o1 的路线图，着重于四个关键部分：策略初始化、奖励设计、搜索与学习。策略初始化让模型能够形成类人的推理行为，使其具备有效探索复杂问题解决空间的能力。奖励设计通过奖励塑造或奖励建模提供密集且有效的信号，这对搜索和学习均具指导意义。搜索在训练和测试阶段生成高质量解决方案时发挥着关键作用，通过更多计算能得出更优解。学习利用搜索产生的数据来改进策略，凭借更多参数和更多搜索数据能够实现更出色的性能。现有的试图重现 o1 的开源项目可被视作我们路线图的一部分或变体。总之，这些组成部分凸显了学习和搜索如何推动 o1 的发展，为 LLM 的进步作出了有意义的贡献。
>
> https://arxiv.org/pdf/2412.14135

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/pdf/2412.14135](https://arxiv.org/pdf/2412.14135)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)