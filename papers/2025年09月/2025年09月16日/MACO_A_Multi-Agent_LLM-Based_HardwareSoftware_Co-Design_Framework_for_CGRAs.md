# MACO：基于多智能体大型语言模型（LLM）的CGRAs硬件/软件协同设计框架

发布时间：2025年09月16日

`Agent` `工业与制造`

> MACO: A Multi-Agent LLM-Based Hardware/Software Co-Design Framework for CGRAs

# 摘要

> 粗粒度可重构阵列（CGRAs）是一种前景广阔的计算架构，能在多领域实现高性能、低能耗的加速。凭借功能单元级的重构支持，CGRAs可灵活适配多样化计算模式，优化资源利用率。但CGRAs设计难度极大——设计空间庞大、架构参数相互独立，且手动设计耗时费力。好在大型语言模型（LLMs）的飞速发展，为这一过程的自动化开辟了新路径。
  为此，我们提出MACO：一个基于多智能体LLM的开源框架，专为CGRAs的软硬件（HW/SW）协同设计打造。该框架借助LLM推理能力，分四阶段生成CGRAs：软硬件协同设计、设计纠错、最优方案筛选及评估反馈。更重要的是，MACO会迭代优化生成的CGRAs，通过智能体推理与反馈，为特定领域实现更优的PPA（即功耗、性能、面积）设计指标。此外，我们还引入LLM自学习机制，利用LLM驱动的决策来挑选最优CGRA，大幅加快设计进程。
  我们从性能、功耗、面积三个维度，将MACO与最先进的LLM方法及手动设计进行对比评估。结果显示，MACO能高效生成高质量CGRA架构，显著降低手动设计成本，充分证明其在实际CGRA设计中的应用潜力。

> Coarse-grained Reconfigurable Arrays (CGRAs) are a promising computing architecture that can deliver high-performance, energy-efficient acceleration across diverse domains. By supporting reconfiguration at the functional unit level, CGRAs efficiently adapt to varying computational patterns and optimize resource utilization. However, designing CGRAs is highly challenging due to the vast design space, independent architectural parameters, and the time-consuming nature of manual design. Fortunately, the rapid advancement of large language models (LLMs) presents new opportunities to automate this process.
  In this work, we propose MACO -- an open-source multi-agent LLM-based framework for Hardware/Software (HW/SW) co-design of CGRAs. The framework employs LLM reasoning to generate CGRAs across four stages: HW/SW co-design, Design error correction, Best design selection, and Evaluation & Feedback. Furthermore, MACO iteratively optimizes the generated CGRAs, leveraging agent reasoning and feedback to achieve higher PPA (that is, power, performance, and area) design points for a given domain. In addition, we introduce an LLM self-learning mechanism that employs LLM-driven decision making to select the optimal CGRA to accelerate the design process.
  We evaluate the framework with state-of-the-art LLM-based methods and manual CGRA design, in terms of performance, power consumption, and area. Experimental results show that MACO efficiently generates high-quality CGRA architectures, significantly reducing manual design effort and demonstrating the potential of our framework for real-world CGRA design.

[Arxiv](https://arxiv.org/abs/2509.13557)