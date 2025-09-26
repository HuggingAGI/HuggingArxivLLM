# 基于LLM引导的进化构建集体行动：从非结构化问题到可执行启发式

发布时间：2025年09月24日

`Agent` `农业科技`

> Structuring Collective Action with LLM-Guided Evolution: From Ill-Structured Problems to Executable Heuristics

# 摘要

> 集体行动问题需要协调个体激励与集体目标，是典型的非结构化问题（ISPs）。对单个智能体来说，局部行动与全局结果间的因果关联模糊不清，利益相关者的目标常相互冲突，且没有单一明确的算法能将微观选择与宏观福利衔接起来。为此，我们提出计算框架ECHO-MIMIC：它通过挖掘简洁可执行的启发式规则和具有说服力的解释，将这种全局复杂性转化为每个智能体可处理的结构化问题（WSP）。

该框架分两阶段运行：ECHO（从结果进化生成启发式规则）会演化出编码候选行为策略的Python代码片段；MIMIC（个体-集体对齐的机制推理与消息传递）则生成配套自然语言消息，激励智能体采纳这些策略。两阶段均采用大型语言模型驱动的进化搜索：LLM生成多样化且贴合上下文的代码或文本变体，群体层面的选择则保留那些在模拟环境中能最大化集体性能的变体。

我们在农业景观管理这一典型非结构化问题（ISP）中对该框架进行了验证——在这类问题中，局部农业决策会影响全球生态连通性。结果显示，与基线方法相比，ECHO-MIMIC不仅能挖掘出高性能启发式规则，还能生成定制化消息，成功将模拟农民的行为与景观层面的生态目标协调一致。通过将算法规则发现与定制化沟通相结合，ECHO-MIMIC将集体行动的认知负担转化为智能体层面的简单指令，让以往难以处理的非结构化问题在实践中变得可解，并为可扩展、自适应的政策设计开辟了新方向。

> Collective action problems, which require aligning individual incentives with collective goals, are classic examples of Ill-Structured Problems (ISPs). For an individual agent, the causal links between local actions and global outcomes are unclear, stakeholder objectives often conflict, and no single, clear algorithm can bridge micro-level choices with macro-level welfare. We present ECHO-MIMIC, a computational framework that converts this global complexity into a tractable, Well-Structured Problem (WSP) for each agent by discovering compact, executable heuristics and persuasive rationales. The framework operates in two stages: ECHO (Evolutionary Crafting of Heuristics from Outcomes) evolves snippets of Python code that encode candidate behavioral policies, while MIMIC (Mechanism Inference & Messaging for Individual-to-Collective Alignment) evolves companion natural language messages that motivate agents to adopt those policies. Both phases employ a large-language-model-driven evolutionary search: the LLM proposes diverse and context-aware code or text variants, while population-level selection retains those that maximize collective performance in a simulated environment. We demonstrate this framework on a canonical ISP in agricultural landscape management, where local farming decisions impact global ecological connectivity. Results show that ECHO-MIMIC discovers high-performing heuristics compared to baselines and crafts tailored messages that successfully align simulated farmer behavior with landscape-level ecological goals. By coupling algorithmic rule discovery with tailored communication, ECHO-MIMIC transforms the cognitive burden of collective action into a simple set of agent-level instructions, making previously ill-structured problems solvable in practice and opening a new path toward scalable, adaptive policy design.

[Arxiv](https://arxiv.org/abs/2509.20412)