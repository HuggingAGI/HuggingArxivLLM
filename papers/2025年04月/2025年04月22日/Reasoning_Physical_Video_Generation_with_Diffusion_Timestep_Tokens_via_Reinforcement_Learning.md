# 基于扩散时间步令牌的物理视频推理生成：强化学习方法

发布时间：2025年04月22日

`LLM应用` `视频生成` `物理建模`

> Reasoning Physical Video Generation with Diffusion Timestep Tokens via Reinforcement Learning

# 摘要

> 尽管视频生成领域取得了显著进展，但生成符合物理规律的视频仍是重大挑战。传统扩散模型因依赖数据驱动近似，难以有效推广至未见物理条件（如速度）中。为解决这一问题，我们提出结合符号推理与强化学习，以在视频生成中强制执行物理一致性。我们首先引入了扩散时间步长标记器（DDT），它通过恢复扩散过程中丢失的视觉属性，学习离散递归视觉标记。这些递归视觉标记使大型语言模型能够进行符号推理。基于此，我们提出了Phys-AR框架，包含两个阶段：第一阶段通过监督微调转移符号知识，第二阶段应用强化学习，借助基于物理条件的奖励函数优化模型推理能力。我们的方法使模型能够动态调整和改善生成视频的物理属性，确保其符合物理规律。实验结果表明，PhysAR可生成物理一致的视频。

> Despite recent progress in video generation, producing videos that adhere to physical laws remains a significant challenge. Traditional diffusion-based methods struggle to extrapolate to unseen physical conditions (eg, velocity) due to their reliance on data-driven approximations. To address this, we propose to integrate symbolic reasoning and reinforcement learning to enforce physical consistency in video generation. We first introduce the Diffusion Timestep Tokenizer (DDT), which learns discrete, recursive visual tokens by recovering visual attributes lost during the diffusion process. The recursive visual tokens enable symbolic reasoning by a large language model. Based on it, we propose the Phys-AR framework, which consists of two stages: The first stage uses supervised fine-tuning to transfer symbolic knowledge, while the second stage applies reinforcement learning to optimize the model's reasoning abilities through reward functions based on physical conditions. Our approach allows the model to dynamically adjust and improve the physical properties of generated videos, ensuring adherence to physical laws. Experimental results demonstrate that PhysAR can generate videos that are physically consistent.

[Arxiv](https://arxiv.org/abs/2504.15932)