# 激发长上下文LLM的上下文检索与推理能力

发布时间：2025年01月14日

`RAG

理由：这篇论文主要讨论了长上下文语言模型（LCLMs）在检索增强生成（RAG）中的应用，并提出了新的基准测试和方法来提升LCLMs在RAG任务中的性能。论文的核心内容围绕如何通过改进检索和生成过程来增强RAG的效果，因此应归类为RAG。` `信息检索`

> Eliciting In-context Retrieval and Reasoning for Long-context Large Language Models

# 摘要

> # 摘要
长上下文语言模型（LCLMs）的最新进展有望通过简化流程来革新检索增强生成（RAG）。LCLMs 凭借其扩展的上下文窗口，能够直接处理整个知识库并执行检索和推理——我们称之为上下文检索与推理（ICR^2）。然而，现有基准测试如 LOFT 往往因提供过于简化的上下文而高估 LCLM 的性能。为此，我们推出了 ICR^2 基准测试，通过在更真实的场景中引入强检索器检索的混淆段落来评估 LCLM。我们提出了三种提升 LCLM 性能的方法：（1）检索后生成微调，（2）检索注意力探测，利用注意力头在解码时过滤和去噪长上下文，（3）联合训练检索头与生成头。我们在 LOFT 和 ICR^2 上对五个知名 LCLM 的评估显示，与普通 RAG 和监督微调相比，应用于 Mistral-7B 的最佳方法在 LOFT 上分别提升了 +17 和 +15 分，在 ICR^2 上分别提升了 +13 和 +2 分。尽管模型规模小得多，但在大多数任务上甚至超越了 GPT-4-Turbo。

> Recent advancements in long-context language models (LCLMs) promise to transform Retrieval-Augmented Generation (RAG) by simplifying pipelines. With their expanded context windows, LCLMs can process entire knowledge bases and perform retrieval and reasoning directly -- a capability we define as In-Context Retrieval and Reasoning (ICR^2). However, existing benchmarks like LOFT often overestimate LCLM performance by providing overly simplified contexts. To address this, we introduce ICR^2, a benchmark that evaluates LCLMs in more realistic scenarios by including confounding passages retrieved with strong retrievers. We then propose three methods to enhance LCLM performance: (1) retrieve-then-generate fine-tuning, (2) retrieval-attention-probing, which uses attention heads to filter and de-noise long contexts during decoding, and (3) joint retrieval head training alongside the generation head. Our evaluation of five well-known LCLMs on LOFT and ICR^2 demonstrates significant gains with our best approach applied to Mistral-7B: +17 and +15 points by Exact Match on LOFT, and +13 and +2 points on ICR^2, compared to vanilla RAG and supervised fine-tuning, respectively. It even outperforms GPT-4-Turbo on most tasks despite being a much smaller model.

[Arxiv](https://arxiv.org/abs/2501.08248)