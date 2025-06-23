# 现成的多模态大型语言模型在线情节记忆问答任务中究竟能达到怎样的高度？

发布时间：2025年06月19日

`LLM应用` `视频处理` `视频问答`

> How Far Can Off-the-Shelf Multimodal Large Language Models Go in Online Episodic Memory Question Answering?

# 摘要

> 我们研究了现成的多模态大型语言模型（MLLMs）是否可以在无需额外训练的情况下处理在线情节记忆视频问答（OEM-VQA）任务。我们的方法通过一个多模态描述模块，将流式自我中心视频转换为轻量级文本记忆，每分钟仅占用几千字节的存储空间，并通过一个大型语言模型推理模块查询此记忆来回答多项选择问题。在QAEgo4D-Closed基准测试中，我们的最佳配置实现了56.0%的准确率，每分钟仅占用3.6千字节的存储空间，达到了专用最先进系统的表现水平，同时在内存效率上提高了10^4/10^5倍。大量的消融实验提供了对每个组件和设计选择作用的见解，并为未来的研究指明了改进方向。

> We investigate whether off-the-shelf Multimodal Large Language Models (MLLMs) can tackle Online Episodic-Memory Video Question Answering (OEM-VQA) without additional training. Our pipeline converts a streaming egocentric video into a lightweight textual memory, only a few kilobytes per minute, via an MLLM descriptor module, and answers multiple-choice questions by querying this memory with an LLM reasoner module. On the QAEgo4D-Closed benchmark, our best configuration attains 56.0% accuracy with 3.6 kB per minute storage, matching the performance of dedicated state-of-the-art systems while being 10**4/10**5 times more memory-efficient. Extensive ablations provides insights into the role of each component and design choice, and highlight directions of improvement for future research.

[Arxiv](https://arxiv.org/abs/2506.16450)