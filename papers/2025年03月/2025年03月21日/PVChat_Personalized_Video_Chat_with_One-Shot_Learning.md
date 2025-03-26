# # PVChat: 通过单样本学习实现个性化视频聊天

发布时间：2025年03月21日

`LLM应用` `智能医疗` `智能家居`

> PVChat: Personalized Video Chat with One-Shot Learning

# 摘要

> 视频大型语言模型（ViLLMs）在视频理解方面表现出色，能够识别说话、吃饭等活动，但在身份感知理解方面存在局限，如无法准确理解“Wilson正在接受化疗”或“Tom正在与Sarah讨论”。这种局限性限制了它们在智能医疗和智能家居环境中的应用。为此，我们提出了一种单样本学习框架PVChat，这是首个支持主体感知问答（QA）的个性化ViLLM。PVChat能够在每个主体仅提供一个视频的情况下实现主体相关的问答。我们的方法采用了一种多头混合（MoH）增强的ViLLM，并在合成增强的视频-QA数据集上进行优化，采用渐进式图像到视频的学习策略。我们引入了一条自动增强管道，用于合成保留身份的正样本，并从现有视频语料库中检索困难负样本，生成包含存在性、外貌、动作和位置查询四种QA类型的多样化训练数据集。为了增强主体特定的学习，我们提出了一种ReLU路由的MoH注意力机制，同时提出了两个新颖的目标：(1) 通过指数距离缩放实现渐进式学习的平滑邻近正则化；(2) 用于平衡注意力路由的头部激活增强。最后，我们采用了一种两阶段训练策略，从图像预训练过渡到视频微调，实现了从静态属性到动态表示的渐进式学习过程。我们在涵盖医疗场景、电视剧、动漫和现实世界片段的多样化数据集上对PVChat进行了评估，结果表明，在学习单个视频后，PVChat在个性化特征理解方面优于现有的ViLLMs。

> Video large language models (ViLLMs) excel in general video understanding, e.g., recognizing activities like talking and eating, but struggle with identity-aware comprehension, such as "Wilson is receiving chemotherapy" or "Tom is discussing with Sarah", limiting their applicability in smart healthcare and smart home environments. To address this limitation, we propose a one-shot learning framework PVChat, the first personalized ViLLM that enables subject-aware question answering (QA) from a single video for each subject. Our approach optimizes a Mixture-of-Heads (MoH) enhanced ViLLM on a synthetically augmented video-QA dataset, leveraging a progressive image-to-video learning strategy. Specifically, we introduce an automated augmentation pipeline that synthesizes identity-preserving positive samples and retrieves hard negatives from existing video corpora, generating a diverse training dataset with four QA types: existence, appearance, action, and location inquiries. To enhance subject-specific learning, we propose a ReLU Routing MoH attention mechanism, alongside two novel objectives: (1) Smooth Proximity Regularization for progressive learning through exponential distance scaling and (2) Head Activation Enhancement for balanced attention routing. Finally, we adopt a two-stage training strategy, transitioning from image pre-training to video fine-tuning, enabling a gradual learning process from static attributes to dynamic representations. We evaluate PVChat on diverse datasets covering medical scenarios, TV series, anime, and real-world footage, demonstrating its superiority in personalized feature understanding after learning from a single video, compared to state-of-the-art ViLLMs.

[Arxiv](https://arxiv.org/abs/2503.17069)