# OnionEval: 小-大型语言模型事实冲突幻觉的统一评估

发布时间：2025年01月22日

`LLM理论

**理由**：这篇论文主要讨论了小型语言模型（SLLMs）在任务中的表现及其局限性，特别是幻觉问题。论文提出了一个新的评估框架和指标来评估SLLMs的幻觉倾向，并探讨了如何通过思维链策略来改善这些局限性。这些内容主要涉及对语言模型的理论研究和性能评估，因此归类为“LLM理论”。` `人工智能`

> OnionEval: An Unified Evaluation of Fact-conflicting Hallucination for Small-Large Language Models

# 摘要

> 大型语言模型（LLMs）虽然能力强大，但训练和推理所需的计算资源也相当可观。在LLM家族中，参数少于100亿的小型模型（SLLMs）同样能在多种任务中表现出色。然而，这些小型模型与大型模型一样，也存在容易产生幻觉的局限性。尽管已有不少基准测试用于评估LLM的幻觉问题，但专门针对SLLMs的测试却寥寥无几。此外，SLLMs在不同基准测试中的表现差异显著。本文提出了OnionEval，一个多层结构化框架，并引入了一个名为上下文影响分数（CI）的指标，旨在有效评估SLLMs在不同上下文层次上的事实冲突幻觉倾向。实验结果表明，SLLMs在事实分析上表现出色，但在上下文推理上存在挑战。进一步研究发现，简单的思维链策略能显著改善这些局限性，提升SLLMs在实际应用中的实用性。

> Large Language Models (LLMs) are highly capable but require significant computational resources for both training and inference. Within the LLM family, smaller models (those with fewer than 10 billion parameters) also perform well across various tasks. However, these smaller models share similar limitations to their larger counterparts, including the tendency to hallucinate. Despite the existence of many benchmarks to evaluate hallucination in LLMs, few have specifically focused on small LLMs (SLLMs). Additionally, SLLMs show widely varying performance across different benchmarks. In this paper, we introduce OnionEval, a multi-layer structured framework with a specific metric called the context-influence score (CI), designed to effectively assess the fact-conflicting hallucination tendencies of small LLMs across different contextual levels. Our experimental results reveal a key feature of SLLMs: they excel in factual analysis but face challenges with context reasoning. Further investigation shows that a simple Chain-of-Thought strategy can significantly reduce these limitations, improving the practical usefulness of SLLMs in real-world applications.

[Arxiv](https://arxiv.org/abs/2501.12975)