# # SHARP：共享状态约简实现高效序列模式匹配

发布时间：2025年07月07日

`RAG` `实时数据处理` `数据处理系统`

> SHARP: Shared State Reduction for Efficient Matching of Sequential Patterns

# 摘要

> 在复杂事件处理（CEP）、联机分析处理（OLAP）和增强检索生成（RAG）等现代数据处理系统中，检测数据中的序列模式是一项基础功能。然而，模式匹配在实践中极具挑战性，因为常见应用场景依赖于大量模式，并且需要在严格的延迟限制内进行评估。同时，匹配过程需要维护状态，即中间结果，这些状态会随着输入规模呈指数级增长。因此，系统不得不采用尽力而为的处理方式，在延迟限制内尽可能提高召回率。然而，现有技术将每个模式孤立考虑，忽视了模式匹配中通过状态共享带来的优化潜力。

本文中，我们提出了SHARP，一个通过状态缩减实现高效尽力而为模式匹配的库。为此，SHARP引入了一种新的抽象概念——模式共享度（PSD），通过该概念在模式之间实现状态共享。在运行时，这一抽象机制能够对部分模式匹配结果进行分类和索引。基于此，当延迟限制被突破时，SHARP能够在常数时间内选择部分匹配结果进行进一步处理，从而实现尽力而为的处理。在使用真实数据进行的实验中，SHARP在CEP、OLAP和RAG应用中的模式匹配召回率分别达到了97%、96%和73%，而延迟限制设定为平均处理延迟的50%。

> The detection of sequential patterns in data is a basic functionality of modern data processing systems for complex event processing (CEP), OLAP, and retrieval-augmented generation (RAG). In practice, pattern matching is challenging, since common applications rely on a large set of patterns that shall be evaluated with tight latency bounds. At the same time, matching needs to maintain state, i.e., intermediate results, that grows exponentially in the input size. Hence, systems turn to best-effort processing, striving for maximal recall under a latency bound. Existing techniques, however, consider each pattern in isolation, neglecting the optimization potential induced by state sharing in pattern matching.
  In this paper, we present SHARP, a library that employs state reduction to achieve efficient best-effort pattern matching. To this end, SHARP incorporates state sharing between patterns through a new abstraction, coined pattern-sharing degree (PSD). At runtime, this abstraction facilitates the categorization and indexing of partial pattern matches. Based thereon, once a latency bound is exceeded, SHARP realizes best-effort processing by selecting a subset of partial matches for further processing in constant time. In experiments with real-world data, SHARP achieves a recall of 97%, 96% and 73% for pattern matching in CEP, OLAP, and RAG applications, under a bound of 50% of the average processing latency.

[Arxiv](https://arxiv.org/abs/2507.04872)