# 多语言 LLM 是否真的以英语进行思考？

发布时间：2025年02月21日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在多语言处理中的内部机制，特别是它们如何依赖英语表示空间进行推理。研究通过logit lens分析了不同语言的内部表示，揭示了LLMs在处理非英语语言时的潜在偏见和机制。这属于对LLMs工作原理的理论分析，因此归类为LLM理论。` `机器翻译`

> Do Multilingual LLMs Think In English?

# 摘要

> 大型语言模型（LLMs）具备多语言处理能力，但无论输入输出语言如何，它们的关键决策却始终依赖于与英语最接近的表示空间。通过logit lens分析法语、德语、荷兰语和普通话句子的内部表示，我们发现LLMs会先将语义丰富的单词转化为接近英语的表示，再进行目标语言的翻译。实验表明，使用英语计算引导向量能显著提升激活引导效果，而非直接使用输入输出语言。这揭示了多语言LLMs的关键推理过程深受英语影响，且这一机制对用户而言并不透明。

> Large language models (LLMs) have multilingual capabilities and can solve tasks across various languages. However, we show that current LLMs make key decisions in a representation space closest to English, regardless of their input and output languages. Exploring the internal representations with a logit lens for sentences in French, German, Dutch, and Mandarin, we show that the LLM first emits representations close to English for semantically-loaded words before translating them into the target language. We further show that activation steering in these LLMs is more effective when the steering vectors are computed in English rather than in the language of the inputs and outputs. This suggests that multilingual LLMs perform key reasoning steps in a representation that is heavily shaped by English in a way that is not transparent to system users.

[Arxiv](https://arxiv.org/abs/2502.15603)