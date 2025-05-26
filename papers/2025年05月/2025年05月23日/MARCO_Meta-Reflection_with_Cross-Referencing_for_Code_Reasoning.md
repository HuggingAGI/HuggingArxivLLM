# MARCO：基于交叉引用的元反思代码推理

发布时间：2025年05月23日

`LLM理论` `人工智能`

> MARCO: Meta-Reflection with Cross-Referencing for Code Reasoning

# 摘要

> 推理能力是大型语言模型 (LLMs) 的核心能力之一，它通过复杂的推理过程使各种下游任务得以实现。其中至关重要的一环是代码推理，即利用逻辑推理和正式语言（即编程代码）进行问题解决。在本文中，我们通过探索以下问题来提升 LLMs 的这一能力：LLM 代理如何通过每次提出的解决方案逐步提升代码推理能力，从而实现显著的累积改进？目前大多数研究采用静态视角，专注于使用固定模型进行孤立的问题解决。而我们则采用认知演进的视角，提出了一种名为元反射跨参考（MARCO）的新框架，该框架通过自我改进使 LLM 在推理过程中实现动态演进。从人类认知发展的角度，我们结合了知识积累和经验共享。具体来说，为了在问题解决过程中积累知识，我们提出了元反射机制，通过反思当前问题的推理路径，获取未来可借鉴的知识与经验。此外，为了有效利用其他代理的经验，我们提出了跨参考机制，将其他代理的解决方案和反馈整合到当前问题解决过程中。我们在多个代码推理数据集上进行了实验，结果证明了 MARCO 的有效性。

> The ability to reason is one of the most fundamental capabilities of large language models (LLMs), enabling a wide range of downstream tasks through sophisticated problem-solving. A critical aspect of this is code reasoning, which involves logical reasoning with formal languages (i.e., programming code). In this paper, we enhance this capability of LLMs by exploring the following question: how can an LLM agent become progressively smarter in code reasoning with each solution it proposes, thereby achieving substantial cumulative improvement? Most existing research takes a static perspective, focusing on isolated problem-solving using frozen LLMs. In contrast, we adopt a cognitive-evolving perspective and propose a novel framework named Meta-Reflection with Cross-Referencing (MARCO) that enables the LLM to evolve dynamically during inference through self-improvement. From the perspective of human cognitive development, we leverage both knowledge accumulation and lesson sharing. In particular, to accumulate knowledge during problem-solving, we propose meta-reflection that reflects on the reasoning paths of the current problem to obtain knowledge and experience for future consideration. Moreover, to effectively utilize the lessons from other agents, we propose cross-referencing that incorporates the solution and feedback from other agents into the current problem-solving process. We conduct experiments across various datasets in code reasoning, and the results demonstrate the effectiveness of MARCO.

[Arxiv](https://arxiv.org/abs/2505.17481)