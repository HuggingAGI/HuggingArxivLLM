# # 进化思维：大型语言模型与进化算法的融合

发布时间：2025年05月08日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLMs）与进化算法（EAs）结合，用于解决复杂问题中的优化挑战。通过开发增强的进化搜索策略，论文展示了LLMs在生成优质候选解方面的有效性，从而提升结果质量。这属于将LLMs应用于特定任务的范畴，因此归类为LLM应用。` `计算智能` `优化方法`

> Evolutionary thoughts: integration of large language models and evolutionary algorithms

# 摘要

> 大型语言模型（LLMs）在理解与生成自然语言和代码方面表现卓越，但其推理过程易出现幻觉，在复杂新颖场景中常陷入局部或错误的解决方案。然而，进化算法（EAs）凭借探索广泛复杂搜索空间的固有优势，在传统优化方法可能失效的场景中表现尤为突出。针对复杂问题，我们提出了一种高效评估框架，以应对评估大规模种群的计算瓶颈，同时保持与现有原始定义的兼容性，确保生成有效个体。利用LLMs，我们开发了一种增强的进化搜索策略，使对广阔解空间的探索更加聚焦。实证结果表明，LLMs能够有效生成更优质的候选解，显著提升结果质量。

> Large Language Models (LLMs) have unveiled remarkable capabilities in understanding and generating both natural language and code, but LLM reasoning is prone to hallucination and struggle with complex, novel scenarios, often getting stuck on partial or incorrect solutions. However, the inherent ability of Evolutionary Algorithms (EAs) to explore extensive and complex search spaces makes them particularly effective in scenarios where traditional optimization methodologies may falter. However, EAs explore a vast search space when applied to complex problems.
  To address the computational bottleneck of evaluating large populations, particularly crucial for complex evolutionary tasks, we introduce a highly efficient evaluation framework. This implementation maintains compatibility with existing primitive definitions, ensuring the generation of valid individuals.
  Using LLMs, we propose an enhanced evolutionary search strategy that enables a more focused exploration of expansive solution spaces. LLMs facilitate the generation of superior candidate solutions, as evidenced by empirical results demonstrating their efficacy in producing improved outcomes.

[Arxiv](https://arxiv.org/abs/2505.05756)