# 推动大型语言模型与特定任务模型在时间序列异常检测中的协同合作

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了如何将大型语言模型（LLMs）与特定任务的小型模型结合起来，以提升异常检测的性能。论文提出了一个名为CoLLaTe的框架，旨在解决LLMs与小型模型协作中的挑战，并通过实验验证了其有效性。虽然论文涉及LLMs的理论分析，但其核心关注点在于如何应用LLMs来解决实际问题（异常检测），因此更适合归类为“LLM应用”。` `异常检测` `人工智能`

> Facilitate Collaboration between Large Language Model and Task-specific Model for Time Series Anomaly Detection

# 摘要

> 在异常检测领域，基于大型语言模型（LLMs）的方法能够整合专家知识，而特定任务的小型模型则擅长捕捉正常模式和检测数值波动。受人类神经系统的启发——大脑存储专家知识，周围神经系统和脊髓处理特定任务（如退缩和膝跳反射）——我们提出了CoLLaTe框架，旨在促进LLMs与特定任务模型的协作，充分发挥两者的优势。
    在本研究中，我们首先定义了协作流程，并识别出LLMs与特定任务模型协作中的两大挑战：（1）LLMs与小型模型在表达领域上的不一致，（2）两模型预测导致的误差累积。
    为应对这些挑战，我们在CoLLaTe中引入了两个核心组件：对齐模块和协作损失函数。通过理论分析和实验验证，我们证明了这些组件能够有效缓解上述挑战，并在性能上超越了基于LLM的方法和特定任务小型模型。

> In anomaly detection, methods based on large language models (LLMs) can incorporate expert knowledge, while task-specific smaller models excel at extracting normal patterns and detecting value fluctuations. Inspired by the human nervous system, where the brain stores expert knowledge and the peripheral nervous system and spinal cord handle specific tasks like withdrawal and knee-jerk reflexes, we propose CoLLaTe, a framework designed to facilitate collaboration between LLMs and task-specific models, leveraging the strengths of both.
  In this work, we first formulate the collaboration process and identify two key challenges in the collaboration between LLMs and task-specific models: (1) the misalignment between the expression domains of LLMs and smaller models, and (2) error accumulation arising from the predictions of both models.
  To address these challenges, we introduce two key components in CoLLaTe: the alignment module and the collaborative loss function. Through theoretical analysis and experimental validation, we demonstrate that these components effectively mitigate the identified challenges and achieve better performance than LLM based methods and task-specific smaller model.

[Arxiv](https://arxiv.org/abs/2501.05675)