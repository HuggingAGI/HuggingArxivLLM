# # 单词形式至关重要：大语言模型在打字错误时的语义重构能力

发布时间：2025年03月03日

`LLM理论

摘要讨论了大型语言模型在处理打乱顺序的单词时的机制，特别是通过实验分析了单词形态和上下文在语义重构中的作用，并研究了模型的注意力模式。这些内容属于对LLM内部机制和理论的探讨，因此归类为LLM理论。` `人工智能`

> Word Form Matters: LLMs' Semantic Reconstruction under Typoglycemia

# 摘要

> 人类读者能高效理解字母顺序被打乱的单词，这一现象称为Typoglycemia，主要依靠单词形态；当形态信息不足时，他们会借助上下文线索。尽管大型语言模型（LLMs）也具备类似能力，但其背后的机制尚不明确。为探究这一问题，我们设计了控制实验，分析单词形态和上下文信息在语义重构中的作用，并研究LLM的注意力模式。具体而言，我们首先提出了SemRecScore这一可靠指标，用于量化语义重构程度，并验证了其有效性。通过该指标，我们发现单词形态是LLMs语义重构的核心因素。进一步分析表明，LLMs依赖于专门的注意力头提取和处理单词形态信息，且这一机制在不同层次的单词打乱中保持稳定。LLMs固定的注意力模式主要关注单词形态，而人类读者在平衡形态与上下文信息时采用的自适应策略之间的区别，为通过整合类似人类、上下文感知的机制提升LLM性能提供了重要启示。

> Human readers can efficiently comprehend scrambled words, a phenomenon known as Typoglycemia, primarily by relying on word form; if word form alone is insufficient, they further utilize contextual cues for interpretation. While advanced large language models (LLMs) exhibit similar abilities, the underlying mechanisms remain unclear. To investigate this, we conduct controlled experiments to analyze the roles of word form and contextual information in semantic reconstruction and examine LLM attention patterns. Specifically, we first propose SemRecScore, a reliable metric to quantify the degree of semantic reconstruction, and validate its effectiveness. Using this metric, we study how word form and contextual information influence LLMs' semantic reconstruction ability, identifying word form as the core factor in this process. Furthermore, we analyze how LLMs utilize word form and find that they rely on specialized attention heads to extract and process word form information, with this mechanism remaining stable across varying levels of word scrambling. This distinction between LLMs' fixed attention patterns primarily focused on word form and human readers' adaptive strategy in balancing word form and contextual information provides insights into enhancing LLM performance by incorporating human-like, context-aware mechanisms.

[Arxiv](https://arxiv.org/abs/2503.01714)