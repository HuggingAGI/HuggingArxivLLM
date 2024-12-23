# 多模态代理调优：构建一个由 VLM 驱动的高效工具使用代理

发布时间：2024年12月20日

`Agent` `多模态` `代理调优`

> Multi-modal Agent Tuning: Building a VLM-Driven Agent for Efficient Tool Usage

# 摘要

> 大型语言模型（LLMs）的进步推动了多模态代理的发展，它被用作控制器来调用外部工具，为解决实际任务提供了可行途径。在本文中，我们提出了一种多模态代理调优方法，能自动生成多模态工具使用数据，并将视觉语言模型（VLM）调优为强大的工具使用推理控制器。为保证数据质量，我们让 GPT-4o 迷你模型生成查询、文件和轨迹，接着使用查询文件和轨迹验证器。基于数据合成管道，我们收集了包含 20K 个带有工具使用轨迹任务的 MM-Traj 数据集。随后，我们通过在 VLMs 上基于轨迹调优开发了用于工具使用的 T3-Agent ，所用数据集为 MM-Traj 。在 GTA 和 GAIA 基准上的评估显示，T3-Agent 在两个热门的 VLMs（MiniCPM-V-8.5B 和 {Qwen2-VL-7B}）上持续取得改进，其性能比未经训练的 VLMs 高出 20％，这表明所提出的数据合成管道行之有效，为工具使用能力带来了高质量数据。

> The advancement of large language models (LLMs) prompts the development of multi-modal agents, which are used as a controller to call external tools, providing a feasible way to solve practical tasks. In this paper, we propose a multi-modal agent tuning method that automatically generates multi-modal tool-usage data and tunes a vision-language model (VLM) as the controller for powerful tool-usage reasoning. To preserve the data quality, we prompt the GPT-4o mini model to generate queries, files, and trajectories, followed by query-file and trajectory verifiers. Based on the data synthesis pipeline, we collect the MM-Traj dataset that contains 20K tasks with trajectories of tool usage. Then, we develop the T3-Agent via underline{T}rajectory underline{T}uning on VLMs for underline{T}ool usage using MM-Traj. Evaluations on the GTA and GAIA benchmarks show that the T3-Agent consistently achieves improvements on two popular VLMs: MiniCPM-V-8.5B and {Qwen2-VL-7B}, which outperforms untrained VLMs by $20\%$, showing the effectiveness of the proposed data synthesis pipeline, leading to high-quality data for tool-usage capabilities.

[Arxiv](https://arxiv.org/abs/2412.15606)