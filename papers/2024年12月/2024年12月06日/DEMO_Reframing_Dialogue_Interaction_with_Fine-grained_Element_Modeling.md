# DEMO: 以细粒度元素建模重构对话交互

发布时间：2024年12月06日

`Agent` `人机交互` `对话系统`

> DEMO: Reframing Dialogue Interaction with Fine-grained Element Modeling

# 摘要

> 大型语言模型（LLMs）让对话成为人机交互的核心模式之一，由此积累了海量的对话日志，也使对话生成的需求与日俱增。对话的生命周期涵盖序曲、对话过程和尾声等阶段，包含诸多元素。尽管有关对话的研究众多，但涵盖全面对话元素的基准缺失，这妨碍了精确建模和系统评估。为填补这一空白，我们引入创新研究任务“对话元素建模”，包括“元素感知”和“对话代理交互”，并提出全新基准“DEMO”，用于全面的对话建模与评估。受模仿学习的启发，我们进一步构建了基于DEMO基准、具备熟练建模对话元素能力的代理。大量实验表明，现有的LLMs仍有很大的提升空间，而且我们的DEMO代理在域内和域外任务中均表现出色。

> Large language models (LLMs) have made dialogue one of the central modes of human-machine interaction, leading to the accumulation of vast amounts of conversation logs and increasing demand for dialogue generation. A conversational life-cycle spans from the Prelude through the Interlocution to the Epilogue, encompassing various elements. Despite the existence of numerous dialogue-related studies, there is a lack of benchmarks that encompass comprehensive dialogue elements, hindering precise modeling and systematic evaluation. To bridge this gap, we introduce an innovative research task $\textbf{D}$ialogue $\textbf{E}$lement $\textbf{MO}$deling, including $\textit{Element Awareness}$ and $\textit{Dialogue Agent Interaction}$, and propose a novel benchmark, $\textbf{DEMO}$, designed for a comprehensive dialogue modeling and assessment. Inspired by imitation learning, we further build the agent which possesses the adept ability to model dialogue elements based on the DEMO benchmark. Extensive experiments indicate that existing LLMs still exhibit considerable potential for enhancement, and our DEMO agent has superior performance in both in-domain and out-of-domain tasks.

[Arxiv](https://arxiv.org/abs/2412.04905)