# EH基准：眼科幻觉基准与智能体驱动的自顶向下可追溯推理工作流

发布时间：2025年07月24日

`LLM应用` `人工智能`

> EH-Benchmark Ophthalmic Hallucination Benchmark and Agent-Driven Top-Down Traceable Reasoning Workflow

# 摘要

> 医学大型语言模型（MLLMs）在眼科诊断领域具有重要应用价值，能够有效应对威胁视力的疾病。然而，受限于眼科知识储备、视觉定位与推理能力的不足以及多模态眼科数据的匮乏，MLLMs的诊断准确性受到幻觉现象的显著影响，导致病灶检测与疾病诊断的精确性受限。此外，现有医学评估基准无法全面评估幻觉类型，也未能提供有效的缓解方案。针对这些挑战，我们开发了EH-Benchmark，一个专为评估MLLMs幻觉设计的新一代眼科基准测试。我们基于任务特性和错误类型，将MLLMs的幻觉主要划分为视觉理解和逻辑组合两大类，每类下包含多个细分类型。考虑到MLLMs主要依赖语言推理而非视觉处理的特点，我们提出了一种以智能体为中心的三阶段框架，包含知识层面检索、任务层面案例研究以及结果层面验证三个阶段。实验结果表明，我们的多智能体框架显著降低了两类幻觉的发生，有效提升了诊断的准确性、可解释性和可靠性。我们的项目已开源，访问地址为https://github.com/ppxy1/EH-Benchmark。

> Medical Large Language Models (MLLMs) play a crucial role in ophthalmic diagnosis, holding significant potential to address vision-threatening diseases. However, their accuracy is constrained by hallucinations stemming from limited ophthalmic knowledge, insufficient visual localization and reasoning capabilities, and a scarcity of multimodal ophthalmic data, which collectively impede precise lesion detection and disease diagnosis. Furthermore, existing medical benchmarks fail to effectively evaluate various types of hallucinations or provide actionable solutions to mitigate them. To address the above challenges, we introduce EH-Benchmark, a novel ophthalmology benchmark designed to evaluate hallucinations in MLLMs. We categorize MLLMs' hallucinations based on specific tasks and error types into two primary classes: Visual Understanding and Logical Composition, each comprising multiple subclasses. Given that MLLMs predominantly rely on language-based reasoning rather than visual processing, we propose an agent-centric, three-phase framework, including the Knowledge-Level Retrieval stage, the Task-Level Case Studies stage, and the Result-Level Validation stage. Experimental results show that our multi-agent framework significantly mitigates both types of hallucinations, enhancing accuracy, interpretability, and reliability. Our project is available at https://github.com/ppxy1/EH-Benchmark.

[Arxiv](https://arxiv.org/abs/2507.22929)