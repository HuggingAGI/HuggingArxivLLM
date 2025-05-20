# # 大型语言模型中的思维与语言建模差距探讨

发布时间：2025年05月19日

`LLM理论` `人工智能` `认知科学`

> On the Thinking-Language Modeling Gap in Large Language Models

# 摘要

> System 2推理是智能的重要标志，它依赖于缓慢而有逻辑的思考过程。人类通过思维语言将推理过程组织成一个因果链条，由心理语言或思维构成。最近的研究发现，大型语言模型（LLMs）经过大规模自然语言预训练后，能够进行System 2推理。然而，我们发现语言与思维在建模上存在显著差距。由于语言主要用于知识和思想的交流，对人类语言的建模容易引入偏见，使LLMs偏离心理中的思维链条。进一步研究表明，这些偏见会误导LLMs中“思维”的提取，使其仅关注前提中的偏见部分。为解决这一问题，我们提出了一种名为思维语言（Language-of-Thoughts，LoT）的新提示技术。与直接从部分信息中提取思维链条不同，LoT指示LLMs调整所有相关信息的表达顺序和使用的标记。实验证明，这一策略显著减少了LLMs中的语言建模偏见，并在多种推理任务中提升了模型性能。

> System 2 reasoning is one of the defining characteristics of intelligence, which requires slow and logical thinking. Human conducts System 2 reasoning via the language of thoughts that organizes the reasoning process as a causal sequence of mental language, or thoughts. Recently, it has been observed that System 2 reasoning can be elicited from Large Language Models (LLMs) pre-trained on large-scale natural languages. However, in this work, we show that there is a significant gap between the modeling of languages and thoughts. As language is primarily a tool for humans to share knowledge and thinking, modeling human language can easily absorb language biases into LLMs deviated from the chain of thoughts in minds. Furthermore, we show that the biases will mislead the eliciting of "thoughts" in LLMs to focus only on a biased part of the premise. To this end, we propose a new prompt technique termed Language-of-Thoughts (LoT) to demonstrate and alleviate this gap. Instead of directly eliciting the chain of thoughts from partial information, LoT instructs LLMs to adjust the order and token used for the expressions of all the relevant information. We show that the simple strategy significantly reduces the language modeling biases in LLMs and improves the performance of LLMs across a variety of reasoning tasks.

[Arxiv](https://arxiv.org/abs/2505.12896)