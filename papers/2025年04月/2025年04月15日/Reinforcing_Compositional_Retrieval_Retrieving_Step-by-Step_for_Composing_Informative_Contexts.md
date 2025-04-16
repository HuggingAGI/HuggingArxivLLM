# 加强组合式检索：通过逐步检索生成信息丰富的上下文

发布时间：2025年04月15日

`RAG` `信息检索`

> Reinforcing Compositional Retrieval: Retrieving Step-by-Step for Composing Informative Contexts

# 摘要

> 大型语言模型（LLMs）在各类任务中展现出了非凡的能力，但它们通常需要依赖外部上下文来处理复杂任务。虽然传统的检索增强框架通常专注于在单次检索中选择排名靠前的文档，但许多现实场景需要组合式检索，即需要协调地结合多个来源的信息。为此，我们提出了一种三编码器顺序检索器，将这一过程建模为一个马尔可夫决策过程（MDP），将检索一组元素的概率分解为一系列条件概率，并允许每个检索步骤基于之前选择的示例进行条件化。我们分两个阶段训练检索器：首先，我们高效地构建监督顺序数据以进行初始策略训练；然后，我们通过基于生成程序的结构对应性奖励来优化策略，使其与LLM的偏好相一致。实验结果表明，我们提出的方法在多个基准测试中表现显著优于现有方法，突显了显式建模示例间依赖关系的重要性。这些发现凸显了组合式检索在需要多条证据或示例的任务中的潜力。

> Large Language Models (LLMs) have demonstrated remarkable capabilities across numerous tasks, yet they often rely on external context to handle complex tasks. While retrieval-augmented frameworks traditionally focus on selecting top-ranked documents in a single pass, many real-world scenarios demand compositional retrieval, where multiple sources must be combined in a coordinated manner. In this work, we propose a tri-encoder sequential retriever that models this process as a Markov Decision Process (MDP), decomposing the probability of retrieving a set of elements into a sequence of conditional probabilities and allowing each retrieval step to be conditioned on previously selected examples. We train the retriever in two stages: first, we efficiently construct supervised sequential data for initial policy training; we then refine the policy to align with the LLM's preferences using a reward grounded in the structural correspondence of generated programs. Experimental results show that our method consistently and significantly outperforms baselines, underscoring the importance of explicitly modeling inter-example dependencies. These findings highlight the potential of compositional retrieval for tasks requiring multiple pieces of evidence or examples.

[Arxiv](https://arxiv.org/abs/2504.11420)