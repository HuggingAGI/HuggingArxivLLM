# DebFlow：智能体辩论驱动的自动化创建工具

发布时间：2025年03月31日

`LLM应用` `计算机科学` `工作流管理`

> DebFlow: Automating Agent Creation via Agent Debate

# 摘要

> 大型语言模型（LLMs）在工作流生成与优化方面展现出强大的潜力。然而，现有方法存在推理能力有限、计算需求高以及资源消耗大等问题。为此，我们提出了DebFlow框架，通过辩论机制优化工作流，并结合反思机制提升性能。我们在HotpotQA、MATH和ALFWorld等六个基准数据集上进行了评估，结果显示我们的方法比最新基线平均提升了3%的性能，证明了其在多种问题领域的有效性。特别地，相比最先进基线，我们的框架在训练过程中将资源消耗降低了37%。此外，消融研究表明，去除辩论组件会导致两个基准数据集上的性能下降4%，远高于去除反思组件时2%的性能下降。这表明辩论在提升框架性能中起着关键作用，而反思则提供了重要的辅助优化。

> Large language models (LLMs) have demonstrated strong potential and impressive performance in automating the generation and optimization of workflows. However, existing approaches are marked by limited reasoning capabilities, high computational demands, and significant resource requirements. To address these issues, we propose DebFlow, a framework that employs a debate mechanism to optimize workflows and integrates reflexion to improve based on previous experiences. We evaluated our method across six benchmark datasets, including HotpotQA, MATH, and ALFWorld. Our approach achieved a 3\% average performance improvement over the latest baselines, demonstrating its effectiveness in diverse problem domains. In particular, during training, our framework reduces resource consumption by 37\% compared to the state-of-the-art baselines. Additionally, we performed ablation studies. Removing the Debate component resulted in a 4\% performance drop across two benchmark datasets, significantly greater than the 2\% drop observed when the Reflection component was removed. These findings strongly demonstrate the critical role of Debate in enhancing framework performance, while also highlighting the auxiliary contribution of reflexion to overall optimization.

[Arxiv](https://arxiv.org/abs/2503.23781)