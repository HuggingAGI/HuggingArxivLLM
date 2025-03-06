# 利用大型语言模型开发新兴优化问题的启发式方法

发布时间：2025年03月05日

`LLM应用` `运筹学` `人工智能`

> Leveraging Large Language Models to Develop Heuristics for Emerging Optimization Problems

# 摘要

> 组合优化问题通常依赖启发式算法来生成高效解决方案。然而，手动设计启发式算法不仅资源消耗大，还受限于设计者的专业知识水平。人工智能的最新进展，特别是大型语言模型（LLMs），已展现出通过进化框架自动化启发式生成的潜力。近期研究在设计构造性启发式时，仅关注旅行商问题和在线装箱问题等知名组合优化问题。本研究探讨LLMs能否有效为利基、尚未被广泛研究的优化问题生成启发式，以单元负载预编排问题为例。我们提出Contextual Evolution of Heuristics (CEoH)框架，作为Evolution of Heuristics (EoH)框架的扩展，整合了问题特定描述以增强启发式生成过程中的上下文学习。通过计算实验，我们评估CEoH和EoH，并比较结果。结果显示，CEoH使小型LLMs能更一致地生成高质量启发式，甚至超越大型模型。大型模型在有或无上下文提示的情况下均表现稳健。生成的启发式在不同实例配置中展现出良好的扩展性。

> Combinatorial optimization problems often rely on heuristic algorithms to generate efficient solutions. However, the manual design of heuristics is resource-intensive and constrained by the designer's expertise. Recent advances in artificial intelligence, particularly large language models (LLMs), have demonstrated the potential to automate heuristic generation through evolutionary frameworks. Recent works focus only on well-known combinatorial optimization problems like the traveling salesman problem and online bin packing problem when designing constructive heuristics. This study investigates whether LLMs can effectively generate heuristics for niche, not yet broadly researched optimization problems, using the unit-load pre-marshalling problem as an example case. We propose the Contextual Evolution of Heuristics (CEoH) framework, an extension of the Evolution of Heuristics (EoH) framework, which incorporates problem-specific descriptions to enhance in-context learning during heuristic generation. Through computational experiments, we evaluate CEoH and EoH and compare the results. Results indicate that CEoH enables smaller LLMs to generate high-quality heuristics more consistently and even outperform larger models. Larger models demonstrate robust performance with or without contextualized prompts. The generated heuristics exhibit scalability to diverse instance configurations.

[Arxiv](https://arxiv.org/abs/2503.03350)