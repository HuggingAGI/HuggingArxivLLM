# 高风险人群模拟中语言智能体的隐式行为对齐

发布时间：2025年09月19日

`Agent` `基础理论`

> Implicit Behavioral Alignment of Language Agents in High-Stakes Crowd Simulations

# 摘要

> 语言驱动的生成式智能体已实现大规模社会模拟，其应用具有变革性，涵盖人际培训乃至全球政策制定辅助。然而，近期研究显示，生成式智能体的行为常与专家预期及现实数据不符——我们将此现象命名为“行为-现实差距”。为解决这一问题，我们提出“人格-环境行为对齐”（PEBA）理论框架，将其构建为分布匹配问题，该问题基于勒温行为方程（行为是个体与环境共同作用的函数）。基于PEBA框架，我们设计了PersonaEvolve（PEvo）——一种基于LLM的优化算法，通过迭代优化智能体人格，在特定环境中隐式将其集体行为与真实专家基准对齐。我们在自主开发的校园枪击事件模拟中对PEvo进行了验证：与无引导相比，分布差异平均降低84%；相较于显式指令基线，性能提升34%。结果还显示，经PEvo优化的人格可推广至全新的相关模拟场景。该方法显著提升了高风险社会模拟中的行为真实性与可靠性。更广泛而言，PEBA-PEvo框架为构建可信的LLM驱动社会模拟提供了一套原则性方案。

> Language-driven generative agents have enabled large-scale social simulations with transformative uses, from interpersonal training to aiding global policy-making. However, recent studies indicate that generative agent behaviors often deviate from expert expectations and real-world data--a phenomenon we term the Behavior-Realism Gap. To address this, we introduce a theoretical framework called Persona-Environment Behavioral Alignment (PEBA), formulated as a distribution matching problem grounded in Lewin's behavior equation stating that behavior is a function of the person and their environment. Leveraging PEBA, we propose PersonaEvolve (PEvo), an LLM-based optimization algorithm that iteratively refines agent personas, implicitly aligning their collective behaviors with realistic expert benchmarks within a specified environmental context. We validate PEvo in an active shooter incident simulation we developed, achieving an 84% average reduction in distributional divergence compared to no steering and a 34% improvement over explicit instruction baselines. Results also show PEvo-refined personas generalize to novel, related simulation scenarios. Our method greatly enhances behavioral realism and reliability in high-stakes social simulations. More broadly, the PEBA-PEvo framework provides a principled approach to developing trustworthy LLM-driven social simulations.

[Arxiv](https://arxiv.org/abs/2509.16457)