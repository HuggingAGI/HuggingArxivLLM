# AgentTrek：借助网络教程引导重放实现代理轨迹合成

发布时间：2024年12月12日

`Agent` `数字环境` `图形用户界面`

> AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials

# 摘要

> 图形用户界面（GUI）代理在各种数字环境（从网络应用到桌面软件）中实现复杂任务自动化方面潜力巨大。然而，这类代理的开发因缺乏高质量多步骤轨迹数据以供有效训练而受阻。现有的方法依赖于昂贵且费力的人工标注，难以大规模持续。为应对此挑战，我们提出了 AgentTrek，这是一个可扩展的数据合成管道，借助网络教程生成高质量的 GUI 代理轨迹。我们的方法会自动从互联网收集类似教程的文本，将其转化为带有分步说明的任务目标，并让视觉语言模型代理在真实数字环境中模拟执行。基于 VLM 的评估器保证生成轨迹的正确性。我们表明，用这些合成轨迹训练 GUI 代理，能显著提升其在当前模型中的基础和规划性能。而且，与传统人工标注方法相比，我们的方法成本效益更高。这项工作突显了利用网络教程进行有指导的重放作为大规模 GUI 代理训练可行策略的潜力，为更强大、更自主的数字代理铺平了道路。

> Graphical User Interface (GUI) agents hold great potential for automating complex tasks across diverse digital environments, from web applications to desktop software. However, the development of such agents is hindered by the lack of high-quality, multi-step trajectory data required for effective training. Existing approaches rely on expensive and labor-intensive human annotation, making them unsustainable at scale. To address this challenge, we propose AgentTrek, a scalable data synthesis pipeline that generates high-quality GUI agent trajectories by leveraging web tutorials. Our method automatically gathers tutorial-like texts from the internet, transforms them into task goals with step-by-step instructions, and employs a visual-language model agent to simulate their execution in a real digital environment. A VLM-based evaluator ensures the correctness of the generated trajectories. We demonstrate that training GUI agents with these synthesized trajectories significantly improves their grounding and planning performance over the current models. Moreover, our approach is more cost-efficient compared to traditional human annotation methods. This work underscores the potential of guided replay with web tutorials as a viable strategy for large-scale GUI agent training, paving the way for more capable and autonomous digital agents.

[Arxiv](https://arxiv.org/abs/2412.09605)