# PlanLLM: 基于可优化大型语言模型的视频程序规划

发布时间：2024年12月26日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来增强视频流程规划的能力，特别是通过LLMs生成自由形式的规划输出和增强动作步骤解码。论文的核心在于将LLMs应用于具体的任务（视频流程规划），并展示了其在处理封闭集和开放词汇任务中的有效性。因此，这篇论文应归类为LLM应用。` `视频处理` `人工智能`

> PlanLLM: Video Procedure Planning with Refinable Large Language Models

# 摘要

> # 视频流程规划
视频流程规划是指根据起始和目标状态的视频帧规划一系列动作步骤，这是具身AI的核心能力。最近的研究利用大型语言模型（LLMs）生成丰富的动作步骤描述文本，以指导动作步骤解码。然而，尽管引入了LLMs，这些方法仍将动作步骤解码为封闭集的一热向量，限制了模型对新步骤或任务的泛化能力。此外，基于世界级常识的固定动作步骤描述可能在特定视觉状态实例中包含噪声。本文提出PlanLLM，一个用于视频流程规划的跨模态联合学习框架。我们设计了LLM增强规划模块，充分利用LLMs的泛化能力生成自由形式的规划输出，并增强动作步骤解码。同时，我们提出了互信息最大化模块，将步骤描述的世界级常识与视觉状态的样本特定信息相结合，使LLMs能够利用推理能力生成步骤序列。在LLMs的帮助下，我们的方法能够同时处理封闭集和开放词汇的流程规划任务。PlanLLM在三个基准测试中表现优异，证明了我们设计的有效性。

> Video procedure planning, i.e., planning a sequence of action steps given the video frames of start and goal states, is an essential ability for embodied AI. Recent works utilize Large Language Models (LLMs) to generate enriched action step description texts to guide action step decoding. Although LLMs are introduced, these methods decode the action steps into a closed-set of one-hot vectors, limiting the model's capability of generalizing to new steps or tasks. Additionally, fixed action step descriptions based on world-level commonsense may contain noise in specific instances of visual states. In this paper, we propose PlanLLM, a cross-modal joint learning framework with LLMs for video procedure planning. We propose an LLM-Enhanced Planning module which fully uses the generalization ability of LLMs to produce free-form planning output and to enhance action step decoding. We also propose Mutual Information Maximization module to connect world-level commonsense of step descriptions and sample-specific information of visual states, enabling LLMs to employ the reasoning ability to generate step sequences. With the assistance of LLMs, our method can both closed-set and open vocabulary procedure planning tasks. Our PlanLLM achieves superior performance on three benchmarks, demonstrating the effectiveness of our designs.

[Arxiv](https://arxiv.org/abs/2412.19139)