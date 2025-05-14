# CodePDE：基于LLM的PDE求解器生成推理框架

发布时间：2025年05月13日

`LLM应用` `物理建模` `科学计算`

> CodePDE: An Inference Framework for LLM-driven PDE Solver Generation

# 摘要

> 偏微分方程（PDEs）是建模物理系统的核心工具，但求解它们仍然充满挑战。传统数值求解器不仅依赖专家知识，而且计算成本高昂；而基于神经网络的求解器则需要大量训练数据，且通常缺乏可解释性。在本研究中，我们将 PDE 求解重新定义为代码生成任务，并推出了 CodePDE——首个基于大型语言模型（LLMs）的 PDE 求解器生成推理框架。通过结合先进的推理算法和扩展策略，CodePDE 充分挖掘了 LLM 在 PDE 求解中的潜力，包括推理、调试、自我优化和测试时扩展能力，这一切均无需针对特定任务进行调整。CodePDE 在多种典型 PDE 问题中展现了超越人类的表现。我们还对 LLM 生成的求解器进行了系统性分析，深入探讨了其准确性、效率及数值方案选择。我们的研究不仅揭示了 LLM 在 PDE 求解中的巨大潜力及其当前局限性，更为求解器设计提供了全新视角，并为未来模型研发指明了方向。CodePDE 的代码已开源，欢迎访问 https://github.com/LithiumDA/CodePDE 查看。

> Partial differential equations (PDEs) are fundamental to modeling physical systems, yet solving them remains a complex challenge. Traditional numerical solvers rely on expert knowledge to implement and are computationally expensive, while neural-network-based solvers require large training datasets and often lack interpretability. In this work, we frame PDE solving as a code generation task and introduce CodePDE, the first inference framework for generating PDE solvers using large language models (LLMs). Leveraging advanced inference-time algorithms and scaling strategies, CodePDE unlocks critical capacities of LLM for PDE solving: reasoning, debugging, selfrefinement, and test-time scaling -- all without task-specific tuning. CodePDE achieves superhuman performance across a range of representative PDE problems. We also present a systematic empirical analysis of LLM generated solvers, analyzing their accuracy, efficiency, and numerical scheme choices. Our findings highlight the promise and the current limitations of LLMs in PDE solving, offering a new perspective on solver design and opportunities for future model development. Our code is available at https://github.com/LithiumDA/CodePDE.

[Arxiv](https://arxiv.org/abs/2505.08783)