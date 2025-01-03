# 大型语言模型在海洋哺乳动物图像分类中的基准测试

发布时间：2024年10月21日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）和多模态LLMs来处理海洋哺乳动物的图像分类问题，并构建了一个专门的数据集。论文还提到了一种基于LLM的多智能体系统（MAS）来提升分类性能。这些内容都属于LLM在实际应用中的使用，因此分类为LLM应用。` `海洋生物学` `人工智能`

> Benchmarking Large Language Models for Image Classification of Marine Mammals

# 摘要

> 随着人工智能（AI）的迅猛发展，新一代基于海量数据训练的大型语言模型（LLMs）在众多应用中取得了突破性进展。多模态LLMs也取得了显著进步，许多数据集被开发用于评估具备视觉能力的LLMs。然而，这些数据集中尚未有专门针对海洋哺乳动物的，而海洋哺乳动物对生态平衡至关重要。为此，我们构建了一个包含65种海洋哺乳动物的1,423张图像的基准数据集，每种动物被精确分类为从物种级别到群体级别的不同层次。我们还评估了多种分类方法：（1）基于神经网络嵌入的机器学习算法，（2）预训练神经网络，（3）零-shot模型如CLIP和LLMs，以及（4）一种创新的基于LLM的多智能体系统（MAS）。结果显示，传统模型和LLMs各有所长，而MAS则能进一步提升分类性能。数据集已开源，详见GitHub：https://github.com/yeyimilk/LLM-Vision-Marine-Animals.git。

> As Artificial Intelligence (AI) has developed rapidly over the past few decades, the new generation of AI, Large Language Models (LLMs) trained on massive datasets, has achieved ground-breaking performance in many applications. Further progress has been made in multimodal LLMs, with many datasets created to evaluate LLMs with vision abilities. However, none of those datasets focuses solely on marine mammals, which are indispensable for ecological equilibrium. In this work, we build a benchmark dataset with 1,423 images of 65 kinds of marine mammals, where each animal is uniquely classified into different levels of class, ranging from species-level to medium-level to group-level. Moreover, we evaluate several approaches for classifying these marine mammals: (1) machine learning (ML) algorithms using embeddings provided by neural networks, (2) influential pre-trained neural networks, (3) zero-shot models: CLIP and LLMs, and (4) a novel LLM-based multi-agent system (MAS). The results demonstrate the strengths of traditional models and LLMs in different aspects, and the MAS can further improve the classification performance. The dataset is available on GitHub: https://github.com/yeyimilk/LLM-Vision-Marine-Animals.git.

[Arxiv](https://arxiv.org/abs/2410.19848)