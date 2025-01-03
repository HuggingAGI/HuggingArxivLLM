# # 迈向现实的无人机视觉-语言导航：平台、基准与方法

发布时间：2024年10月10日

`Agent

理由：这篇论文主要讨论了开发能够根据语言指令和视觉信息导航到目标位置的智能体，特别是无人机视觉语言导航（VLN）。论文提出了一个名为OpenUAV的平台，用于模拟真实无人机轨迹，并构建了一个专为无人机VLN任务设计的数据集。此外，论文还提出了一个无人机导航LLM模型，用于处理视觉和文本信息并生成分层轨迹。这些内容主要涉及智能体的开发和导航任务，因此应归类为Agent。` `无人机` `导航系统`

> Towards Realistic UAV Vision-Language Navigation: Platform, Benchmark, and Methodology

# 摘要

> # 摘要
开发能够根据语言指令和视觉信息导航到目标位置的智能体，即视觉语言导航（VLN），已引发广泛关注。目前研究多集中于地面智能体，而无人机VLN仍相对未被充分探索。近期无人机VLN研究多沿用地面VLN设置，依赖预定义离散动作空间，忽视了地面与空中环境在智能体运动动态和导航任务复杂性上的差异。为此，我们从平台、基准和方法论三个角度提出解决方案。为在VLN任务中实现真实无人机轨迹模拟，我们推出OpenUAV平台，具备多样化环境、真实飞行控制和广泛算法支持。我们进一步在该平台上构建了目标导向的VLN数据集，包含约12k条轨迹，这是首个专为真实无人机VLN任务设计的数据集。为应对复杂空中环境挑战，我们提出UAV-Need-Help基准，提供不同级别引导信息，助力无人机完成真实VLN任务。我们还提出无人机导航LLM，该模型在给定多视角图像、任务描述和辅助指令的情况下，利用MLLM的多模态理解能力联合处理视觉和文本信息，并执行分层轨迹生成。评估结果显示，我们的方法显著优于基线模型，但与人类操作员的结果仍有较大差距，凸显了UAV-Need-Help任务的挑战性。

> Developing agents capable of navigating to a target location based on language instructions and visual information, known as vision-language navigation (VLN), has attracted widespread interest. Most research has focused on ground-based agents, while UAV-based VLN remains relatively underexplored. Recent efforts in UAV vision-language navigation predominantly adopt ground-based VLN settings, relying on predefined discrete action spaces and neglecting the inherent disparities in agent movement dynamics and the complexity of navigation tasks between ground and aerial environments. To address these disparities and challenges, we propose solutions from three perspectives: platform, benchmark, and methodology. To enable realistic UAV trajectory simulation in VLN tasks, we propose the OpenUAV platform, which features diverse environments, realistic flight control, and extensive algorithmic support. We further construct a target-oriented VLN dataset consisting of approximately 12k trajectories on this platform, serving as the first dataset specifically designed for realistic UAV VLN tasks. To tackle the challenges posed by complex aerial environments, we propose an assistant-guided UAV object search benchmark called UAV-Need-Help, which provides varying levels of guidance information to help UAVs better accomplish realistic VLN tasks. We also propose a UAV navigation LLM that, given multi-view images, task descriptions, and assistant instructions, leverages the multimodal understanding capabilities of the MLLM to jointly process visual and textual information, and performs hierarchical trajectory generation. The evaluation results of our method significantly outperform the baseline models, while there remains a considerable gap between our results and those achieved by human operators, underscoring the challenge presented by the UAV-Need-Help task.

[Arxiv](https://arxiv.org/abs/2410.07087)