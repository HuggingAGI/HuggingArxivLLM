# LossAgent：借助 LLM 代理达成图像处理的任意优化目标

发布时间：2024年12月05日

`Agent` `图像处理` `计算机视觉`

> LossAgent: Towards Any Optimization Objectives for Image Processing with LLM Agents

# 摘要

> 我们推出了首个用于低级图像处理任务（如图像超分辨率和修复）的损失代理，名为 LossAgent，意在不同实际应用中达成低级图像处理的任何定制优化目标。要注意的是，并非所有优化目标，像复杂的手工制作感知指标、文本描述以及繁杂的人类反馈，都能通过现有的低级损失（比如 MSE 损失）来实现。这给以端到端方式优化图像处理网络带来了关键挑战。为解决此问题，我们的 LossAgent 引入强大的大型语言模型（LLM）作为损失代理，其丰富的先验知识文本理解能力，让损失代理能够理解低级图像处理网络优化过程中来自外部环境的复杂优化目标、轨迹和状态反馈。特别是，我们通过整合支持低级图像处理端到端优化的现有损失函数来构建损失库。接着，我们为损失代理设计了面向优化的提示工程，使其在每次优化交互时能主动且智能地决定库中每个损失的组合权重，进而实现任何定制优化目标所需的优化轨迹。在三个典型的低级图像处理任务和多个优化目标上开展的大量实验，证明了我们提出的 LossAgent 的有效性和适用性。代码和预训练模型可在 https://github.com/lbc12345/LossAgent 获取。

> We present the first loss agent, dubbed LossAgent, for low-level image processing tasks, e.g., image super-resolution and restoration, intending to achieve any customized optimization objectives of low-level image processing in different practical applications. Notably, not all optimization objectives, such as complex hand-crafted perceptual metrics, text description, and intricate human feedback, can be instantiated with existing low-level losses, e.g., MSE loss. which presents a crucial challenge in optimizing image processing networks in an end-to-end manner. To eliminate this, our LossAgent introduces the powerful large language model (LLM) as the loss agent, where the rich textual understanding of prior knowledge empowers the loss agent with the potential to understand complex optimization objectives, trajectory, and state feedback from external environments in the optimization process of the low-level image processing networks. In particular, we establish the loss repository by incorporating existing loss functions that support the end-to-end optimization for low-level image processing. Then, we design the optimization-oriented prompt engineering for the loss agent to actively and intelligently decide the compositional weights for each loss in the repository at each optimization interaction, thereby achieving the required optimization trajectory for any customized optimization objectives. Extensive experiments on three typical low-level image processing tasks and multiple optimization objectives have shown the effectiveness and applicability of our proposed LossAgent. Code and pre-trained models will be available at https://github.com/lbc12345/LossAgent.

[Arxiv](https://arxiv.org/abs/2412.04090)