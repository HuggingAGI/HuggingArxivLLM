# # 从传统Fortran到可移植Kokkos：自主智能体AI工作流

发布时间：2025年09月17日

`Agent` `工业与制造`

> From Legacy Fortran to Portable Kokkos: An Autonomous Agentic AI Workflow

# 摘要

> 科学应用仍依赖最初为同构CPU系统开发的遗留Fortran代码库。随着高性能计算（HPC）向异构GPU加速架构转型，许多加速器缺乏原生Fortran绑定，亟需对遗留代码进行现代化改造以提升可移植性。Kokkos等框架虽能提供性能可移植性和单源C++抽象，但手动将Fortran移植到Kokkos需大量专业知识和时间。大型语言模型（LLMs）在源到源代码生成方面已展现潜力，然而其在完全自主工作流中用于翻译和优化并行代码的应用（尤其是跨多样硬件的性能可移植性方面）仍有待探索。
  本文提出一种智能体AI工作流，通过专门的LLM“智能体”协作，将Fortran内核翻译、验证、编译、运行、测试、调试并优化为可移植的Kokkos C++程序。结果显示，该流水线成功对一系列基准内核进行现代化改造，生成了跨硬件分区的性能可移植Kokkos代码。像GPT-5和o4-mini-high这样的付费OpenAI模型仅需几美元即可执行此工作流，其生成的优化代码性能超越Fortran基准；而Llama4-Maverick等开源模型则常无法生成功能正常的代码。
  本研究验证了智能体AI实现Fortran到Kokkos转换的可行性，为自主现代化遗留科学应用程序、使其在各类超级计算机上高效可移植运行提供了新路径。同时，该工作还凸显了LLM驱动的智能体系统在科学及面向系统的应用中，执行结构化、特定领域推理任务的巨大潜力。

> Scientific applications continue to rely on legacy Fortran codebases originally developed for homogeneous, CPU-based systems. As High-Performance Computing (HPC) shifts toward heterogeneous GPU-accelerated architectures, many accelerators lack native Fortran bindings, creating an urgent need to modernize legacy codes for portability. Frameworks like Kokkos provide performance portability and a single-source C++ abstraction, but manual Fortran-to-Kokkos porting demands significant expertise and time. Large language models (LLMs) have shown promise in source-to-source code generation, yet their use in fully autonomous workflows for translating and optimizing parallel code remains largely unexplored, especially for performance portability across diverse hardware. This paper presents an agentic AI workflow where specialized LLM "agents" collaborate to translate, validate, compile, run, test, debug, and optimize Fortran kernels into portable Kokkos C++ programs. Results show the pipeline modernizes a range of benchmark kernels, producing performance-portable Kokkos codes across hardware partitions. Paid OpenAI models such as GPT-5 and o4-mini-high executed the workflow for only a few U.S. dollars, generating optimized codes that surpassed Fortran baselines, whereas open-source models like Llama4-Maverick often failed to yield functional codes. This work demonstrates the feasibility of agentic AI for Fortran-to-Kokkos transformation and offers a pathway for autonomously modernizing legacy scientific applications to run portably and efficiently on diverse supercomputers. It further highlights the potential of LLM-driven agentic systems to perform structured, domain-specific reasoning tasks in scientific and systems-oriented applications.

[Arxiv](https://arxiv.org/abs/2509.12443)