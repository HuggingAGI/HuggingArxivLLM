# MoE量化方法：借助专家平衡采样与亲和力引导，提升混合专家大型语言模型的量化效果

发布时间：2025年05月02日

`LLM理论` `模型优化`

> MoEQuant: Enhancing Quantization for Mixture-of-Experts Large Language Models via Expert-Balanced Sampling and Affinity Guidance

# 摘要

> 混合专家模型（MoE）通过动态路由和稀疏激活技术，在提升大型语言模型（LLMs）性能的同时降低了计算成本。然而，内存开销问题限制了其实际应用。传统的后训练量化（PTQ）方法在应用于MoE模型时，往往导致精度和泛化能力下降。本文深入研究了MoE模型的稀疏和动态特性对量化的影响，发现两大核心挑战：（1）跨专家不平衡，即样本在不同专家间分布不均，导致校准过程对使用较少的专家出现偏差；（2）专家内部不平衡，源于MoE独特的聚合机制，导致样本与专家间相关性差异显著。为解决这些问题，我们提出了专为MoE模型设计的MoEQuant量化框架，包含两大创新技术：1）专家平衡自采样（EBSS），通过令牌累积概率和平衡指标，构建分布均衡的校准集；2）亲和力引导量化（AGQ），将样本与专家的亲和力纳入量化过程，精准评估其对不同专家的影响。实验结果表明，MoEQuant在4位量化下，DeepSeekMoE-16B的性能提升了10个百分点，同时显著提升了运行效率。

> Mixture-of-Experts (MoE) large language models (LLMs), which leverage dynamic routing and sparse activation to enhance efficiency and scalability, have achieved higher performance while reducing computational costs. However, these models face significant memory overheads, limiting their practical deployment and broader adoption. Post-training quantization (PTQ), a widely used method for compressing LLMs, encounters severe accuracy degradation and diminished generalization performance when applied to MoE models. This paper investigates the impact of MoE's sparse and dynamic characteristics on quantization and identifies two primary challenges: (1) Inter-expert imbalance, referring to the uneven distribution of samples across experts, which leads to insufficient and biased calibration for less frequently utilized experts; (2) Intra-expert imbalance, arising from MoE's unique aggregation mechanism, which leads to varying degrees of correlation between different samples and their assigned experts. To address these challenges, we propose MoEQuant, a novel quantization framework tailored for MoE LLMs. MoE-Quant includes two novel techniques: 1) Expert-Balanced Self-Sampling (EBSS) is an efficient sampling method that efficiently constructs a calibration set with balanced expert distributions by leveraging the cumulative probabilities of tokens and expert balance metrics as guiding factors. 2) Affinity-Guided Quantization (AGQ), which incorporates affinities between experts and samples into the quantization process, thereby accurately assessing the impact of individual samples on different experts within the MoE layer. Experiments demonstrate that MoEQuant achieves substantial performance gains (more than 10 points accuracy gain in the HumanEval for DeepSeekMoE-16B under 4-bit quantization) and boosts efficiency.

[Arxiv](https://arxiv.org/abs/2505.03804)