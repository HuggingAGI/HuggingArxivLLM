# ETTA: 探索文本到音频模型的设计空间

发布时间：2024年12月26日

`LLM应用

**解释**：这篇论文主要讨论了文本到音频（TTA）合成技术，特别是通过自然语言提示生成合成音频。虽然论文没有直接提到大型语言模型（LLM），但文本到音频的生成过程通常依赖于自然语言处理技术，这些技术在现代LLM中得到了广泛应用。因此，这篇论文可以被归类为LLM应用，因为它涉及了LLM在音频生成领域的应用。` `音频合成` `创意产业`

> ETTA: Elucidating the Design Space of Text-to-Audio Models

# 摘要

> 近年来，文本到音频（TTA）合成技术突飞猛进，用户可以通过自然语言提示生成的合成音频来丰富创意工作流。然而，数据、模型架构、训练目标函数和采样策略对目标基准的影响仍不明确。为了全面探索TTA模型的设计空间，我们开展了一项大规模实验，聚焦于扩散和流匹配模型。我们的贡献包括：1）AF-Synthetic，一个从音频理解模型生成的高质量合成字幕数据集；2）系统比较了TTA模型的不同架构、训练和推理设计选择；3）分析了采样方法及其在生成质量和推理速度上的帕累托曲线。基于这些分析，我们提出了最佳模型——Elucidated Text-To-Audio（ETTA）。在AudioCaps和MusicCaps上的评估表明，ETTA在公开数据训练的基线模型上表现优异，并与专有数据训练的模型不相上下。此外，ETTA在生成复杂且富有想象力的字幕后的创意音频方面表现出色，这一任务比现有基准更具挑战性。

> Recent years have seen significant progress in Text-To-Audio (TTA) synthesis, enabling users to enrich their creative workflows with synthetic audio generated from natural language prompts. Despite this progress, the effects of data, model architecture, training objective functions, and sampling strategies on target benchmarks are not well understood. With the purpose of providing a holistic understanding of the design space of TTA models, we set up a large-scale empirical experiment focused on diffusion and flow matching models. Our contributions include: 1) AF-Synthetic, a large dataset of high quality synthetic captions obtained from an audio understanding model; 2) a systematic comparison of different architectural, training, and inference design choices for TTA models; 3) an analysis of sampling methods and their Pareto curves with respect to generation quality and inference speed. We leverage the knowledge obtained from this extensive analysis to propose our best model dubbed Elucidated Text-To-Audio (ETTA). When evaluated on AudioCaps and MusicCaps, ETTA provides improvements over the baselines trained on publicly available data, while being competitive with models trained on proprietary data. Finally, we show ETTA's improved ability to generate creative audio following complex and imaginative captions -- a task that is more challenging than current benchmarks.

[Arxiv](https://arxiv.org/abs/2412.19351)