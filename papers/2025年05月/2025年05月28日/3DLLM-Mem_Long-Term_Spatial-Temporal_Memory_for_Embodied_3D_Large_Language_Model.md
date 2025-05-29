# 3DLLM-Mem：三维具身大型语言模型的长期时空记忆机制

发布时间：2025年05月28日

`Agent` `虚拟现实` `增强现实`

> 3DLLM-Mem: Long-Term Spatial-Temporal Memory for Embodied 3D Large Language Model

# 摘要

> 人类在复杂任务中表现出色，这得益于他们在时间和空间体验中运用长期记忆的能力。然而，当前的大型语言模型（LLMs）在动态、多房间的3D环境中进行有效规划和行动时仍存在困难。我们推测，这种局限性部分源于LLMs缺乏适当的空间-时间记忆建模。

为了解决这一问题，我们首先介绍了3DMem-Bench，这是一个全面的基准测试，包含超过26,000条轨迹和2,892个具身任务、问答和描述任务，旨在评估智能体在3D环境中基于长期记忆进行推理的能力。其次，我们提出了3DLLM-Mem，这是一种用于LLMs中具身空间-时间推理和动作的新颖动态内存管理和融合模型。

我们的模型使用工作记忆令牌（代表当前观察）作为查询，选择性地关注并融合来自情景记忆（存储过去观察和交互）中最有用的时空特征。我们的方法使智能体能够在复杂的、长期的环境中专注于与任务相关的信息，同时保持记忆效率。

实验结果表明，3DLLM-Mem在各种任务中实现了最先进的性能，在3DMem-Bench最具挑战性的现实世界具身任务中，成功率为最强基线高出16.5%。

> Humans excel at performing complex tasks by leveraging long-term memory across temporal and spatial experiences. In contrast, current Large Language Models (LLMs) struggle to effectively plan and act in dynamic, multi-room 3D environments. We posit that part of this limitation is due to the lack of proper 3D spatial-temporal memory modeling in LLMs. To address this, we first introduce 3DMem-Bench, a comprehensive benchmark comprising over 26,000 trajectories and 2,892 embodied tasks, question-answering and captioning, designed to evaluate an agent's ability to reason over long-term memory in 3D environments. Second, we propose 3DLLM-Mem, a novel dynamic memory management and fusion model for embodied spatial-temporal reasoning and actions in LLMs. Our model uses working memory tokens, which represents current observations, as queries to selectively attend to and fuse the most useful spatial and temporal features from episodic memory, which stores past observations and interactions. Our approach allows the agent to focus on task-relevant information while maintaining memory efficiency in complex, long-horizon environments. Experimental results demonstrate that 3DLLM-Mem achieves state-of-the-art performance across various tasks, outperforming the strongest baselines by 16.5% in success rate on 3DMem-Bench's most challenging in-the-wild embodied tasks.

[Arxiv](https://arxiv.org/abs/2505.22657)