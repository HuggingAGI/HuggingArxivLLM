# # UniConv：统一大型语言模型在对话场景中的检索与响应生成

发布时间：2025年07月09日

`LLM应用

摘要讨论了如何将大型语言模型应用于对话式搜索系统，优化其在检索和生成任务中的性能，属于应用层面的研究。` `信息检索`

> UniConv: Unifying Retrieval and Response Generation for Large Language Models in Conversations

# 摘要

> 对话式搜索系统的快速发展彻底改变了信息获取的方式，通过实现用户与系统之间的多轮交互。现有的对话式搜索系统通常使用两个不同的模型构建。这种分离限制了系统同时利用模型的内在知识，无法保证检索的有效性以支持生成。现有针对统一模型的研究无法完全解决理解对话上下文、独立管理检索以及生成响应这几个方面的问题。本文探讨如何将密集检索与响应生成统一到大型语言模型的对话中。我们进行了具有不同目标的联合微调，并设计了两种机制来降低不一致风险，同时缓解数据差异。在五个对话式搜索数据集上的评估表明，我们的统一模型可以相互提升两个任务，并且优于现有的基线模型。

> The rapid advancement of conversational search systems revolutionizes how information is accessed by enabling the multi-turn interaction between the user and the system. Existing conversational search systems are usually built with two different models. This separation restricts the system from leveraging the intrinsic knowledge of the models simultaneously, which cannot ensure the effectiveness of retrieval benefiting the generation. The existing studies for developing unified models cannot fully address the aspects of understanding conversational context, managing retrieval independently, and generating responses. In this paper, we explore how to unify dense retrieval and response generation for large language models in conversation. We conduct joint fine-tuning with different objectives and design two mechanisms to reduce the inconsistency risks while mitigating data discrepancy. The evaluations on five conversational search datasets demonstrate that our unified model can mutually improve both tasks and outperform the existing baselines.

[Arxiv](https://arxiv.org/abs/2507.07030)