# 上下文学习与指令微调：小型和多语言模型的研究

发布时间：2025年03月03日

`LLM应用` `语言模型` `多语言处理`

> In-context Learning vs. Instruction Tuning: The Case of Small and Multilingual Language Models

# 摘要

> 指令遵循是大型语言模型执行下游任务的关键能力。传统的指令对齐方法依赖于对模型在精选指令数据集上的特定调优阶段，可选地结合对人类偏好进行对齐的步骤。最近的研究表明，基于上下文学习（ICL）的替代方法可以有效引导基础模型遵循指令。这种方法特别适用于跨语言和不同规模的模型，这些模型适应于不同类型的使用场景。在本研究中，我们比较了 ICL 和指令微调在英语、法语和西班牙语上的应用，尤其是在小型语言模型上的表现，并提供了在基础模型上应用直接偏好优化（DPO）的实验结果。实验结果显示，涉及多语言和较小规模模型的场景会导致 ICL 指令遵循性能下降，而 DPO 对齐只能部分缓解这一问题。这项研究旨在进一步增进我们对当前指令遵循替代方法的优缺点的理解。

> Instruction following is a critical ability for Large Language Models to perform downstream tasks. The standard approach to instruction alignment has relied on a specific phase of model tuning over curated instruction datasets, optionally complemented with an alignment step over human preferences. Recent work has shown the potential of in-context learning (ICL) alternatives to guide base models towards instruction following. This type of approach is particularly relevant to extend instruction following across languages and models of varying sizes adapted to different types of usage. In this work we compare ICL and instruction fine-tuning in English, French and Spanish, on Small Language Models, and provide experimental results on applying Direct Preference Optimisation (DPO) over base models. Our results show that scenarios involving multilingual and smaller models result in downgraded ICL instruction following performance, only partially mitigated by DPO alignment. This study aims to further our understanding of current strengths and limitations of alternative methods for instruction following.

[Arxiv](https://arxiv.org/abs/2503.01611)