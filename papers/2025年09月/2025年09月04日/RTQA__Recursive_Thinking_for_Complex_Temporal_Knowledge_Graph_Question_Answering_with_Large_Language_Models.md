# RTQA：递归思维助力复杂时间知识图谱问答——基于大型语言模型

发布时间：2025年09月04日

`LLM应用` `基础理论`

> RTQA : Recursive Thinking for Complex Temporal Knowledge Graph Question Answering with Large Language Models

# 摘要

> 当前的时间知识图谱问答（TKGQA）方法主要聚焦于隐式时间约束，难以处理更复杂的时间查询，且在分解框架中还面临推理能力有限和错误传播的难题。为此，我们提出了一种无需训练即可增强TKG推理能力的全新框架RTQA。借鉴递归思想，RTQA将问题递归分解为子问题，借助LLM和TKG知识自底向上求解，并通过多路径答案聚合提升容错性。RTQA核心包含三个组件：时间问题分解器、递归求解器和答案聚合器。在MultiTQ和TimelineKGQA基准测试上的实验显示，RTQA在“Multiple”和“Complex”类别中的Hits@1指标显著提升，性能超越现有最优方法。我们的代码和数据已开源，地址为https://github.com/zjukg/RTQA。

> Current temporal knowledge graph question answering (TKGQA) methods primarily focus on implicit temporal constraints, lacking the capability of handling more complex temporal queries, and struggle with limited reasoning abilities and error propagation in decomposition frameworks. We propose RTQA, a novel framework to address these challenges by enhancing reasoning over TKGs without requiring training. Following recursive thinking, RTQA recursively decomposes questions into sub-problems, solves them bottom-up using LLMs and TKG knowledge, and employs multi-path answer aggregation to improve fault tolerance. RTQA consists of three core components: the Temporal Question Decomposer, the Recursive Solver, and the Answer Aggregator. Experiments on MultiTQ and TimelineKGQA benchmarks demonstrate significant Hits@1 improvements in "Multiple" and "Complex" categories, outperforming state-of-the-art methods. Our code and data are available at https://github.com/zjukg/RTQA.

[Arxiv](https://arxiv.org/abs/2509.03995)