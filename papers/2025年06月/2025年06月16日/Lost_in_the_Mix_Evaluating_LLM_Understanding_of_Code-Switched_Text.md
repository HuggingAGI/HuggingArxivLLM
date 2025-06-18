# 迷失在混合中：评估LLM对混合语言文本的理解能力

发布时间：2025年06月16日

`LLM应用` `跨语言理解`

> Lost in the Mix: Evaluating LLM Understanding of Code-Switched Text

# 摘要

> 语言切换（CSW）是指在同一对话中交替使用两种或更多语言的现象。这种现象在多语言社区中广泛存在，并且在在线内容中越来越普遍，用户在日常交流中自然地混合使用语言。因此，大型语言模型（LLMs）在内容处理和生成中占据中心地位，经常接触到混合语言输入。鉴于其广泛应用，理解 LLM 如何处理和推理这种混合语言文本至关重要。本文通过生成 CSW 版本的现有推理和理解基准，系统地评估了 LLM 在语言切换情况下的理解能力。尽管当外语词汇干扰英文文本时，性能下降明显$unicode{x2013}$即使在语言约束下$unicode{x2013}$，将英文嵌入到其他语言中通常可以提高理解能力。虽然提示方法效果不一，但微调为缓解性能下降提供了一条更稳定的路径。

> Code-switching (CSW) is the act of alternating between two or more languages within a single discourse. This phenomenon is widespread in multilingual communities, and increasingly prevalent in online content, where users naturally mix languages in everyday communication. As a result, Large Language Models (LLMs), now central to content processing and generation, are frequently exposed to code-switched inputs. Given their widespread use, it is crucial to understand how LLMs process and reason about such mixed-language text. This paper presents a systematic evaluation of LLM comprehension under code-switching by generating CSW variants of established reasoning and comprehension benchmarks. While degradation is evident when foreign tokens disrupt English text$unicode{x2013}$even under linguistic constraints$unicode{x2013}$embedding English into other languages often improves comprehension. Though prompting yields mixed results, fine-tuning offers a more stable path to degradation mitigation.

[Arxiv](https://arxiv.org/abs/2506.14012)