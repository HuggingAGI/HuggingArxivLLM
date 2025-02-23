# 优化复合型 AI 系统的模型选择方案

发布时间：2025年02月20日

`LLM理论` `AI系统` `模型选择`

> Optimizing Model Selection for Compound AI Systems

# 摘要

> 复合 AI 系统通过结合多个 LLM 调用（如自我优化和多智能体辩论）在众多 AI 任务中表现出色。我们聚焦于优化复合系统的核心问题：如何为每个 LLM 调用或模块选择合适的 LLM？研究表明，LLM 的选择对最终质量影响显著，但搜索空间呈指数级增长。为此，我们提出了 LLMSelector，一个适用于复合系统的高效模型选择框架，它基于两大关键实证发现：(i) 在固定其他模块的前提下，端到端性能通常与单个模块的表现呈单调关系；(ii) 每个模块的表现可通过 LLM 准确评估。基于此，LLMSelector 采用迭代方法，每次选择一个模块，并为其分配由 LLM 评估表现最佳的模型，直至无法进一步优化。该框架适用于模块数量有限的任何复合系统，其 API 调用次数与模块数量线性相关，从而在实际与理论上实现高质量的模型分配。实验结果表明，使用 GPT-4o、Claude 3.5 Sonnet 和 Gemini 1.5 等 LLM 进行多智能体辩论和自我优化等任务时，LLMSelector 相较于为所有模块使用同一 LLM，可带来 5%-70% 的准确性提升。

> Compound AI systems that combine multiple LLM calls, such as self-refine and multi-agent-debate, achieve strong performance on many AI tasks. We address a core question in optimizing compound systems: for each LLM call or module in the system, how should one decide which LLM to use? We show that these LLM choices have a large effect on quality, but the search space is exponential. We propose LLMSelector, an efficient framework for model selection in compound systems, which leverages two key empirical insights: (i) end-to-end performance is often monotonic in how well each module performs, with all other modules held fixed, and (ii) per-module performance can be estimated accurately by an LLM. Building upon these insights, LLMSelector iteratively selects one module and allocates to it the model with the highest module-wise performance, as estimated by an LLM, until no further gain is possible. LLMSelector is applicable to any compound system with a bounded number of modules, and its number of API calls scales linearly with the number of modules, achieving high-quality model allocation both empirically and theoretically. Experiments with popular compound systems such as multi-agent debate and self-refine using LLMs such as GPT-4o, Claude 3.5 Sonnet and Gemini 1.5 show that LLMSelector confers 5%-70% accuracy gains compared to using the same LLM for all modules.

[Arxiv](https://arxiv.org/abs/2502.14815)