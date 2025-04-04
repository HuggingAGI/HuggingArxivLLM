# # OmniCam：通过相机控制实现统一多模态视频生成

发布时间：2025年04月03日

`LLM应用` `计算机视觉` `多模态`

> OmniCam: Unified Multimodal Video Generation via Camera Control

# 摘要

> 相机控制技术通过改变摄像头的位置和姿态，能够实现多样化的视觉效果，因此受到了广泛关注。然而，现有的方法在实现过程中面临交互复杂、控制能力有限等挑战。为了解决这些问题，我们提出了OmniCam，一个统一的多模态相机控制框架。OmniCam结合了大型语言模型和视频扩散模型，能够生成时空一致的视频内容。它支持多种输入模态的组合：用户可以提供文本或视频（附带预期轨迹）作为相机路径的引导，也可以提供图片或视频作为内容参考，从而实现对相机运动的精准控制。为了便于训练OmniCam，我们引入了OmniTr数据集，该数据集包含大量高质量的长序列轨迹、视频及其对应描述。实验结果表明，我们的模型在高质量的相机控制视频生成方面，无论是在哪些指标上，都达到了目前的最先进水平。

> Camera control, which achieves diverse visual effects by changing camera position and pose, has attracted widespread attention. However, existing methods face challenges such as complex interaction and limited control capabilities. To address these issues, we present OmniCam, a unified multimodal camera control framework. Leveraging large language models and video diffusion models, OmniCam generates spatio-temporally consistent videos. It supports various combinations of input modalities: the user can provide text or video with expected trajectory as camera path guidance, and image or video as content reference, enabling precise control over camera motion. To facilitate the training of OmniCam, we introduce the OmniTr dataset, which contains a large collection of high-quality long-sequence trajectories, videos, and corresponding descriptions. Experimental results demonstrate that our model achieves state-of-the-art performance in high-quality camera-controlled video generation across various metrics.

[Arxiv](https://arxiv.org/abs/2504.02312)