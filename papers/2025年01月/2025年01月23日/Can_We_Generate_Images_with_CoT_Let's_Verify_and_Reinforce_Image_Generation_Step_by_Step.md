# 我们能否通过CoT生成图像？让我们逐步验证并优化图像生成过程。

发布时间：2025年01月23日

`LLM应用

理由：这篇论文主要探讨了Chain-of-Thought (CoT) 推理在自回归图像生成中的应用，并提出了几种技术来提升图像生成的性能。虽然论文涉及了图像生成，但其核心是通过CoT推理和奖励模型（如PARM和PARM++）来优化生成过程，这与大型语言模型（LLM）的应用密切相关。因此，将其归类为LLM应用是合适的。` `图像生成` `人工智能`

> Can We Generate Images with CoT? Let's Verify and Reinforce Image Generation Step by Step

# 摘要

> # 摘要
Chain-of-Thought (CoT) 推理在大型模型中已被广泛用于解决复杂理解任务。然而，这种策略能否应用于图像生成的验证和强化仍是一个未解之谜。本文首次全面探讨了 CoT 推理在提升自回归图像生成中的潜力。我们聚焦于三种技术：扩展测试时间计算以进行验证、通过 Direct Preference Optimization (DPO) 对齐模型偏好，以及整合这些技术以实现协同效应。实验表明，这些方法能够有效结合，显著提升图像生成性能。此外，鉴于奖励模型在研究中的关键作用，我们提出了 Potential Assessment Reward Model (PARM) 和 PARM++，专为自回归图像生成设计。PARM 通过潜在评估方法自适应地评估每个生成步骤，融合现有奖励模型的优势，而 PARM++ 进一步引入反思机制，自动纠正生成的不理想图像。通过我们的推理策略，我们增强了基线模型 Show-o，在 GenEval 基准上取得了 +24% 的显著提升，超越 Stable Diffusion 3 达 +15%。我们希望这项研究为 CoT 推理与自回归图像生成的结合提供独特见解，并开辟新路径。代码和模型已发布于 https://github.com/ZiyuGuo99/Image-Generation-CoT

> Chain-of-Thought (CoT) reasoning has been extensively explored in large models to tackle complex understanding tasks. However, it still remains an open question whether such strategies can be applied to verifying and reinforcing image generation scenarios. In this paper, we provide the first comprehensive investigation of the potential of CoT reasoning to enhance autoregressive image generation. We focus on three techniques: scaling test-time computation for verification, aligning model preferences with Direct Preference Optimization (DPO), and integrating these techniques for complementary effects. Our results demonstrate that these approaches can be effectively adapted and combined to significantly improve image generation performance. Furthermore, given the pivotal role of reward models in our findings, we propose the Potential Assessment Reward Model (PARM) and PARM++, specialized for autoregressive image generation. PARM adaptively assesses each generation step through a potential assessment approach, merging the strengths of existing reward models, and PARM++ further introduces a reflection mechanism to self-correct the generated unsatisfactory image. Using our investigated reasoning strategies, we enhance a baseline model, Show-o, to achieve superior results, with a significant +24% improvement on the GenEval benchmark, surpassing Stable Diffusion 3 by +15%. We hope our study provides unique insights and paves a new path for integrating CoT reasoning with autoregressive image generation. Code and models are released at https://github.com/ZiyuGuo99/Image-Generation-CoT

[Arxiv](https://arxiv.org/abs/2501.13926)