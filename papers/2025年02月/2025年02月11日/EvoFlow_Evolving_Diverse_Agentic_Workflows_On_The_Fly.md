# # 标题
EvoFlow：实时动态演进多样化智能体工作流

发布时间：2025年02月11日

`Agent` `多智能体系统` `自动化设计`

> EvoFlow: Evolving Diverse Agentic Workflows On The Fly

# 摘要

> 在过去两年中，基于大型语言模型（LLM）的多智能体系统经历了从劳动密集型的手动设计到部分自动化（如提示工程、通信拓扑）再到完全自动化设计的演变。然而，现有的智能体自动化流水线通常缺乏 LLM 异构性，专注于单一目标的性能优化，这限制了它们结合较弱模型以实现更定制化和更具成本效益解决方案的潜力。为了解决这一问题，我们提出了 EvoFlow，这是一个基于利基进化算法的框架，用于自动搜索一组异构且复杂度自适应的智能体工作流，而非单一的同构复杂工作流。

从技术层面来看，EvoFlow 通过 	extit{(1) 标签检索}从智能体种群中提取父代工作流，通过 	extit{(2) 交叉}和 	extit{(3) 变异}生成新的工作流，并利用 	extit{(4) 利基选择}来维护种群的多样性和质量。在七项基准测试中的广泛评估验证了 EvoFlow 的以下特性：	extbf{(I) 多样化}，能够演化出从简单的输入输出任务到复杂的多轮交互的工作流；	extbf{(II) 高性能}，在之前的基于手工设计和自动化的工作流基础上提升了 $1.23\%\sim29.86\%$；	extbf{(III) 经济性}，使用较弱的开源模型，仅以强大 \llmname{o1-preview} 的 $12.4\%$ 推理成本就超越了其性能表现。

> The past two years have witnessed the evolution of large language model (LLM)-based multi-agent systems from labor-intensive manual design to partial automation (\textit{e.g.}, prompt engineering, communication topology) and eventually to fully automated design. However, existing agentic automation pipelines often lack LLM heterogeneity and focus on single-objective performance optimization, limiting their potential to combine weaker models for more customized and cost-effective solutions. To address this challenge, we propose EvoFlow, a niching evolutionary algorithm-based framework to automatically search a population of heterogeneous and complexity-adaptive agentic workflows, rather than a single homogeneous, complex workflow. Technically, EvoFlow performs \textit{(1) tag-based retrieval} to extract parent workflows from an agentic population, evolves new workflows through \textit{(2) crossover} and \textit{(3) mutation}, and employs \textit{(4) niching-based selection} to maintain population diversity and quality. Extensive evaluations across seven benchmarks demonstrate that EvoFlow is: \textbf{(I) diverse}, evolving a population of workflows ranging from simple I/O tasks to complex multi-turn interactions; \textbf{(II) high-performing}, outperforming previous handcrafted and automated workflows by $1.23\%\sim29.86\%$; \textbf{(III) economical}, surpassing powerful \llmname{o1-preview} at $12.4\%$ of its inference cost using weaker open-source models.

[Arxiv](https://arxiv.org/abs/2502.07373)