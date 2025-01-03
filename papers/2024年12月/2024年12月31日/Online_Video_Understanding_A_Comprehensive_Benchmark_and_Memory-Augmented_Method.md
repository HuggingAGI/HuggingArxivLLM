# 在线视频理解：全面基准与记忆增强方法

发布时间：2024年12月31日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在在线视频理解中的应用，特别是针对自动驾驶和人机交互等现实场景的挑战。论文提出了评估基准、模型架构和训练策略的系统性解决方案，并开发了一个名为VideoChat-Online的在线视频理解模型。这些内容主要涉及如何将大型语言模型应用于具体的实际问题，因此归类为LLM应用。` `自动驾驶` `人机交互`

> Online Video Understanding: A Comprehensive Benchmark and Memory-Augmented Method

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在离线视频理解领域取得了显著进展。然而，将这些模型应用于自动驾驶和人机交互等现实场景时，由于需要实时处理连续的在线视频流，带来了独特的挑战。为此，本文从评估基准、模型架构和训练策略三个角度提出了系统性解决方案。首先，我们推出了OVBench，这是一个专门用于评估模型在在线视频上下文中感知、记忆和推理能力的综合问答基准，涵盖过去、现在和未来三个时间上下文中的六种核心任务类型，形成了16个子任务。其次，我们提出了金字塔记忆库（PMB），能够有效保留视频流中的关键时空信息。第三，我们设计了一种从离线到在线的学习范式，构建了在线视频数据的交错对话格式，并开发了专门用于在线视频训练的指令微调数据集。这一框架催生了VideoChat-Online，一个强大且高效的在线视频理解模型。尽管计算成本更低且效率更高，VideoChat-Online在流行的离线视频基准和OVBench上均超越了现有的最先进离线和在线模型，充分证明了我们的模型架构和训练策略的有效性。

> Multimodal Large Language Models (MLLMs) have shown significant progress in offline video understanding. However, applying these models to real-world scenarios, such as autonomous driving and human-computer interaction, presents unique challenges due to the need for real-time processing of continuous online video streams. To this end, this paper presents systematic efforts from three perspectives: evaluation benchmark, model architecture, and training strategy. First, we introduce OVBench, a comprehensive question-answering benchmark specifically designed to evaluate models' ability to perceive, memorize, and reason within online video contexts. It features six core task types across three temporal contexts-past, present, and future-forming 16 subtasks from diverse datasets. Second, we propose a new Pyramid Memory Bank (PMB) that effectively retains key spatiotemporal information in video streams. Third, we proposed an offline-to-online learning paradigm, designing an interleaved dialogue format for online video data and constructing an instruction-tuning dataset tailored for online video training. This framework led to the development of VideoChat-Online, a robust and efficient model for online video understanding. Despite the lower computational cost and higher efficiency, VideoChat-Online outperforms existing state-of-the-art offline and online models across popular offline video benchmarks and OVBench, demonstrating the effectiveness of our model architecture and training strategy.

[Arxiv](https://arxiv.org/abs/2501.00584)