# RL2：强化大型语言模型，助力主动配电网能源管理的安全强化学习

发布时间：2024年12月02日

`LLM应用` `配电网`

> RL2: Reinforce Large Language Model to Assist Safe Reinforcement Learning for Energy Management of Active Distribution Networks

# 摘要

> 随着大规模分布式能源资源融入有源配电网（ADNs），相较于传统配电网，ADNs 中的有效能源管理愈发重要。尽管先进的强化学习（RL）方法减轻了复杂建模和优化的负担，大幅提升了 ADNs 能源管理的效率，然而安全性却成为 RL 在实际应用中的关键问题。由于对应操作安全约束的惩罚函数的设计与调整需要丰富的 RL 及电力系统运行领域知识，新兴的 ADN 运营商期望采用更灵活、定制化的方式处理惩罚函数，以进一步提高操作的安全性与效率。具备强大理解、推理和上下文学习能力的大型语言模型（LLMs）为 ADNs 能源管理中的安全 RL 提供了极具前景的助力途径。在本文中，我们引入 LLM 来理解 ADNs 的操作安全要求并生成相应的惩罚函数。此外，我们提出了一种 RL2 机制，通过多轮对话对生成的函数进行迭代和自适应优化，其中 LLM 代理依据下游 RL 代理的训练和测试性能来调整函数的模式与参数。所提方法显著减少了 ADN 运营商的干预。综合测试结果表明了所提方法的有效性。

> As large-scale distributed energy resources are integrated into the active distribution networks (ADNs), effective energy management in ADNs becomes increasingly prominent compared to traditional distribution networks. Although advanced reinforcement learning (RL) methods, which alleviate the burden of complicated modelling and optimization, have greatly improved the efficiency of energy management in ADNs, safety becomes a critical concern for RL applications in real-world problems. Since the design and adjustment of penalty functions, which correspond to operational safety constraints, requires extensive domain knowledge in RL and power system operation, the emerging ADN operators call for a more flexible and customized approach to address the penalty functions so that the operational safety and efficiency can be further enhanced. Empowered with strong comprehension, reasoning, and in-context learning capabilities, large language models (LLMs) provide a promising way to assist safe RL for energy management in ADNs. In this paper, we introduce the LLM to comprehend operational safety requirements in ADNs and generate corresponding penalty functions. In addition, we propose an RL2 mechanism to refine the generated functions iteratively and adaptively through multi-round dialogues, in which the LLM agent adjusts the functions' pattern and parameters based on training and test performance of the downstream RL agent. The proposed method significantly reduces the intervention of the ADN operators. Comprehensive test results demonstrate the effectiveness of the proposed method.

[Arxiv](https://arxiv.org/abs/2412.01303)