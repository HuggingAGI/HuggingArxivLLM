# 从直觉思维到逻辑推理：推理型大型语言模型研究综述

发布时间：2025年02月24日

`LLM理论` `大型语言模型`

> From System 1 to System 2: A Survey of Reasoning Large Language Models

# 摘要

> 实现人类级别的智能需要完善从快速、直观的System 1到更慢、更审慎的System 2推理的过渡。System 1擅长快速、启发式决策，而System 2则依赖逻辑推理来进行更准确的判断并减少偏见。基础大型语言模型（LLMs）在快速决策方面表现出色，但缺乏复杂推理的深度，因为它们尚未完全采用真正System 2思维所特有的逐步分析。最近，像OpenAI的o1/o3和DeepSeek的R1这样的推理LLMs已经在数学和编码等领域展示了专家级的表现，它们几乎模仿了System 2的审慎推理，并展示了类人认知能力。本研究首先简要概述了基础LLMs的进展和System 2技术的早期发展，探讨了它们的结合如何为推理LLMs铺平了道路。接下来，我们讨论如何构建推理LLMs，分析它们的特征、支持高级推理的核心方法以及各种推理LLMs的演变。此外，我们还概述了推理基准，提供了对代表性的推理LLMs性能的深入比较。最后，我们探索了推进推理LLMs的有前途方向，并维护了一个实时\href{https://github.com/zzli2022/Awesome-Slow-Reason-System}{GitHub仓库}以跟踪最新进展。我们希望这项研究能成为宝贵的资源，激发创新并推动这一迅速发展的领域不断进步。

> Achieving human-level intelligence requires refining the transition from the fast, intuitive System 1 to the slower, more deliberate System 2 reasoning. While System 1 excels in quick, heuristic decisions, System 2 relies on logical reasoning for more accurate judgments and reduced biases. Foundational Large Language Models (LLMs) excel at fast decision-making but lack the depth for complex reasoning, as they have not yet fully embraced the step-by-step analysis characteristic of true System 2 thinking. Recently, reasoning LLMs like OpenAI's o1/o3 and DeepSeek's R1 have demonstrated expert-level performance in fields such as mathematics and coding, closely mimicking the deliberate reasoning of System 2 and showcasing human-like cognitive abilities. This survey begins with a brief overview of the progress in foundational LLMs and the early development of System 2 technologies, exploring how their combination has paved the way for reasoning LLMs. Next, we discuss how to construct reasoning LLMs, analyzing their features, the core methods enabling advanced reasoning, and the evolution of various reasoning LLMs. Additionally, we provide an overview of reasoning benchmarks, offering an in-depth comparison of the performance of representative reasoning LLMs. Finally, we explore promising directions for advancing reasoning LLMs and maintain a real-time \href{https://github.com/zzli2022/Awesome-Slow-Reason-System}{GitHub Repository} to track the latest developments. We hope this survey will serve as a valuable resource to inspire innovation and drive progress in this rapidly evolving field.

[Arxiv](https://arxiv.org/abs/2502.17419)