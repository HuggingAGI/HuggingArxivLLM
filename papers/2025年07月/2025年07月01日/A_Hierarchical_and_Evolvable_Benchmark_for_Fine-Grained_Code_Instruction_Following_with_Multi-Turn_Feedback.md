# 分层可演进基准测试：支持多轮反馈的细粒度代码指令遵循

发布时间：2025年07月01日

`LLM应用

理由：这篇论文专注于大型语言模型（LLMs）在代码生成中的应用，特别是评估它们在处理复杂指令时的表现。通过引入新的基准测试框架MultiCodeIF，研究者评估了不同LLMs在多维度约束下的性能，并探讨了如何通过反馈机制优化模型表现。这属于LLM的实际应用研究。` `代码生成` `基准测试框架`

> A Hierarchical and Evolvable Benchmark for Fine-Grained Code Instruction Following with Multi-Turn Feedback

# 摘要

> 大型语言模型（LLMs）在代码生成领域取得了长足进步，但在应对复杂、多层且多样化的编程指令方面仍存在不足。现有基准测试多关注功能正确性，却忽视了现实开发中的多样化需求。为此，我们推出了MultiCodeIF，一个全面的基准测试框架，从约束类型、层级结构和迭代优化三个维度评估代码生成中的指令遵循能力。基于9个类别和27种约束类型的结构化分类体系，MultiCodeIF能够细致评估功能性和非功能性指令的遵循情况。通过自动化工具ConstraGen，我们合成并演化了来自14种编程语言的2021个代码任务，并通过反馈驱动的任务变体支持多轮评估。对六种前沿LLMs的实证评估揭示了显著的性能差异：Claude-3-7-Sonnet以63.0%的平均约束满足率领先，而Qwen3-1.7B等较小模型则为44.8%。模型在显性约束下表现良好，但面对隐性或抽象约束时则显得力不从心。涉及多层级约束的任务大幅降低了模型的成功率，从单一层级的54.5%降至多层级场景下的18.8%。然而，结构化的反馈机制能够促进逐步改进：在四轮迭代优化中，平均约束满足率从63.0%提升至83.4%。MultiCodeIF提供了一个可扩展、关注约束且对反馈敏感的框架，用于在现实代码生成场景下基准测试LLMs，弥合了合成评估与现实指令复杂性之间的差距。完整的基准数据集、评估管道和源代码可在https://github.com/SYSUSELab/MultiCodeIF获取。

> Large language models (LLMs) have advanced significantly in code generation, yet their ability to follow complex programming instructions with layered and diverse constraints remains underexplored. Existing benchmarks often prioritize functional correctness, overlooking the nuanced requirements found in real-world development. We introduce MultiCodeIF, a comprehensive benchmark designed to evaluate instruction-following in code generation across multiple dimensions: constraint type, hierarchical levels, and iterative refinement. Built upon a structured taxonomy of 9 categories and 27 constraint types, MultiCodeIF enables granular assessment of both functional and non-functional instruction adherence. Using an automated pipeline, ConstraGen, we synthesize and evolve 2,021 code tasks sourced from 14 programming languages, supporting multi-turn evaluation through feedback-driven task variants. Empirical evaluation of six state-of-the-art LLMs uncovers substantial performance disparities. The top-performing model, Claude-3-7-Sonnet, achieves 63.0% average constraint satisfaction, while smaller models like Qwen3-1.7B fall to 44.8%. Models perform well on explicit constraints, but struggle with implicit or abstract constraints. Tasks with multiple hierarchical constraints significantly reduce model success rates, from 54.5% in single-level to just 18.8% in multi-level scenarios. However, structured feedback enables progressive improvement: average constraint satisfaction rises from 63.0% to 83.4% over four iterative refinement rounds. MultiCodeIF provides a scalable, constraint-aware, and feedback-sensitive framework to benchmark LLMs under realistic code generation scenarios, bridging the gap between synthetic evaluations and real-world instruction complexity. The full benchmark dataset, evaluation pipeline, and source code are available at https://github.com/SYSUSELab/MultiCodeIF.

[Arxiv](https://arxiv.org/abs/2507.00699)