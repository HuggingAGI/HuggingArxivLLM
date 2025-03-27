# AXUNet：CNN与自注意力的创新结合，助力脑肿瘤分割任务。

发布时间：2025年03月26日

`其他` `医学影像`

> Attention Xception UNet (AXUNet): A Novel Combination of CNN and Self-Attention for Brain Tumor Segmentation

# 摘要

> 胶质瘤脑肿瘤的准确分割对诊断和治疗至关重要。深度学习技术虽提供了有前景的解决方案，但最优模型架构仍需进一步探索。我们基于BraTS 2021数据集，选取T1加对比增强（T1CE）、T2及流体衰减反转恢复（FLAIR）序列进行模型开发。

我们提出的注意力Xception UNet（AXUNet）架构，将Xception主干网络与点积自注意力模块相结合，灵感来源于Google Bard和OpenAI ChatGPT等先进大型语言模型，并将其融入UNet框架。与现有最优模型的对比实验显示，AXUNet展现出更优的性能。

测试集评估结果显示：
- Inception-UNet：平均Dice得分90.88
- Xception-UNet：平均Dice得分93.24
- 注意力ResUNet（AResUNet）：平均Dice得分92.80（其中增强肿瘤区域ET得分最高，达84.92）
- 注意力门控UNet（AGUNet）：平均Dice得分90.38

AXUNet以93.73的平均Dice得分超越所有模型，在肿瘤整体（WT）、肿瘤核心（TC）和增强肿瘤（ET）区域均表现优异，分别取得92.59、86.81和84.89的Dice得分。AXUNet将Xception主干网络与点积自注意力机制相结合，充分展现了其在捕获空间和上下文信息方面的优越性能。这一研究结果凸显了AXUNet在实现精准肿瘤分割方面的潜在应用价值。


> Accurate segmentation of glioma brain tumors is crucial for diagnosis and treatment planning. Deep learning techniques offer promising solutions, but optimal model architectures remain under investigation. We used the BraTS 2021 dataset, selecting T1 with contrast enhancement (T1CE), T2, and Fluid-Attenuated Inversion Recovery (FLAIR) sequences for model development. The proposed Attention Xception UNet (AXUNet) architecture integrates an Xception backbone with dot-product self-attention modules, inspired by state-of-the-art (SOTA) large language models such as Google Bard and OpenAI ChatGPT, within a UNet-shaped model. We compared AXUNet with SOTA models. Comparative evaluation on the test set demonstrated improved results over baseline models. Inception-UNet and Xception-UNet achieved mean Dice scores of 90.88 and 93.24, respectively. Attention ResUNet (AResUNet) attained a mean Dice score of 92.80, with the highest score of 84.92 for enhancing tumor (ET) among all models. Attention Gate UNet (AGUNet) yielded a mean Dice score of 90.38. AXUNet outperformed all models with a mean Dice score of 93.73. It demonstrated superior Dice scores across whole tumor (WT) and tumor core (TC) regions, achieving 92.59 for WT, 86.81 for TC, and 84.89 for ET. The integration of the Xception backbone and dot-product self-attention mechanisms in AXUNet showcases enhanced performance in capturing spatial and contextual information. The findings underscore the potential utility of AXUNet in facilitating precise tumor delineation.

[Arxiv](https://arxiv.org/abs/2503.20446)