# DREAMS：基于密度泛函理论的智能材料模拟研究引擎

发布时间：2025年07月18日

`Agent` `材料科学` `计算材料发现`

> DREAMS: Density Functional Theory Based Research Engine for Agentic Materials Simulation

# 摘要

> 材料发现依赖于高通量、高保真的模拟技术，如密度泛函理论（DFT），但这些技术需要漫长的训练周期、繁琐的参数微调和系统的错误处理。为解决这些难题，我们推出了DREAMS（基于DFT的研究引擎），这是一个分层式多智能体框架，专为DFT模拟设计。该框架的核心是一个大型语言模型（LLM）规划器智能体，协同多个领域专用的LLM智能体，分别负责原子结构生成、系统性DFT收敛测试、高性能计算（HPC）调度和错误处理。此外，共享画布功能帮助智能体们组织讨论，保持上下文连贯，避免信息混乱。我们在Sol27LC晶格常数基准测试中验证了DREAMS的能力，其结果与人类DFT专家的输出相比，平均误差低于1%。更令人兴奋的是，DREAMS成功攻克了CO/Pt(111)吸附这一长期未解之谜，充分展现了其在复杂、长期问题上的解决能力。该框架还精确再现了文献中的吸附能差异，达到专家级水准。此外，DREAMS通过贝叶斯集成采样量化功能驱动的不确定性，证实了在广义梯度近似（GGA）DFT水平上FCC位点的偏好。综上所述，DREAMS已实现L3级自动化，能够在定义的设计空间内进行自主探索，大幅降低了对人类专业知识和干预的依赖，为实现民主化、高通量、高保真的计算材料发现开辟了一条可扩展的道路。

> Materials discovery relies on high-throughput, high-fidelity simulation techniques such as Density Functional Theory (DFT), which require years of training, extensive parameter fine-tuning and systematic error handling. To address these challenges, we introduce the DFT-based Research Engine for Agentic Materials Screening (DREAMS), a hierarchical, multi-agent framework for DFT simulation that combines a central Large Language Model (LLM) planner agent with domain-specific LLM agents for atomistic structure generation, systematic DFT convergence testing, High-Performance Computing (HPC) scheduling, and error handling. In addition, a shared canvas helps the LLM agents to structure their discussions, preserve context and prevent hallucination. We validate DREAMS capabilities on the Sol27LC lattice-constant benchmark, achieving average errors below 1\% compared to the results of human DFT experts. Furthermore, we apply DREAMS to the long-standing CO/Pt(111) adsorption puzzle, demonstrating its long-term and complex problem-solving capabilities. The framework again reproduces expert-level literature adsorption-energy differences. Finally, DREAMS is employed to quantify functional-driven uncertainties with Bayesian ensemble sampling, confirming the Face Centered Cubic (FCC)-site preference at the Generalized Gradient Approximation (GGA) DFT level. In conclusion, DREAMS approaches L3-level automation - autonomous exploration of a defined design space - and significantly reduces the reliance on human expertise and intervention, offering a scalable path toward democratized, high-throughput, high-fidelity computational materials discovery.

[Arxiv](https://arxiv.org/abs/2507.14267)