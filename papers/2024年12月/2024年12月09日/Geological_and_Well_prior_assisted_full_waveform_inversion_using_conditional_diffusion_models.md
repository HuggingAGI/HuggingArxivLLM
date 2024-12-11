# 利用条件扩散模型进行地质和井先验辅助的全波形反演

发布时间：2024年12月09日

`其他` `地震勘探`

> Geological and Well prior assisted full waveform inversion using conditional diffusion models

# 摘要

> 全波形反演（FWI）常因地震观测不充分而遭遇难题，致使反演结果频带受限且地质情况不准确。将潜在速度分布、测井信息以及我们的地质知识和预期等先验信息加以融合，能显著促进 FWI 收敛至更贴合实际的模型。尽管扩散正则化 FWI 结合速度分布先验后，相比传统 FWI 性能有所提升，但融入测井信息和其他地质知识先验，其效果会更佳。鉴于此，我们提出了一种借助条件扩散模型的地质类别和测井信息先验辅助的 FWI 方法。该方法将多模态信息无缝融入 FWI，同步达成数据拟合以及通用地质和地球物理先验匹配，这是传统正则化方法往往难以做到的。具体来说，我们提议将条件扩散模型与 FWI 相结合，在条件扩散模型中，利用无分类器引导将测井数据和地质类别条件融入其中，实现超越原始速度分布先验的多模态先验匹配。在 OpenFWI 数据集和现场海洋数据上开展的数值实验表明，我们的方法比传统 FWI 和无条件扩散正则化 FWI 更有效。

> Full waveform inversion (FWI) often faces challenges due to inadequate seismic observations, resulting in band-limited and geologically inaccurate inversion results. Incorporating prior information from potential velocity distributions, well-log information, and our geological knowledge and expectations can significantly improve FWI convergence to a realistic model. While diffusion-regularized FWI has shown improved performance compared to conventional FWI by incorporating the velocity distribution prior, it can benefit even more by incorporating well-log information and other geological knowledge priors. To leverage this fact, we propose a geological class and well-information prior-assisted FWI using conditional diffusion models. This method seamlessly integrates multi-modal information into FWI, simultaneously achieving data fitting and universal geologic and geophysics prior matching, which is often not achieved with traditional regularization methods. Specifically, we propose to combine conditional diffusion models with FWI, where we integrate well-log data and geological class conditions into these conditional diffusion models using classifier-free guidance for multi-modal prior matching beyond the original velocity distribution prior. Numerical experiments on the OpenFWI datasets and field marine data demonstrate the effectiveness of our method compared to conventional FWI and the unconditional diffusion-regularized FWI.

[Arxiv](https://arxiv.org/abs/2412.06959)