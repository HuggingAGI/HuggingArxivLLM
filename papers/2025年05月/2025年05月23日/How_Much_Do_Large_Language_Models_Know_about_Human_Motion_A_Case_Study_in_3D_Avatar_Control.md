# # 大型语言模型了解人类运动的奥秘吗？——三维虚拟角色控制案例分析

发布时间：2025年05月23日

`LLM应用` `计算机图形学` `虚拟角色控制`

> How Much Do Large Language Models Know about Human Motion? A Case Study in 3D Avatar Control

# 摘要

> 我们通过3D虚拟角色控制探索大型语言模型（LLMs）对人体运动的理解。给定一个运动指令，我们提示LLMs先生成包含连续步骤的高层次运动计划，然后在每个步骤中具体指定身体部位的位置，将这些位置线性插值到虚拟角色动画中，作为人类评估者进行明确验证的视角。通过精心设计的20个具有代表性的运动指令，全面覆盖基本运动原语并平衡身体部位使用，我们进行了全面评估，包括人类对生成动画和高层次运动计划的评估，以及与低层次规划中oracle位置的自动比较。我们发现，LLMs擅长解读高层次的身体动作，但在精确身体部位定位方面存在困难。虽然将运动查询分解为原子组件可以提高规划性能，但LLMs在涉及高自由度身体部位的多步骤运动方面存在困难。此外，LLMs能够对一般空间描述提供合理的近似，但无法处理文本中精确的空间规范以及用于虚拟角色控制所需的精确时空参数。值得注意的是，LLMs在构思创意动作和区分文化特定的运动模式方面显示出潜力。

> We explore Large Language Models (LLMs)' human motion knowledge through 3D avatar control. Given a motion instruction, we prompt LLMs to first generate a high-level movement plan with consecutive steps (High-level Planning), then specify body part positions in each step (Low-level Planning), which we linearly interpolate into avatar animations as a clear verification lens for human evaluators. Through carefully designed 20 representative motion instructions with full coverage of basic movement primitives and balanced body part usage, we conduct comprehensive evaluations including human assessment of both generated animations and high-level movement plans, as well as automatic comparison with oracle positions in low-level planning. We find that LLMs are strong at interpreting the high-level body movements but struggle with precise body part positioning. While breaking down motion queries into atomic components improves planning performance, LLMs have difficulty with multi-step movements involving high-degree-of-freedom body parts. Furthermore, LLMs provide reasonable approximation for general spatial descriptions, but fail to handle precise spatial specifications in text, and the precise spatial-temporal parameters needed for avatar control. Notably, LLMs show promise in conceptualizing creative motions and distinguishing culturally-specific motion patterns.

[Arxiv](https://arxiv.org/abs/2505.21531)