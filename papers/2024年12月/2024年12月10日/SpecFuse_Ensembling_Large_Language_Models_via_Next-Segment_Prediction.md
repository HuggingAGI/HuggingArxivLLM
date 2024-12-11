# SpecFuse：借助下一段预测来集成大型语言模型

发布时间：2024年12月10日

`LLM应用` `语言模型` `开放域查询`

> SpecFuse: Ensembling Large Language Models via Next-Segment Prediction

# 摘要

> 生成式大型语言模型（LLMs）的集成能够融合不同 LLMs 的长处，弥补单个模型的不足。然而，近期的工作侧重于训练额外的融合模型来整合多个 LLMs 的完整响应，未能充分发挥它们的协作潜能以生成更优质的响应。而且，由于额外的融合模型是基于专门的数据集训练的，这些方法在应对在线用户的开放域查询时表现不佳。在本文中，我们提出了 SpecFuse 这一全新的集成框架，它通过 LLMs 之间的协作迭代生成下一个片段来输出融合结果。这是借助其推理和验证组件的循环执行达成的。在每一轮里，推理组件并行调用每个基础 LLMs 生成候选片段，验证组件再次调用这些 LLMs 来预测片段的排名。排名首位的片段会广播给所有 LLMs，激励它们在下一轮生成更高质量的片段。这种方式还使得基础 LLMs 能够即插即用，无需任何训练或适配，规避了泛化限制。另外，为节省计算资源，我们提出了一种模型退出机制，在每次查询响应过程中动态排除前几轮表现欠佳的模型。如此一来，在维持整体性能的同时有效减少了模型调用的数量。

> Ensembles of generative large language models (LLMs) can integrate the strengths of different LLMs to compensate for the limitations of individual models. However, recent work has focused on training an additional fusion model to combine complete responses from multiple LLMs, failing to tap into their collaborative potential to generate higher-quality responses. Moreover, as the additional fusion model is trained on a specialized dataset, these methods struggle with generalizing to open-domain queries from online users. In this paper, we propose SpecFuse, a novel ensemble framework that outputs the fused result by iteratively producing the next segment through collaboration among LLMs. This is achieved through cyclic execution of its inference and verification components. In each round, the inference component invokes each base LLM to generate candidate segments in parallel, and the verify component calls these LLMs again to predict the ranking of the segments. The top-ranked segment is then broadcast to all LLMs, encouraging them to generate higher-quality segments in the next round. This approach also allows the base LLMs to be plug-and-play, without any training or adaptation, avoiding generalization limitations. Furthermore, to conserve computational resources, we propose a model exit mechanism that dynamically excludes models exhibiting poor performance in previous rounds during each query response. In this way, it effectively reduces the number of model calls while maintaining overall performance.

[Arxiv](https://arxiv.org/abs/2412.07380)