# # 思想分割：混合语言模型协同助力高效设备端代理
Division-of-Thoughts: Harnessing Hybrid Language Model Synergy for Efficient On-Device Agents

发布时间：2025年02月05日

`Agent` `移动设备` `云计算`

> Division-of-Thoughts: Harnessing Hybrid Language Model Synergy for Efficient On-Device Agents

# 摘要

> 网络内容的快速扩张让设备端AI助手在应对日益复杂的在线任务时变得不可或缺。大型语言模型中涌现出的推理能力为下一代设备端AI代理提供了有希望的发展路径。然而，在资源受限的本地设备上部署完整的大型语言模型极具挑战性。本文提出了一种名为“思想分割”（DoT）的协作推理框架，通过本地部署的小型语言模型（SLMs）与云端大型语言模型（LLMs）的协同作用，实现更高效的推理过程。DoT利用任务分解器激发语言模型的内在规划能力，将用户查询分解为更小的子任务，从而充分发挥混合语言模型的优势。此外，DoT通过任务调度器分析子任务间的依赖关系，创建依赖图，促进子任务的并行推理和关键步骤的识别。为了根据子任务难度分配合适的模型，DoT引入了一个即插即用的适配器，该适配器作为附加任务头连接到SLM，且不会改变其参数。我们还提出了一种仅依赖任务执行反馈的自我强化训练方法，以提升适配器的任务分配能力。实验结果表明，DoT在保持具有竞争力的推理准确性的同时，显著降低了LLM的使用成本。具体而言，DoT将平均推理时间和API成本分别降低了66.12%和83.57%，同时实现了与最佳基线方法相当的推理准确度。

> The rapid expansion of web content has made on-device AI assistants indispensable for helping users manage the increasing complexity of online tasks. The emergent reasoning ability in large language models offer a promising path for next-generation on-device AI agents. However, deploying full-scale Large Language Models (LLMs) on resource-limited local devices is challenging. In this paper, we propose Division-of-Thoughts (DoT), a collaborative reasoning framework leveraging the synergy between locally deployed Smaller-scale Language Models (SLMs) and cloud-based LLMs. DoT leverages a Task Decomposer to elicit the inherent planning abilities in language models to decompose user queries into smaller sub-tasks, which allows hybrid language models to fully exploit their respective strengths. Besides, DoT employs a Task Scheduler to analyze the pair-wise dependency of sub-tasks and create a dependency graph, facilitating parallel reasoning of sub-tasks and the identification of key steps. To allocate the appropriate model based on the difficulty of sub-tasks, DoT leverages a Plug-and-Play Adapter, which is an additional task head attached to the SLM that does not alter the SLM's parameters. To boost adapter's task allocation capability, we propose a self-reinforced training method that relies solely on task execution feedback. Extensive experiments on various benchmarks demonstrate that our DoT significantly reduces LLM costs while maintaining competitive reasoning accuracy. Specifically, DoT reduces the average reasoning time and API costs by 66.12% and 83.57%, while achieving comparable reasoning accuracy with the best baseline methods.

[Arxiv](https://arxiv.org/abs/2502.04392)