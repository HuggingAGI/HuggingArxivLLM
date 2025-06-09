# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月22日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（MLLMs）如GPT-4V在图像取证领域的应用，特别是在图像拼接检测任务中的表现。研究采用了不同的提示策略进行评估，并分析了模型的检测能力和泛化能力。这属于对大型语言模型的具体应用研究，因此归类为LLM应用。` `图像处理` `计算机视觉`

> Can ChatGPT Perform Image Splicing Detection? A Preliminary Study

# 摘要

> 多模态大型语言模型（MLLMs）如GPT-4V在跨模态推理方面表现突出，在复杂的视觉-语言任务中展现出巨大潜力。本研究聚焦于探索GPT-4V在图像取证领域的开箱即用能力，特别是针对图像拼接检测任务。我们采用零样本（ZS）、少样本（FS）和链式思维（CoT）三种提示策略，对GPT-4V进行了系统评估，所有实验均基于CASIA v2.0拼接数据集的精选子集开展。

研究数据显示，GPT-4V在零样本场景下实现了超过85%的检测准确率，其中链式思维提示策略在真实与拼接图像的检测效果之间达到了最佳平衡。进一步的定性分析表明，该模型不仅能够识别低级视觉伪迹，还能借助现实世界中的常识信息（如物体尺度、语义一致性及建筑细节）来揭示不合理图像合成。尽管GPT-4V在性能上尚未超越专业的拼接检测模型，但其强大的泛化能力、可解释性和百科全书式的推理能力，使其成为图像取证领域极具潜力的灵活工具。

> Multimodal Large Language Models (MLLMs) like GPT-4V are capable of reasoning across text and image modalities, showing promise in a variety of complex vision-language tasks. In this preliminary study, we investigate the out-of-the-box capabilities of GPT-4V in the domain of image forensics, specifically, in detecting image splicing manipulations. Without any task-specific fine-tuning, we evaluate GPT-4V using three prompting strategies: Zero-Shot (ZS), Few-Shot (FS), and Chain-of-Thought (CoT), applied over a curated subset of the CASIA v2.0 splicing dataset.
  Our results show that GPT-4V achieves competitive detection performance in zero-shot settings (more than 85% accuracy), with CoT prompting yielding the most balanced trade-off across authentic and spliced images. Qualitative analysis further reveals that the model not only detects low-level visual artifacts but also draws upon real-world contextual knowledge such as object scale, semantic consistency, and architectural facts, to identify implausible composites. While GPT-4V lags behind specialized state-of-the-art splicing detection models, its generalizability, interpretability, and encyclopedic reasoning highlight its potential as a flexible tool in image forensics.

[Arxiv](https://arxiv.org/abs/2506.05358)