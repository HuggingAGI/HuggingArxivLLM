# 大型语言模型中的计算思维推理

发布时间：2025年06月03日

`LLM理论

摘要讨论了大型语言模型在推理中的不足，并提出了一种新的框架（计算思维模型）来增强其推理能力，属于理论层面的探讨。` `计算思维` `计算机科学`

> Computational Thinking Reasoning in Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）在推理方面表现卓越，但面对需要特定思维范式的复杂任务时，它们往往力不从心，例如分而治之和程序化推理等。此前的研究通过引入外部工具来缓解LLMs在问题解决过程中出现的逻辑不一致和幻觉问题。然而，我们认为问题根源更为深刻：LLMs在推理过程中缺乏复杂的思维范式，即计算思维。本文提出了一种全新的框架——计算思维模型（CTM），旨在将计算思维范式融入LLMs。通过分解、抽象、简化和模拟等技术，CTM使LLMs能够重新表述复杂问题。值得注意的是，实时代码执行被无缝整合到推理过程中，使得CTM能够“通过计算来思考”。通过定制的强化学习奖励机制，CTM将计算思维目标直接注入LLMs，从而推动问题简化、模块化规划和迭代验证。我们在多个代码生成和数学基准测试中进行了全面评估，结果显示，CTM在准确性、可解释性和泛化能力方面均优于传统推理模型和工具增强的基线。我们希望这项研究能为AI推理领域提供有价值的见解，使LLMs能够像计算机科学家一样，将问题转化为强大、可验证且可扩展的计算工作流。

> While large language models (LLMs) have demonstrated remarkable reasoning capabilities, they often struggle with complex tasks that require specific thinking paradigms, such as divide-and-conquer and procedural deduction, \etc Previous researches integrate external, reliable tools to alleviate logical inconsistencies and hallucinations in LLMs' problem-solving processes. However, we argue that the root challenge is more profound: LLMs lack the complex thinking paradigms (\ie, computational thinking) during reasoning. In this paper, we propose Computational Thinking Model (CTM), a novel framework that incorporates computational thinking paradigms into LLMs. This framework enables LLMs to reformulate complex problems through decomposition, abstraction, reduction, and simulation, among other techniques. Specifically, live code execution is seamlessly integrated into the reasoning process, allowing CTM to think by computing. CTM directly instills computational thinking objectives into LLMs through tailored reinforcement learning rewards, which encourages problem simplification, modular planning, and iterative verification. We conduct extensive evaluations on multiple code generation and mathematical benchmarks. The results demonstrate that CTM outperforms conventional reasoning models and tool-augmented baselines in terms of accuracy, interpretability, and generalizability. We hope this study offers valuable insights for AI reasoning, where LLMs can transform problems into robust, verifiable, and scalable computational workflows, much like computer scientists do.

[Arxiv](https://arxiv.org/abs/2506.02658)