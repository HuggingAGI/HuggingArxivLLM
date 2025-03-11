# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月10日

`LLM应用` `计算机视觉` `数据选择`

> Filter Images First, Generate Instructions Later: Pre-Instruction Data Selection for Visual Instruction Tuning

# 摘要

> 对大型视觉语言模型（LVLMs）进行视觉指令微调（VIT）需要在包含大量图像-指令对的扩展数据集上进行训练，这可能会非常昂贵。最近的 VIT 数据选择工作旨在通过选择一小部分高质量的图像-指令对，在减少运行时间的同时保持性能。然而，一个常被忽视的挑战是，为 VIT 从无标签图像生成指令的成本极高。现有的 VIT 数据集多依赖人工标注或付费服务，这限制了资源有限的用户创建自定义数据集。为解决这一问题，我们提出了预指令数据选择（PreSel），一种更实用的范式，直接选择最有益的无标签图像并生成指令。PreSel 首先估计任务重要性以确定采样预算，然后在每个任务内聚类图像特征并选择代表性图像。这降低了指令生成和模型微调的计算开销。通过仅为 15% 的图像生成指令，PreSel 在 LLaVA-1.5 和 Vision-Flan 数据集上实现了与全数据 VIT 相当的性能。项目链接：https://bardisafa.github.io/PreSel

> Visual instruction tuning (VIT) for large vision-language models (LVLMs) requires training on expansive datasets of image-instruction pairs, which can be costly. Recent efforts in VIT data selection aim to select a small subset of high-quality image-instruction pairs, reducing VIT runtime while maintaining performance comparable to full-scale training. However, a major challenge often overlooked is that generating instructions from unlabeled images for VIT is highly expensive. Most existing VIT datasets rely heavily on human annotations or paid services like the GPT API, which limits users with constrained resources from creating VIT datasets for custom applications. To address this, we introduce Pre-Instruction Data Selection (PreSel), a more practical data selection paradigm that directly selects the most beneficial unlabeled images and generates instructions only for the selected images. PreSel first estimates the relative importance of each vision task within VIT datasets to derive task-wise sampling budgets. It then clusters image features within each task, selecting the most representative images with the budget. This approach reduces computational overhead for both instruction generation during VIT data formation and LVLM fine-tuning. By generating instructions for only 15% of the images, PreSel achieves performance comparable to full-data VIT on the LLaVA-1.5 and Vision-Flan datasets. The link to our project page: https://bardisafa.github.io/PreSel

[Arxiv](https://arxiv.org/abs/2503.07591)