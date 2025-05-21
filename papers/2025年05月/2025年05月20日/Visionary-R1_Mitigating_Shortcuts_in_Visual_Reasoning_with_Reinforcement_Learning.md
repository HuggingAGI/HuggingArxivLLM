# Visionary-R1：强化学习缓解视觉推理中的捷径问题

发布时间：2025年05月20日

`LLM应用` `视觉推理` `计算机视觉`

> Visionary-R1: Mitigating Shortcuts in Visual Reasoning with Reinforcement Learning

# 摘要

> 通用推理能力的学习一直是人工智能领域的难题。近期研究表明，强化学习技术（如GRPO）能让大型语言模型（如DeepSeek-R1）通过简单问答对发展推理能力。本研究尝试通过强化学习和视觉问答对训练视觉语言模型（VLMs），使其无需显式思维链（CoT）监督即可进行图像推理。研究发现，仅通过强化学习训练VLM——先生成推理链再给出答案——会导致模型从简单问题中寻找捷径，从而降低其在未见数据上的泛化能力。我们认为，缓解捷径学习的关键在于鼓励模型先解读图像再推理。因此，我们训练模型遵循“描述-推理-回答”的输出格式：先生成详细图像描述，再构建完整推理链。在仅使用强化学习训练，基于27.3万条无CoT的视觉问答对数据集上，我们的模型Visionary-R1在多个视觉推理基准测试中超越了GPT-4o、Claude3.5-Sonnet和Gemini-1.5-Pro等强大多模态模型。

> Learning general-purpose reasoning capabilities has long been a challenging problem in AI. Recent research in large language models (LLMs), such as DeepSeek-R1, has shown that reinforcement learning techniques like GRPO can enable pre-trained LLMs to develop reasoning capabilities using simple question-answer pairs. In this paper, we aim to train visual language models (VLMs) to perform reasoning on image data through reinforcement learning and visual question-answer pairs, without any explicit chain-of-thought (CoT) supervision. Our findings indicate that simply applying reinforcement learning to a VLM -- by prompting the model to produce a reasoning chain before providing an answer -- can lead the model to develop shortcuts from easy questions, thereby reducing its ability to generalize across unseen data distributions. We argue that the key to mitigating shortcut learning is to encourage the model to interpret images prior to reasoning. Therefore, we train the model to adhere to a caption-reason-answer output format: initially generating a detailed caption for an image, followed by constructing an extensive reasoning chain. When trained on 273K CoT-free visual question-answer pairs and using only reinforcement learning, our model, named Visionary-R1, outperforms strong multimodal models, such as GPT-4o, Claude3.5-Sonnet, and Gemini-1.5-Pro, on multiple visual reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2505.14677)