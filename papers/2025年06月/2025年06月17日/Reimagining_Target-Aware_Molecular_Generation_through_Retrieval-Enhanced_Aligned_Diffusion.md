# 通过检索增强对齐扩散重新构想目标导向的分子生成

发布时间：2025年06月17日

`其他` `药物设计` `生物技术`

> Reimagining Target-Aware Molecular Generation through Retrieval-Enhanced Aligned Diffusion

# 摘要

> 高精度蛋白质结构预测领域的突破，如AlphaFold，已确立基于受体的分子设计为快速早期药物发现的关键驱动力。然而，现有方法在平衡口袋特异性几何匹配与严格的价键及合成约束方面仍面临挑战。为解决这一权衡问题，我们引入了一种名为检索增强对齐扩散（READ）的方法，它是首个将分子检索增强生成与SE(3)-等变扩散模型相结合的方案。具体而言，通过对比预训练的编码器在训练过程中对齐原子级表示，然后在推理时检索与口袋匹配的支架图嵌入以指导每一步逆扩散过程。这种单一机制能够精准注入现实世界的化学先验知识，生成有效、多样且形状互补的配体。实验结果表明，READ在CBGBench上取得了极具竞争力的性能，超越了现有最先进的生成模型，甚至优于原生配体。这表明检索与扩散的协同优化能够实现更快、更可靠的基于结构的药物设计。

> Breakthroughs in high-accuracy protein structure prediction, such as AlphaFold, have established receptor-based molecule design as a critical driver for rapid early-phase drug discovery. However, most approaches still struggle to balance pocket-specific geometric fit with strict valence and synthetic constraints. To resolve this trade-off, a Retrieval-Enhanced Aligned Diffusion termed READ is introduced, which is the first to merge molecular Retrieval-Augmented Generation with an SE(3)-equivariant diffusion model. Specifically, a contrastively pre-trained encoder aligns atom-level representations during training, then retrieves graph embeddings of pocket-matched scaffolds to guide each reverse-diffusion step at inference. This single mechanism can inject real-world chemical priors exactly where needed, producing valid, diverse, and shape-complementary ligands. Experimental results demonstrate that READ can achieve very competitive performance in CBGBench, surpassing state-of-the-art generative models and even native ligands. That suggests retrieval and diffusion can be co-optimized for faster, more reliable structure-based drug design.

[Arxiv](https://arxiv.org/abs/2506.14488)