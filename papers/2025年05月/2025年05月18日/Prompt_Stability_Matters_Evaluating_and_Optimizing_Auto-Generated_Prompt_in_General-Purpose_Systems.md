# 提示词稳定性很重要：在通用系统中评估和优化自动生成的提示词

发布时间：2025年05月18日

`Agent` `人工智能` `多智能体系统`

> Prompt Stability Matters: Evaluating and Optimizing Auto-Generated Prompt in General-Purpose Systems

# 摘要

> 自动提示生成在使通用多智能体系统自主执行多样化任务中发挥着关键作用。现有方法通常根据提示的即时任务表现对其进行评估，忽视了决定其可靠性的内在品质。这种结果导向的视角不仅限制了可解释性，还未能考虑到大型语言模型（LLMs）的内在随机性。在这项研究中，我们将注意力集中在提示稳定性上——即模型在重复执行中对提示的一致性响应——作为构建稳健有效提示生成系统的关键因素。为了量化这一点，我们提出语义稳定性作为评估提示响应一致性的标准，并微调了一个基于LLaMA的评估器，以自动跨任务衡量这一特性。这些组件使我们能够开发出首个具备稳定感知能力的通用提示生成系统，该系统利用稳定性反馈来逐步提升提示质量和系统级性能。此外，我们通过分析系统内的结构依赖关系，建立了一个从提示稳定性到任务成功的逻辑链条，证明了稳定性是有效系统级执行的必要条件。在通用和领域特定任务上的实证结果表明，我们的稳定感知框架提高了准确性和输出一致性。通过将关注点从一次性结果转向持续可靠性，我们的工作为提示设计提供了一个新的视角，并为构建更值得信赖的通用系统提供了实用工具。

> Automatic prompt generation plays a crucial role in enabling general-purpose multi-agent systems to perform diverse tasks autonomously. Existing methods typically evaluate prompts based on their immediate task performance, overlooking the intrinsic qualities that determine their reliability. This outcome-centric view not only limits interpretability but also fails to account for the inherent stochasticity of large language models (LLMs). In this work, we bring attention to prompt stability-the consistency of model responses across repeated executions-as a key factor for building robust and effective prompt generation systems. To quantify this, we propose semantic stability as a criterion for assessing the response consistency of prompts, and fine-tune a LLaMA-based evaluator to measure it automatically across tasks. These components have enabled us to develop the first stability-aware general-purpose prompt generation system that leverages stability feedback to iteratively enhance both prompt quality and system-level performance. Furthermore, we establish a logical chain between prompt stability and task success by analyzing the structural dependencies within our system, proving stability as a necessary condition for effective system-level execution. Empirical results across general and domain-specific tasks demonstrate that our stability-aware framework improves both accuracy and output consistency. By shifting the focus from one-off results to persistent reliability, our work offers a new perspective on prompt design and contributes practical tools for building more trustworthy general-purpose systems.

[Arxiv](https://arxiv.org/abs/2505.13546)