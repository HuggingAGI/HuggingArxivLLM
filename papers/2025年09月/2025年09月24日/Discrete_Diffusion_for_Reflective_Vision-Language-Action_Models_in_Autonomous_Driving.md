# 自动驾驶中反射式视觉-语言-动作模型的离散扩散

发布时间：2025年09月24日

`Agent` `交通运输`

> Discrete Diffusion for Reflective Vision-Language-Action Models in Autonomous Driving

# 摘要

> 端到端（E2E）解决方案已成为自动驾驶系统的主流方案，而视觉-语言-动作（VLA）模型则代表了一种新范式——它借助视觉-语言模型（VLMs）的预训练多模态知识，实现对复杂现实环境的理解与交互。然而，这些方法仍受限于模仿学习的固有缺陷——训练时难以从根本上编码物理规则。现有方案往往依赖复杂的规则后优化，或采用多限于仿真环境的强化学习，亦或使用需大量计算资源的梯度扩散引导。为此，我们提出ReflectDrive——一种全新的基于学习的框架，它集成反射机制，通过离散扩散实现安全轨迹生成。我们首先将二维驾驶空间离散化，构建动作码本，再通过微调让预训练扩散语言模型可直接用于规划任务。该框架的核心在于安全感知反射机制——无需梯度计算即可实现迭代自我修正。具体而言，我们的方法先通过目标条件轨迹生成，建模多模态驾驶行为；在此基础上，通过局部搜索识别不安全标记并确定可行解，将其作为安全锚点进行基于修复的轨迹再生。在NAVSIM基准测试中，ReflectDrive在安全关键轨迹生成上展现出显著优势，为自动驾驶系统提供了可扩展且可靠的全新方案。

> End-to-End (E2E) solutions have emerged as a mainstream approach for autonomous driving systems, with Vision-Language-Action (VLA) models representing a new paradigm that leverages pre-trained multimodal knowledge from Vision-Language Models (VLMs) to interpret and interact with complex real-world environments. However, these methods remain constrained by the limitations of imitation learning, which struggles to inherently encode physical rules during training. Existing approaches often rely on complex rule-based post-refinement, employ reinforcement learning that remains largely limited to simulation, or utilize diffusion guidance that requires computationally expensive gradient calculations. To address these challenges, we introduce ReflectDrive, a novel learning-based framework that integrates a reflection mechanism for safe trajectory generation via discrete diffusion. We first discretize the two-dimensional driving space to construct an action codebook, enabling the use of pre-trained Diffusion Language Models for planning tasks through fine-tuning. Central to our approach is a safety-aware reflection mechanism that performs iterative self-correction without gradient computation. Our method begins with goal-conditioned trajectory generation to model multi-modal driving behaviors. Based on this, we apply local search methods to identify unsafe tokens and determine feasible solutions, which then serve as safe anchors for inpainting-based regeneration. Evaluated on the NAVSIM benchmark, ReflectDrive demonstrates significant advantages in safety-critical trajectory generation, offering a scalable and reliable solution for autonomous driving systems.

[Arxiv](https://arxiv.org/abs/2509.20109)