# 复杂性陷阱：简单观察掩蔽在智能体上下文管理中的效率与LLM摘要相当

发布时间：2025年08月29日

`Agent` `基础理论`

> The Complexity Trap: Simple Observation Masking Is as Efficient as LLM Summarization for Agent Context Management

# 摘要

> 基于大型语言模型（LLM）的智能体借助迭代推理、探索与工具使用解决复杂任务，但其过程可能生成冗长且成本高昂的上下文历史。尽管最先进的软件工程（SE）智能体（如OpenHands或Cursor）采用基于LLM的摘要技术应对这一问题，但与直接省略旧观测记录相比，这种复杂性增加能否带来实际性能提升仍不明确。我们在SWE-bench Verified数据集上，基于SWE-agent框架，针对五种不同模型配置对这些策略展开系统性比较。研究发现，简单的观测掩蔽策略相比原始智能体成本减半，同时解决率与LLM摘要策略持平，有时甚至略有超越。例如，在Qwen3-Coder 480B模型上，掩蔽策略将解决率从53.8%（原始智能体）提升至54.8%，且以更低成本维持了与摘要策略的竞争力。这些结果表明，至少在SWE-bench Verified数据集的SWE-agent框架中，最有效且高效的上下文管理方法或许就是最简单的。我们已发布相关代码和数据，以便复现研究结果。

> Large Language Model (LLM)-based agents solve complex tasks through iterative reasoning, exploration, and tool-use, a process that can result in long, expensive context histories. While state-of-the-art Software Engineering ( SE) agents like OpenHands or Cursor use LLM-based summarization to tackle this issue, it is unclear whether the increased complexity offers tangible performance benefits compared to simply omitting older observations. We present a systematic comparison of these strategies within SWE-agent on SWE-bench Verified across five diverse model configurations. We find that a simple observation-masking strategy halves cost relative to a raw agent while matching, and sometimes slightly exceeding, the solve rate of LLM summarization. For example, with Qwen3-Coder 480B, masking improves solve rate from 53.8% (raw agent) to 54.8%, while remaining competitive with summarization at a lower cost. These results suggest that, at least within SWE-agent on SWE-bench Verified, the most effective and efficient context management can be the simplest. We release code and data for reproducibility

[Arxiv](https://arxiv.org/abs/2508.21433)