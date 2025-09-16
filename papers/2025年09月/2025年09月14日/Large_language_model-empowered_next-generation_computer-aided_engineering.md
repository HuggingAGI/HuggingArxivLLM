# 大型语言模型赋能的下一代计算机辅助工程

发布时间：2025年09月14日

`Agent` `工业与制造`

> Large language model-empowered next-generation computer-aided engineering

# 摘要

> 软件开发已迈入新纪元，大型语言模型（LLMs）如今成为通用推理引擎，实现了自然语言交互，并在多个领域催生了变革性应用。这一范式正延伸至计算机辅助工程（CAE）领域：LLMs近期在CAE中的应用已成功实现CAD模型生成、有限元模拟等常规任务的自动化。然而，这些仅以减少人工为目标的成果，尚不足以应对大规模高维系统带来的严峻计算挑战。为此，我们首先提出LLM驱动的CAE智能体概念：LLMs作为自主协作者，能够规划、执行并调整CAE工作流。接着，我们提出了适用于无数据模型降阶（MOR）的LLM驱动CAE智能体。MOR本是超快速大规模参数分析的强大工具，但由于求解器的侵入性和开发过程的高人力成本，其应用一直受限。而LLMs能够通过自动化推导、代码重构与实现来突破这一限制，让侵入式MOR变得实用且易于普及。为验证可行性，我们开发了一个LLM驱动的CAE智能体，通过基于张量分解的先验代理模型（TAPS）求解超大规模空间-参数-时间（S-P-T）物理问题。结果显示，描述参数化偏微分方程（PDEs）的自然语言指令可被转化为高效求解器，在生成高保真降阶模型的同时显著减少人力投入。此外，LLMs还能基于内部知识库，为非线性、高维参数问题等未见过的场景生成全新的MOR求解器。这充分彰显了LLMs为下一代CAE系统奠定基础的巨大潜力。

> Software development has entered a new era where large language models (LLMs) now serve as general-purpose reasoning engines, enabling natural language interaction and transformative applications across diverse domains. This paradigm is now extending into computer-aided engineering (CAE). Recent applications of LLMs in CAE have successfully automated routine tasks, including CAD model generation and FEM simulations. Nevertheless, these contributions, which primarily serve to reduce manual labor, are often insufficient for addressing the significant computational challenges posed by large-scale, high-dimensional systems. To this aim, we first introduce the concept of LLM-empowered CAE agent, where LLMs act as autonomous collaborators that plan, execute, and adapt CAE workflows. Then, we propose an LLM-empowered CAE agent for data-free model order reduction (MOR), a powerful yet underused approach for ultra-fast large-scale parametric analysis due to the intrusive nature and labor-intensive redevelopment of solvers. LLMs can alleviate this barrier by automating derivations, code restructuring, and implementation, making intrusive MOR both practical and broadly accessible. To demonstrate feasibility, we present an LLM-empowered CAE agent for solving ultra-large-scale space-parameter-time (S-P-T) physical problems using Tensor-decomposition-based A Priori Surrogates (TAPS). Our results show that natural language prompts describing parametric partial differential equations (PDEs) can be translated into efficient solver implementations, substantially reducing human effort while producing high-fidelity reduced-order models. Moreover, LLMs can synthesize novel MOR solvers for unseen cases such as nonlinear and high-dimensional parametric problems based on their internal knowledge base. This highlights the potential of LLMs to establish the foundation for next-generation CAE systems.

[Arxiv](https://arxiv.org/abs/2509.11447)