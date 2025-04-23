# # 基于文本、音频与视觉的扩散模型用于视频显著性预测

发布时间：2025年04月19日

`其他` `多媒体` `计算机视觉`

> Text-Audio-Visual-conditioned Diffusion Model for Video Saliency Prediction

# 摘要

> 视频显著性预测在视频压缩和人机交互等下游应用中发挥着重要作用。随着多模态学习的快速发展，研究人员开始探索视听和文本视觉等多模态视频显著性预测方法。听觉线索引导观众的注意力指向声源，文本线索则为理解视频内容提供语义指导。整合这些互补线索可以提升显著性预测的准确性。因此，本文提出了一种基于文本-音频-视觉条件的扩散模型——TAVDiff，用于视频显著性预测。TAVDiff将视频显著性预测视为基于文本、音频和视觉输入的图像生成任务，并通过逐步去噪生成显著性图。为了充分利用文本信息，我们采用大型多模态模型生成视频帧的文本描述，并引入以显著性为导向的图像-文本响应（SITR）机制，生成图像-文本响应图作为条件信息，引导模型定位与文本描述语义相关的视觉区域。在听觉模态方面，其被用作另一种条件信息，引导模型关注由声音指示的显著区域。同时，由于扩散变换器（DiT）直接将条件信息与时间步连接可能影响噪声水平的估计，我们提出了Saliency-DiT，将条件信息与时间步解耦以实现更有效的条件引导。实验结果表明，TAVDiff在SIM、CC、NSS和AUC-J指标上分别提升了1.03%、2.35%、2.71%和0.33%，显著优于现有方法。

> Video saliency prediction is crucial for downstream applications, such as video compression and human-computer interaction. With the flourishing of multimodal learning, researchers started to explore multimodal video saliency prediction, including audio-visual and text-visual approaches. Auditory cues guide the gaze of viewers to sound sources, while textual cues provide semantic guidance for understanding video content. Integrating these complementary cues can improve the accuracy of saliency prediction. Therefore, we attempt to simultaneously analyze visual, auditory, and textual modalities in this paper, and propose TAVDiff, a Text-Audio-Visual-conditioned Diffusion Model for video saliency prediction. TAVDiff treats video saliency prediction as an image generation task conditioned on textual, audio, and visual inputs, and predicts saliency maps through stepwise denoising. To effectively utilize text, a large multimodal model is used to generate textual descriptions for video frames and introduce a saliency-oriented image-text response (SITR) mechanism to generate image-text response maps. It is used as conditional information to guide the model to localize the visual regions that are semantically related to the textual description. Regarding the auditory modality, it is used as another conditional information for directing the model to focus on salient regions indicated by sounds. At the same time, since the diffusion transformer (DiT) directly concatenates the conditional information with the timestep, which may affect the estimation of the noise level. To achieve effective conditional guidance, we propose Saliency-DiT, which decouples the conditional information from the timestep. Experimental results show that TAVDiff outperforms existing methods, improving 1.03\%, 2.35\%, 2.71\% and 0.33\% on SIM, CC, NSS and AUC-J metrics, respectively.

[Arxiv](https://arxiv.org/abs/2504.14267)