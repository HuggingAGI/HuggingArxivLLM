# BeamLLM：结合大型语言模型的视觉增强毫米波波束预测

发布时间：2025年03月13日

`LLM应用`

> BeamLLM: Vision-Empowered mmWave Beam Prediction with Large Language Models

# 摘要

> 本文提出了一种视觉辅助的毫米波（mmWave）波束预测框架 BeamLLM，借助大型语言模型（LLMs）解决毫米波通信系统中的高训练开销和时延问题。该框架结合计算机视觉（CV）与 LLMs 的跨模态推理能力，从 RGB 图像中提取用户设备（UE）的位置特征，并通过重新编程技术将视觉-时间特征与 LLMs 的语义空间对齐。在现实的车-路（V2I）场景下评估，该方法在标准预测任务中实现 61.01% 的 top-1 准确率和 97.39% 的 top-3 准确率，显著优于传统深度学习模型。在 few-shot 预测场景中，从时间样本 1 到 10，性能下降幅度仅为 12.56%（top-1）和 5.55%（top-3），展现出卓越的预测能力。

> In this paper, we propose BeamLLM, a vision-aided millimeter-wave (mmWave) beam prediction framework leveraging large language models (LLMs) to address the challenges of high training overhead and latency in mmWave communication systems. By combining computer vision (CV) with LLMs' cross-modal reasoning capabilities, the framework extracts user equipment (UE) positional features from RGB images and aligns visual-temporal features with LLMs' semantic space through reprogramming techniques. Evaluated on a realistic vehicle-to-infrastructure (V2I) scenario, the proposed method achieves 61.01% top-1 accuracy and 97.39% top-3 accuracy in standard prediction tasks, significantly outperforming traditional deep learning models. In few-shot prediction scenarios, the performance degradation is limited to 12.56% (top-1) and 5.55% (top-3) from time sample 1 to 10, demonstrating superior prediction capability.

[Arxiv](https://arxiv.org/abs/2503.10432)