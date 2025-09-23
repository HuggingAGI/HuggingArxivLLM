# AHA——预测下一步关键：无需前瞻的在线高光检测

发布时间：2025年09月19日

`Agent` `交通运输`

> AHA -- Predicting What Matters Next: Online Highlight Detection Without Looking Ahead

# 摘要

> 在自动驾驶汽车、监控无人机和灾害响应机器人等高风险环境中，智能体对连续视频流的实时理解能力至关重要。然而，现有的大多数视频理解和高光检测方法在推理时需要访问完整视频，因此无法适用于在线或流式场景。尤其是，现有模型多针对离线摘要生成进行优化，难以支持实时决策所需的逐步推理过程。为此，我们提出Aha——一种自回归高光检测框架，能够根据自然语言描述的任务预测每个视频帧的相关性。

Aha无需访问未来视频帧，而是借助多模态视觉语言模型和轻量级解耦头（在大型精心整理的以人为中心的视频标签数据集上训练）实现检测。为实现可扩展性，我们提出动态SinkCache机制，该机制能在无限长度流上保持恒定内存占用，且不会降低在标准基准测试中的性能。该机制促使隐藏表示捕捉高级任务目标，进而实现针对自然语言任务的信息量、相关性和不确定性的有效帧级排序。

Aha在高光检测基准测试中达到了最先进（SOTA）性能，在TVSum和Mr.Hisum数据集上的平均精度均值（mAP）分别比以往的离线全上下文方法和视频语言模型高出5.9%和8.3%。我们还探索了Aha在现实世界机器人应用中的潜力，具体场景为给定面向任务的自然语言输入和连续的以机器人为中心的视频。两项实验均表明，Aha有望成为下游规划和长程理解的实时推理模块。

> Real-time understanding of continuous video streams is essential for intelligent agents operating in high-stakes environments, including autonomous vehicles, surveillance drones, and disaster response robots. Yet, most existing video understanding and highlight detection methods assume access to the entire video during inference, making them unsuitable for online or streaming scenarios. In particular, current models optimize for offline summarization, failing to support step-by-step reasoning needed for real-time decision-making. We introduce Aha, an autoregressive highlight detection framework that predicts the relevance of each video frame against a task described in natural language. Without accessing future video frames, Aha utilizes a multimodal vision-language model and lightweight, decoupled heads trained on a large, curated dataset of human-centric video labels. To enable scalability, we introduce the Dynamic SinkCache mechanism that achieves constant memory usage across infinite-length streams without degrading performance on standard benchmarks. This encourages the hidden representation to capture high-level task objectives, enabling effective frame-level rankings for informativeness, relevance, and uncertainty with respect to the natural language task. Aha achieves state-of-the-art (SOTA) performance on highlight detection benchmarks, surpassing even prior offline, full-context approaches and video-language models by +5.9% on TVSum and +8.3% on Mr.Hisum in mAP (mean Average Precision). We explore Aha's potential for real-world robotics applications given a task-oriented natural language input and a continuous, robot-centric video. Both experiments demonstrate Aha's potential effectiveness as a real-time reasoning module for downstream planning and long-horizon understanding.

[Arxiv](https://arxiv.org/abs/2509.16421)