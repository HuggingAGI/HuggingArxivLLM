# # CodeSwift：加速LLM推理，实现高效代码生成

发布时间：2025年02月24日

`LLM应用` `软件工程` `代码生成`

> CodeSwift: Accelerating LLM Inference for Efficient Code Generation

# 摘要

> 代码生成是一项对延迟敏感的任务，要求具备高时效性。然而，大型语言模型（LLMs）的自回归解码机制导致推理效率低下。现有的LLM推理加速方法主要集中在仅使用内置组件的独立功能上。此外，它们将代码视为自然语言序列，忽略了其独特的语法和语义特性。因此，这些方法在代码生成任务中的有效性仍然有限，无法与现实世界的编程场景相匹配。为了解决这一问题，我们提出了CodeSwift，这是一种专为代码生成设计的简单而高效的推理加速方法，同时不会降低输出质量。CodeSwift构建了一个多源数据集，提供了访问通用知识和项目特定知识的途径，从而促进高质量草稿序列的检索。此外，CodeSwift通过控制检索时机来降低检索成本，并通过并行检索以及上下文和LLM偏好感知缓存来提升效率。实验结果表明，与自回归解码相比，CodeSwift在仓库级和独立代码生成任务中分别达到了2.53倍和2.54倍的加速效果，优于现有的最先进的推理加速方法，提升幅度最高达88%。

> Code generation is a latency-sensitive task that demands high timeliness, but the autoregressive decoding mechanism of Large Language Models (LLMs) leads to poor inference efficiency. Existing LLM inference acceleration methods mainly focus on standalone functions using only built-in components. Moreover, they treat code like natural language sequences, ignoring its unique syntax and semantic characteristics. As a result, the effectiveness of these approaches in code generation tasks remains limited and fails to align with real-world programming scenarios. To alleviate this issue, we propose CodeSwift, a simple yet highly efficient inference acceleration approach specifically designed for code generation, without comprising the quality of the output. CodeSwift constructs a multi-source datastore, providing access to both general and project-specific knowledge, facilitating the retrieval of high-quality draft sequences. Moreover, CodeSwift reduces retrieval cost by controlling retrieval timing, and enhances efficiency through parallel retrieval and a context- and LLM preference-aware cache. Experimental results show that CodeSwift can reach up to 2.53x and 2.54x speedup compared to autoregressive decoding in repository-level and standalone code generation tasks, respectively, outperforming state-of-the-art inference acceleration approaches by up to 88%.

[Arxiv](https://arxiv.org/abs/2502.17139)