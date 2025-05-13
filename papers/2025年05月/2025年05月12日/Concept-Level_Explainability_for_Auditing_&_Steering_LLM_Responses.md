# 概念层面的可解释性，用于审核与引导大型语言模型的响应

发布时间：2025年05月12日

`LLM应用` `人工智能`

> Concept-Level Explainability for Auditing & Steering LLM Responses

# 摘要

> # 摘要
随着大型语言模型 (LLMs) 的广泛应用，对其安全性和对齐性的担忧日益增加。为了引导 LLM 行为（例如缓解偏见或防御越狱攻击），识别提示中的哪些部分影响模型输出的特定方面至关重要。基于 token 的归因方法虽然提供了一种解决方案，但在文本生成方面仍存在困难，它们单独解释输出中每个 token 的存在，而非整个 LLM 响应的潜在语义。

我们引入了 ConceptX，这是一种模型不可知论、基于概念的可解释性方法。它能够识别提示中的概念（即语义丰富的 token），并根据输出的语义相似性为这些概念分配重要性。与当前基于 token 的方法不同，ConceptX 通过原位 token 替换保留上下文完整性，并支持灵活的解释目标，例如性别偏见。

ConceptX 既支持通过揭示偏见来源进行审核，也支持通过修改提示来改变 LLM 响应的情感或减少其危害性，而无需重新训练。在三个 LLM 上，ConceptX 在保真度和人类对齐方面均优于 TokenSHAP 等基于 token 的方法。在引导任务中，情感变化提高了 0.252（相对于随机编辑的 0.131），并将攻击成功率从 0.463 降低到 0.242，优于归因和改写基线。

虽然提示工程和自我解释方法有时能产生更安全的响应，但 ConceptX 提供了一种透明且忠实的替代方案，可用于提升 LLM 的安全性和对齐性，展示了基于归因的可解释性在引导 LLM 行为方面的实际价值。

> As large language models (LLMs) become widely deployed, concerns about their safety and alignment grow. An approach to steer LLM behavior, such as mitigating biases or defending against jailbreaks, is to identify which parts of a prompt influence specific aspects of the model's output. Token-level attribution methods offer a promising solution, but still struggle in text generation, explaining the presence of each token in the output separately, rather than the underlying semantics of the entire LLM response. We introduce ConceptX, a model-agnostic, concept-level explainability method that identifies the concepts, i.e., semantically rich tokens in the prompt, and assigns them importance based on the outputs' semantic similarity. Unlike current token-level methods, ConceptX also offers to preserve context integrity through in-place token replacements and supports flexible explanation goals, e.g., gender bias. ConceptX enables both auditing, by uncovering sources of bias, and steering, by modifying prompts to shift the sentiment or reduce the harmfulness of LLM responses, without requiring retraining. Across three LLMs, ConceptX outperforms token-level methods like TokenSHAP in both faithfulness and human alignment. Steering tasks boost sentiment shift by 0.252 versus 0.131 for random edits and lower attack success rates from 0.463 to 0.242, outperforming attribution and paraphrasing baselines. While prompt engineering and self-explaining methods sometimes yield safer responses, ConceptX offers a transparent and faithful alternative for improving LLM safety and alignment, demonstrating the practical value of attribution-based explainability in guiding LLM behavior.

[Arxiv](https://arxiv.org/abs/2505.07610)