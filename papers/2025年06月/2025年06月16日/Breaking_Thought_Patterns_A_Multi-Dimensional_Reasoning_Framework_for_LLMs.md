# 打破思维模式：一个助力大型语言模型的多维度推理框架。该框架旨在帮助LLMs提升推理能力，涵盖逻辑推理、数学计算、因果关系等多维度能力，助力模型实现更智能、更全面的任务处理。

发布时间：2025年06月16日

`LLM理论` `大型语言模型`

> Breaking Thought Patterns: A Multi-Dimensional Reasoning Framework for LLMs

# 摘要

> # 大型语言模型的限制与突破  
大型语言模型 (LLMs) 通常受限于 rigid 的推理过程，限制了生成创意和多样化回应的能力。为了解决这一问题，我们提出了一个名为 LADDER 的新框架，结合了思维链推理 (CoT)、专家模型混合 (MoE) 和多维上/下采样策略，打破了传统 LLM 的限制。  

首先，CoT 推理引导模型进行多步逻辑推理，扩展语义空间，打破思维 rigidity。其次，MoE 将推理任务分配给多个专家模块，每个模块专注于特定子任务。最后，降维将推理输出映射回低维语义空间，生成更精确和创意的回应。  

在多个任务上的广泛实验表明，LADDER 显著提高了任务完成度、创造力和流畅度，生成了创新且连贯的回应，优于传统模型。消融研究表明 CoT 和 MoE 在增强推理能力和创意输出中的关键作用。这项工作为开发更灵活和创意的 LLM 贡献了力量，能够应对复杂和新颖的任务。


> Large language models (LLMs) are often constrained by rigid reasoning processes, limiting their ability to generate creative and diverse responses. To address this, a novel framework called LADDER is proposed, combining Chain-of-Thought (CoT) reasoning, Mixture of Experts (MoE) models, and multi-dimensional up/down-sampling strategies which breaks the limitations of traditional LLMs. First, CoT reasoning guides the model through multi-step logical reasoning, expanding the semantic space and breaking the rigidity of thought. Next, MoE distributes the reasoning tasks across multiple expert modules, each focusing on specific sub-tasks. Finally, dimensionality reduction maps the reasoning outputs back to a lower-dimensional semantic space, yielding more precise and creative responses. Extensive experiments across multiple tasks demonstrate that LADDER significantly improves task completion, creativity, and fluency, generating innovative and coherent responses that outperform traditional models. Ablation studies reveal the critical roles of CoT and MoE in enhancing reasoning abilities and creative output. This work contributes to the development of more flexible and creative LLMs, capable of addressing complex and novel tasks.

[Arxiv](https://arxiv.org/abs/2506.13192)