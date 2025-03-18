# 以图示思：概念图助力大型语言模型稳健规划

发布时间：2025年03月14日

`LLM应用

摘要中提到的论文探讨了如何改进大型语言模型和大型多模态模型的推理能力，特别是通过引入概念图来增强其规划和推理效果。这属于模型的应用层面研究，因此归类为LLM应用。`

> Visualizing Thought: Conceptual Diagrams Enable Robust Planning in LMMs

# 摘要

> 人类推理依赖于构建和操作心理模型，这些模型帮助我们理解和解决问题。概念图（如人类绘制的辅助推理草图）将心理模型外化，抽象无关细节，高效捕捉关系和空间信息。相比之下，大型语言模型（LLMs）和大型多模态模型（LMMs）主要通过文本推理，这限制了它们在复杂多步任务中的效果。本研究提出了一种零样本全自动框架，使LMMs能够通过多个自我生成的中间概念图链进行推理，显著提升其组合规划能力。方法仅需任务的自然语言描述，无需人工初始化。它在一个优化的图式思维推理框架中整合了文本和图式推理，并通过束搜索和深度回溯增强。在多个具有挑战性的PDDL规划领域中，我们的方法显著提升了GPT-4o的性能（例如，在Blocksworld中从35.5%提升到90.2%）。在更复杂的规划领域（解决方案深度高达40步）中，我们的方法甚至超越了o1-preview推理模型（例如，在Parking任务中提升了超过13%）。这些结果突显了概念图作为LMMs推理媒介的互补价值。

> Human reasoning relies on constructing and manipulating mental models-simplified internal representations of situations that we use to understand and solve problems. Conceptual diagrams (for example, sketches drawn by humans to aid reasoning) externalize these mental models, abstracting irrelevant details to efficiently capture relational and spatial information. In contrast, Large Language Models (LLMs) and Large Multimodal Models (LMMs) predominantly reason through textual representations, limiting their effectiveness in complex multi-step combinatorial and planning tasks. In this paper, we propose a zero-shot fully automatic framework that enables LMMs to reason through multiple chains of self-generated intermediate conceptual diagrams, significantly enhancing their combinatorial planning capabilities. Our approach does not require any human initialization beyond a natural language description of the task. It integrates both textual and diagrammatic reasoning within an optimized graph-of-thought inference framework, enhanced by beam search and depth-wise backtracking. Evaluated on multiple challenging PDDL planning domains, our method substantially improves GPT-4o's performance (for example, from 35.5% to 90.2% in Blocksworld). On more difficult planning domains with solution depths up to 40, our approach outperforms even the o1-preview reasoning model (for example, over 13% improvement in Parking). These results highlight the value of conceptual diagrams as a complementary reasoning medium in LMMs.

[Arxiv](https://arxiv.org/abs/2503.11790)