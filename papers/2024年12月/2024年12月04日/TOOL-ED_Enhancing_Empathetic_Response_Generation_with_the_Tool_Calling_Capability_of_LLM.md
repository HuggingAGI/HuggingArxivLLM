# TOOL-ED：凭借 LLM 的工具调用能力提升共情响应的生成

发布时间：2024年12月04日

`LLM应用`

> TOOL-ED: Enhancing Empathetic Response Generation with the Tool Calling Capability of LLM

# 摘要

> 共情对话在个人的日常交流中是一项关键特性。当下，大型语言模型（LLMs）在生成共情回应方面表现出众。诸如 COMET 之类的知识库能够助力 LLMs 减少幻觉，增进对用户意图和情感的理解。不过，模型仍高度依赖固定的知识库，无限制地融入外部知识可能引入噪声。工具学习是一种灵活的端到端方式，能协助 LLMs 处理复杂问题。在本文中，我们提出了情感知识工具调用（EKTC）框架，将常识知识库封装为共情工具，让 LLMs 能通过工具调用灵活整合外部知识。为使模型适应新任务，我们基于共情对话（ED）数据集构建了全新的数据集 TOOL-ED。我们在 ED 数据集上对 EKTC 进行了验证，实验结果显示，我们的框架能够有效提升 LLMs 生成共情回应的能力。

> Empathetic conversation is a crucial characteristic in daily conversations between individuals. Nowadays, Large Language models (LLMs) have shown outstanding performance in generating empathetic responses. Knowledge bases like COMET can assist LLMs in mitigating illusions and enhancing the understanding of users' intentions and emotions. However, models remain heavily reliant on fixed knowledge bases and unrestricted incorporation of external knowledge can introduce noise. Tool learning is a flexible end-to-end approach that assists LLMs in handling complex problems. In this paper, we propose Emotional Knowledge Tool Calling (EKTC) framework, which encapsulates the commonsense knowledge bases as empathetic tools, enabling LLMs to integrate external knowledge flexibly through tool calling. In order to adapt the models to the new task, we construct a novel dataset TOOL-ED based on the EMPATHETICMPATHETIC DIALOGUE (ED) dataset. We validate EKTC on the ED dataset, and the experimental results demonstrate that our framework can enhance the ability of LLMs to generate empathetic responses effectively.

[Arxiv](https://arxiv.org/abs/2412.03096)