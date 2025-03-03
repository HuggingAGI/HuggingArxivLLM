# ECLeKTic：跨语言知识转移评估的创新挑战集

发布时间：2025年02月28日

`LLM理论` `多语言` `问答系统`

> ECLeKTic: a Novel Challenge Set for Evaluation of Cross-Lingual Knowledge Transfer

# 摘要

> 要实现跨语言的公平性能，多语言大型语言模型必须能够超越知识获取的语言进行抽象。然而，目前缺乏可靠的方法来衡量LLMs的跨语言知识转移能力。为此，我们提出了ECLeKTic，一个以简单、黑箱方式评估跨语言知识转移的多语言闭式问答（CBQA）数据集。通过控制12种语言中维基百科文章的存在与否，我们检测了跨语言覆盖不均的信息。我们用源语言生成知识探索型问题，这些问题的答案出现在相关维基百科文章中，并将这些问题翻译成其他11种语言，而这些语言的维基百科缺乏等效文章。假设维基百科反映了LLM训练数据中的突出知识，解决ECLeKTic的CBQA任务需要模型在语言之间转移知识。通过实验8种LLMs，我们发现，即使SOTA模型在知识获取语言的相同语言查询中能够很好地预测答案，它们也难以有效地跨语言共享知识。

> To achieve equitable performance across languages, multilingual large language models (LLMs) must be able to abstract knowledge beyond the language in which it was acquired. However, the current literature lacks reliable ways to measure LLMs' capability of cross-lingual knowledge transfer. To that end, we present ECLeKTic, a multilingual closed-book QA (CBQA) dataset that Evaluates Cross-Lingual Knowledge Transfer in a simple, black-box manner. We detected information with uneven coverage across languages by controlling for presence and absence of Wikipedia articles in 12 languages. We generated knowledge-seeking questions in a source language, for which the answer appears in a relevant Wikipedia article and translated them to all other 11 languages, for which the respective Wikipedias lack equivalent articles. Assuming that Wikipedia reflects the prominent knowledge in the LLM's training data, to solve ECLeKTic's CBQA task the model is required to transfer knowledge between languages. Experimenting with 8 LLMs, we show that SOTA models struggle to effectively share knowledge across, languages even if they can predict the answer well for queries in the same language the knowledge was acquired in.

[Arxiv](https://arxiv.org/abs/2502.21228)