# 分步解决与逐步优化：正式数学问题的高效解法

发布时间：2025年07月20日

`Agent` `自动化推理` `定理证明`

> Solving Formal Math Problems by Decomposition and Iterative Reflection

# 摘要

> 通用大型语言模型（LLMs）在智能领域取得了显著成功，在编码和数学推理等复杂推理任务上表现得与人类专家相当。然而，生成像Lean 4这样的专业语言的正式证明仍然是这些模型面临的重要挑战，限制了它们在复杂定理证明和自动化验证中的应用。目前的方法通常需要通过对专用正式语料库进行微调来专门化模型，这导致数据收集和训练成本高昂。在本研究中，我们引入了	extbf{Delta Prover}，这是一个基于代理的框架，用于协调通用大型语言模型与Lean 4证明环境之间的交互。Delta Prover利用通用大型语言模型的反思和推理能力，与Lean 4环境进行交互式正式证明构造，从而避免了对模型专门化的需要。在核心部分，该代理集成了两个新颖且相互依存的组件：一个用于反思分解和迭代证明修复的算法框架，以及一个基于Lean 4构建的自定义领域特定语言（DSL），用于简化子问题管理。在miniF2F-test基准上，	extbf{Delta Prover达到了95.9\%的成功率，超越了所有现有方法，包括那些需要模型专门化的方法。}此外，与标准的Best-of-N证明策略相比，Delta Prover展现出显著更强的测试时间缩放定律。至关重要的是，我们的研究结果表明，当通用大型语言模型由有效的代理结构引导时，它们具备巨大的尚未开发的定理证明能力。这为在正式环境中实现稳健的自动化推理提供了一种计算效率更高的替代方案，无需依赖专门化的模型。

> General-purpose Large Language Models (LLMs) have achieved remarkable success in intelligence, performing comparably to human experts on complex reasoning tasks such as coding and mathematical reasoning. However, generating formal proofs in specialized languages like Lean 4 remains a significant challenge for these models, limiting their application in complex theorem proving and automated verification. Current approaches typically require specializing models through fine-tuning on dedicated formal corpora, incurring high costs for data collection and training. In this work, we introduce \textbf{Delta Prover}, an agent-based framework that orchestrates the interaction between a general-purpose LLM and the Lean 4 proof environment. Delta Prover leverages the reflection and reasoning capabilities of general-purpose LLMs to interactively construct formal proofs in Lean 4, circumventing the need for model specialization. At its core, the agent integrates two novel, interdependent components: an algorithmic framework for reflective decomposition and iterative proof repair, and a custom Domain-Specific Language (DSL) built upon Lean 4 for streamlined subproblem management. \textbf{Delta Prover achieves a state-of-the-art 95.9\% success rate on the miniF2F-test benchmark, surpassing all existing approaches, including those requiring model specialization.} Furthermore, Delta Prover exhibits a significantly stronger test-time scaling law compared to standard Best-of-N proof strategies. Crucially, our findings demonstrate that general-purpose LLMs, when guided by an effective agentic structure, possess substantial untapped theorem-proving capabilities. This presents a computationally efficient alternative to specialized models for robust automated reasoning in formal environments.

[Arxiv](https://arxiv.org/abs/2507.15225)