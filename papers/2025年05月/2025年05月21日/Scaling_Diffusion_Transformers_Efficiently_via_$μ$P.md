# # 标题
利用 $μ$P 实现扩散 Transformer 的高效缩放

发布时间：2025年05月21日

`其他` `计算机视觉`

> Scaling Diffusion Transformers Efficiently via $μ$P

# 摘要

> 扩散Transformer已成为视觉生成模型的基石，但其大规模应用的扩展性却受限于高昂的超参数（HP）调优成本。最近，针对基础Transformer模型，研究者提出了最大更新参数化（$μ$P），该方法实现了从小规模到大规模语言模型的稳定HP迁移，显著降低了调优成本。然而，基础Transformer的$μ$P能否适用于架构和目标上均存在差异的扩散Transformer，目前尚不明确。本研究将标准$μ$P扩展至扩散Transformer领域，并通过大规模实验验证其有效性。首先，我们严格证明了主流扩散Transformer（包括DiT、U-ViT、PixArt-$α$和MMDiT）的$μ$P与基础Transformer的$μ$P具有一致性，从而实现了现有$μ$P方法的直接应用。基于这一成果，我们系统性地展示了DiT-$μ$P在HP迁移上的鲁棒性。特别值得注意的是，采用迁移学习率的DiT-XL-2-$μ$P较原版DiT-XL-2实现了2.9倍的加速收敛。最后，我们通过将PixArt-$α$从0.04B扩展至0.61B，以及将MMDiT从0.18B扩展至18B，成功验证了$μ$P在文本到图像生成任务中的有效性。在两种情况下，采用$μ$P的模型均超越了各自的基准模型，且调优成本极低，PixArt-$α$只需一次训练运行的5.5%，而MMDiT-18B仅需人类专家3%的参与。这些结果确立了$μ$P作为扩展扩散Transformer的原理性且高效的框架。

> Diffusion Transformers have emerged as the foundation for vision generative models, but their scalability is limited by the high cost of hyperparameter (HP) tuning at large scales. Recently, Maximal Update Parametrization ($μ$P) was proposed for vanilla Transformers, which enables stable HP transfer from small to large language models, and dramatically reduces tuning costs. However, it remains unclear whether $μ$P of vanilla Transformers extends to diffusion Transformers, which differ architecturally and objectively. In this work, we generalize standard $μ$P to diffusion Transformers and validate its effectiveness through large-scale experiments. First, we rigorously prove that $μ$P of mainstream diffusion Transformers, including DiT, U-ViT, PixArt-$α$, and MMDiT, aligns with that of the vanilla Transformer, enabling the direct application of existing $μ$P methodologies. Leveraging this result, we systematically demonstrate that DiT-$μ$P enjoys robust HP transferability. Notably, DiT-XL-2-$μ$P with transferred learning rate achieves 2.9 times faster convergence than the original DiT-XL-2. Finally, we validate the effectiveness of $μ$P on text-to-image generation by scaling PixArt-$α$ from 0.04B to 0.61B and MMDiT from 0.18B to 18B. In both cases, models under $μ$P outperform their respective baselines while requiring small tuning cost, only 5.5% of one training run for PixArt-$α$ and 3% of consumption by human experts for MMDiT-18B. These results establish $μ$P as a principled and efficient framework for scaling diffusion Transformers.

[Arxiv](https://arxiv.org/abs/2505.15270)