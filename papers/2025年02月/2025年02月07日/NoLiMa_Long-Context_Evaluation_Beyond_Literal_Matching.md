# NoLiMa: 长上下文评估，超越字面匹配

发布时间：2025年02月07日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在处理长上下文时的性能表现，并提出了一个新的基准测试（NoLiMa）来评估模型在缺乏字面匹配的情况下提取关键信息的能力。论文的核心关注点是LLMs的注意力机制及其在处理长上下文时的局限性，这属于对LLM内部机制和理论的研究，因此应归类为LLM理论。` `基准测试`

> NoLiMa: Long-Context Evaluation Beyond Literal Matching

# 摘要

> # 摘要
近期的大型语言模型（LLMs）已能处理长达128K至1M tokens的上下文。评估其能力的一种常用方法是“大海捞针”（NIAH）测试，即从大量无关信息中提取关键内容。该方法的扩展包括增加干扰项、事实链和上下文推理。然而，现有基准测试中，模型往往依赖字面匹配来简化任务。为此，我们提出了NoLiMa基准测试，通过精心设计的针集，减少问题与针之间的词汇重叠，迫使模型通过潜在关联来定位关键信息。我们测试了12个声称支持至少128K tokens上下文的LLMs。结果显示，尽管这些模型在短上下文（<1K）中表现优异，但随着上下文长度增加，性能显著下降。例如，在32K tokens时，10个模型的表现低于其短上下文基线的50%。即使是表现优异的GPT-4o，其准确率也从99.3%降至69.7%。分析表明，这种性能下降源于注意力机制在缺乏字面匹配的长上下文中难以有效提取相关信息。

> Recent large language models (LLMs) support long contexts ranging from 128K to 1M tokens. A popular method for evaluating these capabilities is the needle-in-a-haystack (NIAH) test, which involves retrieving a "needle" (relevant information) from a "haystack" (long irrelevant context). Extensions of this approach include increasing distractors, fact chaining, and in-context reasoning. However, in these benchmarks, models can exploit existing literal matches between the needle and haystack to simplify the task. To address this, we introduce NoLiMa, a benchmark extending NIAH with a carefully designed needle set, where questions and needles have minimal lexical overlap, requiring models to infer latent associations to locate the needle within the haystack. We evaluate 12 popular LLMs that claim to support contexts of at least 128K tokens. While they perform well in short contexts (<1K), performance degrades significantly as context length increases. At 32K, for instance, 10 models drop below 50% of their strong short-length baselines. Even GPT-4o, one of the top-performing exceptions, experiences a reduction from an almost-perfect baseline of 99.3% to 69.7%. Our analysis suggests these declines stem from the increased difficulty the attention mechanism faces in longer contexts when literal matches are absent, making it harder to retrieve relevant information.

[Arxiv](https://arxiv.org/abs/2502.05167)