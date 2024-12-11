# “我的话语暗示你的观点”：基于读者代理的个性化隐性情绪分析传播增强

发布时间：2024年12月10日

`LLM应用` `情绪分析` `用户研究`

> My Words Imply Your Opinion: Reader Agent-Based Propagation Enhancement for Personalized Implicit Emotion Analysis

# 摘要

> 在隐性情绪分析（IEA）里，情绪表达的微妙之处使得它对用户的特定特征极为敏感。现有的研究往往通过聚焦情感文本的作者维度来为分析注入个性化元素。然而，这些方法却忽视了预期读者对隐性情绪反应的潜在影响。在本文中，我们把IEA任务细化为个性化隐性情绪分析（PIEA），还引入了RAPPIE模型，这是一个专门用来解决该任务中用户信息缺失问题的新框架。具体而言，1）我们基于大型语言模型创建读者代理来模拟读者的反应，以此应对获取读者反馈信息时遭遇的沉默螺旋和数据不完整等难题。2）我们构建了读者传播角色系统，并研发了角色感知的情感传播多视图图学习模型，借助传播角色的分布有效处理了读者信息的稀疏性。3）我们用详尽的用户元数据为两个中文PIEA数据集做了标注，从而化解了先前数据集主要关注文本内容标注的局限性。在这些数据集上开展的大量实验表明，RAPPIE模型优于当下最先进的基线，凸显了将读者反馈融入PIEA过程的重要意义和显著成效。

> In implicit emotion analysis (IEA), the subtlety of emotional expressions makes it particularly sensitive to user-specific characteristics. Existing studies often inject personalization into the analysis by focusing on the authorial dimension of the emotional text. However, these methods overlook the potential influence of the intended reader on the reaction of implicit emotions. In this paper, we refine the IEA task to Personalized Implicit Emotion Analysis (PIEA) and introduce the RAPPIE model, a novel framework designed to address the issue of missing user information within this task. In particular, 1) we create reader agents based on the Large Language Model to simulate reader reactions, to address challenges of the spiral of silence and data incompleteness encountered when acquiring reader feedback information. 2) We establish a reader propagation role system and develop a role-aware emotion propagation multi-view graph learning model, which effectively deals with the sparsity of reader information by utilizing the distribution of propagation roles. 3) We annotate two Chinese PIEA datasets with detailed user metadata, thereby addressing the limitation of prior datasets that primarily focus on textual content annotation. Extensive experiments on these datasets indicate that the RAPPIE model outperforms current state-of-the-art baselines, highlighting the significance and efficacy of incorporating reader feedback into the PIEA process.

[Arxiv](https://arxiv.org/abs/2412.07367)