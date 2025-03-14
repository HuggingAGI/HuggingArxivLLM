# CoSTA$st$: 用于多轮图像编辑的成本敏感工具路径代理

发布时间：2025年03月13日

`LLM应用

摘要中提到的论文探讨了如何将大型语言模型（LLMs）与图搜索算法结合，优化多轮图像编辑任务的工作流程。这种方法利用LLMs生成子任务树，并通过A*搜索找到成本高效的工具路径，同时引入视觉语言模型（VLM）进行评估和反馈。论文的重点在于应用LLMs解决实际问题，提升任务效率，因此归类为LLM应用。` `图像编辑` `计算机视觉`

> CoSTA$\ast$: Cost-Sensitive Toolpath Agent for Multi-turn Image Editing

# 摘要

> 文本到图像模型（如Stable Diffusion和DALLE-3）在多轮图像编辑任务上仍面临挑战。我们将其分解为一个使用工具的智能工作流（路径），通过一系列不同成本的AI工具解决子任务序列。传统搜索算法需要高昂的探索成本才能找到工具路径。虽然大型语言模型（LLMs）具备子任务规划的先验知识，但它们可能缺乏对工具能力和成本的准确评估，难以确定在每个子任务中使用哪些工具。我们能否结合LLMs和图搜索的优势，找到成本高效的工具路径？我们提出了一种三阶段方法“CoSTA*”，利用LLMs生成子任务树，帮助剪枝给定任务的工具图，然后在小工具子图上进行A*搜索。为了更好地平衡总成本和质量，CoSTA*结合每个工具在各个子任务的成本和质量指标来指导A*搜索。每个子任务的输出将由视觉语言模型（VLM）进行评估，若失败则会触发对工具在该子任务的成本和质量的更新，从而让A*搜索能够快速恢复并探索其他路径。此外，CoSTA*可以在子任务之间自动切换模态，以实现更好的成本-质量权衡。我们构建了一个全新的多轮图像编辑基准测试，结果显示CoSTA*在成本和质量方面均优于现有最先进的图像编辑模型或代理，并可根据用户偏好进行灵活的权衡。

> Text-to-image models like stable diffusion and DALLE-3 still struggle with multi-turn image editing. We decompose such a task as an agentic workflow (path) of tool use that addresses a sequence of subtasks by AI tools of varying costs. Conventional search algorithms require expensive exploration to find tool paths. While large language models (LLMs) possess prior knowledge of subtask planning, they may lack accurate estimations of capabilities and costs of tools to determine which to apply in each subtask. Can we combine the strengths of both LLMs and graph search to find cost-efficient tool paths? We propose a three-stage approach "CoSTA*" that leverages LLMs to create a subtask tree, which helps prune a graph of AI tools for the given task, and then conducts A* search on the small subgraph to find a tool path. To better balance the total cost and quality, CoSTA* combines both metrics of each tool on every subtask to guide the A* search. Each subtask's output is then evaluated by a vision-language model (VLM), where a failure will trigger an update of the tool's cost and quality on the subtask. Hence, the A* search can recover from failures quickly to explore other paths. Moreover, CoSTA* can automatically switch between modalities across subtasks for a better cost-quality trade-off. We build a novel benchmark of challenging multi-turn image editing, on which CoSTA* outperforms state-of-the-art image-editing models or agents in terms of both cost and quality, and performs versatile trade-offs upon user preference.

[Arxiv](https://arxiv.org/abs/2503.10613)