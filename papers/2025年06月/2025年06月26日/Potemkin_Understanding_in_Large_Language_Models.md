# # 大型语言模型的Potemkin理解

发布时间：2025年06月26日

`LLM理论` `模型评估`

> Potemkin Understanding in Large Language Models

# 摘要

> 大型语言模型（LLMs）通常通过基准数据集进行评估。但为何能通过模型对精选问题的回答推断其能力？本文首先构建了一个正式框架来回答这一问题。关键在于，用于测试 LLMs 的基准——如 AP 考试——同样用于测试人类。然而，这引出了一个重要含义：这些基准测试仅在 LLMs 以与人类误解相似的方式误解概念时才有效。否则，基准测试的成功仅证明了“Potemkin 理解”——一种由与任何人类对概念的解释不可调和的答案驱动的理解假象。我们提出了两种量化 Potemkin 理解存在的程序：一种使用在三个领域中专门设计的基准，另一种使用一种通用程序，提供其普遍存在的下限。我们发现，Potemkin 理解在模型、任务和领域中无处不在。我们还发现，这些失败不仅反映了理解错误，还反映了概念表示中的更深层次的内在不一致。

> Large language models (LLMs) are regularly evaluated using benchmark datasets. But what justifies making inferences about an LLM's capabilities based on its answers to a curated set of questions? This paper first introduces a formal framework to address this question. The key is to note that the benchmarks used to test LLMs -- such as AP exams -- are also those used to test people. However, this raises an implication: these benchmarks are only valid tests if LLMs misunderstand concepts in ways that mirror human misunderstandings. Otherwise, success on benchmarks only demonstrates potemkin understanding: the illusion of understanding driven by answers irreconcilable with how any human would interpret a concept. We present two procedures for quantifying the existence of potemkins: one using a specially designed benchmark in three domains, the other using a general procedure that provides a lower-bound on their prevalence. We find that potemkins are ubiquitous across models, tasks, and domains. We also find that these failures reflect not just incorrect understanding, but deeper internal incoherence in concept representations.

[Arxiv](https://arxiv.org/abs/2506.21521)