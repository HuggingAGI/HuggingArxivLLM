# MMR-V: 未言明之事？视频多模态深度推理基准测试

发布时间：2025年06月04日

`LLM应用` `视频处理` `多模态推理`

> MMR-V: What's Left Unsaid? A Benchmark for Multimodal Deep Reasoning in Videos

# 摘要

> 视频的时序结构对多模态大型语言模型（MLLMs）在定位多帧证据和进行多模态推理方面提出了独特挑战。现有的视频基准测试主要集中在理解任务上，这些任务仅要求模型匹配问题中提到的帧（以下简称“问题帧”）并感知少量相邻帧。为弥补这一研究空白，我们提出了MMR-V：用于视频中多模态深度推理的基准测试。该基准测试具有以下显著特点：

（1）长距离、多帧推理：模型需要推断并分析可能与问题帧相距较远的证据帧。

（2）超越感知：问题不能仅通过直接感知来回答，还需要推理隐藏的信息。

（3）可靠性：所有任务都经过人工标注，并参考了广泛的真实世界用户理解，以符合普遍认知。

（4）混淆性：精心设计的干扰标注策略以减少模型的捷径。

MMR-V包含317个视频和1,257个任务。实验结果显示，当前模型在多模态推理方面仍面临显著挑战；即使是最先进的模型o4-mini也只能达到52.5%的准确率。此外，当前的推理增强策略（Chain-of-Thought和扩展测试时间计算）带来的增益十分有限。进一步分析表明，多模态推理所需的CoT与文本推理中的CoT存在显著差异，这在一定程度上解释了性能提升的有限性。我们希望MMR-V能够激发进一步研究，以提升多模态推理能力。

> The sequential structure of videos poses a challenge to the ability of multimodal large language models (MLLMs) to locate multi-frame evidence and conduct multimodal reasoning. However, existing video benchmarks mainly focus on understanding tasks, which only require models to match frames mentioned in the question (hereafter referred to as "question frame") and perceive a few adjacent frames. To address this gap, we propose MMR-V: A Benchmark for Multimodal Deep Reasoning in Videos. The benchmark is characterized by the following features. (1) Long-range, multi-frame reasoning: Models are required to infer and analyze evidence frames that may be far from the question frame. (2) Beyond perception: Questions cannot be answered through direct perception alone but require reasoning over hidden information. (3) Reliability: All tasks are manually annotated, referencing extensive real-world user understanding to align with common perceptions. (4) Confusability: Carefully designed distractor annotation strategies to reduce model shortcuts. MMR-V consists of 317 videos and 1,257 tasks. Our experiments reveal that current models still struggle with multi-modal reasoning; even the best-performing model, o4-mini, achieves only 52.5% accuracy. Additionally, current reasoning enhancement strategies (Chain-of-Thought and scaling test-time compute) bring limited gains. Further analysis indicates that the CoT demanded for multi-modal reasoning differs from it in textual reasoning, which partly explains the limited performance gains. We hope that MMR-V can inspire further research into enhancing multi-modal reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2506.04141)