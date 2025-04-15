# 基于动态频率平衡与知识引导的结构精准医学图像翻译

发布时间：2025年04月13日

`LLM应用` `医学成像` `医学图像处理`

> Structure-Accurate Medical Image Translation based on Dynamic Frequency Balance and Knowledge Guidance

# 摘要

> 多模态医学图像在精准和全面的临床诊断中起着关键作用。扩散模型是一种强大的策略，用于合成所需的医学图像。然而，现有方法仍然面临由于高频率信息的过拟合和低频率信息的减弱而导致的解剖结构失真问题。因此，我们提出了一种基于动态频率平衡和知识引导的新方法。具体来说，我们首先通过小波变换分解模型的关键特征，提取低频率和高频率成分。然后，设计了一个动态频率平衡模块，用于自适应调整频率，以增强全局低频率特征和有效的高频率细节，并抑制高频率噪声。为了进一步克服不同医学模态之间巨大差异带来的挑战，我们构建了一个知识引导机制，将视觉语言模型中的先验临床知识与视觉特征融合，以促进准确解剖结构的生成。在多个数据集上的实验评估表明，所提出的方法在定性和定量评估中都取得了显著改进，验证了其有效性和优越性。

> Multimodal medical images play a crucial role in the precise and comprehensive clinical diagnosis. Diffusion model is a powerful strategy to synthesize the required medical images. However, existing approaches still suffer from the problem of anatomical structure distortion due to the overfitting of high-frequency information and the weakening of low-frequency information. Thus, we propose a novel method based on dynamic frequency balance and knowledge guidance. Specifically, we first extract the low-frequency and high-frequency components by decomposing the critical features of the model using wavelet transform. Then, a dynamic frequency balance module is designed to adaptively adjust frequency for enhancing global low-frequency features and effective high-frequency details as well as suppressing high-frequency noise. To further overcome the challenges posed by the large differences between different medical modalities, we construct a knowledge-guided mechanism that fuses the prior clinical knowledge from a visual language model with visual features, to facilitate the generation of accurate anatomical structures. Experimental evaluations on multiple datasets show the proposed method achieves significant improvements in qualitative and quantitative assessments, verifying its effectiveness and superiority.

[Arxiv](https://arxiv.org/abs/2504.09441)