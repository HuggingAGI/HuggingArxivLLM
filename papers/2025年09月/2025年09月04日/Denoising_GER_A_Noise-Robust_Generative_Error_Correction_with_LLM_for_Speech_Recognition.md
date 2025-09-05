# Denoising GER：基于LLM的噪声鲁棒生成式语音识别纠错

发布时间：2025年09月04日

`LLM应用` `基础理论`

> Denoising GER: A Noise-Robust Generative Error Correction with LLM for Speech Recognition

# 摘要

> 近年来，大型语言模型（LLM）在自动语音识别（ASR）后处理的生成错误校正（GER）任务上已取得显著进展。然而，在复杂噪声环境中，其仍面临适应性差、信息利用率低等挑战，使得GER效果受限。针对这些问题，本文提出一种抗噪声的多模态GER框架（Denoising GER）。该框架借助噪声自适应声学编码器提升模型对不同噪声场景的适应能力，并通过异构特征补偿动态融合（HFCDF）机制优化多模态信息融合，进而提升LLM对多模态信息的利用率。此外，还引入强化学习（RL）训练策略以提升模型的预测能力。实验结果显示，Denoising GER在噪声环境中显著提升了准确性与鲁棒性，并在未见过的噪声场景中具备良好泛化能力。

> In recent years, large language models (LLM) have made significant progress in the task of generation error correction (GER) for automatic speech recognition (ASR) post-processing. However, in complex noisy environments, they still face challenges such as poor adaptability and low information utilization, resulting in limited effectiveness of GER. To address these issues, this paper proposes a noise-robust multi-modal GER framework (Denoising GER). The framework enhances the model's adaptability to different noisy scenarios through a noise-adaptive acoustic encoder and optimizes the integration of multi-modal information via a heterogeneous feature compensation dynamic fusion (HFCDF) mechanism, improving the LLM's utilization of multi-modal information. Additionally, reinforcement learning (RL) training strategies are introduced to enhance the model's predictive capabilities. Experimental results demonstrate that Denoising GER significantly improves accuracy and robustness in noisy environments and exhibits good generalization abilities in unseen noise scenarios.

[Arxiv](https://arxiv.org/abs/2509.04392)