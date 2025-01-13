# 零-shot 鲨鱼追踪与航拍图像生物特征提取

发布时间：2025年01月10日

`LLM应用

理由：这篇论文主要讨论了如何利用现有的机器学习模型（如Segment Anything Model 2和CLIP）来改进无人机图像分析的工作流程，特别是通过零-shot方法减少对标记数据和模型训练的依赖。虽然论文中提到的模型（如SAM2和CLIP）本身是大型语言模型（LLM）或与LLM相关的技术，但论文的重点在于如何将这些模型应用于具体的任务（无人机图像分析），而不是探讨LLM的理论或开发新的LLM技术。因此，这篇论文更适合归类为“LLM应用”。` `海洋生物学` `无人机`

> Zero-shot Shark Tracking and Biometrics from Aerial Imagery

# 摘要

> 近年来，无人机在研究海洋动物中的广泛应用为从航空图像中提取生物信息提供了新的机会。无人机获取的大规模图像数据非常适合机器学习（ML）分析。然而，传统的ML模型开发流程需要为每个数据集训练、测试和部署新模型，耗费大量时间、人力和专业知识。为此，我们提出了帧级对齐和跟踪（FLAIR）方法，结合了Segment Anything Model 2（SAM2）的视频理解能力和对比语言-图像预训练（CLIP）的视觉-语言能力。FLAIR以无人机视频为输入，输出视频中目标物种的分割掩码。FLAIR采用零-shot方法，无需标记数据、训练新模型或微调现有模型即可泛化到其他物种。我们使用18,000张太平洋护士鲨的无人机图像数据集，训练了最先进的目标检测模型与FLAIR进行对比。结果显示，FLAIR在这些目标检测器上表现卓越，并且在两种人类参与的SAM2提示方法中表现优异，Dice分数达到0.81。FLAIR能够轻松泛化到其他鲨鱼物种，无需额外人力，并且可以与新的启发式方法结合，自动提取包括长度和尾拍频率在内的相关信息。FLAIR在加速航空图像分析工作流程方面具有巨大潜力，相比传统ML工作流程，显著减少了人力和专业知识需求，同时实现了更高的准确性。通过减少航空图像分析的工作量，FLAIR使科学家能够将更多时间用于解释结果和获取海洋生态系统的见解。

> The recent widespread adoption of drones for studying marine animals provides opportunities for deriving biological information from aerial imagery. The large scale of imagery data acquired from drones is well suited for machine learning (ML) analysis. Development of ML models for analyzing marine animal aerial imagery has followed the classical paradigm of training, testing, and deploying a new model for each dataset, requiring significant time, human effort, and ML expertise. We introduce Frame Level ALIgment and tRacking (FLAIR), which leverages the video understanding of Segment Anything Model 2 (SAM2) and the vision-language capabilities of Contrastive Language-Image Pre-training (CLIP). FLAIR takes a drone video as input and outputs segmentation masks of the species of interest across the video. Notably, FLAIR leverages a zero-shot approach, eliminating the need for labeled data, training a new model, or fine-tuning an existing model to generalize to other species. With a dataset of 18,000 drone images of Pacific nurse sharks, we trained state-of-the-art object detection models to compare against FLAIR. We show that FLAIR massively outperforms these object detectors and performs competitively against two human-in-the-loop methods for prompting SAM2, achieving a Dice score of 0.81. FLAIR readily generalizes to other shark species without additional human effort and can be combined with novel heuristics to automatically extract relevant information including length and tailbeat frequency. FLAIR has significant potential to accelerate aerial imagery analysis workflows, requiring markedly less human effort and expertise than traditional machine learning workflows, while achieving superior accuracy. By reducing the effort required for aerial imagery analysis, FLAIR allows scientists to spend more time interpreting results and deriving insights about marine ecosystems.

[Arxiv](https://arxiv.org/abs/2501.05717)