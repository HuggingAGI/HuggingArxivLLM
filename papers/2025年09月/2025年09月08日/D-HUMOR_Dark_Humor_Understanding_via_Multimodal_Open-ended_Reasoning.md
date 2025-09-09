# D-HUMOR：基于多模态开放式推理的黑色幽默理解

发布时间：2025年09月08日

`LLM应用` `媒体与娱乐`

> D-HUMOR: Dark Humor Understanding via Multimodal Open-ended Reasoning

# 摘要

> 网络表情包中的黑色幽默因其依赖隐晦、敏感且具有文化背景的线索，带来了独特的挑战。为解决多模态内容中黑色幽默检测资源与方法的匮乏，我们构建了一个全新数据集，包含4379个Reddit表情包，并标注了黑色幽默、目标类别（性别、心理健康、暴力、种族、残疾及其他）以及三级强度评级（轻微、中等、严重）。基于该数据集，我们提出了一个推理增强框架：首先利用大型视觉语言模型（VLM）为每个表情包生成结构化解释；通过“角色反转自循环”机制，VLM切换到表情包作者视角，迭代优化解释内容，确保其完整性与一致性。接着，我们通过文本编码器从OCR文字转录与自优化推理中提取文本特征，同时借助视觉Transformer提取视觉特征。三流交叉推理网络（TCRNet）通过成对注意力机制融合文本、图像与推理这三个流，生成用于分类的统一特征表示。实验结果显示，我们的方法在三个任务上均优于现有强基线：黑色幽默检测、目标识别与强度预测。我们已公开数据集、标注及代码，旨在推动多模态幽默理解与内容审核领域的深入研究。代码与数据集获取链接：https://github.com/Sai-Kartheek-Reddy/D-Humor-Dark-Humor-Understanding-via-Multimodal-Open-ended-Reasoning

> Dark humor in online memes poses unique challenges due to its reliance on implicit, sensitive, and culturally contextual cues. To address the lack of resources and methods for detecting dark humor in multimodal content, we introduce a novel dataset of 4,379 Reddit memes annotated for dark humor, target category (gender, mental health, violence, race, disability, and other), and a three-level intensity rating (mild, moderate, severe). Building on this resource, we propose a reasoning-augmented framework that first generates structured explanations for each meme using a Large Vision-Language Model (VLM). Through a Role-Reversal Self-Loop, VLM adopts the author's perspective to iteratively refine its explanations, ensuring completeness and alignment. We then extract textual features from both the OCR transcript and the self-refined reasoning via a text encoder, while visual features are obtained using a vision transformer. A Tri-stream Cross-Reasoning Network (TCRNet) fuses these three streams, text, image, and reasoning, via pairwise attention mechanisms, producing a unified representation for classification. Experimental results demonstrate that our approach outperforms strong baselines across three tasks: dark humor detection, target identification, and intensity prediction. The dataset, annotations, and code are released to facilitate further research in multimodal humor understanding and content moderation. Code and Dataset are available at: https://github.com/Sai-Kartheek-Reddy/D-Humor-Dark-Humor-Understanding-via-Multimodal-Open-ended-Reasoning

[Arxiv](https://arxiv.org/abs/2509.06771)