# # 有效性分析：提示优化在自然语言到SQL转换系统中的应用效果

发布时间：2025年05月26日

`LLM应用` `数据库`

> Effectiveness of Prompt Optimization in NL2SQL Systems

# 摘要

> NL2SQL方法得益于大型语言模型（LLMs）的强大能力。具体而言，为特定领域构建NL2SQL系统，只需向LLM提供足够的上下文信息，如模式细节和翻译示例。然而，构建一个准确的系统仍需严格选择每个查询的适当上下文，包括识别相关模式元素、单元值以及有助于LLM理解领域特定细微差别的合适示例。基于检索的方法成为识别上下文的首选，尽管有效，但检索过程增加了推理时的成本。

本文主张，生产环境需要高精度、高性能的NL2SQL系统，而不仅仅是高质量的SQL生成，这是当前大多数方法的重点。在这些场景中，选择一组静态示例——捕捉查询日志、目标数据库、SQL结构和执行延迟的复杂性——比仅基于相似性的选择更为关键。然而，关键挑战在于为给定的生产环境识别一组具有代表性的示例。为此，我们提出了一种提示优化框架，满足高精度要求，并通过多目标优化提升SQL性能。初步分析证明了框架的有效性。

> NL2SQL approaches have greatly benefited from the impressive capabilities of large language models (LLMs). In particular, bootstrapping an NL2SQL system for a specific domain can be as simple as instructing an LLM with sufficient contextual information, such as schema details and translation demonstrations. However, building an accurate system still requires the rigorous task of selecting the right context for each query-including identifying relevant schema elements, cell values, and suitable exemplars that help the LLM understand domain-specific nuances. Retrieval-based methods have become the go-to approach for identifying such context. While effective, these methods introduce additional inference-time costs due to the retrieval process.
  In this paper, we argue that production scenarios demand high-precision, high-performance NL2SQL systems, rather than simply high-quality SQL generation, which is the focus of most current NL2SQL approaches. In such scenarios, the careful selection of a static set of exemplars-capturing the intricacies of the query log, target database, SQL constructs, and execution latencies-plays a more crucial role than exemplar selection based solely on similarity. The key challenge, however, lies in identifying a representative set of exemplars for a given production setting. To this end, we propose a prompt optimization framework that not only addresses the high-precision requirement but also optimizes the performance of the generated SQL through multi-objective optimization. Preliminary empirical analysis demonstrates the effectiveness of the proposed framework.

[Arxiv](https://arxiv.org/abs/2505.20591)