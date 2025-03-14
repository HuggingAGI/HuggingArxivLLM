# 多模态大型语言模型如何应对复杂的多模态推理？我们通过可扩展的密室逃脱游戏来探索它们的表现。

发布时间：2025年03月13日

`LLM应用

论文摘要：多模态大语言模型（MLLMs）的快速发展激发了在现实与虚拟环境中对复杂多模态推理任务的兴趣。这些任务需要整合视觉感知、视觉推理、空间意识和目标推断等多种能力。然而，现有的评估主要关注最终任务的完成情况，常常将评估简化为视觉定位和视觉问答等孤立能力的考察。对多模态环境下的推理过程进行全面和定量分析的关注较少，而这对于理解模型行为和推理机制至关重要，而不仅仅是任务的成功与否。

为了解决这一问题，我们引入了MM-Escape，这是一个可扩展的基准测试，旨在研究多模态推理，灵感来源于现实世界的密室逃脱游戏。MM-Escape不仅关注最终任务的完成，还强调模型在中间过程中的行为表现。为此，我们开发了EscapeCraft，这是一个可定制且开放的环境，使模型能够进行自由探索，从而评估其多模态推理能力。

大量实验表明，无论规模大小，MLLMs都能成功完成最简单的密室逃脱任务，其中一些模型表现出类似人类的探索策略。然而，随着任务难度的增加，性能急剧下降。此外，我们观察到不同模型的性能瓶颈各不相同，揭示了它们在多模态推理能力上的不同失败模式和局限性，例如重复轨迹而没有自适应探索、由于较差的视觉空间意识而被困在角落，以及未能有效利用获得的道具（如钥匙）。

我们希望这项工作能够揭示多模态推理中的新挑战，并为MLLMs的能力提升提供潜在的改进方向。` `人工智能`

> How Do Multimodal Large Language Models Handle Complex Multimodal Reasoning? Placing Them in An Extensible Escape Game

# 摘要

> 多模态大语言模型（MLLMs）的快速发展激发了在现实与虚拟环境中对复杂多模态推理任务的兴趣。这些任务需要整合视觉感知、视觉推理、空间意识和目标推断等多种能力。然而，现有的评估主要关注最终任务的完成情况，常常将评估简化为视觉定位和视觉问答等孤立能力的考察。对多模态环境下的推理过程进行全面和定量分析的关注较少，而这对于理解模型行为和推理机制至关重要，而不仅仅是任务的成功与否。

为了解决这一问题，我们引入了MM-Escape，这是一个可扩展的基准测试，旨在研究多模态推理，灵感来源于现实世界的密室逃脱游戏。MM-Escape不仅关注最终任务的完成，还强调模型在中间过程中的行为表现。为此，我们开发了EscapeCraft，这是一个可定制且开放的环境，使模型能够进行自由探索，从而评估其多模态推理能力。

大量实验表明，无论规模大小，MLLMs都能成功完成最简单的密室逃脱任务，其中一些模型表现出类似人类的探索策略。然而，随着任务难度的增加，性能急剧下降。此外，我们观察到不同模型的性能瓶颈各不相同，揭示了它们在多模态推理能力上的不同失败模式和局限性，例如重复轨迹而没有自适应探索、由于较差的视觉空间意识而被困在角落，以及未能有效利用获得的道具（如钥匙）。

我们希望这项工作能够揭示多模态推理中的新挑战，并为MLLMs的能力提升提供潜在的改进方向。

> The rapid advancing of Multimodal Large Language Models (MLLMs) has spurred interest in complex multimodal reasoning tasks in the real-world and virtual environment, which require coordinating multiple abilities, including visual perception, visual reasoning, spatial awareness, and target deduction. However, existing evaluations primarily assess the final task completion, often degrading assessments to isolated abilities such as visual grounding and visual question answering. Less attention is given to comprehensively and quantitatively analyzing reasoning process in multimodal environments, which is crucial for understanding model behaviors and underlying reasoning mechanisms beyond merely task success. To address this, we introduce MM-Escape, an extensible benchmark for investigating multimodal reasoning, inspired by real-world escape games. MM-Escape emphasizes intermediate model behaviors alongside final task completion. To achieve this, we develop EscapeCraft, a customizable and open environment that enables models to engage in free-form exploration for assessing multimodal reasoning. Extensive experiments show that MLLMs, regardless of scale, can successfully complete the simplest room escape tasks, with some exhibiting human-like exploration strategies. Yet, performance dramatically drops as task difficulty increases. Moreover, we observe that performance bottlenecks vary across models, revealing distinct failure modes and limitations in their multimodal reasoning abilities, such as repetitive trajectories without adaptive exploration, getting stuck in corners due to poor visual spatial awareness, and ineffective use of acquired props, such as the key. We hope our work sheds light on new challenges in multimodal reasoning, and uncovers potential improvements in MLLMs capabilities.

[Arxiv](https://arxiv.org/abs/2503.10042)