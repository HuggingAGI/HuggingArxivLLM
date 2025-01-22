# 多模态LLMs能否胜任视觉时间理解和推理？答案是：不行！

发布时间：2025年01月18日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在视觉问答（VQA）任务中的应用，特别是针对时间理解和推理能力的评估。论文提出了一个新的评估基准（TemporalVQA），并对现有的MLLMs（如GPT-4o和Gemini-1.5-Pro）进行了测试。这些内容属于LLM在实际任务中的应用和性能评估，因此分类为LLM应用。` `计算机视觉` `时间理解`

> Can Multimodal LLMs do Visual Temporal Understanding and Reasoning? The answer is No!

# 摘要

> 多模态大型语言模型（MLLMs）借助基础大型语言模型（LLMs）在视觉问答（VQA）等任务中取得了显著进展。然而，它们在时间理解等关键领域的能力仍待深入探索。为此，我们提出了一个名为TemporalVQA的挑战性评估基准，包含两部分：（1）时间顺序理解和（2）时间间隔估计。第一部分要求MLLMs通过分析连续视频帧来确定事件顺序；第二部分则以多项选择题形式展示不同时间间隔的图像对，要求MLLMs估计图像间的时间差，选项从秒到年不等。我们对包括GPT-4o和Gemini-1.5-Pro在内的先进MLLMs进行评估，发现显著挑战：GPT-4o在时间顺序任务中仅达到43.8%的平均一致准确率，在时间间隔估计中为70%，开源模型表现更差。这些结果揭示了当前MLLMs在视觉时间理解和推理方面的不足，强调了进一步改进其时间能力的必要性。数据集可在https://huggingface.co/datasets/fazliimam/temporal-vqa获取。

> Multimodal Large Language Models (MLLMs) have achieved significant advancements in tasks like Visual Question Answering (VQA) by leveraging foundational Large Language Models (LLMs). However, their abilities in specific areas such as temporal understanding, which is crucial for comprehending real-world dynamics, remain underexplored. To address this, we propose a challenging evaluation benchmark named TemporalVQA, consisting of two parts: (1) Temporal Order Understanding and (2) Time-lapse Estimation. The first part requires MLLMs to determine the sequence of events by analyzing temporally consecutive video frames. The second part presents image pairs with varying time differences, framed as multiple-choice questions, asking MLLMs to estimate the time-lapse between images with options ranging from seconds to years. Our evaluations of advanced MLLMs, including models like GPT-4o and Gemini-1.5-Pro, reveal significant challenges: GPT-4o achieved only 43.8% average consistent accuracy in temporal order tasks and 70% in time-lapse estimation, with open-source models performing even less effectively. These findings underscore the limitations of current MLLMs in visual temporal understanding and reasoning, highlighting the need for further improvements in their temporal capabilities. Our dataset can be found at https://huggingface.co/datasets/fazliimam/temporal-vqa.

[Arxiv](https://arxiv.org/abs/2501.10674)