# 无监督视觉链式推理：基于偏好优化的新探索

发布时间：2025年04月25日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（MLLMs）在视觉链式思维推理中的应用，提出了一种新的无监督方法（UV-CoT）来提升模型的视觉理解能力。论文专注于如何通过改进模型的推理机制来增强其实际应用效果，属于应用层面的创新。` `计算机视觉` `多模态模型`

> Unsupervised Visual Chain-of-Thought Reasoning via Preference Optimization

# 摘要

> # 摘要
链式思维（Chain-of-thought, CoT）推理显著提升了多模态大型语言模型（MLLMs）的可解释性和问题解决能力。然而，现有方法主要集中在文本链式思维上，限制了它们对视觉线索的利用能力。视觉链式思维尚未得到充分探索，目前唯一相关的工作基于监督微调（SFT），依赖大量标注的边界框数据，难以推广到未见案例。本文引入无监督视觉链式思维（Unsupervised Visual CoT, UV-CoT），一种通过偏好优化实现图像级链式推理的新框架。UV-CoT对模型生成的边界框进行偏好比较（一个被偏好，另一个被排除），无需边界框标注。我们通过引入自动数据生成管道获取此类偏好数据。给定一张图像，目标 MLLM（例如 LLaVA-1.5-7B）使用模板提示生成种子边界框，然后使用每个边界区域作为输入回答问题。评估器 MLLM（例如 OmniLLM-12B）对回答进行排序，这些排序作为监督信号，通过最小化负对数似然损失来训练目标 MLLM 进行 UV-CoT。通过模拟人类感知——识别关键区域并基于它们进行推理——UV-CoT 可以提升视觉理解，特别是在仅靠文本描述难以解决的空间推理任务中。我们在六个数据集上的实验表明，UV-CoT 优于现有的文本和视觉链式思维方法。我们在四个未见数据集上的零样本测试展示了 UV-CoT 的强大泛化能力。代码可在 https://github.com/kesenzhao/UV-CoT 获取。


> Chain-of-thought (CoT) reasoning greatly improves the interpretability and problem-solving abilities of multimodal large language models (MLLMs). However, existing approaches are focused on text CoT, limiting their ability to leverage visual cues. Visual CoT remains underexplored, and the only work is based on supervised fine-tuning (SFT) that relies on extensive labeled bounding-box data and is hard to generalize to unseen cases. In this paper, we introduce Unsupervised Visual CoT (UV-CoT), a novel framework for image-level CoT reasoning via preference optimization. UV-CoT performs preference comparisons between model-generated bounding boxes (one is preferred and the other is dis-preferred), eliminating the need for bounding-box annotations. We get such preference data by introducing an automatic data generation pipeline. Given an image, our target MLLM (e.g., LLaVA-1.5-7B) generates seed bounding boxes using a template prompt and then answers the question using each bounded region as input. An evaluator MLLM (e.g., OmniLLM-12B) ranks the responses, and these rankings serve as supervision to train the target MLLM with UV-CoT by minimizing negative log-likelihood losses. By emulating human perception--identifying key regions and reasoning based on them--UV-CoT can improve visual comprehension, particularly in spatial reasoning tasks where textual descriptions alone fall short. Our experiments on six datasets demonstrate the superiority of UV-CoT, compared to the state-of-the-art textual and visual CoT methods. Our zero-shot testing on four unseen datasets shows the strong generalization of UV-CoT. The code is available in https://github.com/kesenzhao/UV-CoT.

[Arxiv](https://arxiv.org/abs/2504.18397)