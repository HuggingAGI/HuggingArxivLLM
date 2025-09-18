# SAIL-VL2 技术报告

发布时间：2025年09月17日

`其他` `基础理论`

> SAIL-VL2 Technical Report

# 摘要

> 我们推出SAIL-VL2——一款用于全面多模态理解与推理的开源视觉语言基础模型（LVM）套件。作为SAIL-VL的升级版，SAIL-VL2在20亿和80亿参数规模下，于各类图像与视频基准测试中均达到了最先进水平，展现出从细粒度感知到复杂推理的强大能力。其卓越性能源于三大核心创新。首先，构建了大规模数据整理管道，通过评分与过滤策略，全面提升了字幕、OCR、问答及视频数据的质量与分布均衡性，有效提高了训练效率。其次，采用渐进式训练框架：以强大的预训练视觉编码器（SAIL-ViT）为起点，经多模态预训练逐步推进，最终以思维融合SFT-RL混合范式收尾，系统性增强了模型能力。第三，在架构上突破了密集型LLM的局限，采用高效稀疏的混合专家（MoE）设计。凭借这些创新，SAIL-VL2在106个数据集上均表现出竞争力，并在MMMU、MathVista等挑战性推理基准测试中刷新了最先进水平。此外，在OpenCompass排行榜上，SAIL-VL2-2B在40亿参数规模以下的官方开源模型中位列第一，为开源多模态社区提供了高效且可扩展的基础。

> We introduce SAIL-VL2, an open-suite vision-language foundation model (LVM) for comprehensive multimodal understanding and reasoning. As the successor to SAIL-VL, SAIL-VL2 achieves state-of-the-art performance at the 2B and 8B parameter scales across diverse image and video benchmarks, demonstrating strong capabilities from fine-grained perception to complex reasoning. Three core innovations drive its effectiveness. First, a large-scale data curation pipeline with scoring and filtering strategies enhances both quality and distribution across captioning, OCR, QA, and video data, improving training efficiency. Second, a progressive training framework begins with a powerful pre-trained vision encoder (SAIL-ViT), advances through multimodal pre-training, and culminates in a thinking-fusion SFT-RL hybrid paradigm that systematically strengthens model capabilities. Third, architectural advances extend beyond dense LLMs to efficient sparse Mixture-of-Experts (MoE) designs. With these contributions, SAIL-VL2 demonstrates competitive performance across 106 datasets and achieves state-of-the-art results on challenging reasoning benchmarks such as MMMU and MathVista. Furthermore, on the OpenCompass leaderboard, SAIL-VL2-2B ranks first among officially released open-source models under the 4B parameter scale, while serving as an efficient and extensible foundation for the open-source multimodal community.

[Arxiv](https://arxiv.org/abs/2509.14033)