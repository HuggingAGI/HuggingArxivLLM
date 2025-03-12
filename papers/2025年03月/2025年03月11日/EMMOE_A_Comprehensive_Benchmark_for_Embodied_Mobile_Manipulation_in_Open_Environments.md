# EMMOE：面向开放环境具身移动操作的全面基准测试

发布时间：2025年03月11日

`Agent` `人工智能` `机器人技术`

> EMMOE: A Comprehensive Benchmark for Embodied Mobile Manipulation in Open Environments

# 摘要

> # 摘要
人类一直追求开发能通过自然语言控制的自主家庭机器人。虽然大型语言模型（LLMs）和具身智能的突破性进展让我们离这一目标更近了一步，但仍面临诸多挑战：缺乏统一的复杂机器人任务基准、有限的评估手段与指标、以及LLMs与移动操作轨迹之间的数据兼容性问题。为了解决这些问题，我们提出了“开放环境中的具身移动操作”（EMMOE）框架，要求智能体能够理解用户指令并在连续空间中执行长期的日常任务。EMMOE巧妙地将高低级别的具身任务整合到一个统一框架中，并引入了三个新指标以实现更全面的评估。此外，我们构建了EMMOE-100数据集，其特色包括丰富的任务属性、详细的过程标注、失败后的重新规划能力，以及两个专门用于LLM训练的子数据集。我们还设计了HomieBot，这一先进代理系统集成了带有直接偏好优化（DPO）的LLM、轻量级导航与操作模型，以及多种错误检测机制。最后，我们展示了HomieBot的性能表现，并对不同模型与策略进行了全面评估。


> Developing autonomous home robots controlled by natural language has long been a pursuit of human. While advancements in large language models (LLMs) and embodied intelligence make this goal closer, several challenges persist: the lack of a unified benchmark for more complex robot tasks, limited evaluation methods and metrics, data incompatibility between LLMs and mobile manipulation trajectories. To address these issues, we introduce Embodied Mobile Manipulation in Open Environments (EMMOE), which requires agents to interpret user instructions and execute long-horizon everyday tasks in continuous space. EMMOE seamlessly integrates high-level and low-level embodied tasks into a unified framework, along with three new metrics for more diverse assessment. Additionally, we collect EMMOE-100, which features in various task attributes, detailed process annotations, re-plans after failures, and two sub-datasets for LLM training. Furthermore, we design HomieBot, a sophisticated agent system consists of LLM with Direct Preference Optimization (DPO), light weighted navigation and manipulation models, and multiple error detection mechanisms. Finally, we demonstrate HomieBot's performance and the evaluation of different models and policies.

[Arxiv](https://arxiv.org/abs/2503.08604)