# 大型语言模型在利用参数化知识进行反事实推理时表现欠佳。

发布时间：2025年06月14日

`LLM理论` `知识密集型任务` `反事实推理`

> LLMs Struggle to Perform Counterfactual Reasoning with Parametric Knowledge

# 摘要

> 大型语言模型（LLMs）的参数中蕴含着丰富的世界知识，使其在知识密集型任务中表现出色。然而，当部署在新环境中时，LLMs往往需要结合其参数知识与新的信息。本研究通过反事实推理的视角，探讨了LLMs是否能够将上下文知识与其参数知识相结合。通过在多跳推理问题中的合成和真实实验，我们发现LLMs通常在反事实推理方面表现挣扎，常常只能依赖其参数知识。此外，简单的后训练微调往往难以赋予模型反事实推理能力，甚至可能导致其存储的参数知识退化。最终，我们的研究揭示了当前LLMs在新环境中重新利用参数知识方面的重要局限性。

> Large Language Models have been shown to contain extensive world knowledge in their parameters, enabling impressive performance on many knowledge intensive tasks. However, when deployed in novel settings, LLMs often encounter situations where they must integrate parametric knowledge with new or unfamiliar information. In this work, we explore whether LLMs can combine knowledge in-context with their parametric knowledge through the lens of counterfactual reasoning. Through synthetic and real experiments in multi-hop reasoning problems, we show that LLMs generally struggle with counterfactual reasoning, often resorting to exclusively using their parametric knowledge. Moreover, we show that simple post-hoc finetuning can struggle to instill counterfactual reasoning ability -- often leading to degradation in stored parametric knowledge. Ultimately, our work reveals important limitations of current LLM's abilities to re-purpose parametric knowledge in novel settings.

[Arxiv](https://arxiv.org/abs/2506.15732)