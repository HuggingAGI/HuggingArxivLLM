# 流媒体视频理解与记忆增强知识的多轮交互

发布时间：2025年01月23日

`LLM应用

理由：这篇论文主要介绍了StreamChat，一个用于流媒体视频推理与对话交互的框架，该框架结合了视频数据和语言任务，属于大型语言模型（LLMs）在多模态学习中的应用。论文的重点在于如何通过创新的分层记忆系统和并行调度策略来提升视频理解和对话交互的性能，这属于LLM在实际应用中的具体实现和优化，因此归类为LLM应用。` `流媒体` `视频理解`

> Streaming Video Understanding and Multi-round Interaction with Memory-enhanced Knowledge

# 摘要

> # 摘要
大型语言模型（LLMs）的最新进展催生了视频-LLMs，通过融合视频数据与语言任务，推动了多模态学习的发展。然而，现有视频理解模型在处理长视频、支持多轮对话及适应动态场景方面仍面临挑战。为此，我们提出了StreamChat，一个无需训练的流媒体视频推理与对话交互框架。StreamChat采用创新的分层记忆系统，高效处理并压缩长视频序列特征，实现实时多轮对话。框架还引入了并行系统调度策略，提升处理速度，降低延迟，确保实际应用中的稳定表现。此外，我们推出了StreamBench，一个多功能基准测试，用于评估跨媒体类型和交互场景的流媒体视频理解能力，涵盖多轮对话和复杂推理任务。在StreamBench及其他公共基准测试上的广泛评估显示，StreamChat在准确性和响应时间上显著超越现有顶尖模型，证明了其在流媒体视频理解中的卓越性能。代码已开源：https://github.com/hmxiong/StreamChat。

> Recent advances in Large Language Models (LLMs) have enabled the development of Video-LLMs, advancing multimodal learning by bridging video data with language tasks. However, current video understanding models struggle with processing long video sequences, supporting multi-turn dialogues, and adapting to real-world dynamic scenarios. To address these issues, we propose StreamChat, a training-free framework for streaming video reasoning and conversational interaction. $\StreamChat$ leverages a novel hierarchical memory system to efficiently process and compress video features over extended sequences, enabling real-time, multi-turn dialogue. Our framework incorporates a parallel system scheduling strategy that enhances processing speed and reduces latency, ensuring robust performance in real-world applications. Furthermore, we introduce StreamBench, a versatile benchmark that evaluates streaming video understanding across diverse media types and interactive scenarios, including multi-turn interactions and complex reasoning tasks. Extensive evaluations on StreamBench and other public benchmarks demonstrate that StreamChat significantly outperforms existing state-of-the-art models in terms of accuracy and response times, confirming its effectiveness for streaming video understanding. Code is available at StreamChat: https://github.com/hmxiong/StreamChat.

[Arxiv](https://arxiv.org/abs/2501.13468)