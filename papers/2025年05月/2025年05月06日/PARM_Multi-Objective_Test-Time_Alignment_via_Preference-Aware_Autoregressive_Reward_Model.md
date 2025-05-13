# PARM：基于偏好感知自回归奖励模型的多目标测试时对齐方法

发布时间：2025年05月06日

`LLM应用` `NLP` `人工智能`

> PARM: Multi-Objective Test-Time Alignment via Preference-Aware Autoregressive Reward Model

# 摘要

> 多目标测试时对齐的目标是在推理过程中将大型语言模型（LLMs）适应多样化的多维用户偏好，同时保持模型固定。最近，GenARM（徐等人，2025）通过为每个偏好维度独立训练自回归奖励模型（ARMs），并在推理时结合它们的输出，实现了多目标对齐。然而，这种方法存在两个主要问题：需要多个ARM增加了推理成本，且单独训练ARM导致生成与用户偏好不一致。为了解决这些问题，我们提出了带有偏好意识的ARM（PARM），这是一个跨所有偏好维度训练的统一ARM。通过采用我们提出的偏好感知双线性低秩适配（PBLoRA），PARM能够根据偏好向量进行条件化，从而实现对偏好权衡的精准控制。实验结果表明，PARM不仅降低了推理成本，还实现了与偏好向量更好的对齐。此外，PARM支持从弱到强的引导，允许一个较小的PARM引导一个较大的固定LLM，无需昂贵的训练，使多目标对齐在计算资源有限的情况下也能实现。代码可在https://github.com/Baijiong-Lin/PARM获取。

> Multi-objective test-time alignment aims to adapt large language models (LLMs) to diverse multi-dimensional user preferences during inference while keeping LLMs frozen. Recently, GenARM (Xu et al., 2025) first independently trains Autoregressive Reward Models (ARMs) for each preference dimension without awareness of each other, then combines their outputs based on user-specific preference vectors during inference to achieve multi-objective test-time alignment, leading to two key limitations: the need for \textit{multiple} ARMs increases the inference cost, and the separate training of ARMs causes the misalignment between the guided generation and the user preferences. To address these issues, we propose Preference-aware ARM (PARM), a single unified ARM trained across all preference dimensions. PARM uses our proposed Preference-Aware Bilinear Low-Rank Adaptation (PBLoRA), which employs a bilinear form to condition the ARM on preference vectors, enabling it to achieve precise control over preference trade-offs during inference. Experiments demonstrate that PARM reduces inference costs and achieves better alignment with preference vectors compared with existing methods. Additionally, PARM enables weak-to-strong guidance, allowing a smaller PARM to guide a larger frozen LLM without expensive training, making multi-objective alignment accessible with limited computing resources. The code is available at https://github.com/Baijiong-Lin/PARM.

[Arxiv](https://arxiv.org/abs/2505.06274)