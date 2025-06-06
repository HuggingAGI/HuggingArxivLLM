# 事实性：用于验证材料科学文献声明可行性的基准

发布时间：2025年06月04日

`LLM应用

摘要中提到的研究利用语言模型生成科学假设并评估其可行性，属于大型语言模型在科学发现中的实际应用，因此归类为LLM应用。` `材料科学` `科学发现`

> Matter-of-Fact: A Benchmark for Verifying the Feasibility of Literature-Supported Claims in Materials Science

# 摘要

> 现代辅助科学发现方法借助语言模型，能够自动生成大量待验证的科学假设，同时自动生成实验代码来检验这些假设。虽然生成假设相对容易，但自动化实验成本高昂，尤其是大规模运行时（即成千上万次实验）。开发基于假设可行性的筛选能力，将使发现系统实现规模化运行，同时提高其取得突破性发现的可能性。在本研究中，我们推出了Matter-of-Fact，这是一个用于评估以声明形式提出的假设可行性的挑战数据集。Matter-of-Fact包含从涵盖四个当代高影响力材料科学主题的科学文章中提取的8.4千个声明，包括超导体、半导体、电池和航空航天材料，同时包含来自理论、实验以及代码/模拟结果的定性和定量声明。我们发现，包含基于科学文献检索增强生成和代码生成的强基线模型在该任务上的表现未超过72%（随机猜测准确率为50%），而领域专家验证表明几乎所有声明均可解决——这既凸显了当前模型在该任务上的难度，也彰显了通过近期进展加速科学发现的潜力。

> Contemporary approaches to assisted scientific discovery use language models to automatically generate large numbers of potential hypothesis to test, while also automatically generating code-based experiments to test those hypotheses. While hypotheses can be comparatively inexpensive to generate, automated experiments can be costly, particularly when run at scale (i.e. thousands of experiments). Developing the capacity to filter hypotheses based on their feasibility would allow discovery systems to run at scale, while increasing their likelihood of making significant discoveries. In this work we introduce Matter-of-Fact, a challenge dataset for determining the feasibility of hypotheses framed as claims. Matter-of-Fact includes 8.4k claims extracted from scientific articles spanning four high-impact contemporary materials science topics, including superconductors, semiconductors, batteries, and aerospace materials, while including qualitative and quantitative claims from theoretical, experimental, and code/simulation results. We show that strong baselines that include retrieval augmented generation over scientific literature and code generation fail to exceed 72% performance on this task (chance performance is 50%), while domain-expert verification suggests nearly all are solvable -- highlighting both the difficulty of this task for current models, and the potential to accelerate scientific discovery by making near-term progress.

[Arxiv](https://arxiv.org/abs/2506.04410)