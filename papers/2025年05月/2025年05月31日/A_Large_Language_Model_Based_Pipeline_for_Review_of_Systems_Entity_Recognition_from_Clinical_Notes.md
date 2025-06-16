# 基于大型语言模型的临床笔记系统回顾实体识别流水线

发布时间：2025年05月31日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）在临床环境中自动提取系统回顾（ROS）实体，属于将LLM应用于特定领域的实际案例。论文详细描述了管道的实现方法及其在真实数据上的评估结果，重点在于展示LLM在医疗文档处理中的应用效果和可行性，而不是探讨LLM的理论机制或安全性问题。因此，这篇论文应归类为LLM应用。` `医疗信息处理`

> A Large Language Model Based Pipeline for Review of Systems Entity Recognition from Clinical Notes

# 摘要

> 目标: 开发一个经济高效、基于大型语言模型 (LLM) 的管道，用于从临床笔记中自动提取系统回顾 (ROS) 实体。材料和方法: 该管道首先使用 SecTag 提取 ROS 部分，然后利用少量样本的 LLM 识别 ROS 实体的跨度、正/负状态及其相关身体系统。我们使用开源 LLM (Mistral, Llama, Gemma) 和 ChatGPT 实现了该管道。评估在 36 份内科笔记上进行，这些笔记包含 341 个标注的 ROS 实体。结果: 集成 ChatGPT 后，管道在检测 ROS 实体跨度及其对应状态/系统方面表现最佳，错误率分别为 28.2% 和 14.5%。开源 LLM 不仅能够以经济高效的方式本地执行管道，还能提供具有类似低错误率的优秀性能（跨度: 30.5-36.7%; 状态/系统: 24.3-27.3%）。讨论与结论: 我们的管道提供了一种可扩展且可本地部署的解决方案，有效减轻了 ROS 文档负担。开源 LLM 在资源有限的医疗环境中为商业模型提供了一种可行的替代方案。

> Objective: Develop a cost-effective, large language model (LLM)-based pipeline for automatically extracting Review of Systems (ROS) entities from clinical notes. Materials and Methods: The pipeline extracts ROS sections using SecTag, followed by few-shot LLMs to identify ROS entity spans, their positive/negative status, and associated body systems. We implemented the pipeline using open-source LLMs (Mistral, Llama, Gemma) and ChatGPT. The evaluation was conducted on 36 general medicine notes containing 341 annotated ROS entities. Results: When integrating ChatGPT, the pipeline achieved the lowest error rates in detecting ROS entity spans and their corresponding statuses/systems (28.2% and 14.5%, respectively). Open-source LLMs enable local, cost-efficient execution of the pipeline while delivering promising performance with similarly low error rates (span: 30.5-36.7%; status/system: 24.3-27.3%). Discussion and Conclusion: Our pipeline offers a scalable and locally deployable solution to reduce ROS documentation burden. Open-source LLMs present a viable alternative to commercial models in resource-limited healthcare environments.

[Arxiv](https://arxiv.org/abs/2506.11067)