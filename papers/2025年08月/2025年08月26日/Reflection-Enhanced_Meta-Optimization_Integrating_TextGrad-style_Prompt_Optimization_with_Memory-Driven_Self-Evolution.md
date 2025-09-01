# 反思增强型元优化：融合TextGrad风格提示优化与记忆驱动自进化

发布时间：2025年08月26日

`LLM应用` `基础理论`

> Reflection-Enhanced Meta-Optimization Integrating TextGrad-style Prompt Optimization with Memory-Driven Self-Evolution

# 摘要

> 近年来，提示优化领域成果斐然（如TextGrad等方法），它们通过文本提示的自动类梯度优化，有效提升了大型语言模型（LLMs）在特定下游任务中的性能。但当前方法多为无状态设计，在不同优化轮次中独立运行，既无法保留和复用历史优化经验，又容易陷入过拟合——生成的提示更新往往在当前任务场景外泛化效果不佳。
  为此，我们提出反思增强元优化（REMO）框架：它创新性地整合了两大核心模块：（1）记忆增强的反思检索增强生成（RAG）模块，采用“错误笔记本”结构存储历史经验；（2）自适应优化器，由LLM驱动的元控制器实现，通过提炼epoch级反思见解来迭代优化系统级提示策略。这一架构不仅能像TextGrad那样进行本地细粒度提示微调，更能系统积累跨优化轮次的知识，实现持续改进。
  我们基于Qwen3-32B在标准推理模式（无需显式思维链提示）下构建REMO，并在数学推理基准GSM8K上测试。结果显示：相比TextGrad基线，REMO的泛化能力更稳定、更鲁棒，不过计算开销略有增加。此外，我们还详细阐述了算法设计，对优化动态进行了定性与定量分析，并通过全面的消融实验阐明了各组件的具体作用。

> Recent advances in prompt optimization, exemplified by methods such as TextGrad, enable automatic, gradient-like refinement of textual prompts to enhance the performance of large language models (LLMs) on specific downstream tasks. However, current approaches are typically stateless and operate independently across optimization runs, lacking mechanisms to preserve and leverage historical optimization experience. Furthermore, they are susceptible to overfitting, often yielding prompt updates that generalize poorly beyond the immediate task context.
  To address these limitations, we propose Reflection-Enhanced Meta-Optimization (REMO), a novel framework that integrates (1) a memory-augmented Reflection Retrieval-Augmented Generation (RAG) module - structured as a "mistake notebook" and (2) a Self-Adaptive Optimizer, implemented via an LLM-driven meta-controller that synthesizes epoch-level reflective insights to iteratively improve system-level prompting strategies. This architecture enables not only local, fine-grained prompt tuning akin to TextGrad, but also the systematic accumulation and reuse of cross-run optimization knowledge, thereby supporting continual improvement over time.
  We instantiate the REMO framework using Qwen3-32B in standard inference mode - without explicit chain-of-thought prompting - and evaluate its efficacy on the GSM8K benchmark for mathematical reasoning. Experimental results demonstrate that, compared to a TextGrad baseline, REMO achieves more stable and robust generalization, albeit at the cost of increased computational overhead. We provide a detailed exposition of the algorithmic design, conduct a qualitative and quantitative analysis of optimization dynamics, and present a comprehensive ablation study to elucidate the contributions of each component.

[Arxiv](https://arxiv.org/abs/2508.18749)