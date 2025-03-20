# # ChatStitch：基于结构的可视化，利用协作式LLM智能体进行环绕视图无监督深度图像拼接

发布时间：2025年03月19日

`Agent` `智能驾驶` `计算机视觉`

> ChatStitch: Visualizing Through Structures via Surround-View Unsupervised Deep Image Stitching with Collaborative LLM-Agents

# 摘要

> 协作感知因其通过与周围车辆智能体交换信息的能力来增强单个车辆的感知能力而受到广泛关注。然而，现有的协作感知系统在用户交互效率和多摄像头 photorealistic 可视化方面存在局限性。为了解决这些挑战，本文介绍了 ChatStitch，这是首个能够通过集成外部数字资产的自然语言命令揭示被遮挡的盲点信息的协作感知系统。为了能够处理复杂或抽象的命令，ChatStitch 采用了基于大型语言模型的多智能体协作框架。为了实现人类最直观的感知，ChatStitch 提出了 SV-UDIS，这是首个在非全局重叠条件下的全视角无监督深度图像拼接方法。我们在 UDIS-D、MCOV-SLAM 开源数据集以及我们的真实世界数据集上进行了大量实验。具体来说，我们的 SV-UDIS 方法在 UDIS-D 数据集上实现了 3、4 和 5 张图像拼接任务的最先进性能，PSNR 分别提升了 9%、17% 和 21%，SSIM 分别提升了 8%、18% 和 26%。

> Collaborative perception has garnered significant attention for its ability to enhance the perception capabilities of individual vehicles through the exchange of information with surrounding vehicle-agents. However, existing collaborative perception systems are limited by inefficiencies in user interaction and the challenge of multi-camera photorealistic visualization. To address these challenges, this paper introduces ChatStitch, the first collaborative perception system capable of unveiling obscured blind spot information through natural language commands integrated with external digital assets. To adeptly handle complex or abstract commands, ChatStitch employs a multi-agent collaborative framework based on Large Language Models. For achieving the most intuitive perception for humans, ChatStitch proposes SV-UDIS, the first surround-view unsupervised deep image stitching method under the non-global-overlapping condition. We conducted extensive experiments on the UDIS-D, MCOV-SLAM open datasets, and our real-world dataset. Specifically, our SV-UDIS method achieves state-of-the-art performance on the UDIS-D dataset for 3, 4, and 5 image stitching tasks, with PSNR improvements of 9%, 17%, and 21%, and SSIM improvements of 8%, 18%, and 26%, respectively.

[Arxiv](https://arxiv.org/abs/2503.14948)