# 推理模型中的同侪学习之道

发布时间：2025年05月12日

`LLM理论` `人工智能`

> Learning from Peers in Reasoning Models

# 摘要

> 大型推理模型（LRMs）虽能自我修正推理中的错误，但我们的研究发现，若推理初始阶段表现欠佳，模型往往难以恢复，这一现象被称为“前缀主导陷阱”。受心理学研究启发，我们提出**Learning from Peers**（LeaP）方法，通过同伴互动促进自我修正。具体来说，每间隔一定数量的token，各推理路径通过路由机制共享当前推理进展，使其他路径能够参考同伴见解。针对小规模模型无法有效执行总结和反思的问题，我们开发了**LeaP-T**微调模型系列。实验结果显示，LeaP显著提升了模型性能。例如，配备LeaP的QwQ-32B在AIME 2024等测试集上的平均得分比基线高出近5分，并在三个数学基准测试中以平均3.3分的优势超越DeepSeek-R1-671B。值得注意的是，LeaP-T-7B在AIME 2024上的表现与DeepSeek-R1-Distill-Qwen-14B相当。深入分析表明，LeaP通过及时引入同伴见解实现了强大的错误修正能力，展现出良好的容错性和处理不同任务难度的能力。LeaP的提出标志着LRMs在推理过程中实现协作能力的一个重要里程碑。我们的代码、数据集和模型已开源，详情请访问https://learning-from-peers.github.io/。

> Large Reasoning Models (LRMs) have the ability to self-correct even when they make mistakes in their reasoning paths. However, our study reveals that when the reasoning process starts with a short but poor beginning, it becomes difficult for the model to recover. We refer to this phenomenon as the "Prefix Dominance Trap". Inspired by psychological findings that peer interaction can promote self-correction without negatively impacting already accurate individuals, we propose **Learning from Peers** (LeaP) to address this phenomenon. Specifically, every tokens, each reasoning path summarizes its intermediate reasoning and shares it with others through a routing mechanism, enabling paths to incorporate peer insights during inference. However, we observe that smaller models sometimes fail to follow summarization and reflection instructions effectively. To address this, we fine-tune them into our **LeaP-T** model series. Experiments on AIME 2024, AIME 2025, AIMO 2025, and GPQA Diamond show that LeaP provides substantial improvements. For instance, QwQ-32B with LeaP achieves nearly 5 absolute points higher than the baseline on average, and surpasses DeepSeek-R1-671B on three math benchmarks with an average gain of 3.3 points. Notably, our fine-tuned LeaP-T-7B matches the performance of DeepSeek-R1-Distill-Qwen-14B on AIME 2024. In-depth analysis reveals LeaP's robust error correction by timely peer insights, showing strong error tolerance and handling varied task difficulty. LeaP marks a milestone by enabling LRMs to collaborate during reasoning. Our code, datasets, and models are available at https://learning-from-peers.github.io/ .

[Arxiv](https://arxiv.org/abs/2505.07787)