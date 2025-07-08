# # CoT-lized 扩散：一步步强化 T2I 生成
通过逐步引导，CoT-lized 扩散方法能够显著提升文本到图像生成的质量。

发布时间：2025年07月06日

`LLM应用

理由：这篇论文主要讨论了如何将多模态大型语言模型（MLLM）应用于文本到图像生成模型的改进，特别是通过引入CoT-Diff框架来增强空间对齐和生成质量。研究的重点在于应用MLLM来优化T2I生成过程，属于LLM在具体任务中的应用。` `图像生成` `3D场景`

> CoT-lized Diffusion: Let's Reinforce T2I Generation Step-by-step

# 摘要

> 文本到图像（T2I）生成模型在复杂场景下难以实现空间构图与输入文本的精准对齐。尽管基于布局的方法在一定程度上改进了空间控制，但由于其生成过程与布局规划相互独立，导致在合成过程中难以优化布局。我们提出了CoT-Diff框架，通过将多模态大型语言模型（MLLM）驱动的3D布局规划与扩散过程深度融合，将逐步的CoT式推理引入T2I生成。CoT-Diff能够在单次扩散过程中实现布局感知推理：在每个去噪步骤中，MLLM实时评估中间预测结果，动态调整3D场景布局，并持续优化生成过程。更新后的布局被转换为语义条件和深度图，通过条件感知注意力机制融入扩散模型中，从而实现精确的空间控制和语义注入。实验结果表明，CoT-Diff在3D场景基准测试中显著提升了空间对齐和组合保真度，并在复杂场景的空间准确性上比现有最优方法高出34.7%，充分验证了这种创新生成范式的有效性。

> Current text-to-image (T2I) generation models struggle to align spatial composition with the input text, especially in complex scenes. Even layout-based approaches yield suboptimal spatial control, as their generation process is decoupled from layout planning, making it difficult to refine the layout during synthesis. We present CoT-Diff, a framework that brings step-by-step CoT-style reasoning into T2I generation by tightly integrating Multimodal Large Language Model (MLLM)-driven 3D layout planning with the diffusion process. CoT-Diff enables layout-aware reasoning inline within a single diffusion round: at each denoising step, the MLLM evaluates intermediate predictions, dynamically updates the 3D scene layout, and continuously guides the generation process. The updated layout is converted into semantic conditions and depth maps, which are fused into the diffusion model via a condition-aware attention mechanism, enabling precise spatial control and semantic injection. Experiments on 3D Scene benchmarks show that CoT-Diff significantly improves spatial alignment and compositional fidelity, and outperforms the state-of-the-art method by 34.7% in complex scene spatial accuracy, thereby validating the effectiveness of this entangled generation paradigm.

[Arxiv](https://arxiv.org/abs/2507.04451)