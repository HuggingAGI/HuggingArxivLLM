# 数感的脆弱性：探析大型语言模型数值推理的根本局限

发布时间：2025年09月08日

`Agent` `基础理论`

> A Fragile Number Sense: Probing the Elemental Limits of Numerical Reasoning in LLMs

# 摘要

> 大型语言模型（LLMs）虽已展现出惊人的涌现能力，但其数值推理的稳健性仍是未解之谜。尽管标准基准通过聚合指标评估LLM在复杂问题集上的推理表现，却常常掩盖了其基础层面的弱点。本研究通过评估LLM在复杂度递增问题（从基础运算到组合谜题）上的表现，深入探究其数学计算能力。我们设计了100个问题挑战（分为四类），对多个最先进的基于LLM的智能体进行测试：（1）基本算术，（2）高级运算，（3）素数检查，（4）24点数字谜题。结果显示，智能体在前三类（需确定性算法执行）的准确率很高，但在数字谜题上却屡屡失败——这凸显出，在庞大组合空间中进行启发式搜索的需求是其显著瓶颈。这些发现揭示，智能体的能力主要局限于回忆和执行已知算法，而非开展生成式问题解决。这意味着，它们看似具备的数值推理能力，实则更接近复杂的模式匹配，而非灵活的分析思维——这限制了其在需新颖或创造性数值洞察任务中的应用潜力。

> Large Language Models (LLMs) have demonstrated remarkable emergent capabilities, yet the robustness of their numerical reasoning remains an open question. While standard benchmarks evaluate LLM reasoning on complex problem sets using aggregated metrics, they often obscure foundational weaknesses. In this work, we probe LLM mathematical numeracy by evaluating performance on problems of escalating complexity, from constituent operations to combinatorial puzzles. We test several state-of-the-art LLM-based agents on a 100-problem challenge comprising four categories: (1) basic arithmetic, (2) advanced operations, (3) primality checking, and (4) the Game of 24 number puzzle. Our results show that while the agents achieved high accuracy on the first three categories, which require deterministic algorithmic execution, they consistently failed at the number puzzle, underlining its demand for a heuristic search over a large combinatorial space to be a significant bottleneck. These findings reveal that the agents' proficiency is largely confined to recalling and executing known algorithms, rather than performing generative problem-solving. This suggests their apparent numerical reasoning is more akin to sophisticated pattern-matching than flexible, analytical thought, limiting their potential for tasks that require novel or creative numerical insights.

[Arxiv](https://arxiv.org/abs/2509.06332)