# LLMs中的化学推理实现了可控的合成规划和反应机制的阐明。

发布时间：2025年03月11日

`LLM应用` `计算机辅助化学`

> Chemical reasoning in LLMs unlocks steerable synthesis planning and reaction mechanism elucidation

# 摘要

> 机器学习算法在特定化学任务中表现出色，但它们难以捕捉专家化学推理中的战略思维，限制了其广泛应用。我们展示了大型语言模型（LLMs）与传统搜索算法结合后，可作为强大的化学推理引擎，为计算机辅助化学开启了一种全新方法，模拟人类专家的思维方式。我们不直接利用LLMs操作化学结构，而是利用其评估化学策略的能力，引导搜索算法寻找化学上有意义的解决方案。我们通过策略感知的逆合成规划和机理阐明两个挑战展示了这一范式。在逆合成规划中，化学家可用自然语言指定合成策略，从而在广泛搜索中找到满足约束条件的路径。在机理阐明中，LLMs结合化学原理和系统性探索，指导寻找合理反应机理。我们的方法在各类化学任务中表现出色，且模型规模越大，化学推理越复杂。我们的方法为计算机辅助化学建立了新范式，将LLMs的战略理解与传统化学工具的精确性结合，为更直观、强大的化学推理系统开辟了可能性。

> While machine learning algorithms have been shown to excel at specific chemical tasks, they have struggled to capture the strategic thinking that characterizes expert chemical reasoning, limiting their widespread adoption. Here we demonstrate that large language models (LLMs) can serve as powerful chemical reasoning engines when integrated with traditional search algorithms, enabling a new approach to computer-aided chemistry that mirrors human expert thinking. Rather than using LLMs to directly manipulate chemical structures, we leverage their ability to evaluate chemical strategies and guide search algorithms toward chemically meaningful solutions. We demonstrate this paradigm through two fundamental challenges: strategy-aware retrosynthetic planning and mechanism elucidation. In retrosynthetic planning, our method allows chemists to specify desired synthetic strategies in natural language to find routes that satisfy these constraints in vast searches. In mechanism elucidation, LLMs guide the search for plausible reaction mechanisms by combining chemical principles with systematic exploration. Our approach shows strong performance across diverse chemical tasks, with larger models demonstrating increasingly sophisticated chemical reasoning. Our approach establishes a new paradigm for computer-aided chemistry that combines the strategic understanding of LLMs with the precision of traditional chemical tools, opening possibilities for more intuitive and powerful chemical reasoning systems.

[Arxiv](https://arxiv.org/abs/2503.08537)